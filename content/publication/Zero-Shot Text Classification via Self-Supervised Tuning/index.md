---
title: Zero-Shot Text Classification via Self-Supervised Tuning
publication_types:
  - "1"
authors:
  - Chaoqun Liu
  - Wenxuan Zhang
  - Guizhen Chen
  - Xiaobao Wu
  - Luu Anh Tuan
  - Chip Hong Chang
  - Lidong Bing
publication: "Association for Computational Linguistics"
publication_short: ACL
abstract: Existing solutions to zero-shot text classification either conduct prompting with pre-trained language models, which is sensitive to the choices of templates, or rely on large-scale annotated data of relevant tasks for meta-tuning. In this work, we propose a new paradigm based on self-supervised learning to solve zero-shot text classification tasks by tuning the language models with unlabeled data, called self-supervised tuning. By exploring the inherent structure of free texts, we propose a new learning objective called first sentence prediction to bridge the gap between unlabeled data and text classification tasks. After tuning the model to learn to predict the first sentence in a paragraph based on the rest, the model is able to conduct zero-shot inference on unseen tasks such as topic classification and sentiment analysis. Experimental results show that our model outperforms the state-of-the-art baselines on 7 out of 10 tasks. Moreover, the analysis reveals that our model is less sensitive to the prompt design.
draft: false
featured: false
tags:
  - ACL
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://arxiv.org/abs/2305.11442#:~:text=Existing%20solutions%20to%20zero%2Dshot,relevant%20tasks%20for%20meta%2Dtuning.