---

title: "ResNet-Like Belief-Propagation Decoding for Polar Codes"
authors: [JianGao,DexinZhang,JinchengDai,KaiNiu,ChaoDong]
date: 2021-01
doi: "10.1109/LWC.2021.3050819"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-01-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Wireless Communications Letters"
publication_short: "IEEE LWC"

abstract: The polar neural decoder has a performance improvement at the cost of additional storage and computation. In this letter, we first propose a ResNet-like BP architecture to improve the standard polar BP decoding. Each iteration inherits a portion of information from the previous iteration as additional input and passes its output to the next iteration. Second, trainable damping factors, which can be learned through deep learning techniques, are applied to determine the inheritance ratio in the ResNet-like BP. We allocate the damping factors flexibly and demonstrate the optimization of a shared constant damping factor provides the same level of performance with the individual optimization of the damping factor at each state. Moreover, we qualitatively explain the performance gain by analyzing the mutual information between the input and output of the decoder. Numerical and simulation results indicate that the ResNet-like BP decoder can effectively improve the error correction performance and accelerate convergence compared with the standard polar BP algorithm.


tags: []
categories: [Polar Codes]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
# url: https://twitter.com
# icon_pack: fab
# icon: twitter

links:
- name: LWC
  url: 

url_pdf: https://ieeexplore.ieee.org/abstract/document/9319713
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
