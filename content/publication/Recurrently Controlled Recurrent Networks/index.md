---
title: Recurrently Controlled Recurrent Networks
publication_types:
  - "1"
authors:
  - Yi Tay
  - Luu Anh Tuan
  - Siu Cheung Hui
publication: "The Advances in Neural Information Processing Systems"
publication_short: NeurIPS
abstract: Recurrent neural networks (RNNs) such as long short-term memory and gated recurrent units are pivotal building blocks across a broad spectrum of sequence modeling problems. This paper proposes a recurrently controlled recurrent network (RCRN) for expressive and powerful sequence encoding. More concretely, the key idea behind our approach is to learn the recurrent gating functions using recurrent networks. Our architecture is split into two components - a controller cell and a listener cell whereby the recurrent controller actively influences the compositionality of the listener cell. We conduct extensive experiments on a myriad of tasks in the NLP domain such as sentiment analysis (SST, IMDb, Amazon reviews, etc.), question classification (TREC), entailment classification (SNLI, SciTail), answer selection (WikiQA, TrecQA) and reading comprehension (NarrativeQA). Across all 26 datasets, our results demonstrate that RCRN not only consistently outperforms BiLSTMs but also stacked BiLSTMs, suggesting that our controller architecture might be a suitable replacement for the widely adopted stacked architecture.
draft: false
featured: false
tags:
  - NeurIPS
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://arxiv.org/abs/1811.09786