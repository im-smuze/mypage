---
title: 'Rethinking Radiology Report Generation via Causal Reasoning and Counterfactual Augmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jiafan Liu
  - Yun Li
  - Wenbin Lei
  - Ruxin Wang

# Author notes (optional)
author_notes:
  - 
  - 

date: '2023-11-23T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
# publication_short: In *ICW*

abstract: 'Radiology Report Generation (RRG) draws attention as an interaction between vision and language fields. Previous works inherited the ideology of vision-to-language generation tasks,aiming to generate paragraphs with high consistency as reports. However, one unique characteristic of RRG, the independence between diseases, was neglected, leading to the injection of the spurious confounder, i.e., the disease co-occurrence. Unfortunately, this confounder confuses the process of report generation worse because of the biased RRG data distribution. In this paper, to rethink this issue thoroughly, we reason about its causes and effects from a novel perspective of statistics and causality, where the Joint Vision Coupling and the Conditional Sentence Coherence Coupling are two aspects prone to implicitly decrease the accuracy of reports. Then, a counterfactual augmentation strategy that contains the Counterfactual Sample Synthesis and the Counterfactual Report Reconstruction sub-methods is proposed to break these two aspects of spurious effects. Experimental results and further analyses on two widely used datasets justify our reasoning and proposed methods.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Medical Report Generation]

# Display this page in the Featured widget?
featured: true


url_pdf: 'https://arxiv.org/abs/2311.13307'
url_code: ''
url_dataset: ''
# url_poster: 'https://smuze.netlify.app/publication/JVCIR_Multi-scale_Superpixel_based_Hierarchical_Attention_Model_for_Brain_CT_Classification/poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: "COLING2022_Cross_modal_Contrastive_Attention_Model_for_Medical_Report_Generation"
---

