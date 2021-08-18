---
title: "Comparison of Adaptive Differential Evolution Algorithms on the MOEA/D-DE Framework"

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

date: "2021-06-28T00:00:00Z"
doi: "10.1109/CEC45853.2021.9504997"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper; 
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Congress on Evolutionary Computation (CEC)*"
publication_short: "*Proc. IEEE Congr. Evol. Comput. (CEC)*"

abstract: Existing works have reported that adaptive differential evolution algorithms, i.e., adaptive DEs, improve the MOEA/D-DE algorithm, but this result is limited to small-scale multi-objective optimization problems. This paper compares four popular adaptive DEs on the MOEA/D-DE framework to evaluate their scalability to the number of decision variables and objectives. Specifically, we employ jDE, JADE, EPSDE, and SaDE in this paper. Our experimental results provide the following novel observations. MOEA/D-DE with JADE derives the best average rank on small-scale problems. However, the performances of MOEA/D-DE with JADE, EPSDE, and SaDE gradually degrade with the increase of the problem scale. In contrast, jDE stably improves the performance of MOEA/D-DE on large-scale problems employed in this paper (i.e., 11 objectives and 100 decision variables). Thus, we find a critical tradeoff among adaptive DEs in terms of the scalability of the MOEA/D-DE framework; a statistical adaption like JADE is suitable for small-scale problems, but a randomization adaptation like jDE is effective with the increase of the problem scale. Our results also suggest that parameter-only adaptation can be suitable for MOEA/D-DE regardless of the problem scale.

# Summary. An optional shortened abstract.
summary: This paper compares four popular adaptive DEs on the MOEA/D-DE framework to evaluate their scalability to the number of decision variables and objectives. Specifically, we employ jDE, JADE, EPSDE, and SaDE in this paper. Our experimental results provide several novel observations.

tags: [Algorithmic Configuration Adaptation, MOEA/D-DE, Many-objective Optimization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link (Paper)
  url: https://ieeexplore.ieee.org/document/9504997
- name: Link (Conference)
  url: https://cec2021.mini.pw.edu.pl/
 
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

- 本サイトの全ての添付ファイルは著者バージョンであり，出版バージョンと一致するとは限りません．