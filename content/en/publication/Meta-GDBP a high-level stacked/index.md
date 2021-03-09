---
title: "Meta-GDBP: a high-level stacked regression model to improve anticancer drug response prediction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Xinyi Liu
- Guobao Xiao*
- Leyi Wei*

date: "2019-3-01T00:00:00Z"
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

abstract: Anticancer drug response prediction plays an important role in personalized medicine. In particular, precisely predictingdrug response in specific cancer types and patients is still a challenge problem. Here we propose Meta-GDBP, a novel anticancer drug-response model, which involves two levels. At the first level of Meta-GDBP, we build four optimized base models (BMs) using genetic information, chemical properties and biological context with an ensemble optimization strategy, while at the second level, we construct a weighted model to integrate the four BMs. Notably, the weights of the models are learned upstream, thus the parameter cost is significantly reduced compared to previous methods. We evaluate the Meta-GDBP on Genomics of Drug Sensitivity in Cancer (GDSC) and the Cancer Cell Line Encyclopedia (CCLE) data sets. Benchmarking results demonstrate that compared to other methods, the Meta-GDBP achieves a much higher correlation between the predicted and the observed responses for almost all the drugs. Moreover, we apply the Meta-GDBP to predict the GDSC-missing drug response and use the CCLE-known data to validate the performance. The results show quite a similar tendency between these two response sets. Particularly, we here for the first time introduce a biological context-based frequency matrix (BCFM) to associate the biological context with the drug response. It is encouraging that the proposed BCFM is biologically meaningful and consistent with the reported biological mechanism, further demonstrating its efficacy for predicting drug response. The R implementation for the proposed Meta-GDBP is available at https://github.com/ RanSuLab/Meta-GDBP.

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

