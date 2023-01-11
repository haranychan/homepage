---
title: "High-level Ensemble of Adaptive Differential Evolution with Prior-validation toward Computationally Expensive Optimization Problems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Masaya Nakata

# Author notes (optional)
author_notes:
- "Yokohama National University"
- "Yokohama National University"

date: "2021-09-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Symposium on Fuzzy, Artificial Intelligence, Neural Networks and Computational Intelligence (FAN2021)*, pp. 132--137 (in Japanese)"
publication_short: "*Proc. Symp. Fuzzy Artif. Intell. Neural Netw. Comput. Intell. (FAN)*, pp. 132--137 (in Japanese)"

abstract: Computational expensive optimization problems (CEPs) are widely seen in real-world applications. In this domain, high-performance solution derivation with as few fitness evaluations (FEs) as possible is required. Adaptive Differential Evolution Algorithms (adaptive DE), optimization techniques that automatically adapt their hyperparameters to the problem during a single run, can be effective methodologies for CEPs if the adaptation is done properly. Ensemble adaptive DEs, which consist of heterogeneous adaptive DEs, have the potential to improve performance with suitable adaptive DEs found in a larger algorithm space than that of a single adaptive DE, but they also make it difficult to find a suitable adaptive DE due to a large algorithm search space. The existing methods verify the validity of the used adaptive DEs in a post-hoc validation manner while utilizing FEs obtained in certain periods of generations to search the algorithm space. Thus they require a large number of FEs and are unsuitable for CEPs. This paper proposes a new ensemble adaptive DE with a prior validation that estimates a suitable adaptive DE every generation without additional FEs before solution generation. Experimental results show that our proposal outperforms existing methods and has a better convergence speed.
# Summary. An optional shortened abstract.
summary: This paper proposes a new ensemble adaptive DE with a prior validation that estimates a suitable adaptive DE every generation without additional FEs before solution generation. Experimental results show that our proposal outperforms existing methods and has a better convergence speed.

tags: [Adaptive Differential Evolution, Prior-validation, Computationally Expensive Optimization, Ensemble Evolutionary Computation]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Link (Conference)
  url: https://sites.google.com/view/fan2021online/
- name: Link (CFP)
  url: https://drive.google.com/file/d/1pIN88Pqc25CmB6EX20Mfc2iICIIiVNxQ/view

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

### Notice

- We got the [Excellent Paper Award](https://sites.google.com/view/fan2021online/%E8%A1%A8%E5%BD%B0).
- FAN2021 is a not refereed national conference, but abstract is refereed.
- All materials on this page are author’s versions, not necessarily coincide with final published versions.