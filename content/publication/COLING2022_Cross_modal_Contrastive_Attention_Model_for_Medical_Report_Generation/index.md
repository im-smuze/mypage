---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiaodan Zhang
  - Junzhong Ji
  - Ying Liu
  - Pengxu Wei

# Author notes (optional)
author_notes:
  - 
  - 'Corresponding Author'

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
publication: In *COLING*
# publication_short: In *ICW*

abstract: 'Medical report automatic generation has gained increasing interests recently as a way to help radiologists write reports more efficiently.
However, this image-to-text task is rather challenging due to the typical data biases: 1) Normal physiological structures dominate the images, with only tiny abnormalities; 2) Normal descriptions accordingly dominate the reports.
Existing methods have attempted to solve these problems, but they neglect to exploit useful information from similar historical cases. In this paper, we propose a novel Cross-modal Contrastive Attention (CMCA) model to capture both visual and semantic information from similar cases, with mainly two modules: a Visual Contrastive Attention Module for refining the unique abnormal regions compared to the retrieved case images; a Cross-modal Attention Module for matching the positive semantic information from the case reports.
Extensive experiments on two widely-used benchmarks, IU X-Ray and MIMIC-CXR, demonstrate that the proposed model outperforms the state-of-the-art methods on almost all metrics.
Further analyses also validate that our proposed model is able to improve the reports with more accurate abnormal findings and richer descriptions.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Radiolody Report Generation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'COLING2022_Cross_modal_Contrastive_Attention_Model_for_Medical_Report_Generation.pdf'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: "COLING2022_Cross_modal_Contrastive_Attention_Model_for_Medical_Report_Generation"
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
