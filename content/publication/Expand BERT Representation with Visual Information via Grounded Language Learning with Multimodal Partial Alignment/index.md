---
title: Expand BERT Representation with Visual Information via Grounded Language Learning with Multimodal Partial Alignment
publication_types:
  - "1"
authors:
  - Duy Nguyen
  - Anh Vu
  - Thong Nguyen
  - Luu_Anh_Tuan
publication: "ACM International Conference on Multimedia"
publication_short: ACM MM
abstract: In natural language processing, most models try to learn semantic representations merely from texts. The learned representations encode the “distributional semantics” but fail to connect to any knowledge about the physical world. In contrast, humans learn language by grounding concepts in perception and action and the brain encodes “grounded semantics” for cognition. Inspired by this notion and recent work in vision-language learning, we design a two-stream model for grounding language learning in vision. The model includes a VGG-based visual stream and a Bert-based language stream. The two streams merge into a joint representational space. Through cross-modal contrastive learning, the model first learns to align visual and language representations with the MS COCO dataset. The model further learns to retrieve visual objects with language queries through a cross-modal attention module and to infer the visual relations between the retrieved objects through a bilinear operator with the Visual Genome dataset. After training, the model’s language stream is a stand-alone language model capable of embedding concepts in a visually grounded semantic space. This semantic space manifests principal dimensions explainable with human intuition and neurobiological knowledge. Word embeddings in this semantic space are predictive of human-defined norms of semantic features and are segregated into perceptually distinctive clusters. Furthermore, the visually grounded language model also enables compositional language understanding based on visual knowledge and multimodal image search with queries based on images, texts, or their combinations.
draft: false
featured: false
tags:
  - ACM
date: '2023-05-01T00:00:00Z'
---