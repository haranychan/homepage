---
title: "パレート最適なサロゲート群を利用する適応サロゲート進化計算"

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

date: "2023-12-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*第17回進化計算シンポジウム講演論文集*, pp. 380--387"
publication_short: "*第17回進化計算シンポジウム講演論文集*, pp. 380--387"

abstract: 機械学習により解評価を代替するサロゲート進化計算（SAEA）では，最適化性能はサロゲートの性能に依存するため，これを適切に選択することが重要である．近年では，一回の最適化プロセス中にオンラインにサロゲートを選択する適応SAEAが盛んに研究されている。既存の適応SAEAでは，目的関数値に対する推定誤差などの近似精度指標でサロゲートを選択することがほとんどである。しかしながら，目的関数を忠実に再現することのみが重視された結果，多数の局所解を持つサロゲートが構築され，探索を不要に困難にしている可能性がある．そこで本研究では，近似関数の滑らかさに変化を与えるパラメータを変化させながら，近似精度とサロゲートの複雑性の両方を考慮したサロゲートの選択法を提案する．具体的には，提案法では，近似精度とサロゲートの複雑性を2目的最適化問題とみなし，多目的進化計算でパレート最適なサロゲート群を得る．次に，近似精度の高いサロゲートと，滑らかに近似して問題を易化したサロゲートの両方を活用して，解評価する解を選別する．実験では，CEC2013ベンチマークセットで提案手法が最先端のSAEAよりも優れた性能を導出することを示す．

# Summary. An optional shortened abstract.
summary: 近似関数の滑らかさに変化を与えるパラメータを変化させながら，近似精度とサロゲートの複雑性の両方を考慮したサロゲートの選択法を提案する．

tags: [Surrogate-assisted Evolutionary Algorithm, Adaptation of Surrogate, Radial Basis Function Network, Pareto-optimal Surrogates Set, NSGA-II, Differential Evolution]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Link (Conference)
  url: http://www.jpnsec.org/symposium202303.html

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
