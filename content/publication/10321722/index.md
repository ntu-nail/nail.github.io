---
title: ' Efficient and Privacy-Preserving Feature Importance-Based Vertical Federated
  Learning '

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Anran Li
- Jiahui Huang
- Ju Jia
- Hongyi Peng
- Lan Zhang
- Luu Anh Tuan
- Han Yu
- Xiang-Yang Li

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-01-06T12:05:09.959925Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '* IEEE Transactions on Mobile Computing *'
publication_short: ''

doi: 10.1109/TMC.2023.3333879

abstract: " Vertical Federated Learning (VFL) enables multiple data owners, each holding
  a different subset of features about a largely overlapping set of data samples,
  to collaboratively train a global model. The quality of data owners’ local features
  affects the performance of the VFL model, which makes feature selection vitally
  important. However, existing feature selection methods for VFL either assume the
  availability of prior knowledge on the number of noisy features or prior knowledge
  on the post-training threshold of useful features to be selected, making them unsuitable
  for practical applications. To bridge this gap, we propose the Federated Stochastic
  Dual-Gate based Feature Selection (FedSDG-FS) approach. It consists of a Gaussian
  stochastic dual-gate to efficiently approximate the probability of a feature being
  selected. FedSDG-FS further designs a local embedding perturbation approach to achieve
  differential privacy for local training data. To reduce overhead, we propose a feature
  importance initialization method based on Gini impurity, which can accomplish its
  goals with only two parameter transmissions between the server and the clients.
  The enhanced version, FedSDG-FS++, protects the privacy for both the clients’ training
  data and the server's labels through Partially Homomorphic Encryption (PHE) without
  relying on a trusted third-party. Theoretically, we analyze the convergence rate,
  privacy guarantees and security analysis of our methods. Extensive experiments on
  both synthetic and real-world datasets show that FedSDG-FS and FedSDG-FS++ significantly
  outperform existing approaches in terms of achieving more accurate selection of
  high-quality features as well as improving VFL performance in a privacy-preserving
  manner. "

# Summary. An optional shortened abstract.
summary: ''

tags:
- Feature extraction;privacy;data models;training data;noise measurement;training;mobile
  computing

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
  url: https://doi.ieeecomputersociety.org/10.1109/TMC.2023.3333879
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
