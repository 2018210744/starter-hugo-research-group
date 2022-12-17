---

title: "Semantic Coding for Text Transmission: An Iterative Design"
authors: [ShengshiYao, KaiNiu, SixianWang, JinchengDai]
date: 2022-07
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Cognitive Communications and Networking"
publication_short: "IEEE TCCN"

abstract: "We consider the wireless text transmission using joint source-channel coding (JSCC). Classical source coding only considers the syntactic information based on probabilistic models, ignoring the meaning of source messages. Neural network based joint source and channel coders handle the source semantic information more efficiently. However, existing semantic transmission using end-to-end neural networks do not generalize well under varying channel conditions. To tackle this, we propose a semi-neural framework with an iterative architecture, named iterative semantic JSCC (IS-JSCC). Specifically, at each iteration, the remaining semantics is extracted from the intermediate decoded text and is then used as a priori information for the channel decoder in the next iteration. Instead of reconstructing text explicitly, we synthesize the semantics of candidate words in the embedding space, weighted by their posterior probability. This soft semantic synthesis alleviates the error propagation and reduces the complexity of iterative decoding as well. Results show that compared to full-neural designs, the proposed framework can improve the quality of text reconstruction by joint iterative decoding and exhibit better robustness over wireless channels. "

tags: [Text, Semantic]
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
- name: TCCN
  url:

url_pdf: https://ieeexplore.ieee.org/abstract/document/9834044
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
