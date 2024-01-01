---
title: Our paper has been accepted to CAIS
subtitle: Our paper has been accepted to Complex & Intelligent Systems.

# Summary for listings and search engines
summary: "Our paper on an adaptive evolutionary algorithm has been accepted to Complex & Intelligent Systems journal."

# Link this post with a project
projects: []

# Date published
date: "2023-12-30T00:00:00Z"

# Date updated
lastmod: "2023-12-30T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ""
  focal_point: ""
  placement: 0
  preview_only: false

authors:
- admin

tags: [Adaptive Differential Evolution, Prior-validation, Multi-population, Moderately Computationally Expensive Optimization]

categories:
- Research
---

### Message

Our paper entitled \"[Emulation-based Adaptive Differential Evolution: Fast and Auto-tunable Approach for Moderately Expensive Optimization Problems]({{< relref "/publication/J-2024CAIS/index.md" >}})\" has been accepted to [Complex & Intelligent Systems](https://link.springer.com/journal/40747) journal.

This paper proposes an adaptive differential evolution (DE) algorithm for moderately expensive optimization problems (moderately EOPs). Our proposed algorithm, an emulation-based adaptive DE (EBADE), emulates the principle of sample-efficient optimization, such as that in surrogate-assisted evolutionary algorithms (SAEAs), by adaptively tuning the DE parameter configurations. Specifically, EBADE beforehand identifies parameter configurations that may produce expected-to-improve solutions, without using function evaluations. Further, EBADE incepts a multi-population mechanism and assigns a parameter configuration to each subpopulation to estimate the effectiveness of parameter configurations with multiple samples carefully. This subpopulation-based adaptation can help improve the selection accuracy of promising parameter configurations, even when using an expected-to-improve indicator with high uncertainty, by validating with respect to multiple samples.

In experiments, EBADE outperformed existing adaptive DEs and SAEAs in a scenario of a moderately EOPs for which almost no effective algorithm has been proposed so far. EBADE also enables significantly faster optimization than existing SAEAs. Moreover, EBADE is easy to use, allowing automatic control of parameter configurations, which is difficult to achieve in EOPs. 

![photo1](1.jpg)
