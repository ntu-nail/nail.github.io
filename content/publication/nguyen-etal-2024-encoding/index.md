---
title: Encoding and Controlling Global Semantics for Long-form Video Question Answering

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Thong Thanh Nguyen
- Zhiyuan Hu
- Xiaobao Wu
- Cong-Duy T Nguyen
- See-Kiong Ng
- Anh Tuan Luu

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-01-06T12:05:09.902737Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 2024 Conference on Empirical Methods in Natural
  Language Processing*'
publication_short: ''

doi: 10.18653/v1/2024.emnlp-main.400

abstract: Seeking answers effectively for long videos is essential to build video
  question answering (videoQA) systems. Previous methods adaptively select frames
  and regions from long videos to save computations. However, this fails to reason
  over the whole sequence of video, leading to sub-optimal performance. To address
  this problem, we introduce a state space layer (SSL) into multi-modal Transformer
  to efficiently integrate global semantics of the video, which mitigates the video
  information loss caused by frame and region selection modules. Our SSL includes
  a gating unit to enable controllability over the flow of global semantics into visual
  representations. To further enhance the controllability, we introduce a cross-modal
  compositional congruence objective to encourage global semantics aligned with the
  question. To rigorously evaluate long-form videoQA capacity, we construct two new
  benchmarks Ego-QA and MAD-QA featuring videos of considerably long length, i.e.
  17.5 minutes and 1.9 hours, respectively. Extensive experiments demonstrate the
  superiority of our framework on these new as well as existing datasets.

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
  url: https://aclanthology.org/2024.emnlp-main.400/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
