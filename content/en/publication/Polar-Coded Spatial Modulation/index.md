---

title: "Polar-Coded Spatial Modulation"
authors: [JinchengDai,KaiNiu,ZhongweiSi,DexinZhang]
date: 2021-03
doi: "10.1109/TSP.2021.3068848"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Signal Processing"
publication_short: "IEEE TSP"

abstract: In this paper, we propose a framework to attain the integrated design of polar coding and spatial modulation (SM) such that the performance of coded SM-MIMO system can be efficiently improved. This Polar-SM framework recognizes SM and polar coding from a unified perspective of polarization by which the original SM-MIMO channel is split into a series of bit polarized subchannels under the three-stage channel transform, i.e., index-symbol→modulation→bit partitions. This paradigm exploits the underlying weak polarization effect within the SM signal, then concatenates with the binary polarization in polar coding, forming a signal-coding cascaded polarization framework. In particular, the first stage channel transform serially decomposes the original SM-MIMO channel into the index subchannel and the symbol subchannel. This mechanism follows the chain rule of mutual information, which preserves the capacity and maximizes the polarization effect. Combining with modulation and bit partitions, we prove the capacity-achieving property of Polar-SM. From the point of practicality, we propose a rate-filling method to realize a fast and low-complexity code construction of Polar-SM. Guided by the three-stage channel transform, we design a glued successive cancellation list (gSCL) decoding algorithm at the receiver to integrate SM detection and polar decoding as a collaborative ensemble. Simulation results validate the performance gain of Polar-SM over state-of-the-art polar-coded MIMO systems and LDPC-coded SM systems.


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
- name: TSP
  url: 

url_pdf: https://ieeexplore.ieee.org/abstract/document/9387135
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
