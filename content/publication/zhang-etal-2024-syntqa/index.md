---
title: 'SynTQA: Synergistic Table-based Question Answering via Mixture of Text-to-SQL
  and E2E TQA'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Siyue Zhang
- Anh Tuan Luu
- Chen Zhao

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-01-06T12:05:09.911266Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Findings of the Association for Computational Linguistics: EMNLP 2024*'
publication_short: ''

doi: 10.18653/v1/2024.findings-emnlp.131

abstract: 'Text-to-SQL parsing and end-to-end question answering (E2E TQA) are two
  main approaches for Table-based Question Answering task. Despite success on multiple
  benchmarks, they have yet to be compared and their synergy remains unexplored. In
  this paper, we identify different strengths and weaknesses through evaluating state-of-the-art
  models on benchmark datasets: Text-to-SQL demonstrates superiority in handling questions
  involving arithmetic operations and long tables; E2E TQA excels in addressing ambiguous
  questions, non-standard table schema, and complex table contents. To combine both
  strengths, we propose a Synergistic Table-based Question Answering approach that
  integrate different models via answer selection, which is agnostic to any model
  types. Further experiments validate that ensembling models by either feature-based
  or LLM-based answer selector significantly improves the performance over individual
  models.'

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
  url: https://aclanthology.org/2024.findings-emnlp.131/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
