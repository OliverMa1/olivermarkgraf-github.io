---
title: "The Power of Regular Constraint Propagation"
collection: talks
type: "Conference Talk"
permalink: /talks/2025-10-16-conference
venue: "OOPSLA 2025, Marina Bay Sands Convention Centre, Singapore"
date: 2025-10-16
location: "Singapore"
---

[Paper](https://dl.acm.org/doi/10.1145/3763165) 

The past decade has witnessed substantial developments in string solving. Motivated by the complexity of string solving strategies adopted in existing string solvers, we investigate a simple and generic method for solving string constraints: regular constraint propagation. The method repeatedly computes pre- or post-images of regular languages under the string functions present in a string formula, inferring more and more knowledge about the possible values of string variables, until either a conflict is found or satisfiability of the string formula can be concluded. Such a propagation strategy is applicable to string constraints with multiple operations like concatenation, replace, and almost all flavors of string transductions. We demonstrate the generality and effectiveness of this method theoretically and experimentally. On the theoretical side, we show that RCP is sound and complete for a large fragment of string constraints, subsuming both straight-line and chain-free constraints, two of the most expressive decidable fragments for which some modern string solvers provide formal completeness guarantees. On the practical side, we implement regular constraint propagation within the open-source string solver OSTRICH. Our experimental evaluation shows that this addition significantly improves OSTRICH’s performance and makes it competitive with existing solvers. In fact, it substantially outperforms other solvers on random PCP and bioinformatics benchmarks. The results also suggest that incorporating regular constraint propagation alongside other techniques could lead to substantial performance gains for existing solvers.