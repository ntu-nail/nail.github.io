---
title: SeVe - Automatic Tool for Verification of Security Protocols
publication_types:
  - "1"
authors:
  - Luu_Anh_Tuan
  - Jun Sun
  - Yang Liu
  - Jin Song Dong
  - Xiaohong Li
  - Thanh Tho Quan
publication: "Frontiers of Computer Science"
publication_short: FCS
abstract: Security protocols play more and more important roles with wide use in many applications nowadays. Currently, there are many tools for specifying and verifying security protocols such as Casper/FDR, ProVerif, or AVISPA. In these tools, the intruder’s ability, which either needs to be specified explicitly or set by default, is not flexible in some circumstances. Moreover, whereas most of the existing tools focus on secrecy and authentication properties, few supports privacy properties like anonymity, receipt freeness, and coercion resistance, which are crucial in many applications such as in electronic voting systems or anonymous online transactions. In this paper, we introduce a framework for specifying security protocols in the labeled transition system (LTS) semantics model, which embeds the knowledge of the participants and parameterizes the ability of an attacker. Using this model, we give the formal definitions for three types of privacy properties based on trace equivalence and knowledge reasoning. The formal definitions for some other security properties, such as secrecy and authentication, are introduced under this framework, and the verification algorithms are also given. The results of this paper are embodied in the implementation of a SeVe module in a process analysis toolkit (PAT) model checker, which supports specifying, simulating, and verifying security protocols. The experimental results show that a SeVe module is capable of verifying many types of security protocols and complements the state-of-the-art security verifiers in several aspects. Moreover, it also proves the ability in building an automatic verifier for security protocols related to privacy type, which are mostly verified by hand now.
draft: false
featured: false
tags:
  - FCS
date: '2012-01-27T00:00:00Z'
---
Link: https://link.springer.com/article/10.1007/s11704-012-2903-3