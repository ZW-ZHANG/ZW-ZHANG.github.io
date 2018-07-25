---
title: "TIMERS Error Bounded SVD Restart on Dynamic Networks"
collection: publications
permalink: /publication/2018-02-TIMERS-Error-Bounded-SVD-Restart-on-Dynamic-Networks
date: 2018-02-01
venue: AAAI
paperurl: 'https://zw-zhang.github.io/files/2018_AAAI_TIMERS.pdf'
citation: 'Zhang, Ziwei, et al. "TIMERS: Error-Bounded SVD Restart on Dynamic Networks." Proceedings of the 32nd AAAI Conference on Artificial Intelligence (2018).'
---

Singular Value Decomposition (SVD) is a popular approach
in various network applications, such as link prediction and
network parameter characterization. Incremental SVD approaches
are proposed to process newly changed nodes and edges
in dynamic networks. However, incremental SVD approaches
suffer from serious error accumulation inevitably due to
approximation on incremental updates. SVD restart is an effective
approach to reset the aggregated error, but when to restart
SVD for dynamic networks is not addressed in literature.
  
In this paper, we propose TIMERS, Theoretically Instructed
Maximum-Error-bounded Restart of SVD, a novel approach
which optimally sets the restart time in order to reduce error
accumulation in time. Specifically, we monitor the margin
between reconstruction loss of incremental updates and the
minimum loss in SVD model. To reduce the complexity of
monitoring, we theoretically develop a lower bound of SVD
minimum loss for dynamic networks and use the bound to replace
the minimum loss in monitoring. By setting a maximum
tolerated error as a threshold, we can trigger SVD restart automatically
when the margin exceeds this threshold.We prove
that the time complexity of our method is linear with respect
to the number of local dynamic changes, and our method is
general across different types of dynamic networks. We conduct
extensive experiments on several synthetic and real dynamic
networks. The experimental results demonstrate that our
proposed method significantly outperforms the existing methods
by reducing 27% to 42% in terms of the maximum error
for dynamic network reconstruction when fixing the number
of restarts. Our method reduces the number of restarts by 25%
to 50% when fixing the maximum error tolerated.

Recommended citation: 
```
@inproceedings{zhang2018timers,
  title={TIMERS: Error-Bounded SVD Restart on Dynamic Networks},
  author={Zhang, Ziwei and Cui, Peng and Pei, Jian and Wang, Xiao and Zhu, Wenwu},
  booktitle={Proceedings of the 32nd AAAI Conference on Artificial Intelligence},
  year={2018},
  organization={AAAI}
}
```