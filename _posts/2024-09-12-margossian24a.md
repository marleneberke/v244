---
title: 'Amortized Variational Inference: When and Why?'
abstract: In a probabilistic latent variable model, factorized (or mean-field) variational
  inference (F-VI) fits a separate parametric distribution for each latent variable.
  Amortized variational inference (A-VI) instead learns a common inference function,
  which maps each observation to its corresponding latent variable’s approximate posterior.
  Typically, A-VI is used as a cog in the training of variational autoencoders, however
  it stands to reason that A-VI could also be used as a general alternative to F-VI.
  In this paper we study when and why A-VI can be used for approximate Bayesian inference.
  We derive conditions on a latent variable model which are necessary, sufficient,
  and verifiable under which A-VI can attain F-VI’s optimal solution, thereby closing
  the amortization gap. We prove these conditions are uniquely verified by simple
  hierarchical models, a broad class that encompasses many models in machine learning.
  We then show, on a broader class of models, how to expand the domain of AVI’s inference
  function to improve its solution, and we provide examples, e.g. hidden Markov models,
  where the amortization gap cannot be closed.
openreview: mCVYIsnctr
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: margossian24a
month: 0
tex_title: 'Amortized Variational Inference: When and Why?'
firstpage: 2434
lastpage: 2449
page: 2434-2449
order: 2434
cycles: false
bibtex_author: Margossian, Charles C. and Blei, David M.
author:
- given: Charles C.
  family: Margossian
- given: David M.
  family: Blei
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/margossian24a/margossian24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
