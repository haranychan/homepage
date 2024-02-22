---
title: "Evolutionary Multiobjective Optimization Assisted by Scalarization Function Approximation for High-Dimensional Expensive Problems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuma Horaguchi
- admin
- Masaya Nakata

# Author notes (optional)
author_notes:
- "Yokohama National University"
- "Yokohama National University"
- "Yokohama National University"

date: "2024-02-22T00:00:00Z"
doi: "10.1016/j.swevo.2024.101516"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Swarm and Evolutionary Computation*, Vol. 86" #Vol. ,No. , pp. --"
publication_short: "*Swarm Evol. Comput.*, Vol. 86" #Vol. , No. , pp. --"

abstract: Surrogate-assisted evolutionary algorithms (SAEAs) are a promising approach for solving expensive multiobjective optimization problems, but they often cannot address high-dimensional problems. Although one common approach to overcoming this challenge is to construct reliable surrogates, their accuracy inevitably deteriorates in a high-dimensional search space. Thus, this paper presents a novel SAEA based on scalarization function approximation, which is designed to strengthen its robustness against this deterioration. The proposed algorithm constructs an approximation model for each scalarization function defined in a decomposition-based framework. Each decomposed problem is then solved using multiple independent models trained for its neighbor problems. The intent is to decrease the risk of search performance degradations caused by unreliable approximations and retain the redundancy of the surrogate-assisted search to hedge the risk of over-fitting. Furthermore, each approximation model is adapted to a promising region of its corresponding decomposed problem to reduce the complexity of model fitting given a limited number of training samples. Experimental results show that the proposed algorithm is competitive with state-of-the-art SAEAs adapted for high-dimensional problems.

# Summary. An optional shortened abstract.
summary: This paper presents a novel surrogate-assisted evolutionary algorithm based on scalarization function approximation, which is designed to strengthen its robustness against this deterioration. The proposed algorithm, called SFA/DE, constructs an approximation model for each scalarization function defined in a decomposition-based framework. Each decomposed problem is then solved using multiple independent models trained for its neighbor problems.

tags: [Surrogate-assisted Evolutionary Algorithm, Multiobjective Optimization, Scalarization Function, Many-objective Optimization, Differential Evolution]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Link
  url: https://www.sciencedirect.com/science/article/pii/S221065022400049X

url_pdf: ''
url_code: 'https://github.com/YNU-NakataLab/SFA-DE'
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

- All materials on this page are author’s versions, not necessarily coincide with final published versions.
