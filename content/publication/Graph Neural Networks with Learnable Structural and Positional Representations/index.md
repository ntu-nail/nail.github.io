---
title: Graph Neural Networks with Learnable Structural and Positional Representations
publication_types:
  - "1"
authors:
  - Vijay Prakash Dwivedi
  - Luu Anh Tuan
  - Thomas Laurent
  - Yoshua Bengio
  - Xavier Bresson
publication: "The International Conference on Learning Representations"
publication_short: ICLR
abstract: Graph neural networks (GNNs) have become the standard learning architectures for graphs. GNNs have been applied to numerous domains ranging from quantum chemistry, recommender systems to knowledge graphs and natural language processing. A major issue with arbitrary graphs is the absence of canonical positional information of nodes, which decreases the representation power of GNNs to distinguish e.g. isomorphic nodes and other graph symmetries. An approach to tackle this issue is to introduce Positional Encoding (PE) of nodes, and inject it into the input layer, like in Transformers. Possible graph PE are Laplacian eigenvectors. In this work, we propose to decouple structural and positional representations to make easy for the network to learn these two essential properties. We introduce a novel generic architecture which we call LSPE (Learnable Structural and Positional Encodings). We investigate several sparse and fully-connected (Transformer-like) GNNs, and observe a performance increase for molecular datasets, from 1.79% up to 64.14% when considering learnable PE for both GNN classes.
draft: false
featured: false
tags:
  - ICLR
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-03-2T08:29:00.179Z
---
https://arxiv.org/abs/2110.07875