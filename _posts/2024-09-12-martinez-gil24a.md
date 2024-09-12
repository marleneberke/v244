---
title: Identifying Homogeneous and Interpretable Groups for Conformal Prediction
abstract: Conformal prediction methods are a tool for uncertainty quantification of
  a model’s prediction, providing a model-agnostic and distribution-free  statistical
  wrapper that generates prediction intervals/sets for a given model with finite sample
  generalization guarantees. However, these guarantees hold only on average, or conditioned
  on the output values of the predictor or on a set of predefined groups, which a-priori
  may not relate to the prediction task at hand. We propose a method to learn a generalizable
  partition function of the input space (or representation mapping) into interpretable
  groups of varying sizes where the non-conformity scores - a measure of discrepancy
  between prediction and target - are as homogeneous as possible when conditioned
  to the group. The learned partition can be integrated with any of the group conditional
  conformal approaches to produce conformal sets with group conditional guarantees
  on the discovered regions. Since these learned groups are expressed as strictly
  a function of the input, they can be used for downstream tasks such as data collection
  or model selection. We show the effectiveness of our method in reducing worst case
  group coverage outcomes in a variety of datasets.
openreview: 5qW3Ojxt9m
software: https://github.com/trustyai-explainability/trustyai-model-trust
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: martinez-gil24a
month: 0
tex_title: Identifying Homogeneous and Interpretable Groups for Conformal Prediction
firstpage: 2471
lastpage: 2485
page: 2471-2485
order: 2471
cycles: false
bibtex_author: Martinez Gil, Natalia and Patel, Dhaval and Reddy, Chandra and Ganapavarapu,
  Giri and Vaculin, Roman and Kalagnanam, Jayant
author:
- given: Natalia
  family: Martinez Gil
- given: Dhaval
  family: Patel
- given: Chandra
  family: Reddy
- given: Giri
  family: Ganapavarapu
- given: Roman
  family: Vaculin
- given: Jayant
  family: Kalagnanam
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/martinez-gil24a/martinez-gil24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
