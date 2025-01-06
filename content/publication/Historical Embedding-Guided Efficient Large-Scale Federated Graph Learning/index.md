---
title: Historical Embedding-Guided Efficient Large-Scale Federated Graph Learning
publication_types:
  - Conference
authors:
  - Anran Li
  - Yuanyuan Chen
  - Jian Zhang
  - Mingfei Cheng
  - Yihao Huang 
  - Yueming Wu
  - Luu_Anh_Tuan
  - Han Yu
publication: "Association for Computing Machinery"
publication_short: ACM
abstract: Graph convolutional networks (GCNs) are promising for graph learning tasks. For privacy-preserving graph learning tasks involving distributed graph datasets, federated learning (FL)-based GCN (FedGCN) training is required. An important open challenge for FedGCN is scaling to large graphs, which typically incurs 1) high computation overhead for handling the explosively-increasing number of neighbors, and 2) high communication overhead of training GCNs involving multiple FL clients. Thus, neighbor sampling is being studied to enhance the scalability of FedGCNs. Existing FedGCN training techniques with neighbor sampling often produce extremely large communication and computation overhead and inaccurate node embeddings, leading to poor model performance. To bridge this gap, we propose the <u>Fed</u>erated <u>A</u>daptive <u>A</u>ttention-based <u>S</u>ampling (FedAAS) approach. It achieves substantial cost savings by efficiently leveraging historical embedding estimators and focusing the limited communication resources on transmitting the most influential neighbor node embeddings across FL clients. We further design an adaptive embedding synchronization scheme to optimize the efficiency and accuracy of FedAAS on large-scale datasets. Theoretical analysis shows that the approximation error induced by the staleness of historical embedding is upper bounded, and the model is guaranteed to converge in an efficient manner. Extensive experimental evaluation against four state-of-the-art baselines on six real-world graph datasets show that FedAAS achieves up to 5.12\% higher test accuracy, while saving communication and computation costs by 95.11\% and 94.76\%, respectively.
draft: false
featured: false
tags:
  - ACM
date: '2024-06-01T00:00:00Z'
---
Link: https://dl.acm.org/doi/10.1145/3654947