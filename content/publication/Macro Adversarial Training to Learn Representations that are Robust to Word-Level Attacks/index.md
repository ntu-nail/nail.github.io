---
title: 'SemRoDe: Macro Adversarial Training to Learn Representations that are Robust to Word-Level Attacks'
publication_types:
  - Conference
authors:
  - Brian Formento
  - Wenjie Feng
  - Chuan Sheng Foo
  - Luu_Anh_Tuan
  - See-Kiong Ng

publication: "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics"
publication_short: NAACL
abstract: Language models (LMs) are indispensable tools for natural language processing tasks, but their vulnerability to adversarial attacks remains a concern. While current research has explored adversarial training techniques, their improvements to defend against word-level attacks have been limited. In this work, we propose a novel approach called Semantic Robust Defence (SemRoDe), a Macro Adversarial Training strategy to enhance the robustness of LMs. Drawing inspiration from recent studies in the image domain, we investigate and later confirm that in a discrete data setting such as language, adversarial samples generated via word substitutions do indeed belong to an adversarial domain exhibiting a high Wasserstein distance from the base domain. Our method learns a robust representation that bridges these two domains. We hypothesize that if samples were not projected into an adversarial domain, but instead to a domain with minimal shift, it would improve attack robustness. We align the domains by incorporating a new distance-based objective. With this, our model is able to learn more generalized representations by aligning the model’s high-level output features and therefore better handling unseen adversarial samples. This method can be generalized across word embeddings, even when they share minimal overlap at both vocabulary and word-substitution levels. To evaluate the effectiveness of our approach, we conduct experiments on BERT and RoBERTa models on three datasets. The results demonstrate promising state-of-the-art robustness.
draft: false
featured: false
tags:
  - NAACL
date: '2024-06-01T00:00:00Z'
---
Link: https://aclanthology.org/2024.naacl-long.443/