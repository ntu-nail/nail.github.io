---
title: 'KDMCSE: Knowledge Distillation Multimodal Sentence Embeddings with Adaptive Angular margin Contrastive Learning'
publication_types:
  - Conference
authors:
  - Cong-Duy Nguyen
  - Thong Nguyen
  - Xiaobao Wu
  - Luu_Anh_Tuan 
publication: "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics"
publication_short: NAACL
abstract: 'Previous work on multimodal sentence embedding has proposed multimodal contrastive learning and achieved promising results. However, by taking the rest of the batch as negative samples without reviewing when forming contrastive pairs, those studies encountered many suspicious and noisy negative examples, significantly affecting the methods’ overall performance. In this work, we propose KDMCSE (Knowledge Distillation Multimodal contrastive learning of Sentence Embeddings), a novel approach that enhances the discrimination and generalizability of multimodal representation and inherits the knowledge from the teacher model to learn the difference between positive and negative instances and via that, can detect noisy and wrong negative samples effectively before they are calculated in the contrastive objective. Furthermore, to overcome the limitation of modeling the variation within negative pairs, we introduce a new contrastive objective, AdapACSE (Adaptive Angular Margin Supervised Contrastive Learning for Multimodal sentence embeddings), that enhances the discriminative representation by strengthening the margin within the angular space while capturing varying semantics within the negative. Experimental results on widely used Semantic Textual Similarity (STS) benchmarks demonstrate the effectiveness of our approach.'
draft: false
featured: false
tags:
  - NAACL
date: '2024-06-01T00:00:00Z'
---
Link: https://aclanthology.org/2024.naacl-long.42/