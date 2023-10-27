---
title: Gradient-Boosted Decision Tree for Listwise Context Model in Multimodal Review Helpfulness Prediction
publication_types:
  - "1"
authors:
  - Thong Nguyen
  - Xiaobao Wu
  - Xinshuai Dong
  - Cong-Duy T. Nguyen
  - Zhen Hai
  - Lidong Bing
  - Luu_Anh_Tuan
publication: "Association for Computational Linguistics"
publication_short: ACL
abstract: Multimodal Review Helpfulness Prediction (MRHP) aims to rank product reviews based on predicted helpfulness scores and has been widely applied in e-commerce via presenting customers with useful reviews. Previous studies commonly employ fully-connected neural networks (FCNNs) as the final score predictor and pairwise loss as the training objective. However, FCNNs have been shown to perform inefficient splitting for review features, making the model difficult to clearly differentiate helpful from unhelpful reviews. Furthermore, pairwise objective, which works on review pairs, may not completely capture the MRHP goal to produce the ranking for the entire review list, and possibly induces low generalization during testing. To address these issues, we propose a listwise attention network that clearly captures the MRHP ranking context and a listwise optimization objective that enhances model generalization. We further propose gradient-boosted decision tree as the score predictor to efficaciously partition product reviews' representations. Extensive experiments demonstrate that our method achieves state-of-the-art results and polished generalization performance on two large-scale MRHP benchmark datasets.
draft: false
featured: false
tags:
  - ACL
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: '2023-05-01T00:00:00Z'
---
Link: https://arxiv.org/abs/2305.12678