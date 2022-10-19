---
title: 'Cross-modal Contrastive Attention Model for Medical Report Generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiaodan Zhang
  - Junzhong Ji *
  - Ying Liu
  - Pengxu Wei

# Author notes (optional)
author_notes:
  - 
  - 

date: '2022-08-16T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The 29th International Conference on Computational Linguistics (COLING)* (pp. 2388-2397) Oral
# publication_short: In *ICW*

abstract: 'Medical report automatic generation has gained increasing interest recently as a way to help radiologists write reports more efficiently. However, this image-to-text task is rather challenging due to the typical data biases: 1) Normal physiological structures dominate the images, with only tiny abnormalities; 2) Normal descriptions accordingly dominate the reports. Existing methods have attempted to solve these problems, but they neglect to exploit useful information from similar historical cases. In this paper, we propose a novel Cross-modal Contrastive Attention (CMCA) model to capture both visual and semantic information from similar cases, with mainly two modules: a Visual Contrastive Attention Module for refining the unique abnormal regions compared to the retrieved case images; a Cross-modal Attention Module for matching the positive semantic information from the case reports. Extensive experiments on two widely-used benchmarks, IU X-Ray and MIMIC-CXR, demonstrate that the proposed model outperforms the state-of-the-art methods on almost all metrics. Further analyses also validate that our proposed model is able to improve the reports with more accurate abnormal findings and richer descriptions.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Radiolody Report Generation]

# Display this page in the Featured widget?
featured: true


url_pdf: 'https://aclanthology.org/2022.coling-1.210/'
url_code: ''
url_dataset: ''
url_poster: ''
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

