---
title: "Learning-Based Synthesis of Safety Controllers"
collection: talks
type: "Conference Talk"
permalink: /talks/2019-10-24-conference
venue: "FMCAD 2019, Hyatt Place San Jose Downtown, San Jose, California"
date: 2019-10-24
location: "San Jose, USA"
---

[Paper](https://theory.stanford.edu/~barrett/fmcad/papers/FMCAD2019_paper_11.pdf) |
[Slides](https://theory.stanford.edu/~barrett/fmcad/slides/12_Markgraf.pdf)

We propose a machine learning framework to synthesize reactive controllers for systems whose interactions with their adversarial environment are modeled by infinite-duration, two-player games over (potentially) infinite graphs. Our framework targets safety games with infinitely many vertices, but it is also applicable to safety games over finite graphs whose size is too prohibitive for conventional synthesis techniques. The learning takes place in a feedback loop between a teacher component, which can reason symbolically about the safety game, and a learning algorithm, which successively learns an overapproximation of the winning set from various kinds of examples provided by the teacher. We develop a novel decision tree learning algorithm for this setting and show that our algorithm is guaranteed to converge to a reactive safety controller if a suitable overapproximation of the winning set can be expressed as a decision tree. Finally, we empirically compare the performance of a prototype implementation to existing approaches, which are based on constraint solving and automata learning, respectively.