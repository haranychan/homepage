---
title: 進化計算シンポジウム2023

event: 進化計算シンポジウム2023
event_url: http://www.jpnsec.org/symposium202303.html

location: 小田原お堀端コンベンションホール
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: 進化計算シンポジウム2023にて発表を行います．
abstract: "「パレート最適なサロゲート群を利用する適応サロゲート進化計算」というタイトルで，進化計算シンポジウム2023にて発表を行います．[オープンスペースディスカッション](https://sites.google.com/view/osd2023-jpnsec)では，学生幹事を2年連続で務めます．"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-12-21T13:30:00Z"
date_end: "2023-12-23T18:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2023-12-22T00:00:00Z"

authors: []
tags: [Surrogate-assisted Evolutionary Algorithm, Adaptation of Surrogate, Radial Basis Function Network, Pareto-optimal Surrogates Set, NSGA-II, Differential Evolution]

# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  # focal_point: Right

links:
links:
- name: CFP
  url: http://www.jpnsec.org/symposium202303.html
url_code: ""
url_pdf: ""
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

機械学習により解評価を代替するサロゲート進化計算（SAEA）では，最適化性能はサロゲートの性能に依存するため，これを適切に選択することが重要である．近年では，一回の最適化プロセス中にオンラインにサロゲートを選択する適応SAEAが盛んに研究されている。既存の適応SAEAでは，目的関数値に対する推定誤差などの近似精度指標でサロゲートを選択することがほとんどである。しかしながら，目的関数を忠実に再現することのみが重視された結果，多数の局所解を持つサロゲートが構築され，探索を不要に困難にしている可能性がある．そこで本研究では，近似関数の滑らかさに変化を与えるパラメータを変化させながら，近似精度とサロゲートの複雑性の両方を考慮したサロゲートの選択法を提案する．具体的には，提案法では，近似精度とサロゲートの複雑性を2目的最適化問題とみなし，多目的進化計算でパレート最適なサロゲート群を得る．次に，近似精度の高いサロゲートと，滑らかに近似して問題を易化したサロゲートの両方を活用して，解評価する解を選別する．実験では，CEC2013ベンチマークセットで提案手法が最先端のSAEAよりも優れた性能を導出することを示す．


#### 開催趣旨（[ホームページ](http://www.jpnsec.org/symposium202303.html)より引用）

> 進化計算シンポジウムは，国内の進化計算の研究者が年に一度合宿形式でじっくりと議論する機会を持つことを目的として企画され，これまで16回開催されてきました．