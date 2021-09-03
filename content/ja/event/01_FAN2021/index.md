---
title: FAN 2021 Online

event: インテリジェント・システム・シンポジウム (FAN2021)
event_url: https://sites.google.com/view/fan2021online/

location: オンライン
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: インテリジェント・システム・シンポジウム（FAN2021）にて発表を行います．
abstract: "「高計算コストな最適化問題に向けた事前検証型アンサンブル適応差分進化」というタイトルで，インテリジェント・システム・シンポジウム（FAN2021）にて発表を行います．FAN2021は査読なし国内会議ですが，論文概要（abstract）にのみ査読があります．"

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
url_pdf: "/ja/publication/NC-2021FAN/NC-2021FAN.pdf"
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

### 論文概要

1回の解評価に時間がかかる高計算コストな問題(CEP)が実最適化問題に多く存在し，少ない解評価での高性能な解導出が求められる．探索中にパラメータを問題に自動特化させる最適化技術である適応差分進化(適応DE)は，適応が適切に成されればCEPに有効な方法論になり得る．異種の適応DEから成るアンサンブル適応DEは，適応DEより広いアルゴリズム空間から見つかる好適な適応DEで性能向上する可能性を持つ一方で，膨大化したアルゴリズム空間の探索は困難になる．既存手法は，使用した適応DEの妥当性を，一定世代毎の解評価値で事後的に検証しながらアルゴリズム空間を探索するため，大量の解評価を要しCEPに不適である．そこで本稿では，好適な適応DEを解生成に先立って追加の解評価なしに毎世代推定する，事前検証型のアンサンブル適応DEを提案する．実験では，提案法が既存手法より優れた性能と収束速度を導出することを示す．


### Abstract of the Paper (in English)

Computational expensive optimization problems (CEPs) are widely seen in real-world applications. In this domain, high-performance solution derivation with as few fitness evaluations (FEs) as possible is required. Adaptive Differential Evolution Algorithms (adaptive DE), optimization techniques that automatically adapt their hyperparameters to the problem during a single run, can be effective methodologies for CEPs if the adaptation is done properly. Ensemble adaptive DEs, which consist of heterogeneous adaptive DEs, have the potential to improve performance with suitable adaptive DEs found in a larger algorithm space than that of a single adaptive DE, but they also make it difficult to find a suitable adaptive DE due to a large algorithm search space. The existing methods verify the validity of the used adaptive DEs in a post-hoc validation manner while utilizing FEs obtained in certain periods of generations to search the algorithm space. Thus they require a large number of FEs and are unsuitable for CEPs. This paper proposes a new ensemble adaptive DE with a prior validation that estimates a suitable adaptive DE every generation without additional FEs before solution generation. Experimental results show that our proposal outperforms existing methods and has a better convergence speed.


#### 開催趣旨（[ホームページ](https://sites.google.com/view/fan2021online/)より引用）

> インテリジェント・システム・シンポジウム（FANシンポジウム）は，ファジィ理論，ニューラルネットワーク，進化計算をはじめとした様々な計算知能技術の基礎から応用までを含む先端的研究発表の場として実績を積み重ねてきました．知的システムのさらなる高度化を目指して，個々の計算知能技術及びそれらの融合等に関する最新の研究成果，また，これらのシステムの計画，設計，最適化，製作，診断，制御，運用，評価等，及びロボット，コンピュータ，ネットワーク等への応用等に関する研究成果の発表を通して，情報交換と活発な討議を行います．