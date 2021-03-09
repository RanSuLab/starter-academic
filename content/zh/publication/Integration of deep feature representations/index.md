---
title: "Integration of deep feature representations and handcrafted features to improve the prediction of N6-methyladenosine sites"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.                    
authors:
- Leyi Wei 
- Ran Su
- Bing Wang
- Xiuting Li
- Quan Zou*
- Xing Gao*


date: "2018-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Neurocomputing*

abstract: N6-methyladenosine (m6A), as one of the most well-studied RNA modifications, has been found to be involved with a wide range of biological processes. Recently, diverse computational methods have been developed for automated identification of m6A sites within RNAs. To identify m6A sites accurately, one of the major challenges is to extract informative features to describe characteristics of m6A sites. However, existing feature representation methods are usually hand-crafted based, and cannot capture discriminative information of m6A sites. In this paper, we develop a m6A site predictor, named DeepM6APred. In this predictor, we propose to use a deep learning based feature descriptor with deep belief network (DBN) to extract high-level latent features. By integrating the deep features with traditional handcrafted features, we train a classification model based on support vector machine and successfully improve the predictive ability of m6A sites. Experimental results on a benchmark dataset show that our proposed method outperforms the state-of-the-art predictors, at least 2% higher in terms of Matthew's correlation coefficient (MCC). Moreover, a webserver that implements the DeepM6APred is established, which is currently available at the website http //server.malab.cn/DeepM6APred. It is expected to be a useful tool to assist biologists to reveal the functional mechanisms of m6A sites.

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

