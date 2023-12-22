---
title: GECCO 2023

event: The Genetic and Evolutionary Computation Conference (GECCO 2023)
event_url: https://gecco-2023.sigevo.org/HomePage

location: Altis Grand Hotel, Lisbon, Portugal
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: The Genetic and Evolutionary Computation Conference (GECCO 2023)
abstract: "I will give a poster presentation entitled \"Utilizing the Expected Gradient in Surrogate-assisted Evolutionary Algorithms\" at GECCO 2023, a refereed international conference."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-07-15T12:00:00Z"
date_end: "2023-07-19T18:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2023-06-29T00:00:00Z"

authors: []
tags: [Surrogate-assisted Evolutionary Algorithm, Expected Gradient, Quasi-Newton Method, Differential Evolution, Gaussian Process]

# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  # focal_point: Right

links:
- name: CFP
  url: https://gecco-2023.sigevo.org/Call-for-Papers
url_code: ""
url_pdf: "/publication/IC-2023GECCO/IC-2023GECCO.pdf"
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

In addition to the main conference, I will take part in [SIGEVO Summer School (S3)](https://gecco-2023.sigevo.org/Summer-School).

I'm looking forward to having a lot of discussions!

### Abstract of the Paper

In the field of surrogate-assisted evolutionary algorithms (SAEAs), Gaussian Process (GP) is a widely used technique to approximate the objective function. Although a GP model can provide an expected gradient of a function to be approximated, little attention has been paid to the utilization of the gradient information. Thus, this paper presents an expected gradient-based SAEA, in which the expected gradient of the objective function provided by the GP models is utilized to conduct an efficient local search. Specifically, the proposed algorithm first conducts a global search with a differential evolution algorithm to find promising regions of the search space. Then, it builds a GP model for each promising region, and a quasi-Newton method (L-BFGS-B) is executed on its model with guidance from the expected gradient. This gradient-based local search intends to sufficiently search the approximate objective function, by finding various local optimal solutions in an efficient manner. Experimental results show that our algorithm is competitive with state-of-the-art SAEAs on a single-objective optimization benchmark suite.


#### Why GECCO ? (Cited from the [Homepage](https://gecco-2023.sigevo.org/HomePage))

> The Genetic and Evolutionary Computation Conference (GECCO) presents the latest high-quality results in genetic and evolutionary computation since 1999. Topics include: genetic algorithms, genetic programming, ant colony optimization and swarm intelligence, complex systems, evolutionary combinatorial optimization and metaheuristics, evolutionary machine learning, evolutionary multiobjective optimization, evolutionary numerical optimization, neuroevolution, real world applications, search-based software engineering, theory, hybrids and more.