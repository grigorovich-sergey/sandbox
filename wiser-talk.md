# WISER–Moderna Finalist Presentation Script


Hello, my name is Sergey Grigorovich.

My project asks: **where should RNA structural constraints live - inside the quantum objective, or in classical postprocessing and how does the answer scale with increased lenght of RNA?**

---

## Slide 1 — The Engineering Question

As a scientist, I try to change as few parts of a model as possible at once, so the results can be interpreted clearly.

That is why my project started with a deliberately simple stem-length reward instead of a full thermodynamic objective. This allowed me to isolate a quantum-engineering question: how constraint placement affects scaling, sampled quality and circuit cost. ViennaRNA remains the independent biological benchmark after sampling.

This question also matters beyond RNA. Practical quantum computers are going to operate as parts of **hybrid systems**. If a step can be done classically, there is no reason to spend quantum resources on it. So as quantum systems grow, the question of **what should stay insode and outside the quantum circuit** will appear again and again.

---

## Slide 2 — One Controlled Experiment

With this question in mind, I compared three QUBO formulations with different constrains placement. 

Everything else is held constant, so the main variable is where conflicts are resolved.
***
**Strict** formulation penalizes overlap and crossing stems.
***
**Relaxed** penalizes overlap, but repairs crossings after sampling.
***
**Postprocessed** rewards stems lenght only and repairs all conflicts classically.

---

## Slide 3 — What I Actually Tested

Starting from semi-synthetic sequnces of given lenghts, I established same workflow for all lenghts and formulations.

I completed **more than a thousand successful variant-runs**: 600 Aer simulations and **500 hardware runs**.

Hardware experiments reached **44-nucleotide sequences** and **143 qubits** on IBM Heron Quebec System One.

For each run, I measured circuit cost, raw validity, repair burden, and ViennaRNA-based quality.

I also separated whether a good oracle candidate was sampled, from whether it could be selected with or without repair.

---

## Slide 4 — Some Constraints Can Move Out

The most interesting is the comparison between Strict and Relaxed encodings.
***
Relaxed used **37 percent fewer quadratic interactions** than strict and 
***
reduced mean circuit depth by **21 percent**.
***
But sampled-oracle quality stayed similar: energy gap was **0.44 versus 0.47**, and F1 was **0.8 versus 0.81**.
***
So encoding crossing penalties in quantum circuit added quantum cost without improving the best repaired candidates that were sampled.

---

## Slide 5 — Good Candidates Are Easier to Find Than to Select

However, sampled-oracle quality is only an upper bound.

Reference-independent selection is much harder.
***
Repaired MAP improved over objective-first for strict and relaxed, showing useful probability mass across repaired structures.
***
This shows a key bottleneck: generating a good candidate and identifying it are not the same problem.
***
Strict and relaxed QUBOs sampled useful structures, but selecting them without a reference is another challenge

---

## Slide 6 — Moving Everything Out Goes Too Far

Compared to other encodings, postprocessed kept the circuit cheap.

But it required more repair and produced much weaker sampled candidates.

So the two extremes have costs: strict is quantum expensive, while postprocessed removes too much useful structure.
***
Relaxed encoding gave the best balance in my experiment.

---

## Slide 7 — Conclusion + Follow-up Check

So, on simplified model, relaxed gave the best observed balance between circuit cost, repair burden and candidate quality.

One future direction was to test whether this conclusion survives a richer energy model.
***
Since submission, I checked this with **Turner-2004 stacking energies**. I keeps the same candidate stems, constraints, repair procedure, and quantum parameters.

The result appears robust: relaxed candidates quality still stays close to strict while keeping about **20 percent lower circuit depth**. Postprocessed still remains much weaker.

So result is is not only about one RNA model. It points to a broader hybrid-design principle: **quantum resources should be reserved for the parts of the problem where they add value, while rest of the work remains classical.**
***
It highlights the key design questions for present and future systems: **not how many constraints we can encode, but which constraints are worth paying quantum resources for.**

Thank you.
