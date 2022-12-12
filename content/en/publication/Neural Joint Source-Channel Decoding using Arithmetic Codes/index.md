---

title: "Neural Joint Source-Channel Decoding using Arithmetic Codes"
authors: [ZijianLiang,KaiNiu,JinchengDai]
date: 2021-12
doi: "10.1109/GCWkshps52748.2021.9682040"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-12-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Globecom Workshops"
publication_short: "IEEE GCWkshps"

abstract: Traditional iterative joint source-channel coding (JSCD) scheme based on soft-in-soft-out (SISO) decoding for arithmetic codes (AC) has a very high implementation complexity, which will cause an unbearable decoding latency due to a plenty of AC decoding steps and cross-layer interactions between physical layer and application layer. To tackle this, we propose a learning-based joint source-channel decoding approach, neural-JSCD, which consists of a series of AC SISO decoders and channel SISO decoders. The proposed approach introduces weights and offset factors to the simplified AC SISO decoders and damping factors to the output extrinsic information of both AC and channel SISO decoders, cooperated with trainable low-density parity-check (LDPC) neural decoders to realize the iterative decoding for AC. Through a greedy training method based on gradient descent, the learnable factors of neural-JSCD can be tuned to learn the a priori information of arithmetic codes, thus avoiding the great number of AC decoding steps together with cross-layer interactions during the iterative decoding process and rapidly reducing the implementation complexity of iterative AC decoding. Simulation results show that with a better decoding performance, neural-JSCD can reduce the number of iterations by at least 50% with no AC decoding steps and cross-layer interactions compared to traditional JSCD, in consequence, it greatly reduces the decoding latency of iterative decoding.


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
- name: GLOBECOM
  url:

url_pdf: https://ieeexplore.ieee.org/abstract/document/9682040
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
