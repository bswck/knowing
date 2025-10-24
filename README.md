# knowing
Logic framework built for fun

Nothing here. I'll be building this thing in my free time, diving into [set theory](https://en.wikipedia.org/wiki/Set_theory), [relational algebra](https://en.wikipedia.org/wiki/Relational_algebra), [category theory](https://en.wikipedia.org/wiki/Category_theory), [type theory](https://en.wikipedia.org/wiki/Type_theory), [model theory](https://en.wikipedia.org/wiki/Model_theory), [formal semantics](https://en.wikipedia.org/wiki/Formal_semantics_(natural_language)), [abstract interpretation](https://en.wikipedia.org/wiki/Abstract_interpretation), [symbolic execution](https://en.wikipedia.org/wiki/Symbolic_execution) and [lambda calculus](https://en.wikipedia.org/wiki/Lambda_calculus), hoping to find something interesting that connects all the dots together.

The main goal is ~~not to learn Datalog or Prolog~~ being able to build any new knowledge+logic framework using Python code.
I'd do that for many purposes:
- Examining the implications of my interpretations of facts
- Having a funnel to gather and validate my knowledge in different areas
- Writing [codegens that don't suck](https://github.com/bswck/generate-errno-stub) to test new software
- Writing specifications

When humans learn, they are essentially building a graph. That graph often needs to express relations between sets, unknown concepts or known facts.

What frustrates me deeply is the ambiguity that tampers that graph. The ambiguity or [incompleteness](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems#Formal_systems:_completeness,_consistency,_and_effective_axiomatization) in academic books have real consequences. At least to me, they make it very difficult to solve tests.

I often have tons of questions about new knowledge, but they come from very different reasons that I often find only subconscious. I'd like to have any formal-like system that can verify them, simplify some, and point me to what the ambiguities are in the new things that I learn about the world.

Moreover, I think that future lies in reasoning that you can actually follow. Back in high school, I wanted to build a solver for math tasks at the level of the matura exam. They really often just boil down to having a set of facts, being asked to traverse a knowledge graph to find a path to solution and deliver that path along with a solution. There are often lots of ways to come to a solution, and I'm not yet sure what algorithms humans use to get them. Is it more like BFS, more like DFS, more like Dijkstra, more like A*? There were tasks that could be solved in 10 different ways, and what I found fascinating is that half of them was essentially the same way but just differently framed. To illustrate, there was a task that can be solved by Stewart's Theorem or by applying the law of cosines twice. Stewart's Theorem is essentially the law of cosines twice! These solutions are *functionally* identical, but the way we framed the steps are different. This often matters in software, where you constantly hit the problem of laying out things in a way that isn't too fine-grained but also not too coarse-grained. What I want to capture is what is being framed, so that it can come up with all the different ways to frame things. I want to program an inductive system.

I want an orchestrator for functional and imperative methods. I want Church methods and Turing methods as a Service.
