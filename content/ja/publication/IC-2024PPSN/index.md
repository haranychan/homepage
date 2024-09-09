---
title: "A Surrogate-assisted Partial Optimization for Expensive Constrained Optimization Problems"

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

date: "2024-09-07T00:00:00Z"
doi: "10.1007/978-3-031-70068-2_24"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Parallel Problem Solving from Nature (PPSN)*, pp. 391--407"
publication_short: "*Proc. Int. Conf. Parallel Probl. Solving Nat. (PPSN)*, pp. 391--407"

abstract: Surrogate-assisted evolutionary algorithms (SAEAs) are gradually gaining attention as a method for solving expensive optimization problems with inequality constraints. Most SAEAs construct a surrogate model for each objective/constraint function and then aggregate approximation functions of constraints to estimate the feasibility of unevaluated solutions. However, because of the aggregation, the differences in the scales among constraints are ignored. Constraints with smaller scales do not benefit from constraint handling techniques as much as larger constraints, while the effects of handling constraints with larger scales scatter to the other many constraints. This results in an inefficient constraint optimization. Accordingly, this work proposes a new SAEA that partially optimizes each objective/constraint, namely surrogate-assisted partial optimization (SAPO). Solutions with better values of objective/constraint are selected from the evaluated solutions as the parent solutions and a focused objective/constraint is independently optimized using surrogate models one by one. Experimental results reveal the superiority of SAPO compared to the state-of-the-art SAEAs on a single-objective optimization problem suite with inequality constraints under an expensive optimization scenario.

# Summary. An optional shortened abstract.
summary: This work proposes a new surrogate-assisted evolutionary algorithm that partially optimizes each objective/constraint, namely surrogate-assisted partial optimization (SAPO). Solutions with better values of objective/constraint are selected from the evaluated solutions as the parent solutions and a focused objective/constraint is independently optimized using surrogate models one by one.

tags: [Surrogate-assisted Evolutionary Algorithm, Constrained Optimization Problem, Expensive Optimization Problem, Radial Basis Function Network, Differential Evolution]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link (Paper)
  url: https://link.springer.com/chapter/10.1007/978-3-031-70068-2_24
- name: Link (Conference)
  url: https://ppsn2024.fh-ooe.at
 
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

- すべての発表はポスター形式です．
