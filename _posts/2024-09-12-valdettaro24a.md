---
title: Offline Bayesian Aleatoric and Epistemic Uncertainty Quantification and Posterior
  Value Optimisation in Finite-State MDPs
abstract: We address the challenge of quantifying Bayesian uncertainty and incorporating
  it in offline use cases of finite-state Markov Decision Processes (MDPs) with unknown
  dynamics. Our approach provides a principled method to disentangle epistemic and
  aleatoric uncertainty, and a novel technique to find policies that optimise Bayesian
  posterior expected value without relying on strong assumptions about the MDP’s posterior
  distribution. First, we utilise standard Bayesian reinforcement learning methods
  to capture the posterior uncertainty in MDP parameters based on available data.
  We then analytically compute the first two moments of the return distribution across
  posterior samples and apply the law of total variance to disentangle aleatoric and
  epistemic uncertainties.  To find policies that maximise posterior expected value,
  we leverage the closed-form expression for value as a function of policy. This allows
  us to propose a stochastic gradient-based approach for solving the problem. We illustrate
  the uncertainty quantification and Bayesian posterior value optimisation performance
  of our agent in simple, interpretable gridworlds and validate it through ground-truth
  evaluations on synthetic MDPs. Finally, we highlight the real-world impact and computational
  scalability of our method by applying it to the AI Clinician problem, which recommends
  treatment for patients in intensive care units and has emerged as a key use case
  of finite-state MDPs with offline data. We discuss the challenges that arise with
  Bayesian modelling of larger scale MDPs while demonstrating the potential to apply
  our methods rooted in Bayesian decision theory into the real world. We make our
  code available at https://github.com/filippovaldettaro/finite-state-mdps.
openreview: Kr0UJQ7Vbx
software: https://github.com/filippovaldettaro/finite-state-mdps
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: valdettaro24a
month: 0
tex_title: Offline Bayesian Aleatoric and Epistemic Uncertainty Quantification and
  Posterior Value Optimisation in Finite-State MDPs
firstpage: 3391
lastpage: 3409
page: 3391-3409
order: 3391
cycles: false
bibtex_author: Valdettaro, Filippo and Faisal, Aldo
author:
- given: Filippo
  family: Valdettaro
- given: Aldo
  family: Faisal
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/valdettaro24a/valdettaro24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
