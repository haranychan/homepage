---
title: 進化計算シンポジウム2022

event: 進化計算シンポジウム2022
event_url: http://www.jpnsec.org/symposium202203.html

location: 北海道大学 学術交流会館
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: 進化計算シンポジウム2022にて発表を行います．
abstract: "「解更新の成功実績を選定基準とする適応サロゲート進化計算」というタイトルで，進化計算シンポジウム2022にて発表を行います．前日イベントの[オープンスペースディスカッション](https://sites.google.com/view/osd2022-jpsec)では，学生幹事も務めます．"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-12-16T13:30:00Z"
date_end: "2022-12-18T18:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-12-17T00:00:00Z"

authors: []
tags: [Surrogate-assisted Evolutionary Algorithm, Adaptation of Surrogate, Radial Basis Function Network, Gaussian Process, Differential Evolution]

# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  # focal_point: Right

links:
links:
- name: CFP
  url: http://www.jpnsec.org/symposium202203.html
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

機械学習により解評価を代替するサロゲート進化計算（SAEA）では，最適化性能はサロゲートの性能に依存するため，これを適切に選択することが重要である．近年では，一回の最適化プロセス中にオンラインにモデル適応を行う適応SAEAが主流である．しかしながら，SAEAの探索効率を向上させるサロゲートの有効な性能指標は定まっておらず，目的関数値に対する推定誤差や順位相関などが使用されてきた．高々数百から数千程度の学習データの下では，これらの性能指標は信頼性に欠け，推定誤差が最小のサロゲートを用いてもSAEAの性能が改善しない場合がある．そこで本研究では，評価値の高い解を実際に発見できたか否か，つまり，解更新の成功実績をサロゲートの選定基準とする適応SAEAを提案する．実験では，CEC2013ベンチマークセットで提案手法が最先端のSAEAよりも優れた性能を導出することを示す．また考察では，解更新の成功実績を選定基準とする適応の妥当性を，解更新成功率などの観点から定量的に検証する．


#### 開催趣旨（[ホームページ](http://www.jpnsec.org/symposium202203.html)より引用）

> 進化計算シンポジウムは，国内の進化計算の研究者が年に一度合宿形式でじっくりと議論する機会を持つことを目的として企画され，これまで15回開催されてきました．