---
title: Mitigating Overconfidence in Out-of-Distribution Detection by Capturing Extreme
  Activations
abstract: Detecting out-of-distribution (OOD) instances is crucial for the reliable
  deployment of machine learning models in real-world scenarios. OOD inputs are commonly
  expected to cause a more uncertain prediction in the primary task; however, there
  are OOD cases for which the model returns a highly confident prediction. This phenomenon,
  denoted as "overconfidence", presents a challenge to OOD detection.  Specifically,
  theoretical evidence indicates that overconfidence is an intrinsic property of certain
  neural network architectures, leading to poor OOD detection. In this work, we address
  this issue by measuring extreme activation values in the penultimate layer of neural
  networks and then leverage this proxy of overconfidence to improve on several OOD
  detection baselines. We test our method on a wide array of experiments spanning
  synthetic data and real-world data, tabular and image datasets, multiple architectures
  such as ResNet and Transformer, different training loss functions, and include the
  scenarios examined in previous theoretical work. Compared to the baselines, our
  method often grants substantial improvements, with double-digit increases in OOD
  detection AUC, and it does not damage performance in any scenario.
openreview: nwf2mKQVhP
software: https://github.com/mazizmalayeri/CEA
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: azizmalayeri24a
month: 0
tex_title: Mitigating Overconfidence in Out-of-Distribution Detection by Capturing
  Extreme Activations
firstpage: 203
lastpage: 224
page: 203-224
order: 203
cycles: false
bibtex_author: Azizmalayeri, Mohammad and Abu-Hanna, Ameen and Cin\`a, Giovanni
author:
- given: Mohammad
  family: Azizmalayeri
- given: Ameen
  family: Abu-Hanna
- given: Giovanni
  family: Cinà
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/azizmalayeri24a/azizmalayeri24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
