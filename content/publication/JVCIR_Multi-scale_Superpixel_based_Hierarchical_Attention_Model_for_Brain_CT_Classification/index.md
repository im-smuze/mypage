---
title: 'Multi-scale Superpixel based Hierarchical Attention Model for Brain CT Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiaodan Zhang
  - Junzhong Ji
  - Ying Liu

# Author notes (optional)
author_notes:
  - 
  - 

date: '2023-06-17T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Visual Communication and Image Representation (JVCIR)*，91, 103773.
# publication_short: In *ICW*

abstract: 'Brain disease has become a common threat to human life and health, and brain Com- puted Tomography (CT) is an indispensable radiological diagnostic procedure. Convo- lutional Neural Networks (CNN) have achieved remarkable performance on the natural image classification task. However, compared with natural images, 1) the brain CT im- ages contain more noisy information, and 2) the brain lesions are unstable in shapes and locations. These challenges increase the difficulty of capturing lesion information un- der the conventional CNN models which represent uniform grid-level features of neural receptive fields with equal sizes and shapes. In this paper, we propose a novel Multi- scale Superpixel based Hierarchical Attention (MSHA) model to improve the brain CT classification by introducing multi-scale superpixels to a hierarchical fusion struc- ture to remove noise and help the model focus on lesion areas. MSHA contains three modules: a Semantic-level Information Extractor (SIE), a Mixed Multi-head Attention (MMA) module, and a Hierarchical Fusion Structure (HFS). Specifically, SIE extracts semantic-level features that contain appearance and geometry information based on the superpixel of the brain image. Then, MMA learns the appearance and geometry at- tention of the multi-scale superpixel regions through a mixed attention model. Finally, HFS connects and fuses the mixed multi-head attention features of superpixel regions at different scales from coarse to fine in a hierarchical structure. Experimental results on the CQ500-based brain CT dataset demonstrate the effectiveness of the proposed model.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Brain CT Classification]

# Display this page in the Featured widget?
featured: true


url_pdf: 'https://www.sciencedirect.com/science/article/pii/S1047320323000238'
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

