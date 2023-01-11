---
title: "高計算コストな最適化問題に向けた事前検証型アンサンブル適応差分進化"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- 中田 雅也

# Author notes (optional)
author_notes:
- "横浜国立大学"
- "横浜国立大学"

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
publication: "*インテリジェント・システム・シンポジウム（FAN2021）講演論文集*, pp. 132--137"
publication_short: "*FAN2021講演論文集*, pp. 132--137"

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

### 概要（和訳）

1回の解評価に時間がかかる高計算コストな問題（CEP）が実最適化問題に多く存在し，少ない解評価での高性能な解導出が求められる．探索中にパラメータを問題に自動特化させる最適化技術である適応差分進化（適応DE）は，適応が適切に成されればCEPに有効な方法論になり得る．異種の適応DEから成るアンサンブル適応DEは，適応DEより広いアルゴリズム空間から見つかる好適な適応DEで性能向上する可能性を持つ一方で，膨大化したアルゴリズム空間の探索は困難になる．既存手法は，使用した適応DEの妥当性を，一定世代毎の解評価値で事後的に検証しながらアルゴリズム空間を探索するため，大量の解評価を要しCEPに不適である．そこで本稿では，好適な適応DEを解生成に先立って追加の解評価なしに毎世代推定する，事前検証型のアンサンブル適応DEを提案する．実験では，提案法が既存手法より優れた性能と収束速度を導出することを示す．


### 参考

- [優秀論文賞](https://sites.google.com/view/fan2021online/%E8%A1%A8%E5%BD%B0)を受賞しました．
- FAN2021は査読なし国内会議ですが，論文概要（abstract）にのみ査読があります．
- 本サイトの全ての添付ファイルは著者バージョンであり，出版バージョンと一致しない可能性があります．
