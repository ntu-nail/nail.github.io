---
title: 'Universal Vulnerabilities in Large Language Models: Backdoor Attacks for In-context
  Learning'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Shuai Zhao
- Meihuizi Jia
- Anh Tuan Luu
- Fengjun Pan
- Jinming Wen

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-01-06T12:05:09.893924Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 2024 Conference on Empirical Methods in Natural
  Language Processing*'
publication_short: ''

doi: 10.18653/v1/2024.emnlp-main.642

abstract: 'In-context learning, a paradigm bridging the gap between pre-training and
  fine-tuning, has demonstrated high efficacy in several NLP tasks, especially in
  few-shot settings. Despite being widely applied, in-context learning is vulnerable
  to malicious attacks. In this work, we raise security concerns regarding this paradigm.
  Our studies demonstrate that an attacker can manipulate the behavior of large language
  models by poisoning the demonstration context, without the need for fine-tuning
  the model. Specifically, we design a new backdoor attack method, named ICLAttack,
  to target large language models based on in-context learning. Our method encompasses
  two types of attacks: poisoning demonstration examples and poisoning demonstration
  prompts, which can make models behave in alignment with predefined intentions. ICLAttack
  does not require additional fine-tuning to implant a backdoor, thus preserving the
  model`s generality. Furthermore, the poisoned examples are correctly labeled, enhancing
  the natural stealth of our attack method. Extensive experimental results across
  several language models, ranging in size from 1.3B to 180B parameters, demonstrate
  the effectiveness of our attack method, exemplified by a high average attack success
  rate of 95.0% across the three datasets on OPT models.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://aclanthology.org/2024.emnlp-main.642/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
