---
title: "{In Defense of Minhash over Simhash}"
abstract: MinHash and SimHash are the two widely adopted Locality Sensitive Hashing
  (LSH) algorithms for large-scale data processing applications. Deciding which LSH
  to use for a particular problem at hand is an important question, which has no clear
  answer in the existing  literature. In this study, we provide a theoretical answer
  (validated by experiments) that MinHash virtually always outperforms  SimHash when
  the data are binary, as common in practice such as search.      The collision probability
  of MinHash is a function of  \em resemblance similarity (\mathcalR), while the collision
  probability of SimHash is a function of  \em cosine  similarity (\mathcalS). To
  provide a common basis for  comparison,  we evaluate  retrieval results in terms
  of \mathcalS for both MinHash and SimHash. This evaluation is valid  as we can prove
  that MinHash is  a valid LSH with respect to \mathcalS, by using a  general inequality  \mathcalS^2≤\mathcalR≤\frac\mathcalS2-\mathcalS.
  Our \textbfworst case  analysis  can show that MinHash significantly outperforms
  SimHash in  \textbfhigh similarity region.        Interestingly, our intensive experiments
  reveal that MinHash is also substantially better than SimHash even in datasets where
  most of the data points are not too similar to each other. This is partly because,
  in practical data, often \mathcalR≥\frac\mathcalSz-\mathcalS holds where z is only
  slightly larger than 2 (e.g., z≤2.1). Our \textbfrestricted worst case analysis
  by assuming \frac\mathcalSz-\mathcalS≤\mathcalR≤\frac\mathcalS2-\mathcalS shows
  that MinHash indeed significantly outperforms SimHash even in \textbflow similarity
  region.        We believe the results in this paper  will provide valuable guidelines
  for search in practice,  especially when the data are sparse.
layout: inproceedings
id: shrivastava14
month: 0
firstpage: 886
lastpage: 894
page: 886-894
sections: 
author:
- given: Anshumali
  family: Shrivastava
- given: Ping
  family: Li
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
pdf: http://proceedings.mlr.press/v33/shrivastava14/shrivastava14.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
