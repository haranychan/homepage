---
title: 進化計算シンポジウム2024

event: 進化計算シンポジウム2024
event_url: http://www.jpnsec.org/symposium202403.html

location: SHIRAHAMA KEY TERRACE HOTEL SEAMORE
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: 進化計算シンポジウム2024にて発表を行います．
abstract: "「学習データ端点付近での近似精度低下がサロゲート進化計算の性能に与える悪影響の分析とその抑制」というタイトルで，進化計算シンポジウム2024にて発表を行います．[オープンスペースディスカッション](https://sites.google.com/view/osd2024/home)では，トピックを提案しました．"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-12-20T20:00:00Z"
date_end: "2024-12-22T14:20:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2024-12-19T00:00:00Z"

authors: []
tags: [Surrogate-assisted Evolutionary Algorithm, Approximation Accuracy, Training Data Boundary, Radial Basis Function Network, Gaussian Process, Differential Evolution, Particle Swarm Optimization]

# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  # focal_point: Right

links:
links:
- name: CFP
  url: http://www.jpnsec.org/symposium202403.html
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

高コスト最適化問題の代表的解法であるサロゲート進化計算の性能は，サロゲートの性能に依存するため，これを適切に管理する必要がある．既存の多くのサロゲート進化計算は，目的関数を近似するサロゲートを構築し，学習データの存在する範囲，つまり各決定変数の最小値から最大値で定義される領域を進化計算で探索する．しかしながら，一般に，領域の境界付近では，応答する学習データ点数の少なさゆえに，サロゲートの近似精度が低下する．そのため，境界付近での近似精度が低いサロゲートにより，解探索が誤った方向に促される可能性がある．そこで本研究は，この境界付近での近似精度の低下がサロゲート進化計算に与える影響を分析し，その抑制方法を検討する．具体的には，サロゲートを構築した後に，探索範囲を制限することで，近似精度が高い領域でのみ探索して最適化性能を向上できるかを調査する．対照実験として，探索範囲を変えない場合，拡張させた場合も検討し，傾向がサロゲートの学習データ・使用する機械学習モデル・使用する進化計算に依存せず普遍的であるかを調査する．また，既存のサロゲート進化計算や実問題でも幅広く検証する．


#### 開催趣旨（[ホームページ](http://www.jpnsec.org/symposium202403.html)より引用）

> 進化計算シンポジウムは，国内の進化計算の研究者が年に一度合宿形式でじっくりと議論する機会を持つことを目的として企画され，これまで17回開催されてきました．