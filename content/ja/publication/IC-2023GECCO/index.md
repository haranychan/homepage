---
title: "Utilizing the Expected Gradient in Surrogate-assisted Evolutionary Algorithms"

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

date: "2023-07-15T00:00:00Z"
doi: "10.1145/3583133.3590694"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*ACM The Genetic and Evolutionary Computation Conference Companion (GECCO Companion)*, pp. 1--4"
publication_short: "*Proc. ACM Conf. Genet. Evol. Comput. Companion (GECCO Companion)*, pp. 1--4"

abstract: In the field of surrogate-assisted evolutionary algorithms (SAEAs), Gaussian Process (GP) is a widely used technique to approximate the objective function. Although a GP model can provide an expected gradient of a function to be approximated, little attention has been paid to the utilization of the gradient information. Thus, this paper presents an expected gradient-based SAEA, in which the expected gradient of the objective function provided by the GP models is utilized to conduct an efficient local search. Specifically, the proposed algorithm first conducts a global search with a differential evolution algorithm to find promising regions of the search space. Then, it builds a GP model for each promising region, and a quasi-Newton method (L-BFGS-B) is executed on its model with guidance from the expected gradient. This gradient-based local search intends to sufficiently search the approximate objective function, by finding various local optimal solutions in an efficient manner. Experimental results show that our algorithm is competitive with state-of-the-art SAEAs on a single-objective optimization benchmark suite.

# Summary. An optional shortened abstract.
summary: This paper utilizes the expected gradient of the Gaussian Process (GP) in a surrogate-assisted evolutionary algorithm. Specifically, our proposal iteratively runs a quasi-Newton method (L-BFGS-B) changing initial points on multiple GPs constructed to approximate the promising region of the objective function.

tags: [Surrogate-assisted Evolutionary Algorithm, Expected Gradient, Quasi-Newton Method, Differential Evolution, Gaussian Process]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link (Paper)
  url: https://dl.acm.org/doi/10.1145/3583133.3590694
- name: Link (Conference)
  url: https://gecco-2023.sigevo.org/HomePage
 
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

- ポスター発表として採択されました．