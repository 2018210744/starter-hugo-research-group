---

title: "Block Polarization HARQ for Polar-Coded Modulation"
authors: [WeiWang, JinchengDai, KaiNiu]
date: 2022-10
doi: "10.1109/TCOMM.2022.3216040"

# Schedule page publish date (NOT publication's date).
publishDate: 20222-10-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Communications"
publication_short: "IEEE TCOMM"

abstract: In this paper, we propose a block polarization (BP)scheme as a framework to study polar-coded hybrid automatic repeat request (Polar-HARQ) under bit-interleaved polar-coded modulation (BIPCM). The BP scheme of BIPCM can combine multiple independent polar subcodes to form a longer polar code under the block polarization between polar subcodes. The BP scheme of HARQ further carries out block polarization based on the BP scheme of BIPCM, which can combine multiple transmitted BP schemes of BIPCM together to form a longer polar code. When the underlying channels are non-uniform, such as the polarization effect of high-order modulation will lead to nonuniform reliabilities, it is not suitable to use the fixed sequence (e.g., the polarization weight (PW) sequence or Polar sequence in the 5G standard) to construct polar codes. The underlying channels on each polar subcode have uniform reliability by dividing different blocks according to the reliabilities of the underlying channel. Based on this characteristic of BP scheme, we propose a rate-allocation (RA) method to study fast code construction of BP scheme. The key idea of the proposed RA method is finding out the equivalent channel whose average symmetric capacity equals the target transmission rate. The allocated rates are computed according to the symmetric capacities of split channels under the block polarization between polar subcodes. Then the ranking of bit indices within each polar subcode can be obtained by fixed sequence. In this way, the RA code construction is concise and robust for diverse configurations which are the desired features for practical implementation. Simulation results show that the proposed BP scheme under RA construction can achieve almost identical performance as the Gaussian approximation construction with much lower complexity.


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
- name: TCOM
  url: 

url_pdf: https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=26
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
