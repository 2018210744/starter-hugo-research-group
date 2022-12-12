---

title: "Joint Successive Cancellation List Decoding for the Double Polar Codes"
authors: [YanfeiDong,KaiNiu,JinchengDai,SenWang,YifeiYuan]
date: 2022-06
doi: "10.1109/LCOMM.2022.3179644"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Communications Letters"
publication_short: "IEEE LCOMM"

abstract: As a new joint source-channel coding scheme, the double polar (D-Polar) codes have been proposed recently. In this letter, a novel joint source-channel decoder, namely the joint successive cancellation list (J-SCL) decoder, is proposed to improve the decoding performance of the D-Polar codes. We merge the trellis of the source polar code and that of the channel polar code to construct a compound trellis. In this compound trellis, the variable nodes corresponding to the information bits of the channel polar code and the variable nodes representing the highentropy bits are merged into the joint source-channel (JSC) nodes. Based on the compound trellis, the J-SCL decoder is designed to recover the source messages by combining the source SCL decoding and channel SCL decoding. The proposed J-SCL decoder doubles the number of the decoding paths for each JSC node and low-entropy node, and then discard all but the L paths with the smallest joint path-metric (JPM). For the JSC node, the JPM is updated considering both the channel decision log-likelihood ratios (LLRs) and the source decision LLRs. Simulation results show that the J-SCL decoder outperforms the turbo-like BP (TL-BP) decoder with lower complexity.


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
- name: LCOMM
  url: 

url_pdf: https://ieeexplore.ieee.org/abstract/document/9785999
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
