---
title: "Decision Variants for the Automatic Determination of Optimal Feature Subset in RF-RFE"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Qi Chen
- Zhaopeng Meng
- Xinyi Liu
- Qianguo Jin
- admin



date: "2018-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *genes*

abstract: Feature selection, which identifies a set of most informative features from the original feature space, has been widely used to simplify the predictor. Recursive feature elimination (RFE), as one of the most popular feature selection approaches, is effective in data dimension reduction and efficiency increase. A ranking of features, as well as candidate subsets with the corresponding accuracy, is produced through RFE. The subset with highest accuracy (HA) or a preset number of features (PreNum) are often used as the final subset. However, this may lead to a large number of features being selected, or if there is no prior knowledge about this preset number, it is often ambiguous and subjective regarding final subset selection. A proper decision variant is in high demand to automatically determine the optimal subset. In this study, we conduct pioneering work to explore the decision variant after obtaining a list of candidate subsets from RFE. We provide a detailed analysis and comparison of several decision variants to automatically select the optimal feature subset. Random forest (RF)-recursive feature elimination (RF-RFE) algorithm and a voting strategy are introduced. We validated the variants on two totally different molecular biology datasets, one for a toxicogenomic study and the other one for protein sequence analysis. The study provides an automated way to determine the optimal feature subset when using RF-RFE.

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

