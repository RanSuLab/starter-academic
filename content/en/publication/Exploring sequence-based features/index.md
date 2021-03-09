---
title: "Exploring sequence-based features for the improved prediction of DNA N4-methylcytosine sites in multiple species"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Leyi Wei
- Shasha Luan
- Luis Augusto Eijy Nagai
- Ran Su*
- Quan Zou*


date: "2018-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Bioinformatics*

abstract: Motivation: As one of important epigenetic modifications, DNA N4-methylcytosine (4mC) is recently shown to play crucial roles in restriction-modification systems. For better understanding of their functional mechanisms, it is fundamentally important to identify 4mCmodification.Machine learning methods have recently emerged as an effective and efficient approach for the high-throughput identification of 4mC sites, although high predictive error rates are still challenging for existing methods. Therefore, it is highly desirable to develop a computational method to more accurately identify m4C sites. Results: In this study, we propose a machine learning based predictor, namely 4mcPred-SVM, for the genome-wide detection of DNA 4mC sites. In this predictor, we present a new feature representation algorithm that sufficiently exploits sequence based information. To improve the feature representation ability, we use a two-step feature optimization strategy, thereby obtaining the most representative features. Using the resulting features and Support Vector Machine (SVM), we adaptively train the optimal models for different species. Comparative results on benchmark datasets from six species indicate that our predictor is able to achieve generally better performance in predicting 4mC sites as compared to the state-of-the-art predictors. Importantly, the sequence-based features can reliably and robust predict 4mC sites, facilitating the discovery of potentially important sequence characteristics for the prediction of 4mC sites. Availability and implementation: The user friendly webserver that implements the proposed 4mcPred-SVM is well established, and is freely accessible at http//server.malab.cn/4mcPred-SVM. 

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

