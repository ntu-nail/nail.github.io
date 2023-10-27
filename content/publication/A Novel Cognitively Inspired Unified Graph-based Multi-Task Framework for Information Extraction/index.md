---
title: A Novel, Cognitively Inspired, Unified Graph-based Multi-Task Framework for Information Extraction
publication_types:
  - "1"
authors:
  - Yandan Zheng
  - Luu_Anh_Tuan
publication: "Cognitive Computation"
publication_short: Cognit Comput
abstract: Information extraction (IE) transforms unstructured textual sources into structured knowledge, closely resembling human reasoning. IE involves several subtasks, such as named entity recognition (NER), relation extraction (RE), and coreference resolution (CR). The early IE models tend to treat each subtask as a separate task or to apply a sequential pipeline approach, which can lead to cascading errors and obfuscation of the inherent relationship between tasks. Recent research has shown that it is advantageous to incorporate the interdependence of subtasks and optimize performance through joint learning. However, they do not properly model the interaction between tasks, either by modeling the subtasks sequentially or by using shared input data. Inspired by human reasoning, a graph-based multitask IE framework is presented that facilitates the interaction between several IE tasks capable of capturing both local and global information. Graphs were constructed by selecting the most confident entity spans and coupling them with a confidence-weighted relation type and a confidence-weighted coreference. Additionally, in the study, a dynamic span graph approach was employed, where span updates were propagated across both the coreference and the relation graph. This allowed useful information to be learned from a broader context by enhancing interaction across different IE tasks. The input data were globally shared, and the interaction between subtasks was fully exploited, avoiding cascading errors. Experiments demonstrate that the proposed multitask IE framework outperforms the state-of-the-art in multiple information extraction tasks spanning a variety of datasets. The relative error reductions range from 0.19 to 3.74%. This paper presents the feasibility of a cognitively-inspired unified graph-based information extraction framework, which is shown to achieve state-of-the-art results on multiple IE tasks across various domains. The framework’s ability to enhance interaction across tasks allows it to learn valuable information from a broader context.
draft: false
featured: false
tags:
  - CC
date: '2023-07-06T00:00:00Z'
---
Link: https://link.springer.com/article/10.1007/s12559-023-10163-2

