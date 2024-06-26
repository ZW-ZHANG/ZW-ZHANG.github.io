---
title: "Arbitrary-Order Proximity Preserved Network Embedding"
collection: publications
permalink: /publication/2018-08-Arbitrary-Order-Proximity-Preserved-Network-Embedding
excerpt: 'Key words: network embedding, arbitrary-order proximity, SVD, eigen-decomposition'
date: 2018-08-01
venue: KDD
paperurl: 'https://zw-zhang.github.io/files/2018_KDD_AROPE.pdf'
citation: 'Zhang, Ziwei, et al. "Arbitrary-Order Proximity Preserved Network Embedding." Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. ACM, 2018.'
---
Network embedding has received increasing research attention in
recent years. The existing methods show that the high-order proximity
plays a key role in capturing the underlying structure of the
network. However, two fundamental problems in preserving the
high-order proximity remain unsolved. First, all the existing methods
can only preserve fixed-order proximities, despite that proximities
of different orders are often desired for distinct networks
and target applications. Second, given a certain order proximity,
the existing methods cannot guarantee accuracy and efficiency
simultaneously. 

To address these challenges, we propose AROPE
(arbitrary-order proximity preserved embedding), a novel network
embedding method based on SVD framework. We theoretically
prove the eigen-decomposition reweighting theorem, revealing the
intrinsic relationship between proximities of different orders. With
this theorem, we propose a scalable eigen-decomposition solution
to derive the embedding vectors and shift them between proximities
of arbitrary orders. Theoretical analysis is provided to guarantee
that i) our method has a low marginal cost in shifting the embedding
vectors across different orders, ii) given a certain order, our
method can get the global optimal solutions, and iii) the overall
time complexity of our method is linear with respect to network
size. Extensive experimental results on several large-scale networks
demonstrate that our proposed method greatly and consistently
outperforms the baselines in various tasks including network reconstruction,
link prediction and node classification.

Code is available [here](https://github.com/ZW-ZHANG/AROPE).

Slide is available [here](https://zw-zhang.github.io/files/2018_KDD_Slides.pdf).

Recommended citation: 
```
@inproceedings{zhang2018arbitrary,
  title={Arbitrary-Order Proximity Preserved Network Embedding},
  author={Zhang, Ziwei and Cui, Peng and Wang, Xiao and Pei, Jian and Yao, Xuanrong and Zhu, Wenwu},
  booktitle={Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining},
  pages={2778--2786},
  year={2018},
  organization={ACM}
}
```