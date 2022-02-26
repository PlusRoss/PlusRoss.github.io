---
title: "Graph-Revised Convolutional Network"
collection: publications
permalink: /publication/paper6
excerpt: '**Donghan Yu**, Ruohong Zhang, Zhengbao Jiang, Yuexin Wu, Yiming Yang'
date: 2020-10-01
venue: 'ECML-PKDD'
---

Abstract: Graph Convolutional Networks (GCNs) have received increasing attention in the machine learning community for effectively leveraging both the content features of nodes and the linkage patterns across graphs in various applications. As real-world graphs are often incomplete and noisy, treating them as ground-truth information, which is a common practice in most GCNs, unavoidably leads to sub-optimal solutions. Existing efforts for addressing this problem either involve an over-parameterized model which is difficult to scale, or simply re-weight observed edges without dealing with the missing-edge issue. This paper proposes a novel framework called Graph-Revised Convolutional Network (GRCN), which avoids both extremes. Specifically, a GCN-based graph revision module is introduced for predicting missing edges and revising edge weights w.r.t. downstream tasks via joint optimization. A theoretical analysis reveals the connection between GRCN and previous work on multigraph belief propagation. Experiments on six benchmark datasets show that GRCN consistently outperforms strong baseline methods by a large margin, especially when the original graphs are severely incomplete or the labeled instances for model training are highly sparse. [[Full Paper]](https://arxiv.org/abs/1911.07123) [[Code]](https://github.com/PlusRoss/GRCN)
