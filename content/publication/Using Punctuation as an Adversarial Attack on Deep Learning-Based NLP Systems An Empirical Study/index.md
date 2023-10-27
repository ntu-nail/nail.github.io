---
title: Using Punctuation as an Adversarial Attack on Deep Learning-Based NLP Systems:An Empirical Study
publication_types:
  - "1"
authors:
  - Brian Formento
  - Chuan Sheng Foo
  - Luu_Anh_Tuan
  - See-Kiong Ng
publication: "European Chapter of the ACL"
publication_short: EACL
abstract: This work empirically investigates punctuation insertions as adversarial attacks on NLP systems. Data from experiments on three tasks, five datasets, and six models with four attacks show that punctuation insertions, when limited to a few symbols (apostrophes and hyphens), are a superior attack vector compared to character insertions due to 1) a lower after-attack accuracy (Aaft-atk) than alphabetical character insertions; 2) higher semantic similarity between the resulting and original texts; and 3) a resulting text that is easier and faster to read as assessed with the Test of Word Reading Efficiency (TOWRE)). The tests also indicate that 4) grammar checking does not mitigate punctuation insertions and 5) punctuation insertions outperform word-level attacks in settings with a limited number of word synonyms and queries to the victim’s model. Our findings indicate that inserting a few punctuation types that result in easy-to-read samples is a general attack mechanism. In light of this threat, we assess the impact of punctuation insertions, potential mitigations, the mitigation’s tradeoffs, punctuation insertion’s worst-case scenarios and summarize our findings in a qualitative casual map, so that developers can design safer, more secure systems.
draft: false
featured: false
tags:
  - EACL
date: '2023-06-01T00:00:00Z'
---
Link: https://aclanthology.org/2023.findings-eacl.1/