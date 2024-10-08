---
title: Encoding and Controlling Global Semantics for Long-form Video Question Answering
publication_types:
  - "1"
authors:
  - Thong Thanh Nguyen
  - Zhiyuan Hu
  - Xiaobao Wu
  - Cong-Duy Nguyen
  - See-Kiong Ng
  - Luu Anh Tuan

publication: "Empirical Methods in Natural Language Processing"
publication_short: EMNLP
abstract: Seeking answers effectively for long videos is essential to build video question answering (videoQA) systems. Previous methods adaptively select frames and regions from long videos to save computations. However, this fails to reason over the whole sequence of video, leading to sub-optimal performance. To address this problem, we introduce a state space layer (SSL) into multi-modal Transformer to efficiently integrate global semantics of the video, which mitigates the video information loss caused by frame and region selection modules. Our SSL includes a gating unit to enable controllability over the flow of global semantics into visual representations. To further enhance the controllability, we introduce a cross-modal compositional congruence (C^3) objective to encourage global semantics aligned with the question. To rigorously evaluate long-form videoQA capacity, we construct two new benchmarks Ego-QA and MAD-QA featuring videos of considerably long length, i.e. 17.5 minutes and 1.9 hours, respectively. Extensive experiments demonstrate the superiority of our framework on these new as well as existing datasets.

featured: false
date: '2024-10-01T00:00:00Z'
---
Link: https://nguyentthong.github.io/Long_form_VideoQA/