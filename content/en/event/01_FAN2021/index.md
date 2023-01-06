---
title: FAN 2021 Online

event: 2021 Symposium on Fuzzy, Artificial Intelligence, Neural Networks and Computational Intelligence (FAN2021)
event_url: https://sites.google.com/view/fan2021online/

location: Online
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: 2021 Symposium on Fuzzy, Artificial Intelligence, Neural Networks and Computational Intelligence 
abstract: "I will give a presentation entitled \"High-level Ensemble of Adaptive Differential Evolution with Prior-validation toward Computationally Expensive Optimization Problems\" at FAN2021, a not refereed national conference, but abstract is refereed. Both paper and presentation are ***in Japanese***."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-09-21T9:00:00Z"
date_end: "2021-09-23T18:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2021-09-03T00:00:00Z"

authors: []
tags: [Adaptive Differential Evolution, Ensemble Evolutionary Computation, Computationally Expensive Optimization]

# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  # focal_point: Right

links:
- name: CFP
  url: https://drive.google.com/file/d/1pIN88Pqc25CmB6EX20Mfc2iICIIiVNxQ/view
url_code: ""
url_pdf: "/publication/NC-2021FAN/NC-2021FAN.pdf"
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

### Abstract of the Paper

Computational expensive optimization problems (CEPs) are widely seen in real-world applications. In this domain, high-performance solution derivation with as few fitness evaluations (FEs) as possible is required. Adaptive Differential Evolution Algorithms (adaptive DE), optimization techniques that automatically adapt their hyperparameters to the problem during a single run, can be effective methodologies for CEPs if the adaptation is done properly. Ensemble adaptive DEs, which consist of heterogeneous adaptive DEs, have the potential to improve performance with suitable adaptive DEs found in a larger algorithm space than that of a single adaptive DE, but they also make it difficult to find a suitable adaptive DE due to a large algorithm search space. The existing methods verify the validity of the used adaptive DEs in a post-hoc validation manner while utilizing FEs obtained in certain periods of generations to search the algorithm space. Thus they require a large number of FEs and are unsuitable for CEPs. This paper proposes a new ensemble adaptive DE with a prior validation that estimates a suitable adaptive DE every generation without additional FEs before solution generation. Experimental results show that our proposal outperforms existing methods and has a better convergence speed.
