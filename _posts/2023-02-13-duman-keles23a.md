---
title: On The Computational Complexity of Self-Attention
abstract: Transformer architectures have led to remarkable progress in many state-of-art
  applications. However, despite their successes, modern transformers rely on the
  self-attention mechanism, whose time- and space-complexity is quadratic in the length
  of the input. Several approaches have been proposed to speed up self-attention mechanisms
  to achieve sub-quadratic running time; however, the large majority of these works
  are not accompanied by rigorous error guarantees. In this work, we establish lower
  bounds on the computational complexity of self-attention in a number of scenarios.
  We prove that the time complexity of self-attention is necessarily quadratic in
  the input length, unless the Strong Exponential Time Hypothesis (SETH) is false.
  This argument holds even if the attention computation is performed only approximately,
  and for a variety of attention mechanisms. As a complement to our lower bounds,
  we show that it is indeed possible to approximate dot-product self-attention using
  finite Taylor series in linear-time, at the cost of having an exponential dependence
  on the polynomial order.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: duman-keles23a
month: 0
tex_title: On The Computational Complexity of Self-Attention
firstpage: 597
lastpage: 619
page: 597-619
order: 597
cycles: false
bibtex_author: Duman Keles, Feyza and Wijewardena, Pruthuvi Mahesakya and Hegde, Chinmay
author:
- given: Feyza
  family: Duman Keles
- given: Pruthuvi Mahesakya
  family: Wijewardena
- given: Chinmay
  family: Hegde
date: 2023-02-13
address:
container-title: Proceedings of The 34th International Conference on Algorithmic Learning
  Theory
volume: '201'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 2
  - 13
pdf: https://proceedings.mlr.press/v201/duman-keles23a/duman-keles23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
