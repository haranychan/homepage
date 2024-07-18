---
title: PPSN 2024

event: International Conference on Parallel Problem Solving from Nature (PPSN 2024)
event_url: https://ppsn2024.fh-ooe.at

location: University of Applied Sciences Upper Austria, Hagenberg im Mühlkreis, Austria
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: PPSN 2024 にて発表を行います．
abstract: "「A Surrogate-assisted Partial Optimization for Expensive Constrained Optimization Problems」というタイトルで，PPSN 2024 にてポスター発表を行います．会場は University of Applied Sciences Upper Austria です．"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-09-14T09:00:00Z"
date_end: "2024-09-18T18:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2024-07-18T00:00:00Z"

authors: []
tags: [Surrogate-assisted Evolutionary Algorithm, Constrained Optimization Problem, Expensive Optimization Problem, Radial Basis Function Network, Differential Evolution]

# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  # focal_point: Right

links:
- name: CFP
  url: https://ppsn2024.fh-ooe.at/calls/
url_code: ""
url_pdf: "/ja/publication/IC-2024PPSN/IC-2024PPSN.pdf"
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- []
---

すべての発表はポスター形式です．

現時点では，私たちの発表は，9月16日(月) 15:30-17:00 (CEST, 中央ヨーロッパ夏時間)の予定です．

口頭発表より濃い議論ができるポスター発表を楽しみにしています！

### Abstract of the Paper

Surrogate-assisted evolutionary algorithms (SAEAs) are gradually gaining attention as a method for solving expensive optimization problems with inequality constraints. Most SAEAs construct a surrogate model for each objective/constraint function and then aggregate approximation functions of constraints to estimate the feasibility of unevaluated solutions. However, because of the aggregation, the differences in the scales among constraints are ignored. Constraints with smaller scales do not benefit from constraint handling techniques as much as larger constraints, while the effects of handling constraints with larger scales scatter to the other many constraints. This results in an inefficient constraint optimization. Accordingly, this work proposes a new SAEA that partially optimizes each objective/constraint, namely surrogate-assisted partial optimization (SAPO). Solutions with better values of objective/constraint are selected from the evaluated solutions as the parent solutions and a focused objective/constraint is independently optimized using surrogate models one by one. Experimental results reveal the superiority of SAPO compared to the state-of-the-art SAEAs on a single-objective optimization problem suite with inequality constraints under an expensive optimization scenario.


#### 開催趣旨（[ホームページ](https://ppsn2024.fh-ooe.at)より引用）

> The International Conference on Parallel Problem Solving From Nature is a biannual open forum fostering the study of natural models, iterative optimization heuristics search heuristics, machine learning, and other artificial intelligence approaches. We invite researchers and practitioners to present their work, ranging from rigorously derived mathematical results to carefully crafted empirical studies.