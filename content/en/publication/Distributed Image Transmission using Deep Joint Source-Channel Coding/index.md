---

title: "Distributed Image Transmission using Deep Joint Source-Channel Coding"
authors: [SixianWang, KeYang, JinchengDai, KaiNiu]
date: 2022-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Acoustics, Speech and Signal Processing"
publication_short: "IEEE ICASSP"

abstract: "We study the problem of deep joint source-channel coding (D-JSCC) for correlated image sources, where each source is transmitted through a noisy independent channel to the common receiver. In particular, we consider a pair of images captured by two cameras with probably overlapping fields of view transmitted over wireless channels and reconstructed in the center node. The challenging problem involves designing a practical code to utilize both source and channel correlations to improve transmission efficiency without additional transmission overhead. To tackle this, we need to consider the common information across two stereo images as well as the differences between two transmission channels. In this case, we propose a deep neural networks solution that includes lightweight edge encoders and a powerful center decoder. Besides, in the decoder, we propose a novel channel state information aware cross attention module to highlight the overlapping fields and leverage the relevance between two noisy feature maps. Our results show the impressive improvement of reconstruction quality in both links by exploiting the noisy representations of the other link. Moreover, the proposed scheme shows competitive results compared to the separated schemes with capacity-achieving channel codes. "

tags: [Source-Channel Coding, Semantic]
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
- name: ICASSP
  url: 

url_pdf: https://ieeexplore.ieee.org/abstract/document/9746268
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
