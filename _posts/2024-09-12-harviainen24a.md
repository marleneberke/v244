---
title: Faster Perfect Sampling of Bayesian Network Structures
abstract: Bayesian inference of a Bayesian network structure amounts to averaging
  over directed acyclic graphs (DAGs) on a given set of $n$ variables, each DAG weighted
  by its posterior probability. In practice, save some special inference tasks, one
  averages over a sample of DAGs generated perfectly or approximately from the posterior.
  For the hard problem of perfect sampling, we give an algorithm that runs in $O(2.829^n)$
  expected time, getting below $O(3^n)$ for the first time. Our algorithm reduces
  the problem into two smaller sampling problems whose outputs are combined; followed
  by a simple rejection step, perfect samples are obtained. Subsequent samples can
  be generated considerably faster. Empirically, we observe speedups of several orders
  of magnitude over the state of the art.
openreview: eq2rjvKbaG
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: harviainen24a
month: 0
tex_title: Faster Perfect Sampling of Bayesian Network Structures
firstpage: 1558
lastpage: 1568
page: 1558-1568
order: 1558
cycles: false
bibtex_author: Harviainen, Juha and Koivisto, Mikko
author:
- given: Juha
  family: Harviainen
- given: Mikko
  family: Koivisto
date: 2024-09-12
address:
container-title: Proceedings of the Fortieth Conference on Uncertainty in Artificial
  Intelligence
volume: '244'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 9
  - 12
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/harviainen24a/harviainen24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
