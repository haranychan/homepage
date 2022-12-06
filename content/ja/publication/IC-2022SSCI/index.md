---
title: "Surrogate-assisted Differential Evolution with Adaptation of Training Data Selection Criterion"

# Authors
# If you created a profile for a user (e.g. the default `Kei Nishihara` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Kei Nishihara
- Masaya Nakata

# Author notes (optional)
author_notes:
- "Yokohama National University"
- "Yokohama National University"

date: "2022-12-04T00:00:00Z"
doi: "10.1109/CEC45853.2021.9504997"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper; 
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Symposium Series on Computational Intelligence (SSCI)*, pp. 1675--1682"
publication_short: "*Proc. IEEE Symp. Ser. Comput. Intell. (SSCI)*, pp. 1675--1682"

abstract: In surrogate-assisted evolutionary algorithms (SAEAs), the selection criterion of training data is a crucial option to improve the prediction accuracy of surrogate models. In this paper, we hypothesize that a proper selection criterion changes dependent on the problems and/or search situations. Accordingly, this paper proposes a surrogate-assisted differential evolution, which adapts the training data selection criterion to enhance the model accuracy and then optimization performance of our SAEA. In detail, the proposed algorithm builds multiple approximation models under different selection criteria. Then, the best-fitting model is utilized to screen candidate solutions. Experimental results show that the proposed algorithm outperforms the state-of-the-art SAEAs on a single-objective optimization benchmark suite up to 100 dimensions.

# Summary. An optional shortened abstract.
summary: This paper proposes a novel SAEA with adaptation of the training data selection criterion. Our proposal builds multiple RBF surrogate models with sets of training data chosen by different selection criteria, and selects one model with the best accuracy.

tags: [Surrogate-assisted Evolutionary Algorithm, Adaptation of Training Data Selection Criterion, Radial Basis Function Network, Differential Evolution]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link (Paper)
  url: https://ieeexplore.ieee.org/document/
- name: Link (Conference)
  url: https://ieeessci2022.org
 
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
  caption: ""
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
slides: ""
---

### 参考

- 本サイトの全ての添付ファイルは著者バージョンであり，出版バージョンと一致しない可能性があります．