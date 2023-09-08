---
title: Certified Robustness Against Natural Language Attacks by Causal Intervention
publication_types:
  - "1"
authors:
  - Haiteng Zhao
  - Chang Ma
  - Xinshuai Dong
  - Luu Anh Tuan
  - Zhi-Hong Deng
  - Hanwang Zhang
publication: "The International Conference on Machine Learning"
publication_short: ICML
abstract: Deep learning models have achieved great success in many fields, yet they are vulnerable to adversarial examples. This paper follows a causal perspective to look into the adversarial vulnerability and proposes Causal Intervention by Semantic Smoothing (CISS), a novel framework towards robustness against natural language attacks. Instead of merely fitting observational data, CISS learns causal effects p(y|do(x)) by smoothing in the latent semantic space to make robust predictions, which scales to deep architectures and avoids tedious construction of noise customized for specific attacks. CISS is provably robust against word substitution attacks, as well as empirically robust even when perturbations are strengthened by unknown attack algorithms. For example, on YELP, CISS surpasses the runner-up by 6.7% in terms of certified robustness against word substitutions, and achieves 79.4% empirical robustness when syntactic attacks are integrated.
draft: false
featured: false
tags:
  - ICML
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://arxiv.org/abs/2205.12331