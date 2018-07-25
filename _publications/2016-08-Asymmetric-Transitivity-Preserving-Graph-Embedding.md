---
title: "Asymmetric Transitivity Preserving Graph Embedding"
collection: publications
permalink: /publication/2016-08-Asymmetric-Transitivity-Preserving-Graph-Embedding
date: 2016-08-01
venue: KDD
paperurl: 'https://zw-zhang.github.io/files/2016_KDD_HOPE.pdf'
citation: 'Ou, Mingdong, et al. "Asymmetric transitivity preserving graph embedding." Proceedings of the 22nd ACM SIGKDD international conference on Knowledge discovery and data mining. ACM, 2016.'
---

Graph embedding algorithms embed a graph into a vector space where the structure 
and the inherent properties of the graph are preserved. The existing graph embedding 
methods cannot preserve the asymmetric transitivity well, which is a critical property of directed graphs. 
Asymmetric transitivity depicts the correlation among directed edges, that is,
if there is a directed path from u to v, then there is likely a directed edge from u to v. Asymmetric transitivity can help
in capturing structures of graphs and recovering from partially observed graphs. To tackle this challenge, we propose
the idea of preserving asymmetric transitivity by approximating high-order proximity which are based on asymmetric
transitivity. In particular, we develop a novel graph embedding algorithm, High-Order Proximity preserved Embedding
(HOPE for short), which is scalable to preserve high-order proximities of large scale graphs and capable of capturing
the asymmetric transitivity. More specifically, we first derive a general formulation that cover multiple popular highorder
proximity measurements, then propose a scalable embedding algorithm to approximate the high-order proximity
measurements based on their general formulation. Moreover, we provide a theoretical upper bound on the RMSE
(Root Mean Squared Error) of the approximation. Our empirical experiments on a synthetic dataset and three realworld
datasets demonstrate that HOPE can approximate the high-order proximities significantly better than the state-ofart
algorithms and outperform the state-of-art algorithms in tasks of reconstruction, link prediction and vertex recommendation.

Recommended citation: 
```
@inproceedings{ou2016asymmetric,
  title={Asymmetric transitivity preserving graph embedding},
  author={Ou, Mingdong and Cui, Peng and Pei, Jian and Zhang, Ziwei and Zhu, Wenwu},
  booktitle={Proceedings of the 22nd ACM SIGKDD international conference on Knowledge discovery and data mining},
  pages={1105--1114},
  year={2016},
  organization={ACM}
}
```