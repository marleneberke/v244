---
title: Cost-Sensitive Uncertainty-Based Failure Recognition for Object Detection
abstract: Object detectors in real-world applications often fail to detect objects
  due to varying factors such as weather conditions and noisy input. Therefore, a
  process that mitigates false detections is crucial for both safety and accuracy.
  While uncertainty-based thresholding shows promise, previous works demonstrate an
  imperfect correlation between uncertainty and detection errors. This hinders ideal
  thresholding, prompting us to further investigate the correlation and associated
  cost with different types of uncertainty. We therefore propose a cost-sensitive
  framework for object detection tailored to user-defined budgets on the two types
  of errors, missing and false detections. We derive minimum thresholding requirements
  to prevent performance degradation and define metrics to assess the applicability
  of uncertainty for failure recognition. Furthermore, we automate and optimize the
  thresholding process to maximize the failure recognition rate w.r.t. the specified
  budget. Evaluation on three autonomous driving datasets demonstrates that our approach
  significantly enhances safety, particularly in challenging scenarios. Leveraging
  localization aleatoric uncertainty and softmax-based entropy only, our method boosts
  the failure recognition rate by 36-60% compared to conventional approaches. Code
  is available at https://mos-ks.github.io/publications.
openreview: HuibNFkaoi
software: https://mos-ks.github.io/publications
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kassem-sbeyti24a
month: 0
tex_title: Cost-Sensitive Uncertainty-Based Failure Recognition for Object Detection
firstpage: 1890
lastpage: 1900
page: 1890-1900
order: 1890
cycles: false
bibtex_author: Kassem-Sbeyti, Moussa and Karg, Michelle and Wirth, Christian and Klein,
  Nadja and Albayrak, Sahin
author:
- given: Moussa
  family: Kassem-Sbeyti
- given: Michelle
  family: Karg
- given: Christian
  family: Wirth
- given: Nadja
  family: Klein
- given: Sahin
  family: Albayrak
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/kassem-sbeyti24a/kassem-sbeyti24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
