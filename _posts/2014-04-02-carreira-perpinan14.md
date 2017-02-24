---
supplementary: Supplementary:carreira-perpinan14-supp.pdf
section: notable
title: "{Distributed optimization of deeply nested systems}"
abstract: Intelligent processing of complex signals such as images is often performed
  by a hierarchy of nonlinear processing layers, such as a deep net or an object recognition
  cascade. Joint estimation of the parameters of all the layers is a difficult nonconvex
  optimization. We describe a general strategy to learn the parameters and, to some
  extent, the architecture of nested systems, which we call the method of auxiliary
  coordinates (MAC). This replaces the original problem involving a deeply nested
  function with a constrained problem involving a different function in an augmented
  space without nesting. The constrained problem may be solved with penalty-based
  methods using alternating optimization over the parameters and the auxiliary coordinates.
  MAC has provable convergence, is easy to implement reusing existing algorithms for
  single layers, can be parallelized trivially and massively, applies even when parameter
  derivatives are not available or not desirable, can perform some model selection
  on the fly, and is competitive with state-of-the-art nonlinear optimizers even in
  the serial computation setting, often providing reasonable models within a few iterations.
layout: inproceedings
id: carreira-perpinan14
month: 0
firstpage: 10
lastpage: 19
page: 10-19
sections: 
author:
- given: Miguel
  family: Carreira-Perpinan
- given: Weiran
  family: Wang
date: 2014-04-02
address: Reykjavik, Iceland
publisher: PMLR
container-title: Proceedings of the Seventeenth International Conference on Artificial
  Intelligence and Statistics
volume: '33'
genre: inproceedings
issued:
  date-parts:
  - 2014
  - 4
  - 2
pdf: http://proceedings.mlr.press/v33/carreira-perpinan14/carreira-perpinan14.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
