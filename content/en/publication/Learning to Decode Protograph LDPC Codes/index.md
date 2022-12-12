---

title: "Learning to Decode Protograph LDPC Codes"
authors: [JinchengDai,KailinTan,ZhongweiSi,KaiNiu,MingzheChen,H. VincentPoor,ShuguangCui]
date: 2021-02
doi: "10.1109/JSAC.2021.3078488"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Journal on Selected Areas in Communications"
publication_short: "IEEE JSAC"

abstract: The recent development of deep learning methods provides a new approach to optimize the belief propagation (BP) decoding of linear codes. However, the limitation of existing works is that the scale of neural networks increases rapidly with the codelength, thus they can only support short to moderate codelengths. From the point view of practicality, we propose a high-performance neural min-sum (MS) decoding method that makes full use of the lifting structure of protograph low-density parity-check (LDPC) codes. By this means, the size of the parameter array of each layer in the neural decoder only equals the number of edge-types for arbitrary codelengths. In particular, for protograph LDPC codes, the proposed neural MS decoder is constructed in a special way such that identical parameters are shared by a bundle of edges derived from the same edgetype. To reduce the complexity and overcome the vanishing gradient problem in training the proposed neural MS decoder, an iteration-by-iteration (i.e., layer-by-layer in neural networks) greedy training method is proposed. With this, the proposed neural MS decoder tends to be optimized with faster convergence, which is aligned with the early termination mechanism widely used in practice. To further enhance the generalization ability of the proposed neural MS decoder, a codelength/rate compatible training method is proposed, which randomly selects samples from a set of codes lifted from the same base code. As a theoretical performance evaluation tool, a trajectory-based extrinsic information transfer (T-EXIT) chart is developed for various decoders.


tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
# url: https://twitter.com
# icon_pack: fab
# icon: twitter

links:
- name: JSAC
  url: 

url_pdf: https://ieeexplore.ieee.org/abstract/document/9427170
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
