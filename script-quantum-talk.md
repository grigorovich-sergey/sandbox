# Quantum Computing Today: Between Hype, Scepticism, and "Coming Soon"

Greetings, my name is Sergey Grigorovich. 

Today we will see a high-level perspective on quantum computing, build the field mental model and answer a question, whether you should study quantum.

Spoiler alert - Yes, absolutely, but there are nuances.

## [Slide change 2]

First of all, when people hear “quantum computing,” they are often offered one of two stories by the media.
***
The first is extremely sceptical: quantum computing is mostly hype, the machines barely work, useful applications are hypothetical, and the whole field is a bubble.
***
The second is almost the opposite: quantum computers are the next AI, they are transforming medicine, finance, logistics and gaming - and this revolution is already here or just around the corner, with job market waiting for applicants.

None of these statements is true.

## [Slide change 12]

Quantum computing is real.
***
We can build increasingly capable quantum processors. Error correction is improving. Experiments that were unrealistic a decade ago are routine research today.
***
But there is an important difference between **a technology being real** and **a technology being ready to solve economically useful problems**.

Quantum processors have demonstrated calculations that are extremely difficult to reproduce classically. 
***
But these have largely been benchmark designed to be progress milestones. 

We still do not have an established case of a quantum computer providing useful real-world computational advantage over the best existing classical alternative.

## [Slide change 13]

But there is a gap between working technology, and technology that brings utility
*** 
We are not asking, “Can we build quantum computers?”. 
***
We should ask: where does quantum advantage actually exist, and when can we connect it to something people genuinely need?
***
So I would start from this position:

**Quantum computing is neither a miracle nor a mirage. It is a real technology somewhere on this chart, and useful applications are still largely a research question.**

And that view explains everything else - the industry, the job market, and the very uneven prospects of different quantum applications.

## [Slide change 14]

We have seen this situation before in other technologies.

You have likely heard about the fusion power.
***
Fusion is unquestionably real physics. Enormous machines have been constructed, private companies have raised billions of dollars, and the field already employs thousands working on plasma physics, superconducting magnets, materials and reactor engineering.

But notice what most of those people are employed to do.

They are trying to **make fusion power possible**.

There is not yet an established global fleet of commercial fusion power stations where people have routine careers maintaining plants, buying fuel, optimizing electricity production, replacing aging components or regulating an established industrial technology.

## [Slide change 19]

Now compare that with good old nuclear fission power.

There are hundreds of operating nuclear reactors around the world, employing more than a million of specialists. 
***
There is a mature employment ecosystem: plant operators, safety engineers, maintenance specialists, fuel-cycle experts, regulators, construction companies, suppliers, radiation specialists, consultants and managers.

In fusion, the dominant professional question is still:

**“How do we make this technology work at commercial scale?”**

In fission, a huge part of the professionals asks:

**“How do we operate a technology that already works commercially?”**
***
There is no such thing as fusion power plant operator, because there is no fusion power plants.

## [Slide change 20]

This analogy explains a lot about quantum computing industry, which today looks much more like **fusion than fission**.

There are hardware companies, software companies, major technology corporations, national laboratories and startups. People have genuine industry careers in quantum computing.

But we should look carefully at what they are actually doing.
***
A large part of the work is still quantum-facing: building better processors, designing control electronics, improving fabrication, developing error correction, designing quantum algorithms, benchmarking quantum against classical methods, and estimating the resources future fault-tolerant machines would require.

The labour-market data gives us a particularly clear picture of this.

So even when the employer is IBM, Google, Quantinuum, a startup, rather than a university, much of the work still include **frontier research and engineering**.

Yes, we do have small groups studying finance, pharmaceuticals, logistics and other applications. But these groups are trying to discover whether quantum computing can eventually provide useful advantage in future - not operating established quantum solutions.

That distinction matters if somebody is considering quantum as a career.
***
Today, entering quantum computing usually means entering the business of **building and improving the new technology itself**.

And this naturally favours people with strong foundations in physics, electrical engineering, mathematics, computer science, chemistry and related research disciplines.

## [Slide change 21]

People often ask:

**“When will quantum computing become useful?”**

Five years? Ten years? Twenty?

I think this is almost the wrong question.
***
There is probably no single moment when “quantum computing arrives,” because the different proposed applications are radically different.

The better question is:

**“Useful for what?”**
***
Quantum machine learning are one category. Optimization is another. Cryptanalysis is another. Quantum chemistry and simulation is another. 
***
And their progress, even rapid, should not be bundled together.
***
Quantum chemistry and cryptography are showing strong progess and are ahead in the race to utility. 
***
Other fields remain speculative and further from becoming relevant.

They are all worth going into if you are ready to work on the frontier and advance the technology, but some domains are more mature than others.

## [Slide change 23]

Quantum simulation has a particularly natural motivation. Molecules and materials are quantum systems themselves. 

Classical computers can simulate many of them  well, but the cost can grow dramatically as the systems grow and become complex.

Future applications are already on the horizon:

- new materials discovery
- material microstructure
- organic molecule folding
- real-time chemical dynamics

This does not mean a useful quantum chemistry revolution is happening next year. But it is closer to the utility scale than other domains.

That makes chemistry and materials particularly important areas to watch.

## [Slide change 24]

And this brings us to an apparently strange question.

If useful quantum advantage has not yet been demonstrated, then why are major companies already spending money on it?
***
Because waiting until the technology is mature may be too late to begin learning about it.

A pharmaceutical or materials company does not necessarily need to believe that quantum computing will improve its products next year. It only needs to believe that it is too risky to be unprepared when the technology arrives.

## [Slide change 25]

Pharmaceutical giant Moderna provides a good example.

There is a classically hard computational problem: 3d structure of organic molecules folding, proteins, DNA, RNA.

Together with IBM researchers, Moderna has investigated quantum and hybrid approaches to mRNA folding prediction on actual quantum hardware.

Every year they are publishing studies that explore this direction. It was exploratory application research.

## [Slide change 26]

They utilize the community resources too: Moderna supports industry challenges, that invited people to
***
investigate quantum, quantum-inspired, hybrid and classical approaches to the same type of optimization problem-and explicitly compare them with classical benchmarks.
***
That is what serious engagement with an immature technology can look like: they want to understand the current state, benchmark algorithms, build expertise and be ready for the day of quantum utility.
***
Here is the lesson for many of as a professionals, but we will come back to it.

So, for large organizations, quantum matters **before quantum advantage** simply because technological readiness has value.

## [Slide change 27]

Now compare this with quantum machine learning.

There are fascinating theoretical ideas in QML, and we should not declare that quantum machine learning can never work.

But its near-term situation is much less favourable.

One reason is something that discussions of QML sometimes underestimate:
***
**its classical competitor is strong and stil growing.**

Modern machine learning has accumulated decades of algorithmic development.

And, crucially, classical ML is not approaching a technological standstill.

It is still improving rapidly.
***
A recent systematic review looked specifically at studies comparing quantum machine-learning approaches against serious classical baselines. 

The picture is currently sobering: quantum approaches generally reach parity at best in specifically designed tasks and remain inferior once resources and fair comparisons are taken into account. 

## [Slide change 28]

One way to remember the difference is:

**Quantum chemistry is searching for a way through computational walls. Quantum machine learning is trying to overtake one of the fastest-moving technologies**

So QML is not trying to cross a computational barrier while the classical alternative waits patiently on the other side.

It is trying to **catch a competitor that is sprinting forward**.

This is why I would treat “quantum AI” claims particularly carefully.

There may eventually be important quantum-learning applications. But at the moment, classical AI and machine learning have an strong head start and decades of investments and development.

Does it mean that you should not study quantum machine learning? No. 

But keep your expectations realistic - quantum machine learning specialist will less likely apply their skills to industry problem anytime soon.

Today and in near future, QML specialist is a pioneer and algorithms explorer in the research department, with specific skillset and role.

## [Slide change 29]

This brings the story back to a very practical question: should somebody study quantum for a career?

I think the answer can absolutely be yes - but with the correct expectations.

I can roughly divide four approaches to quantum learning depending on your dedication: full quantum, quantum minor, quantum-aware and casual quantum.

## [Slide change 30]

Choosing full quantum today is closer to choosing fusion research.

Working on the frontier can be extremely exciting. But it means you should expect research, uncertainty and specialization rather than assume that a large mature job market is waiting for you. 

Your foundational training also matters a lot: material and electrical engineering, computer science, physics - these domains can bring you to full quantum jobs.

But keep your expectations realistic - job market is small and competitive. Yes, one day, an algorithm might be named after you, but working on the frontier of knowledge is challenging. 

## [Slide change 32]

If you are not ready for a head-forward dive or your interests lie elsewhere, there is another approach to develop a strong professional identity - building a quantum minor.

Become a chemist who understands quantum simulation.

A computer scientist working on algorithms.

A mathematician working on complexity.

Then quantum becomes a powerful specialization built on top of a deep discipline. 

So, even if the quantum advantage is late for the party, you have your classical job. And when it comes to utility stage, you are already ahead of the majority of your collegues.

It make even more sense because quantum computers will not work by themselves in isolation: everything that can be done classically - will be done classically.

The real place for the future quantum computer is inside the classical cluster, as dedicated subsystem of the hybrid machine. So, you will need a deep classical domain knowledge anyways.

## [Slide change 34]

There is another possibility - professional quantum awareness.

**Quantum may matter to your profession even if it never becomes your profession.**

Cryptography is perhaps the clearest example.

Post-quantum cryptography is already being deployed because organizations have to prepare for the future possibility of cryptographically relevant quantum computers. The algorithms themselves still run on ordinary classical machines.

Quantum computers haven't broken any encryption yet, but the government and business are already preparing for the future threats. The exisitng encryption algorithms are suceptable for quantum decryption, so we need to change them today in advance.

PQC transition is already happening
- NIST finalized its first principal post-quantum cryptography standards in 2024, urging organizations to **begin migration now**.
- Current transition planning calls for quantum-vulnerable algorithms to be removed from standards by **2035**, with high-risk systems transitioning earlier.

So quantum computing is already influencing cybersecurity careers without cybersecurity professionals needing to sit in front of a quantum processor.

If you are going into cybersecurity field, you will need to stay deeply informed about quantum progress.

Even in other domains: biology, physics, neuroscience - we already see a wave of papers and proposals where "quantum-based" and “quantum-inspired” language is doing more work than the actual technology. We need at least some quantum expertise to see through this fog.

## [Slide change 36]

And that brings us to the last approach to quantum learning: casual quantum.

Your profession might seem to have nothing that relates to quantum: you might be an entrepreneur, a manager, a teacher, an investor, an engineer.

But that kind of literacy has value even beyond professional crossover.

As public attention and investment grow, **“quantum” becomes a valuable buzzword**.

And valuable words attract marketing. Labeling things quantum to attrach attention. Quantum startups. 
***
Quantum healing.

We already see a growth of products and technologies described as quantum-powered, quantum-ready, quantum-enhanced, quantum-safe, quantum-inspired or quantum-AI. And this is just a beginning.
***
Quantum marketing. Most of those labels will be only deceptive.
***
Quantum jewlery. 
***
Quantum well-being.

Lack of quantum knowledge makes you a target audience for this type of marketing. A basic understanding of quantum computing lets us ask much better questions. 

What exactly is quantum here? Isn't it just a scam?

Does this product actually use a quantum computer?

What is the classical alternative?

Has an advantage been demonstrated against classical?

So quantum literacy becomes a kind of **technological literacy and market self-defence**.

It can help us as scientists and engineers, but also as managers, customers, educators and entrepreneurs.

## [Slide change 37]

So my conclusion is deliberately somewhere between optimism and scepticism.
***
Quantum computing is real.

A genuine industry exists.

The  progress is substantial.
***
But much of that industry is still in the business of **creating the capability**, rather than exploiting a mature capability. Building, but not yet operating.

And different applications are nowhere near equally ready.
***
For somebody whose career lies elsewhere, quantum knowledge can still become useful when it intersects with chemistry, materials, cryptography, computation or another profession.
***
And for everyone else, we should learn from larger companies: stay informed, understand the foundations and limitations of quantum computing and be realistic - this knowledge will be beneficial no matter what

So I would not tell everyone:

**“Bet your career on quantum.”**

I would say:

**Understand the bet.**

Understand what quantum computers can do, what they cannot yet do, where genuine advantage might appear, and what evidence would convince you that it has.
