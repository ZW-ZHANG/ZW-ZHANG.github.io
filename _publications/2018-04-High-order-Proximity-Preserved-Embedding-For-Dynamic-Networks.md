---
title: "High-order Proximity Preserved Embedding For Dynamic Networks"
collection: publications
permalink: /publication/2018-04-High-order-Proximity-Preserved-Embedding-For-Dynamic-Networks
excerpt: 'Key words: network embedding, dynamic networks, Generalized SVD (GSVD), matrix perturbation'
date: 2018-04-01
venue: TKDE
paperurl: 'https://zw-zhang.github.io/files/2018_TKDE_DHPE.pdf'
citation: 'Zhu, Dingyuan, et al. "High-order Proximity Preserved Embedding For Dynamic Networks." IEEE Transactions on Knowledge and Data Engineering (2018).'
---
Network embedding, aiming to embed a network into a low dimensional vector space while preserving the inherent
structural properties of the network, has attracted considerable attention. However, most existing embedding methods focus on the
static network while neglecting the evolving characteristic of real-world networks. Meanwhile, most of previous methods cannot well
preserve the high-order proximity, which is a critical structural property of networks. These problems motivate us to seek an effective
and efficient way to preserve the high-order proximity in embedding vectors when the networks evolve over time. 

In this paper, we
propose a novel method of Dynamic High-order Proximity preserved Embedding (DHPE). Specifically, we adopt the generalized SVD
(GSVD) to preserve the high-order proximity. Then, by transforming the GSVD problem to a generalized eigenvalue problem, we
propose a generalized eigen perturbation to incrementally update the results of GSVD to incorporate the changes of dynamic
networks. Further, we propose an accelerated solution to the DHPE model so that it achieves a linear time complexity with respect to
the number of nodes and number of changed edges in the network. Our empirical experiments on one synthetic network and several
real-world networks demonstrate the effectiveness and efficiency of the proposed method.


Recommended citation: 
```
@article{zhu2018high,
  title={High-order Proximity Preserved Embedding For Dynamic Networks},
  author={Zhu, Dingyuan and Cui, Peng and Zhang, Ziwei and Pei, Jian and Zhu, Wenwu},
  journal={IEEE Transactions on Knowledge and Data Engineering},
  year={2018},
  publisher={IEEE}
}
```