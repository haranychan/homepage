---
title: "Emulation-based adaptive differential evolution: fast and auto-tunable approach for moderately expensive optimization problems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Kei Nishihara
- Masaya Nakata

# Author notes (optional)
author_notes:
- "Yokohama National University"
- "Yokohama National University"

date: "2024-02-15T00:00:00Z"
doi: "10.1007/s40747-023-01340-9"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Complex & Intelligent Systems*" #Vol. , No. , pp. --"
publication_short: "*Complex & Intell. Syst.*" #Vol. , No. , pp. --"

abstract: In the field of expensive optimization, numerous papers have proposed surrogate-assisted evolutionary algorithms (SAEAs) for a few thousand or even hundreds of function evaluations. However, in reality, low-cost simulations suffice for a lot of real-world problems, in which the number of function evaluations is moderately restricted, e.g., to several thousands. In such moderately restricted scenario, SAEAs become unnecessarily time-consuming and tend to struggle with premature convergence. In addition, tuning the SAEA parameters becomes impractical under the restricted budgets of function evaluations—in some cases, inadequate configuration may degrade performance instead. In this context, this paper presents a fast and auto-tunable evolutionary algorithm for solving moderately restricted expensive optimization problems. The presented algorithm is a variant of adaptive differential evolution (DE) algorithms, and is called emulation-based adaptive DE or EBADE. The primary aim of EBADE is to emulate the principle of sample-efficient optimization, such as that in SAEAs, by adaptively tuning the DE parameter configurations. Specifically, similar to Expected Improvement-based sampling, EBADE identifies parameter configurations that may produce expected-to-improve solutions, without using function evaluations. Further, EBADE incepts a multi-population mechanism and assigns a parameter configuration to each subpopulation to estimate the effectiveness of parameter configurations with multiple samples carefully. This subpopulation-based adaptation can help improve the selection accuracy of promising parameter configurations, even when using an expected-to-improve indicator with high uncertainty, by validating with respect to multiple samples. The experimental results demonstrate that EBADE outperforms modern adaptive DEs and is highly competitive compared to SAEAs with a much shorter runtime.

# Summary. An optional shortened abstract.
summary: This paper presents a fast and auto-tunable evolutionary algorithm for solving moderately restricted expensive optimization problems. The presented algorithm is a variant of adaptive differential evolution (DE) algorithms, and is called emulation-based adaptive DE or EBADE.

tags: [Adaptive Differential Evolution, Prior-validation, Multi-population, Moderately Computationally Expensive Optimization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link
  url: https://link.springer.com/article/10.1007/s40747-023-01340-9

url_pdf: ''
url_code: 'https://github.com/YNU-NakataLab/EBADE'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/ja/publication/J-2024CAIS/slide.pdf'
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

![photo1](1.jpg)

### 参考

- 本サイトの全ての添付ファイルは著者バージョンであり，出版バージョンと一致しない可能性があります．
