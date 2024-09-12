---
title: Adaptive Softmax Trees for Many-Class Classification
abstract: 'NLP tasks such as language models or document classification involve classification
  problems with thousands of classes. In these situations, it is difficult to get
  high predictive accuracy and the resulting model can be huge in number of parameters
  and inference time. A recent, successful approach is the softmax tree (ST): a decision
  tree having sparse hyperplane splits at the decision nodes (which make hard, not
  soft, decisions) and small softmax classifiers at the leaves. Inference here is
  very fast because only a small subset of class probabilities need to be computed,
  yet the model is quite accurate. However, a significant drawback is that it assumes
  a complete tree, whose size grows exponentially with depth. We propose a new algorithm
  to train a ST of arbitrary structure. The tree structure itself is learned optimally
  by interleaving steps that grow the structure with steps that optimize the parameters
  of the current structure. This makes it possible to learn STs that can grow much
  deeper but in an irregular way, adapting to the data distribution. The resulting
  STs improve considerably the predictive accuracy while reducing the model size and
  inference time even further, as demonstrated in datasets with thousands of classes.
  In addition, they are interpretable to some extent.'
openreview: WK7rXij5VC
section: Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kairgeldin24a
month: 0
tex_title: Adaptive Softmax Trees for Many-Class Classification
firstpage: 1825
lastpage: 1841
page: 1825-1841
order: 1825
cycles: false
bibtex_author: Kairgeldin, Rasul and Gabidolla, Magzhan and Carreira-Perpi\~n\'an,
  Miguel
author:
- given: Rasul
  family: Kairgeldin
- given: Magzhan
  family: Gabidolla
- given: Miguel
  family: Carreira-Perpiñán
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
pdf: https://raw.githubusercontent.com/mlresearch/v244/main/assets/kairgeldin24a/kairgeldin24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
