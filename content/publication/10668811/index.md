---
title: ' Joint Client-and-Sample Selection for Federated Learning via Bi-Level Optimization '

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Anran Li
- Guangjing Wang
- Ming Hu
- Jianfei Sun
- Lan Zhang
- Luu Anh Tuan
- Han Yu

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-01-06T12:05:09.999367Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '* IEEE Transactions on Mobile Computing *'
publication_short: ''

doi: 10.1109/TMC.2024.3455331

abstract: ' Federated Learning (FL) enables massive local data owners to collaboratively
  train a deep learning model without disclosing their private data. The importance
  of local data samples from various data owners to FL models varies widely. This
  is exacerbated by the presence of noisy data that exhibit large losses similar to
  important (hard) samples. Currently, there lacks an FL approach that can effectively
  distinguish hard samples (which are beneficial) from noisy samples (which are harmful).
  To bridge this gap, we propose the joint Federated Meta-Weighting based Client and
  Sample Selection (FedMW-CSS) approach to simultaneously mitigate label noise and
  hard sample selection. It is a bilevel optimization approach for FL client-and-sample
  selection and global model construction to achieve hard sample-aware noise-robust
  learning in a privacy preserving manner. It performs meta-learning based online
  approximation to iteratively update global FL models, select the most positively
  influential samples and deal with training data noise. To utilize both the instance-level
  information and class-level information for better performance improvements, FedMW-CSS
  efficiently learns a class-level weight by manipulating gradients at the class level,
  e.g., it performs a gradient descent step on class-level weights, which only relies
  on intermediate gradients. Theoretically, we analyze the privacy guarantees and
  convergence of FedMW-CSS. Extensive experiments comparison against eight state-of-the-art
  baselines on six real-world datasets in the presence of data noise and heterogeneity
  shows that FedMW-CSS achieves up to 28.5% higher test accuracy, while saving communication
  and computation costs by at least 49.3% and 1.2%, respectively. '

# Summary. An optional shortened abstract.
summary: ''

tags:
- Training;computational modeling;data models;noise measurement;noise;optimization;servers

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
  url: https://doi.ieeecomputersociety.org/10.1109/TMC.2024.3455331
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
