---
title: "学習データ端点付近での近似精度低下がサロゲート進化計算の性能に与える悪影響の分析とその抑制"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- 三浦 岳也
- 中田 雅也

# Author notes (optional)
author_notes:
- "横浜国立大学"
- "横浜国立大学"
- "横浜国立大学"

date: "2024-12-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*第18回進化計算シンポジウム講演論文集*, pp. 233--240"
publication_short: "*第18回進化計算シンポジウム講演論文集*, pp. 233--240"

abstract: 高コスト最適化問題の代表的解法であるサロゲート進化計算の性能は，サロゲートの性能に依存するため，これを適切に管理する必要がある．既存の多くのサロゲート進化計算は，目的関数を近似するサロゲートを構築し，学習データの存在する範囲，つまり各決定変数の最小値から最大値で定義される領域を進化計算で探索する．しかしながら，一般に，領域の境界付近では，応答する学習データ点数の少なさゆえに，サロゲートの近似精度が低下する．そのため，境界付近での近似精度が低いサロゲートにより，解探索が誤った方向に促される可能性がある．そこで本研究は，この境界付近での近似精度の低下がサロゲート進化計算に与える影響を分析し，その抑制方法を検討する．具体的には，サロゲートを構築した後に，探索範囲を制限することで，近似精度が高い領域でのみ探索して最適化性能を向上できるかを調査する．対照実験として，探索範囲を変えない場合，拡張させた場合も検討し，傾向がサロゲートの学習データ・使用する機械学習モデル・使用する進化計算に依存せず普遍的であるかを調査する．また，既存のサロゲート進化計算や実問題でも幅広く検証する．


# Summary. An optional shortened abstract.
summary: 本研究は，学習データの存在領域境界付近での近似精度の低下がサロゲート進化計算に与える影響を分析し，その抑制方法を検討する．

tags: [Surrogate-assisted Evolutionary Algorithm, Approximation Accuracy, Training Data Boundary, Radial Basis Function Network, Gaussian Process, Differential Evolution, Particle Swarm Optimization]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Link (Conference)
  url: http://www.jpnsec.org/symposium202403.html

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


### 参考

- 本サイトの全ての添付ファイルは著者バージョンであり，出版バージョンと一致しない可能性があります．
