---
title: Defending Against Weight-Poisoning Backdoor Attacks for Parameter-Efficient Fine-Tuning
publication_types:
  - Conference
authors:
  - Shuai Zhao 
  - Leilei Gan
  - Luu_Anh_Tuan
  - Jie Fu
  - Lingjuan Lyu 
  - Meihuizi Jia 
  - Jinming Wen 

publication: "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics"
publication_short: NAACL
abstract: Recently, various parameter-efficient fine-tuning (PEFT) strategies for application to language models have been proposed and successfully implemented. However, this raises the question of whether PEFT, which only updates a limited set of model parameters, constitutes security vulnerabilities when confronted with weight-poisoning backdoor attacks. In this study, we show that PEFT is more susceptible to weight-poisoning backdoor attacks compared to the full-parameter fine-tuning method, with pre-defined triggers remaining exploitable and pre-defined targets maintaining high confidence, even after fine-tuning. Motivated by this insight, we developed a Poisoned Sample Identification Module (PSIM) leveraging PEFT, which identifies poisoned samples through confidence, providing robust defense against weight-poisoning backdoor attacks. Specifically, we leverage PEFT to train the PSIM with randomly reset sample labels. During the inference process, extreme confidence serves as an indicator for poisoned samples, while others are clean. We conduct experiments on text classification tasks, five fine-tuning strategies, and three weight-poisoning backdoor attack methods. Experiments show near 100% success rates for weight-poisoning backdoor attacks when utilizing PEFT. Furthermore, our defensive approach exhibits overall competitive performance in mitigating weight-poisoning backdoor attacks.
draft: false
featured: false
tags:
  - NAACL

date: '2024-06-01T00:00:00Z'

---
Link: https://aclanthology.org/2024.findings-naacl.217/