---
title: Robust Empirical Risk Minimization with Tolerance
abstract: Developing simple, sample-efficient learning algorithms for robust classification
  is a pressing issue in today’s tech-dominated world, and current theoretical techniques
  requiring exponential sample complexity and complicated improper learning rules
  fall far from answering the need. In this work we study the fundamental paradigm
  of (robust) \textit{empirical risk minimization} (RERM), a simple process in which
  the learner outputs any hypothesis minimizing its training error. RERM famously
  fails to robustly learn VC classes \citep{Omar19}, a bound we show extends even
  to ‘nice’ settings such as (bounded) halfspaces. As such, we study a recent relaxation
  of the robust model called \textit{tolerant} robust learning \citep{Urner22} where
  the output classifier is compared to the best achievable error over slightly larger
  perturbation sets. We show that under geometric niceness conditions, a natural tolerant
  variant of RERM is indeed sufficient for $\gamma$-tolerant robust learning VC classes
  over $\mathbb{R}^d$, and requires only $\tilde{O}\left( \frac{VC(H)d\log \frac{D}{\gamma\delta}}{\epsilon^2}\right)$
  samples for robustness regions of (maximum) diameter $D$.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharjee23a
month: 0
tex_title: Robust Empirical Risk Minimization with Tolerance
firstpage: 182
lastpage: 203
page: 182-203
order: 182
cycles: false
bibtex_author: Bhattacharjee, Robi and Hopkins, Max and Kumar, Akash and Yu, Hantao
  and Chaudhuri, Kamalika
author:
- given: Robi
  family: Bhattacharjee
- given: Max
  family: Hopkins
- given: Akash
  family: Kumar
- given: Hantao
  family: Yu
- given: Kamalika
  family: Chaudhuri
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
pdf: https://proceedings.mlr.press/v201/bhattacharjee23a/bhattacharjee23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
