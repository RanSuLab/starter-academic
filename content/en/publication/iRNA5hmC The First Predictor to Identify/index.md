---
title: "iRNA5hmC: The First Predictor to
Identify RNA
5-Hydroxymethylcytosine
Modifications Using Machine
Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuan Liu 
- Dasheng Chen
- Ran Su*
- Wei Chen*
- Leyi Wei*


date: "2020-03-01T00:00:00Z"
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

abstract: RNA 5-hydroxymethylcytosine (5hmC) modification plays an important role in a series of biological processes. Characterization of its distributions in transcriptome is fundamentally important to reveal the biological functions of 5hmC. Sequencing-based technologies allow the high-throughput identification of 5hmC; however, they are laborintensive, time-consuming, as well as expensive. Thus, there is an urgent need to develop more effective and efficient computational methods, at least complementary to the high-throughput technologies. In this study, we developed iRNA5hmC, a computational predictive protocol to identify RNA 5hmC sites using machine learning. In this predictor, we introduced a sequence-based feature algorithm consisting of two feature representations, (1) k-mer spectrum and (2) positional nucleotide binary vector, to capture the sequential characteristics of 5hmC sites. Afterward, we utilized a two-stage feature space optimization strategy to improve the feature representation ability, and trained a predictive model using support vector machine (SVM). Our feature analysis results showed that feature optimization can help to capture the most discriminative features. As compared to well-known existing feature descriptors, our proposed representations can more accurately separate true 5hmC from non-5hmC sites. To the best of our knowledge, iRNA5hmC is the first RNA 5hmC predictor that enables to make predictions based on RNA primary sequences only, without any need of prior experimental knowledge. Importantly, we have established an easy-to-use webserver which is currently available at http//server.malab.cn/iRNA5hmC. We expect it has potential to be a useful tool for the prediction of 5hmC sites.

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

