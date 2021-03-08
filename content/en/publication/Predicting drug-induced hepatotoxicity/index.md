---
title: "Predicting drug-induced hepatotoxicity based on biological feature maps and diverse classification strategies"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Huichen Wu
- Xinyi Liu
- Leyi Wei

date: "2019-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Briefings in Bioinformatics*

abstract: Identifying hepatotoxicity as early as possible is significant in drug development. In this study, we developed a
drug-induced hepatotoxicity prediction model taking account of both the biological context and the computational efficacy
based on toxicogenomics data. Specifically, we proposed a novel gene selection algorithm considering gene’s participation,
named BioCB, to choose the discriminative genes and make more efficient prediction. Then instead of using the raw gene
expression levels to characterize each drug, we developed a two-dimensional biological process feature pattern map to
represent each drug. Then we employed two strategies to handle the maps and identify the hepatotoxicity, the direct use of
maps, named Two-dim branch, and vectorization of maps, named One-dim branch. The two strategies subsequently used
the deep convolutional neural networks and LightGBM as predictors, respectively. Additionally, we here for the first time
proposed a stacked vectorized gene matrix, which was more predictive than the raw gene matrix. Results validated on both
in vivo and in vitro data from two public data sets, the TG-GATES and DrugMatrix, show that the proposed One-dim branch
outperforms the deep framework, the Two-dim branch, and has achieved high accuracy and efficiency. The implementation
of the proposed method is available at https://github.com/RanSuLab/Hepatotoxicity.

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

