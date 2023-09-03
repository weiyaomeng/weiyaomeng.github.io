---
title: "Automated design of search algorithms: Learning on algorithmic components"
collection: publications
permalink: /publication/2021-06-24-autogcop-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-06-24
venue: 'Expert Systems with Applications'
paperurl: 'https://doi.org/10.1016/j.eswa.2021.115493'
citation: 'Meng, W., & Qu, R. (2021). Automated design of search algorithms: Learning on algorithmic components. Expert Systems with Applications, 185, 115493.'
---
Highlights
------
- A framework for automated design of local search algorithms.
- Various local search algorithms are modelled within the framework.
- The vehicle routing problems are used as the domain problem.
- Performance of elementary algorithmic components is analysed.
- Two learning models based on reinforcement learning and Markov chain are compared.

Abstract
------
This paper proposes AutoGCOP, a new general framework for automated design of local search algorithms. In a recently established General Combinatorial Optimisation Problem (GCOP) model, the problem of algorithm design itself is defined as a combinatorial optimisation problem. AutoGCOP defines a general framework to optimise the composition of elementary algorithmic components as decision variables in GCOP. By modelling various well-known local search meta-heuristics within a general framework, AutoGCOP supports automatic design of new novel algorithms which may be highly different from those manually designed in the literature.

Within the consistent AutoGCOP framework, various elementary algorithmic components are analysed for solving the benchmark vehicle routing problem with time window constraints and different characteristics. Furthermore, two learning models based on reinforcement learning and Markov chain are investigated to learn and enhance the compositions of algorithmic components towards the automated design of search algorithms. The Markov chain model presents superior performance learning the compositions of algorithmic components during the search, demonstrating its effectiveness designing new algorithms automatically.

[Download paper here](https://doi.org/10.1016/j.eswa.2021.115493)

Recommended citation: 

@article{meng2021automated,
  title={Automated design of search algorithms: Learning on algorithmic components},
  author={Meng, Weiyao and Qu, Rong},
  journal={Expert Systems with Applications},
  volume={185},
  pages={115493},
  year={2021},
  publisher={Elsevier}
}