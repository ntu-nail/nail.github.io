---
title: Cross Temporal Recurrent Networks for Ranking Question Answer Pairs
publication_types:
  - "1"
authors:
  - Yi Tay
  - Luu Anh Tuan
  - Siu Cheung Hui
publication: " AAAI Conference on Artificial Intelligence"
publication_short: AAAI
abstract: Temporal gates play a significant role in modern recurrent-based neural encoders, enabling fine-grained control over recursive compositional operations over time. In recurrent models such as the long short-term memory (LSTM), temporal gates control the amount of information retained or discarded over time, not only playing an important role in influencing the learned representations but also serving as a protection against vanishing gradients. This paper explores the idea of learning temporal gates for sequence pairs (question and answer), jointly influencing the learned representations in a pairwise manner. In our approach, temporal gates are learned via 1D convolutional layers and then subsequently cross applied across question and answer for joint learning. Empirically, we show that this conceptually simple sharing of temporal gates can lead to competitive performance across multiple benchmarks. Intuitively, what our network achieves can be interpreted as learning representations of question and answer pairs that are aware of what each other is remembering or forgetting, i.e., pairwise temporal gating. Via extensive experiments, we show that our proposed model achieves state-of-the-art performance on two community-based QA datasets and competitive performance on one factoid-based QA dataset.
draft: false
featured: false
tags:
  - AAAI
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://arxiv.org/abs/1711.07656