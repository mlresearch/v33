---
title: "{Efficiently Enforcing Diversity in Multi-Output Structured Prediction}"
abstract: This paper proposes a novel method for efficiently generating multiple diverse
  predictions for structured prediction problems. Existing methods like SDPPs or DivMBest
  work by making a series of predictions where each prediction is made after considering
  the predictions that came before it. Such approaches are inherently sequential and
  computationally expensive. In contrast, our method, Diverse Multiple Choice Learning,
  learns a set of models to make multiple independent, yet diverse, predictions at
  testtime. We achieve this by including a diversity encouraging term in the loss
  function used for training the models. This approach encourages diversity in the
  predictions while preserving computational efficiency at test-time. Experimental
  results on a number of challenging problems show that our method learns models that
  not only predict more diverse results than competing methods, but are also able
  to generalize better and produce results with high test accuracy.
layout: inproceedings
id: guzman-rivera14
month: 0
firstpage: 284
lastpage: 292
page: 284-292
sections: 
author:
- given: Abner
  family: Guzman-Rivera
- given: Pushmeet
  family: Kohli
- given: Dhruv
  family: Batra
- given: Rob
  family: Rutenbar
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
pdf: http://proceedings.mlr.press/v33/guzman-rivera14/guzman-rivera14.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
