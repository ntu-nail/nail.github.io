---
title: Hyperbolic Representation Learning for Fast and Efficient Neural Question Answering
publication_types:
  - "1"
authors:
  - Yi Tay
  - Luu Anh Tuan
  - Siu Cheung Hui
publication: " Web Search and Data Mining"
publication_short: WSDM
abstract: The dominant neural architectures in question answer retrieval are based on recurrent or convolutional encoders configured with complex word matching layers. Given that recent architectural innovations are mostly new word interaction layers or attention-based matching mechanisms, it seems to be a well-established fact that these components are mandatory for good performance. Unfortunately, the memory and computation cost incurred by these complex mechanisms are undesirable for practical applications. As such, this paper tackles the question of whether it is possible to achieve competitive performance with simple neural architectures. We propose a simple but novel deep learning architecture for fast and efficient question-answer ranking and retrieval. More specifically, our proposed model, \textsc{HyperQA}, is a parameter efficient neural network that outperforms other parameter intensive models such as Attentive Pooling BiLSTMs and Multi-Perspective CNNs on multiple QA benchmarks. The novelty behind \textsc{HyperQA} is a pairwise ranking objective that models the relationship between question and answer embeddings in Hyperbolic space instead of Euclidean space. This empowers our model with a self-organizing ability and enables automatic discovery of latent hierarchies while learning embeddings of questions and answers. Our model requires no feature engineering, no similarity matrix matching, no complicated attention mechanisms nor over-parameterized layers and yet outperforms and remains competitive to many models that have these functionalities on multiple benchmarks.
draft: false
featured: false
tags:
  - WSDM
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://arxiv.org/abs/1707.07847