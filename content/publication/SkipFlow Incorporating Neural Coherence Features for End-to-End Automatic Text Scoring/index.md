---
title: SkipFlow:Incorporating Neural Coherence Features for End-to-End Automatic Text Scoring
publication_types:
  - "1"
authors:
  - Yi Tay
  - Luu Anh Tuan
  - Siu Cheung Hui
publication: " AAAI Conference on Artificial Intelligence"
publication_short: AAAI
abstract: Deep learning has demonstrated tremendous potential for Automatic Text Scoring (ATS) tasks. In this paper, we describe a new neural architecture that enhances vanilla neural network models with auxiliary neural coherence features. Our new method proposes a new \textsc{SkipFlow} mechanism that models relationships between snapshots of the hidden representations of a long short-term memory (LSTM) network as it reads. Subsequently, the semantic relationships between multiple snapshots are used as auxiliary features for prediction. This has two main benefits. Firstly, essays are typically long sequences and therefore the memorization capability of the LSTM network may be insufficient. Implicit access to multiple snapshots can alleviate this problem by acting as a protection against vanishing gradients. The parameters of the \textsc{SkipFlow} mechanism also acts as an auxiliary memory. Secondly, modeling relationships between multiple positions allows our model to learn features that represent and approximate textual coherence. In our model, we call this \textit{neural coherence} features. Overall, we present a unified deep learning architecture that generates neural coherence features as it reads in an end-to-end fashion. Our approach demonstrates state-of-the-art performance on the benchmark ASAP dataset, outperforming not only feature engineering baselines but also other deep learning models.
draft: false
featured: false
tags:
  - AAAI
date: '2017-11-01T00:00:00Z'
---
Link: https://arxiv.org/abs/1711.04981