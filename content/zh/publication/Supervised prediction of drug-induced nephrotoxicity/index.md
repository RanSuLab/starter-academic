---
title: "Supervised prediction of drug-induced nephrotoxicity based on interleukin-6 and -8 expression levels"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yao Li
- Daniele Zink
- Lit-Hsin Loo*



date: "2014-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *BMC Bioinformatics*

abstract: Drug-induced nephrotoxicity causes acute kidney injury and chronic kidney diseases, and is a major reason for late-stage failures in the clinical trials of new drugs. Therefore, early, pre-clinical prediction of nephrotoxicity could help to prioritize drug candidates for further evaluations, and increase the success rates of clinical trials. Recently, an in vitro model for predicting renal-proximal-tubular-cell (PTC) toxicity based on the expression levels of two inflammatory markers, interleukin (IL)-6 and -8, has been described. However, this and other existing models usually use linear and manually determined thresholds to predict nephrotoxicity. Automated machine learning algorithms may improve these models, and produce more accurate and unbiased predictions. Here, we report a systematic comparison of the performances of four supervised classifiers, namely random forest, support vector machine, k-nearest-neighbor and naive Bayes classifiers, in predicting PTC toxicity based on IL-6 and -8 expression levels. Using a dataset of human primary PTCs treated with 41 well-characterized compounds that are toxic or not toxic to PTC, we found that random forest classifiers have the highest cross-validated classification performance (mean balanced accuracy = 87.8%, sensitivity = 89.4%, and specificity = 85.9%). Furthermore, we also found that IL-8 is more predictive than IL-6, but a combination of both markers gives higher classification accuracy. Finally, we also show that random forest classifiers trained automatically on the whole dataset have higher mean balanced accuracy than a previous threshold-based classifier constructed for the same dataset (99.3% vs. 80.7%). Our results suggest that a random forest classifier can be used to automatically predict drug-induced PTC toxicity based on the   expression levels of IL-6 and -8.

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

