---
title: "Encoded Texture Features to Characterize Bone Radiograph Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ran Su
- Weijun Chen
- Leyi Wei
- Xiuting Li
- Qiangguo Jin
- Wenyuan Tao*


date: "2018-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2018 24th International Conference on Pattern Recognition (ICPR)*

abstract: Osteoporosis is the most common reason that causes the fracture among the elderly. For the purpose of convenience and safety, 2D texture analysis has been used to diagnose osteoporosis. In this study, a supervised method using proposed texture features to identify osteoporotic cases from healthy was proposed. We designed two groups of new features, Encoded GLCM and Encoded LBP, each of which contains two subgroups through encoding the Gabor and Hessian information into the Gray Level Co-Occurrence Matrix (GLCM) features and Local Binary Patterns (LBP) features respectively. These two groups of features, together with the raw feature group containing the GLCM and LBP features, totally 560 features, were categorized into various groups and used to train the Random Forest classifier. Classification performances using these features were compared inter - and intra - groups/subgroups. And the performance using each individual feature was also provided. We conducted feature selection based on Recursive Feature Elimination (RFE) inside a voting scheme to further increase the efficiency. The inter - and intra - groups/subgroups results indicate that the Encoded GLCM and Encoded LBP, are more discriminative than the raw GLCM and LBP features for the identification of the osteoporosis; The best individual feature is from the Encoded LBP group and can achieve 70% of balanced accuracy; Furthermore, using only ten of the proposed features through feature selection, the balanced accuracy can even be improved from 60% to 71%. This shows that the proposed method is promising to assist the early diagnosis of osteoporosis.

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

