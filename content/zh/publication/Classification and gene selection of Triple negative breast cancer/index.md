---
title: "Classification and gene selection of Triple negative breast cancer subtype embedding gene connectivity matrix in deep neural network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jin Liu
- Ran Su*
- Jiahang Zhang
- Leyi Wei*



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
publication: In *Briefings in Bioinformatics*

abstract: Triple-negative breast cancer (TNBC) has been a challenging breast cancer subtype for oncological therapy. Normally, it can be classified into molecular subtypes. Accurate and stable classification of the six subtypes is essential for personalized treatment of TNBC. In this study, we proposed a new framework to distinguish the six subtypes of TNBC and this is one of the handful studies that completed the classification based on mRNA and long non-coding RNA (lncRNA) expression data. Particularly, we developed a gene selection named DGGA, which takes correlation information between genes into account in the process of measuring gene importance, and then effectively removes redundant genes. A gene scoring approach that combined GeneRank scores with gene importance generated by deep neural network (DNN), taking inter-subtype discrimination and inner-gene correlations was came up to improve gene selection. More importantly, we embedded a gene connectivity matrix in the DNN for sparse learning, which takes additional consideration with weight changes during training when obtaining the measurement of the relative importance of each gene. Finally, genetic Algorithm (GA) was used to simulate the natural evolutionary process to search for the optimal subset of TNBC subtype classification. We validated the proposed method through cross-validation, and the results demonstrate that it can use fewer genes to obtain more accurate classification results. The implementation for the proposed method is available at https://github.com/RanSuLab/TNBC.


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

