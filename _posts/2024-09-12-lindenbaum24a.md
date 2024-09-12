---
title: Transductive and Inductive Outlier Detection with Robust Autoencoders
abstract: Accurate detection of outliers is crucial for the success of numerous data
  analysis tasks. In this context, we propose the Probabilistic Robust AutoEncoder
  (PRAE) that can simultaneously remove outliers during training (transductive) and
  learn a mapping that can be used to detect outliers in new data (inductive). We
  first present the Robust AutoEncoder (RAE) objective that excludes outliers while
  including a subset of samples (inliers) that can be effectively reconstructed using
  an AutoEncoder (AE). RAE minimizes the autoencoder’s reconstruction error while
  incorporating as many samples as possible. This could be formulated via regularization
  by subtracting an $\ell_0$ norm, counting the number of selected samples from the
  reconstruction term. As this leads to an intractable combinatorial problem, we propose
  two probabilistic relaxations of RAE, which are differentiable and alleviate the
  need for a combinatorial search. We prove that the solution to the PRAE problem
  is equivalent to the solution of RAE. We then use synthetic data to demonstrate
  that PRAE can accurately remove outliers in various contamination levels. Finally,
  we show that using PRAE for outlier detection leads to state-of-the-art results
  for inductive and transductive outlier detection.
openreview: UkA5dZs5mP
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lindenbaum24a
month: 0
tex_title: Transductive and Inductive Outlier Detection with Robust Autoencoders
firstpage: 2271
lastpage: 2293
page: 2271-2293
order: 2271
cycles: false
bibtex_author: Lindenbaum, Ofir and Aizenbud, Yariv and Kluger, Yuval
author:
- given: Ofir
  family: Lindenbaum
- given: Yariv
  family: Aizenbud
- given: Yuval
  family: Kluger
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/lindenbaum24a/lindenbaum24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
