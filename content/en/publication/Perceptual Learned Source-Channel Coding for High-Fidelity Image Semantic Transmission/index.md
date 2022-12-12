---

title: "Perceptual Learned Source-Channel Coding for High-Fidelity Image Semantic Transmission"
authors: [JunWang, SixianWang, JinchengDai, ZhongweiSi, DekunZhou, KaiNiu]
date: 2022-11
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Global Communications Conference"
publication_short: "IEEE GLOBECOM"

abstract: As one novel approach to realize end-to-end wireless image semantic transmission, deep learning-based joint source-channel coding (deep JSCC) method is emerging in both deep learning and communication communities. However, current deep JSCC image transmission systems are typically optimized for traditional distortion metrics such as peak signal-to-noise ratio (PSNR) or multi-scale structural similarity (MS-SSIM). But for low transmission rates, due to the imperfect wireless channel, these distortion metrics lose significance as they favor pixel-wise preservation. To account for human visual perception in semantic communications, it is of great importance to develop new deep JSCC systems optimized beyond traditional PSNR and MS-SSIM metrics. In this paper, we introduce adversarial losses to optimize deep JSCC, which tends to preserve global semantic information and local texture. Our new deep JSCC architecture combines encoder, wireless channel, decoder/generator, and discriminator, which are jointly learned under both perceptual and adversarial losses. Our method yields human visually much more pleasing results than state-of-the-art engineered image coded transmission systems and traditional deep JSCC systems. A user study confirms that achieving the perceptually similar end-to-end image transmission quality, the proposed method can save about 50\% wireless channel bandwidth cost. 

tags: [Semantic, Source-Channel Coding, Image]
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
- name: GLOBECOM
  url: 

url_pdf: https://arxiv.org/abs/2205.13120
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
