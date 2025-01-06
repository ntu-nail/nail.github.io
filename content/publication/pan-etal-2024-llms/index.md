---
title: Are LLMs Good Zero-Shot Fallacy Classifiers?

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Fengjun Pan
- Xiaobao Wu
- Zongrui Li
- Anh Tuan Luu

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-01-06T12:05:09.919991Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 2024 Conference on Empirical Methods in Natural
  Language Processing*'
publication_short: ''

doi: 10.18653/v1/2024.emnlp-main.794

abstract: 'Fallacies are defective arguments with faulty reasoning. Detecting and
  classifying them is a crucial NLP task to prevent misinformation, manipulative claims,
  and biased decisions. However, existing fallacy classifiers are limited by the requirement
  for sufficient labeled data for training, which hinders their out-of-distribution
  (OOD) generalization abilities. In this paper, we focus on leveraging Large Language
  Models (LLMs) for zero-shot fallacy classification. To elicit fallacy-related knowledge
  and reasoning abilities of LLMs, we propose diverse single-round and multi-round
  prompting schemes, applying different taskspecific instructions such as extraction,
  summarization, and Chain-of-Thought reasoning. With comprehensive experiments on
  benchmark datasets, we suggest that LLMs could be potential zero-shot fallacy classifiers.
  In general, LLMs under single-round prompting schemes have achieved acceptable zeroshot
  performances compared to the best fullshot baselines and can outperform them in
  all OOD inference scenarios and some opendomain tasks. Our novel multi-round prompting
  schemes can effectively bring about more improvements, especially for small LLMs.
  Our analysis further underlines the future research on zero-shot fallacy classification.
  Codes and data are available at: https://github.com/panFJCharlotte98/Fallacy_Detection.'

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
  url: https://aclanthology.org/2024.emnlp-main.794/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
