---
title: "Competitive-Adaptive Algorithm-Tuning of Metaheuristics inspired by the Equilibrium Theory: A Case Study"

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

date: "2020-07-19T00:00:00Z"
doi: "10.1109/CEC48606.2020.9185493"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Congress on Evolutionary Computation (CEC)*, E-24156, (8)"
publication_short: "*Proc. IEEE Congr. Evol. Comput. (CEC)*, E-24156, (8)"

abstract: This paper proposes a competitive-adaptive algorithm tuning framework for meta-heuristic algorithms. Our proposed method, called CAT, is inspired by the Equilibrium Theory in economics, which explains competitors eventually converge to an equilibrium status, e.g. in terms of the price of products. In detail, our proposal runs multiple optimizers with different algorithmic configurations, e.g. mutation variants. Then, the configurations of inferior optimizers are adaptively tuned so that they can derive good solutions that superior ones have derived. This intends to boost the performance even with a limited number of fitness evaluations, by the following technical advantage. The CAT preliminarily validates a search capacity of tuned algorithmic configurations and then constructs an ensemble optimizer by utilizing multiple optimizers. As a case study, this paper applies the CAT to tune the differential evolution algorithms (DEs). Experimental results show that our proposal outperforms the standard DE and an alternative approach i.e. jDE, which adapts hyper-parameters of genetic operators.

# Summary. An optional shortened abstract.
summary: This paper proposes a competitive-adaptive algorithm tuning framework for meta-heuristic algorithms. Our proposed method, called CAT, is inspired by the Equilibrium Theory in economics, which explains competitors eventually converge to an equilibrium status, e.g. in terms of the price of products.

tags: [Adaptive Differential Evolution]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Link (Paper)
  url: https://ieeexplore.ieee.org/document/9185493
- name: Link (Conference)
  url: https://wcci2020.org/
 
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