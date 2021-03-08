---
title: "A novel method for dendritic spines detection based on directional morphological filter and shortest path"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Changming Sun
- Chao Zhang
- Tuan D. Pham


date: "2014-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Computerized Medical Imaging & Graphics*

abstract: Dendritic spines are tiny membranous protrusions from neuron’s dendrites. They play a very important role in the nervous system. A number of mental diseases such as Alzheimer’s disease and mental retardation are revealed to have close relations with spine morphologies or spine number changes. Spines have various shapes, and spine images are often not of good quality; hence it is very challenging to detect spines in neuron images. This paper presents a novel pipeline to detect dendritic spines in 2D maximum intensity projection (MIP) images and a new dendrite backbone extraction method is developed in the pipeline. The strategy for the backbone extraction approach is that it iteratively refines the extraction result based on directional morphological filtering and improved Hessian filtering until a satisfactory extraction result is obtained. A shortest path method is applied along a backbone to extract the boundary ofthe dendrites. Spines are then segmented from the dendrites outside the extracted boundary. Touching spines will be split using a marker-controlled watershed algorithm. We present the results of our algorithm on real images and compare our algorithm with two other spine detection methods. The results show that the proposed approach can detect dendrites and spines more accurately. Measurements and classification of spines are also made in this paper.

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

