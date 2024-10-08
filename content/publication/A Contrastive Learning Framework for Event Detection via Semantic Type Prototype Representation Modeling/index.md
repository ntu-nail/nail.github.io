---
title: A Contrastive Learning Framework for Event Detection via Semantic Type Prototype Representation Modeling
publication_types:
  - Conference
authors:
  - Anran Hao
  - Luu_Anh_Tuan
  - Siu Cheung Hui
  - Jian Su
publication: "Neurocomputing"
publication_short: Neurocomputing
abstract: The diversity of natural language expressions for describing events poses a challenge for the task of Event Detection (ED) with machine learning methods. To detect and classify event mentions, ED models essentially need to construct a semantic linkage between representations of the mentions and a set of target types. Unfortunately, most existing models use meaningless homogeneous one-hot vectors to represent the event type classes in ED, ignoring the fact that the event type labels also consist of meaningful words and can provide important clues for type representation learning. In this paper, we propose a Contrastive Semantic Prototype Representation Learning Framework for Event Detection (SemPRE), which exploits the pre-defined event type label words to inject the semantic information of the types and guide event detection. Specifically, we utilize pre-trained BERT to fuse text and event type into a joint representation space, and employ a contrastive-regularized module to enhance cross-type interaction. We conduct extensive experiments on the ACE 2005 and MAVEN benchmark datasets. The performance results show that our proposed SemPRE model achieves state-of-the-art performance on the datasets and outperforms existing baselines on limited annotated data and without using any external resources. Further analysis shows that our model is also effective in detecting multiple events and ambiguous trigger words.
draft: false
featured: false
tags:
  - Neurocomputing
date: '2023-11-01T00:00:00Z'
---
Link: https://www.sciencedirect.com/science/article/abs/pii/S0925231223007361
