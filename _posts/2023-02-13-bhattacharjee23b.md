---
title: Online k-means Clustering on Arbitrary Data Streams
abstract: We consider $k$-means clustering in an online setting where each new data
  point is assigned to its closest cluster center and incurs a loss equal to the squared
  distance to that center, after which the algorithm is allowed to update its centers.
  The goal over a data stream $X$ is to achieve a total loss that is not too much
  larger than $L(X, OPT_k)$, the best possible loss using $k$ fixed centers in hindsight.
  We start by introducing a data parameter, $\Lambda(X)$, such that for any online
  algorithm that maintains $O(k \, \text{poly}(\log n))$ centers after seeing $n$
  points, there exists a data stream $X$ for which a loss of $\Omega(\Lambda(X))$
  is inevitable. Next, we give a randomized algorithm that achieves online loss $O(\Lambda(X)
  + L(X, OPT_k))$, while taking $O(k \, \text{poly}(\log n))$ centers and additional
  memory. It has an update time of $O(k \, \text{poly}(\log n))$ and is the first
  algorithm to achieve polynomial space and time complexity in the online setting.
  We note that our results have implications to the related streaming setting, where
  one final clustering is outputted, and the no-substitution setting, where center
  selections are permanent. We show a general reduction between the no-substitution
  cost of a blackbox algorithm and its online cost. Finally, we translate our algorithm
  to the no-substitution setting and streaming settings, and it competes with and
  can outperform existing work in the areas.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharjee23b
month: 0
tex_title: Online k-means Clustering on Arbitrary Data Streams
firstpage: 204
lastpage: 236
page: 204-236
order: 204
cycles: false
bibtex_author: Bhattacharjee, Robi and Imola, Jacob and Moshkovitz, Michal and Dasgupta,
  Sanjoy
author:
- given: Robi
  family: Bhattacharjee
- given: Jacob
  family: Imola
- given: Michal
  family: Moshkovitz
- given: Sanjoy
  family: Dasgupta
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
pdf: https://proceedings.mlr.press/v201/bhattacharjee23b/bhattacharjee23b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
