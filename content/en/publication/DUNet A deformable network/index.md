---
title: "DUNet A deformable network for retinal vessel segmentation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Qiangguo Jin
- Zhaopeng Meng
- Tuan D. Pham b
- Qi Chen
- Leyi Wei
- Ran Su*


date: "2019-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Knowledge-Based Systems*

abstract: Automatic segmentation of retinal vessels in fundus images plays an important role in the diagnosis of some diseases such as diabetes and hypertension. In this paper, we propose Deformable U-Net (DUNet), which exploits the retinal vessels’ local features with a U-shape architecture, in an end to end manner for retinal vessel segmentation. Inspired by the recently introduced deformable convolutional networks, we integrate the deformable convolution into the proposed network. The DUNet, with upsampling operators to increase the output resolution, is designed to extract context information and enable precise localization by combining low-level features with high-level ones. Furthermore, DUNet captures the retinal vessels at various shapes and scales by adaptively adjusting the receptive fields according to 'vessels' scales and shapes. Public datasets, DRIVE, STARE, CHASE_DB1 and HRF are used to test our models. Detailed comparisons between the proposed network and the deformable neural network, U-Net are provided in our study. Results show that more detailed vessels can be extracted by DUNet and it exhibits state-of-the-art performance for retinal vessel segmentation with a global accuracy of 0.9566/0.9641/0.9610/0.9651 and AUC of 0.9802/0.9832/0.9804/0.9831 on DRIVE, STARE, CHASE_DB1 and HRF respectively. Moreover, to show the generalization ability of the DUNet, we use another two retinal vessel data sets, i.e., WIDE and SYNTHE, to qualitatively and quantitatively analyze and compare with other methods. Extensive cross-training evaluations are used to further assess the extendibility of DUNet. The proposed method has the potential to be applied to the early diagnosis of diseases.


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

