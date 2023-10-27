---
title: Effective Neural Topic Modeling with Embedding Clustering Regularization
publication_types:
  - "1"
authors:
  - Xiaobao Wu
  - Xinshuai Dong
  - Thong Nguyen
  - Luu Anh Tuan
publication: "International Conference on Machine Learning"
publication_short: ICML
abstract: Topic models have been prevalent for decades with various applications. However, existing topic models commonly suffer from the notorious topic collapsing:discovered topics semantically collapse towards each other, leading to highly repetitive topics, insufficient topic discovery, and damaged model interpretability. In this paper, we propose a new neural topic model, Embedding Clustering Regularization Topic Model (ECRTM). Besides the existing reconstruction error, we propose a novel Embedding Clustering Regularization (ECR), which forces each topic embedding to be the center of a separately aggregated word embedding cluster in the semantic space. This enables each produced topic to contain distinct word semantics, which alleviates topic collapsing. Regularized by ECR, our ECRTM generates diverse and coherent topics together with high-quality topic distributions of documents. Extensive experiments on benchmark datasets demonstrate that ECRTM effectively addresses the topic collapsing issue and consistently surpasses state-of-the-art baselines in terms of topic quality, topic distributions of documents, and downstream classification tasks.
draft: false
featured: false
tags:
  - ICML

date: '2023-06-01T00:00:00Z'
---
Link: https://arxiv.org/abs/2306.04217