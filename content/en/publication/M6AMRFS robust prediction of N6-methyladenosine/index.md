---
title: "M6AMRFS: Robust Prediction of N6-Methyladenosine Sites With Sequence-Based Features in Multiple Species"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiaoli Qiang
- Huangrong Chen
- Xiucai Ye
- Ran Su*
- Leyi Wei*


date: "2018-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Frontiers in Bioengineering and Biotechnology*

abstract: As one of the well-studied RNA methylation modifications, N6-methyladenosine (m 6 A) plays important roles in various biological progresses, such as RNA splicing and degradation, etc. Identification of m 6 A sites is fundamentally important for better understanding of their functional mechanisms. Recently, machine learning based prediction methods have emerged as an effective approach for fast and accurate identification of m 6 A sites. In this paper, we proposed “M6AMRFS”, a new machine learning based predictor for the identification of m 6 A sites. In this predictor, we exploited a new feature representation algorithm to encode RNA sequences with two feature descriptors (dinucleotide binary encoding and Local position-specific dinucleotide frequency), and used the F-score algorithm combined with SFS (Sequential Forward
Search) to enhance the feature representation ability. To predict m 6 A sites, we employed the eXtreme Gradient Boosting (XGBoost) algorithm to build a predictive model.Benchmarking results showed that the proposed predictor is competitive with the state-of-the art predictors. Importantly, robust predictions for multiple species by our predictor demonstrate that our predictive models have strong generalization ability. To the best of our knowledge, M6AMRFS is the first tool that can be used for the identification of m 6 A sites in multiple species. To facilitate the use of our predictor, we have established a user-friendly webserver with the implementation of M6AMRFS, which is currently available in http//server.malab.cn/M6AMRFS/. We anticipate that it will be a useful tool for the relevant research of m 6 A sites.

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

