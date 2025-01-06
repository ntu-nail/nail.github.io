---
title: 'Universal Vulnerabilities in Large Language Models: Backdoor Attacks for In-context Learning'
publication_types:
  - Conference
authors:
  - Shuai Zhao
  - Meihuizi Jia  
  - Luu_Anh_Tuan 
  - Fengjun Pan
  - Jinming Wen

publication: "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing"
publication_short: EMNLP
abstract: 'In-context learning, a paradigm bridging the gap between pre-training and fine-tuning, has demonstrated high efficacy in several NLP tasks, especially in few-shot settings. Despite being widely applied, in-context learning is vulnerable to malicious attacks. In this work, we raise security concerns regarding this paradigm. Our studies demonstrate that an attacker can manipulate the behavior of large language models by poisoning the demonstration context, without the need for fine-tuning the model. Specifically, we design a new backdoor attack method, named ICLAttack, to target large language models based on in-context learning. Our method encompasses two types of attacks: poisoning demonstration examples and poisoning demonstration prompts, which can make models behave in alignment with predefined intentions. ICLAttack does not require additional fine-tuning to implant a backdoor, thus preserving the model’s generality. Furthermore, the poisoned examples are correctly labeled, enhancing the natural stealth of our attack method. Extensive experimental results across several language models, ranging in size from 1.3B to 180B parameters, demonstrate the effectiveness of our attack method, exemplified by a high average attack success rate of 95.0% across the three datasets on OPT models.'
draft: false
featured: false
tags:
  - EMNLP
date: '2024-11-01T00:00:00Z'
---
Link: https://aclanthology.org/2024.emnlp-main.642/