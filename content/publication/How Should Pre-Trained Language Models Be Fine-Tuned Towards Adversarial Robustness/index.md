---
title: How Should Pre-Trained Language Models Be Fine-Tuned Towards Adversarial Robustness?
publication_types:
  - Conference
authors:
  - Xinhsuai Dong
  - Luu_Anh_Tuan
  - Min Lin
  - Shuicheng Yan
  - Hanwang Zhang
publication: "The Advances in Neural Information Processing Systems"
publication_short: NeurIPS
abstract: The fine-tuning of pre-trained language models has a great success in many NLP fields. Yet, it is strikingly vulnerable to adversarial examples, e.g., word substitution attacks using only synonyms can easily fool a BERT-based sentiment analysis model. In this paper, we demonstrate that adversarial training, the prevalent defense technique, does not directly fit a conventional fine-tuning scenario, because it suffers severely from catastrophic forgetting:failing to retain the generic and robust linguistic features that have already been captured by the pre-trained model. In this light, we propose Robust Informative Fine-Tuning (RIFT), a novel adversarial fine-tuning method from an information-theoretical perspective. In particular, RIFT encourages an objective model to retain the features learned from the pre-trained model throughout the entire fine-tuning process, whereas a conventional one only uses the pre-trained weights for initialization. Experimental results show that RIFT consistently outperforms the state-of-the-arts on two popular NLP tasks:sentiment analysis and natural language inference, under different attacks across various pre-trained language models.
draft: false
featured: false
tags:
  - NeurIPS
date: '2021-12-01T00:00:00Z'
---
Link: https://arxiv.org/abs/2112.11668