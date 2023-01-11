---
title: "解更新の成功実績を選定基準とする適応サロゲート進化計算"

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

date: "2022-12-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper;
# 10 = Invited Paper;
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*第16回進化計算シンポジウム講演論文集*, pp. 177--184"
publication_short: "*第16回進化計算シンポジウム講演論文集*, pp. 177--184"

abstract: 機械学習により解評価を代替するサロゲート進化計算（SAEA）では，最適化性能はサロゲートの性能に依存するため，これを適切に選択することが重要である．近年では，一回の最適化プロセス中にオンラインにモデル適応を行う適応SAEAが主流である．しかしながら，SAEAの探索効率を向上させるサロゲートの有効な性能指標は定まっておらず，目的関数値に対する推定誤差や順位相関などが使用されてきた．高々数百から数千程度の学習データの下では，これらの性能指標は信頼性に欠け，推定誤差が最小のサロゲートを用いてもSAEAの性能が改善しない場合がある．そこで本研究では，評価値の高い解を実際に発見できたか否か，つまり，解更新の成功実績をサロゲートの選定基準とする適応SAEAを提案する．実験では，CEC2013ベンチマークセットで提案手法が最先端のSAEAよりも優れた性能を導出することを示す．また考察では，解更新の成功実績を選定基準とする適応の妥当性を，解更新成功率などの観点から定量的に検証する．

# Summary. An optional shortened abstract.
summary: 適応候補のサロゲートが推薦した解が解更新に成功したかどうか基づいてサロゲートを選択する，新しい適応サロゲート進化計算を提案する．

tags: [Surrogate-assisted Evolutionary Algorithm, Adaptation of Surrogate, Radial Basis Function Network, Kriging, Differential Evolution]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Link (Conference)
  url: http://www.jpnsec.org/symposium202203.html

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

- [IEEE CIS Young Researchers Award]()と[プレゼンテーション賞]()を同時受賞しました．
- 本サイトの全ての添付ファイルは著者バージョンであり，出版バージョンと一致しない可能性があります．
