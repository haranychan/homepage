---
title: "自己適応型差分進化法におけるアルゴリズム構成の事前検証フレームワークによる性能の向上"

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

date: "2020-12-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Refereed Journal Paper;
# 2 = Refereed International Conference Paper;
# 3 = Not refereed National Conference Paper;
# 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = Preprint / Working Paper; 
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*情報処理学会 第131回「数理モデル化と問題解決」研究会（MPS）講演論文集*, Vol. 2020, No. 3, pp. 1--6"
publication_short: "*情報処理学会 第131回MPS研究会講演論文集*, Vol. 2020, No. 3, pp. 1--6"

abstract: 自己適応型差分進化法は，アルゴリズム構成を試行錯誤的に調整するため，少ない解評価回数では性能が十分に改善しない．本論文は，調整されたアルゴリズム構成の事前検証によって，試行錯誤的な調整を削減し，少ない解評価回数で高い性能を実現することを目的とする．また，提案する事前検証フレームワークは高い手法的汎用性があり，スケール係数，交叉率，突然変異・交叉戦略を個体ごとに調整する自己適応型差分進化法に適用できる．ベンチマーク問題を用いた実験では，代表手法であるjDE とSaDEにそれぞれ提案手法を適用した結果，通常よりも少ない数千オーダの解評価回数において，その性能が改善することを示す．これは，自己適応型差分進化法が不得意とする高計算コストな問題において，提案手法がこれに展開できる汎用的な方法論となり得ることを示すものである．

# Summary. An optional shortened abstract.
summary: 

tags: [Adaptive Differential Evolution, Prior-validation, Computationally Expensive Optimization]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Link (Paper)
  url: http://id.nii.ac.jp/1001/00208638/
- name: Link (Conference)
  url: http://www.ipsj.or.jp/kenkyukai/event/mps131.html
- name: Link (CFP)
  url: http://daemon.inf.uec.ac.jp/MPSPortal/events/mps131cfp

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
- 本国内会議は，査読あり論文誌[情報処理学会論文誌「数理モデル化と応用」Vol.14 No.3](../j-2021tom/)の募集と連動して開催されました．