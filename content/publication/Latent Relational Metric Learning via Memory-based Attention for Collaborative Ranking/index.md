---
title: Latent Relational Metric Learning via Memory-based Attention for Collaborative Ranking
publication_types:
  - Conference
authors:
  - Yi Tay
  - Luu_Anh_Tuan
  - Siu Cheung Hui
publication: " The Web Conference"
publication_short: WWW
abstract: This paper proposes a new neural architecture for collaborative ranking with implicit feedback. Our model, LRML (\textit{Latent Relational Metric Learning}) is a novel metric learning approach for recommendation. More specifically, instead of simple push-pull mechanisms between user and item pairs, we propose to learn latent relations that describe each user item interaction. This helps to alleviate the potential geometric inflexibility of existing metric learing approaches. This enables not only better performance but also a greater extent of modeling capability, allowing our model to scale to a larger number of interactions. In order to do so, we employ a augmented memory module and learn to attend over these memory blocks to construct latent relations. The memory-based attention module is controlled by the user-item interaction, making the learned relation vector specific to each user-item pair. Hence, this can be interpreted as learning an exclusive and optimal relational translation for each user-item interaction. The proposed architecture demonstrates the state-of-the-art performance across multiple recommendation benchmarks. LRML outperforms other metric learning models by 6%−7.5% in terms of Hits@10 and nDCG@10 on large datasets such as Netflix and MovieLens20M. Moreover, qualitative studies also demonstrate evidence that our proposed model is able to infer and encode explicit sentiment, temporal and attribute information despite being only trained on implicit feedback. As such, this ascertains the ability of LRML to uncover hidden relational structure within implicit datasets.
draft: false
featured: false
tags:
  - WWW
date: '2017-07-01T00:00:00Z'
---
Link: shttps://arxiv.org/abs/1707.05176