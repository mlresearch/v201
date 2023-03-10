---
title: Reconstructing Ultrametric Trees from Noisy Experiments
abstract: 'The problem of reconstructing evolutionary trees or phylogenies is of great
  interest in computational biology. A popular model for this problem assumes that
  we are given the set of leaves (current species) of an unknown weighted binary tree
  and the results of ‘experiments’ on triples of leaves $(a,b,c)$, which return the
  pair with the deepest least common ancestor. If the tree is assumed to be an \textit{ultrametric}
  (i.e., with all root-leaf paths of the same length), the experiment can be equivalently
  seen to return the closest pair of leaves. In this model, efficient algorithms are
  known for reconstructing the tree. In reality,  since the data on which these ‘experiments’
  are run is itself generated by the stochastic process of evolution, it is noisy.
  In all reasonable models of evolution, if the branches leading to the three leaves
  in a triple, separate from each other at common ancestors that are very close to
  each other  in the tree,  the result of the experiment should be close to uniformly
  random. Motivated by this, in the current paper, we consider a model where the noise
  in an experiment on any triple is just dependent on the three pairwise distances
  (referred to as \emph{distance-based noise}). Our results are the following: \begin{enumerate}
  \item Suppose the length of every edge in the unknown tree is at least  $\tilde{O}
  (\frac{1}{\sqrt n})$ fraction of the length of a root-leaf path, where $n$ is the
  number of leaves. Then, we give an efficient algorithm to reconstruct the topology
  of the unknown tree for a broad family of {distance-based noise} models. Further,
  we show that if the edges are asymptotically shorter, then topology reconstruction
  is information-theoretically impossible. \item Further, for a specific distance-based
  noise model – which we refer to as the {\em{homogeneous noise model}} – we show
  that the edge weights can also be approximately  reconstructed under the same quantitative
  lower bound on the edge lengths. Note that in the noiseless case, such reconstruction
  of edge weights is impossible. \end{enumerate} The phylogeny reconstruction problem
  is essentially the problem of hierarchical clustering. Our result here apply to
  a suitably defined version of this problem.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: arunachaleswaran23a
month: 0
tex_title: Reconstructing Ultrametric Trees from Noisy Experiments
firstpage: 82
lastpage: 114
page: 82-114
order: 82
cycles: false
bibtex_author: Arunachaleswaran, Eshwar Ram and De, Anindya and Kannan, Sampath
author:
- given: Eshwar Ram
  family: Arunachaleswaran
- given: Anindya
  family: De
- given: Sampath
  family: Kannan
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
pdf: https://proceedings.mlr.press/v201/arunachaleswaran23a/arunachaleswaran23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
