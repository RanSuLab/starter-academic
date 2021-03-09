---
title: "Cascade knowledge diffusion network for skin lesion diagnosis and segmentation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Qiangguo Jin
- Hui Cui
- Changming Sun
- Zhaopeng Meng
- Ran Su*


date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Applied Soft Computing*

abstract: Accurate diagnosis and segmentation of skin lesion is critical for early detection and diagnosis of skin cancer. Recent multi-task learning methods require expensive annotations for skin lesion analysis while single-task driven models cannot fully utilize the potential knowledge. The aim of this study is to utilize the neglected knowledge by a flexible architecture in dermoscopy skin lesion classification and segmentation. In this work, we propose a cascade knowledge diffusion network (CKDNet) to transfer and aggregate knowledge learnt from different tasks to simultaneously boost the performances of classification and segmentation. CKDNet consists of a sequence of coarse-level segmentation, classification, and fine-level segmentation networks. We design two novel feature entanglement modules, Entangle-Cls and Entangle-Seg, for classification and segmentation. The Entangle-Cls module aggregates the diffused features from initial segmentation to drive the classification network’s attention to image regions relevant to the disease. The Entangle-Seg module integrates the cascaded context knowledge learnt from classification to benefit fine-level segmentation, especially at uncertain boundaries. The entanglement modules can adaptively control the knowledge that can be diffused from one task to another, which avoids the empirical selection of weights for different learning tasks compared to other multi-task methods. We perform extensive evaluations and comparisons with state-of-the-art methods on skin lesion classification and segmentation with challenge datasets, ISIC2017 and ISIC2018. Our CKDNet demonstrated superior performance without using any ensemble approaches or any external datasets. The effectiveness of each component and loss functions are demonstrated by interpretable results using class activation maps (CAM), t-SNE, and classification and segmentation results.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---

