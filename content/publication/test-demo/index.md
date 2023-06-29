---
title: Fact-Checking Complex Claims with Program-Guided Reasoning
publication_types:
  - "1"
authors:
  - Luu_Anh_Tuan
publication: "Association for Computational Linguistics "
publication_short: ACL
abstract: Fact-checking real-world claims often requires collecting multiple
  pieces of evidence and applying complex multi-step reasoning. In this paper,
  we present Program-Guided Fact-Checking (ProgramFC), a novel fact-checking
  model that decomposes complex claims into simpler sub-tasks that can be solved
  using a shared library of specialized functions. We first leverage the
  in-context learning ability of large language models to generate reasoning
  programs to guide the verification process. Afterward, we execute the program
  by delegating each sub-task to the corresponding sub-task handler. This
  process makes our model both explanatory and data-efficient, providing clear
  explanations of its reasoning process and requiring minimal training data. We
  evaluate ProgramFC on two challenging fact-checking datasets and show that it
  outperforms seven fact-checking baselines across different settings of
  evidence availability, with explicit output programs that benefit human
  debugging. Our codes and data are publicly available at this https URL.
draft: false
featured: false
tags:
  - ACL
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-06-29T08:29:00.179Z
---
