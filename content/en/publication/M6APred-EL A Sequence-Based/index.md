---
title: "M6APred-EL: A Sequence-Based Predictor for Identifying N6-methyladenosine Sites Using Ensemble Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Leyi Wei
- Huangrong Chen
- admin

date: "2018-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Molecular Therapy Nucleic Acids*

abstract: N6-methyladenosine (m6A) modification is the most abundant RNA methylation modification and involves various biological processes, such as RNA splicing and degradation. Recent studies have demonstrated the feasibility of identifying m6A peaks using high-throughput sequencing techniques. However, such techniques cannot accurately identify specific methylated sites, which is important for a better understanding of m6A functions. In this study, we develop a novel machine learning-based predictor called M6APred-EL for the identification of m6A sites. To predict m6A sites accurately within genomic sequences, we trained an ensemble of three support vector machine classifiers that explore the position-specific information and physical chemical information from position-specific k-mer nucleotide propensity, physical-chemical properties, and ring-function-hydrogen-chemical properties. We examined and compared the performance of our predictor with other state-of-the-art methods of benchmarking datasets. Comparative results showed that the proposed M6APred-EL performed more accurately for m6A site identification. Moreover, a user-friendly web server that implements the proposed M6APred-EL is well established and is currently available at http://server.malab.cn/M6APred-EL/. It is expected to be a practical and effective tool for the investigation of m6A functional mechanisms.

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

