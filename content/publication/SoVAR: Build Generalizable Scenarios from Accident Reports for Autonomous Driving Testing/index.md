---
title: "SoVAR: Build Generalizable Scenarios from Accident Reports for Autonomous Driving Testing"
publication_types:
  - Conference
authors:
  - Guizhen Chen
  - Liying Cheng
  - Luu_Anh_Tuan
  - Lidong Bing

publication: "Proceedings of the 39th IEEE/ACM International Conference on Automated Software Engineering"
publication_short: 'ASE'
abstract: "Autonomous driving systems (ADSs) have undergone remarkable development and are increasingly employed in safety-critical applications. However, recently reported data on fatal accidents involving ADSs suggests that the desired level of safety has not yet been fully achieved. Consequently, there is a growing need for more comprehensive and targeted testing approaches to ensure safe driving. Scenarios from real-world accident reports provide valuable resources for ADS testing, including critical scenarios and high-quality seeds. However, existing scenario reconstruction methods from accident reports often exhibit limited accuracy in information extraction. Moreover, due to the diversity and complexity of road environments, matching current accident information with the simulation map data for reconstruction poses significant challenges.
In this paper, we design and implement SoVAR, a tool for automatically generating road-generalizable scenarios from accident reports. SoVAR utilizes well-designed prompts with linguistic patterns to guide the large language model (LLM) in extracting accident information from textual data. Subsequently, it formulates and solves accident-related constraints in conjunction with the extracted accident information to generate accident trajectories. Finally, SoVAR reconstructs accident scenarios on various map structures and converts them into test scenarios to evaluate its capability to detect defects in industrial ADSs. We experiment with SoVAR, using the accident reports from the National Highway Traffic Safety Administration's (NHTSA) database to generate test scenarios for the industrial-grade ADS Apollo. The experimental findings demonstrate that SoVAR can effectively generate generalized accident scenarios across different road structures. Furthermore, the results confirm that SoVAR identified 5 distinct safety violation types that contributed to the crash of Baidu Apollo."
draft: false
featured: false
tags:
  - ASE
date: '2024-10-01T00:00:00Z'
---
Link: https://dl.acm.org/doi/10.1145/3691620.3695037