---
title: Fact-Checking Complex Claims with Program-Guided Reasoning
publication_types:
  - "1"
authors:
  - Liangming Pan
  - Xiaobao Wu
  - Xinyuan Lu
  - Luu Anh Tuan
  - William Yang Wang
  - Min-Yen Kan
  - Preslav Nakov
publication: "Association for Computational Linguistics"
publication_short: ACL
abstract: Fact-checking real-world claims often requires collecting multiple pieces of evidence and applying complex multi-step reasoning. In this paper, we present Program-Guided Fact-Checking (ProgramFC), a novel fact-checking model that decomposes complex claims into simpler sub-tasks that can be solved using a shared library of specialized functions. We first leverage the in-context learning ability of large language models to generate reasoning programs to guide the verification process. Afterward, we execute the program by delegating each sub-task to the corresponding sub-task handler. This process makes our model both explanatory and data-efficient, providing clear explanations of its reasoning process and requiring minimal training data. We evaluate ProgramFC on two challenging fact-checking datasets and show that it outperforms seven fact-checking baselines across different settings of evidence availability, with explicit output programs that benefit human debugging. Our codes and data are publicly available at https://github.com/mbzuai-nlp/ProgramFC.

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
https://aclanthology.org/2023.acl-long.386/#:~:text=Fact%2DChecking%20Complex%20Claims%20with%20Program%2DGuided%20Reasoning,-Liangming%20Pan%2C%20Xiaobao&text=We%20first%20leverage%20the%20in,the%20corresponding%20sub%2Dtask%20handler.