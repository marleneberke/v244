---
title: Learning relevant contextual variables within Bayesian optimization
abstract: Contextual Bayesian Optimization (CBO) efficiently optimizes black-box functions
  with respect to design variables, while simultaneously integrating _contextual_
  information regarding the environment, such as experimental conditions. However,
  the relevance of contextual variables is not necessarily known beforehand. Moreover,
  contextual variables can sometimes be optimized themselves at additional cost, a
  setting overlooked by current CBO algorithms. Cost-sensitive CBO would simply include
  optimizable contextual variables as part of the design variables based on their
  cost. Instead, we adaptively select a subset of contextual variables to include
  in the optimization, based on the trade-off between their _relevance_ and the additional
  cost incurred by optimizing them compared to leaving them to be determined by the
  environment. We learn the relevance of contextual variables by sensitivity analysis
  of the posterior surrogate model while minimizing the cost of optimization by leveraging
  recent developments on early stopping for BO. We empirically evaluate our proposed
  Sensitivity-Analysis-Driven Contextual BO (_SADCBO_) method against alternatives
  on both synthetic and real-world experiments, together with extensive ablation studies,
  and demonstrate a consistent improvement across examples.
openreview: qb33ha9frm
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: martinelli24a
month: 0
tex_title: Learning relevant contextual variables within Bayesian optimization
firstpage: 2450
lastpage: 2470
page: 2450-2470
order: 2450
cycles: false
bibtex_author: Martinelli, Julien and Bharti, Ayush and Tiihonen, Armi and John, S.
  T. and Filstroff, Louis and Sloman, Sabina J. and Rinke, Patrick and Kaski, Samuel
author:
- given: Julien
  family: Martinelli
- given: Ayush
  family: Bharti
- given: Armi
  family: Tiihonen
- given: S. T.
  family: John
- given: Louis
  family: Filstroff
- given: Sabina J.
  family: Sloman
- given: Patrick
  family: Rinke
- given: Samuel
  family: Kaski
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/martinelli24a/martinelli24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
