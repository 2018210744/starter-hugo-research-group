---

title: "Adaptive Semantic Communications: Overfitting the Source and Channel for Profit"
authors: [JinchengDai, SixianWang, KeYang, KailinTan, XiaoqiQin, ZhongweiSi, KaiNiu, PingZhang]
date: 2022-11
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Journal on Selected Areas in Communications"
publication_short: "IEEE JSAC"

abstract: "Most semantic communication systems leverage deep learning models to provide end-to-end transmission performance surpassing the established source and channel coding approaches. While, so far, research has mainly focused on architecture and model improvements, but such a model trained over a full dataset and ergodic channel responses is unlikely to be optimal for every test instance. Due to limitations on the model capacity and imperfect optimization and generalization, such learned models will be suboptimal especially when the testing data distribution or channel response is different from that in the training phase, as is likely to be the case in practice. To tackle this, in this paper, we propose a novel semantic communication paradigm by leveraging the deep learning model's overfitting property. Our model can for instance be updated after deployment, which can further lead to substantial gains in terms of the transmission rate-distortion (RD) performance. This new system is named adaptive semantic communication (ASC). In our ASC system, the ingredients of wireless transmitted stream include both the semantic representations of source data and the adapted decoder model parameters. Specifically, we take the overfitting concept to the extreme, proposing a series of ingenious methods to adapt the semantic codec or representations to an individual data or channel state instance. The whole ASC system design is formulated as an optimization problem whose goal is to minimize the loss function that is a tripartite tradeoff among the data rate, model rate, and distortion terms. The experiments (including user study) verify the effectiveness and efficiency of our ASC system. Notably, the substantial gain of our overfitted coding paradigm can catalyze semantic communication upgrading to a new era."

tags: []
categories: [semantic comm]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
# url: https://twitter.com
# icon_pack: fab
# icon: twitter

links:
- name: arXiv
  url: 

url_pdf: https://arxiv.org/abs/2211.04339
url_code: 
url_dataset:
url_poster:
url_project: 
url_slides:
url_source: 
url_video:




# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
