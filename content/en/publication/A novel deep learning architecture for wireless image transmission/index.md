---

title: "A Novel Deep Learning Architecture for Wireless Image Transmission"
authors: [SixianWang,JinchengDai, ShengshiYao, KaiNiu, PingZhang]
date: 2021-12
doi: "10.1109/GLOBECOM46510.2021.9685036"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-12-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Global Communications Conference (GLOBECOM), 2021"
publication_short: "IEEE GLOBECOM"

abstract: "In this paper, the problem of neural compression based image transmission over wireless channels is studied. Since all procedures are considered over wireless links, the quality of training is affected by wireless factors such as packet errors. In the considered model, compressed data given by the neural source encoder (NSE) are fed into an error-control channel encoder and modulated as discrete symbols sent over a memoryless channel. In the receiving end, the channel decoder and the neural source decoder (NSD) forms an iterative structure to reconstruct the original image. Since all neural compressed data are transmitted over wireless channels, the training of NSD is affected by wireless channel factors such as residual bit errors given by the channel decoder. Meanwhile, during outer-loop iterations, the NSD needs to match the variant of information reliability output by the channel decoder so as to build a global optimal receiver. To this end, a refiner neural network is first attached after the NSD to adjust its output as the format of a priori information sent into the channel decoder. Then, the extrinsic information transfer (EXIT) functions of channel decoder and NSD are derived. At each iteration, the reliability of messages sent into the NSD is explicitly predicted by using the EXIT chart. By this means, the NSD can be trained in a residual bit error aware manner, and we realize a joint learning and iterative decoding framework to ensure the quality of neural image transmission over realistic wireless channels. "

tags: [Image, Semantic]
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
- name: IEEE GLOBECOM
  url: 

url_pdf: https://ieeexplore.ieee.org/abstract/document/9685036
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
