---
title: Response Time Improves Gaussian Process Models for Perception and Preferences
abstract: Models for human choice prediction in preference learning and perception
  science often use binary response data, requiring many samples to accurately learn
  latent utilities or perceptual intensities. The response time (RT) to make each
  choice captures additional information about the decision process, but existing
  models incorporating RTs for choice prediction do so in a fully parametric way or
  over discrete inputs. At the same time, state-of-the-art Gaussian process (GP) models
  of perception and preferences operate on choices only, ignoring RTs. We propose
  two approaches for incorporating RTs into GP preference and perception models. The
  first is based on stacking GP models, and the second uses a novel differentiable
  approximation to the likelihood of the diffusion decision model (DDM), the de-facto
  standard model for choice RTs. Our RT-choice GPs enable better latent value estimation
  and held-out choice prediction relative to baselines, which we demonstrate on three
  real-world multivariate datasets covering both human psychophysics and preference
  learning.
openreview: oUZ5JweNRc
software: https://github.com/facebookresearch/response-time-gps
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shvartsman24a
month: 0
tex_title: Response Time Improves Gaussian Process Models for Perception and Preferences
firstpage: 3211
lastpage: 3226
page: 3211-3226
order: 3211
cycles: false
bibtex_author: Shvartsman, Michael and Letham, Benjamin and Bakshy, Eytan and Keeley,
  Stephen
author:
- given: Michael
  family: Shvartsman
- given: Benjamin
  family: Letham
- given: Eytan
  family: Bakshy
- given: Stephen
  family: Keeley
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/shvartsman24a/shvartsman24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
