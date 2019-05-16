---
title: "Robust Graph Convolutional Networks Against Adversarial Attacks"
collection: publications
permalink: /publication/2019-08-Robust-Graph-Convolutional-Networks-Against-Adversarial-Attacks
excerpt: 'Key words: Graph Convolutional Networks, Robustness, Adversarial Attacks, Deep Learning'
date: 2019-08-04
venue: KDD
paperurl: 'https://zw-zhang.github.io/files/2019_KDD_RGCN.pdf'
citation: 'Zhu, Dingyuan, et al. "Robust Graph Convolutional Networks Against Adversarial Attacks". Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. ACM, 2019.'
---
Graph Convolutional Networks (GCNs) are an emerging type of neural network model 
on graphs which have achieved state-of-the-art performance in the task of node classification. 
However, recent studies show that GCNs are vulnerable to adversarial attacks,
i.e. small deliberate perturbations in graph structures and
node attributes, which poses great challenges for applying GCNs
to real world applications. How to enhance the robustness of GCNs
remains a critical open problem.

To address this problem, we propose Robust GCN (RGCN), a
novel model that “fortifies” GCNs against adversarial attacks. Specifically,
instead of representing nodes as vectors, our method adopts
Gaussian distributions as the hidden representations of nodes in
each convolutional layer. In this way, when the graph is attacked,
our model can automatically absorb the effects of adversarial changes
in the variances of the Gaussian distributions. Moreover, to remedy
the propagation of adversarial attacks in GCNs, we propose a
variance-based attention mechanism, i.e. assigning differentweights
to node neighborhoods according to their variances when performing
convolutions. Extensive experimental results demonstrate that
our proposed method can effectively improve the robustness of
GCNs. On three benchmark graphs, our RGCN consistently shows
a substantial gain in node classification accuracy compared with
state-of-the-art GCNs against various adversarial attack strategies.

Code is available [here](https://github.com/thumanlab/RobustGCN).

Recommended citation: 
```
@inproceedings{zhu2019robust,
  title={Robust Graph Convolutional Networks Against Adversarial Attacks},
  author={Zhu, Dingyuan and Zhang, Ziwei and Cui, Peng and Zhu, Wenwu},
  booktitle={Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining},
  year={2019},
  organization={ACM}
}
```