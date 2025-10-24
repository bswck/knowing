# knowing
*A logic framework built for fun.*

At the moment, there’s nothing here — this is a playground I’ll be building in my free time. I plan to dive into [set theory](https://en.wikipedia.org/wiki/Set_theory), [relational algebra](https://en.wikipedia.org/wiki/Relational_algebra), [category theory](https://en.wikipedia.org/wiki/Category_theory), [type theory](https://en.wikipedia.org/wiki/Type_theory), [model theory](https://en.wikipedia.org/wiki/Model_theory), [formal semantics](https://en.wikipedia.org/wiki/Formal_semantics_(natural_language)), [abstract interpretation](https://en.wikipedia.org/wiki/Abstract_interpretation), [symbolic execution](https://en.wikipedia.org/wiki/Symbolic_execution), and [lambda calculus](https://en.wikipedia.org/wiki/Lambda_calculus) — searching for a way to connect the dots between them.

The goal is to **build new knowledge and logic frameworks directly in Python**.
I want to do this for several reasons:
- To analyze the implications of my own interpretations of facts  
- To create a structured way to gather and validate what I learn  
- To write [code generators that don’t suck](https://github.com/bswck/generate-errno-stub) as part of testing new software ideas  
- To help write better, clearer specifications  

When humans learn, they build *graphs* — structures of knowledge that express relations between sets, unknown ideas, and established facts.  
What frustrates me is the *ambiguity* that clouds these graphs. Ambiguity (or [incompleteness](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems#Formal_systems:_completeness,_consistency,_and_effective_axiomatization)) in academic material has real consequences — it makes reasoning and problem-solving unnecessarily hard.

I constantly generate questions as I learn new things, often for reasons I can’t fully articulate. I’d like to create a formal-like system that can verify those questions, simplify them, and help me pinpoint where ambiguity exists in the knowledge I’m absorbing.

Ultimately, I believe the future lies in **reasoning that you can actually follow**.  
Back in high school, I dreamed of building a math solver for problems at the *matura* level. Those tasks often boiled down to:  
- starting from a set of known facts,  
- traversing a knowledge graph,  
- finding a path to a solution,  
- and presenting both the result and the reasoning behind it.  

There are usually several ways to reach the same conclusion. What fascinates me is that many of these paths are *fundamentally the same*, just expressed differently. For example, a geometry problem might be solved using Stewart’s Theorem or by applying the law of cosines twice — which, in essence, are equivalent. What changes is only the *framing*.

This is an issue that mirrors software design: deciding how fine-grained or coarse-grained your abstractions should be. Framing matters. I want to capture *how* something is framed, so a system could explore multiple valid framings and surface their equivalence. In other words, I want to build an **inductive system** — one that can reason about reasoning.

My endgame is to design an **orchestrator** that bridges functional and imperative approaches.  
I'll call it a *thinking system*.
