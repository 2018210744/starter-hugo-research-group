---

title: "Variational Speech Waveform Compression to Catalyze Semantic Communications"
authors: [ShengshiYao, ZixuanXiao, SixianWang, JinchengDai, KaiNiu]
date: 2022-12
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-12-01T16:24:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Wireless Communications and Networking Conference"
publication_short: "IEEE WCNC"

abstract: "We propose a novel neural waveform compression
method to catalyze emerging speech semantic communications.
By introducing nonlinear transform and variational modeling,
we effectively capture the dependencies within speech frames
and estimate the probabilistic distribution of the speech feature
more accurately, giving rise to better compression performance.
In particular, the speech signals are analyzed and synthesized by a
pair of nonlinear transforms, yielding latent features. An entropy
model with hyperprior is built to capture the probabilistic
distribution of latent features, followed with quantization and
entropy coding. The proposed waveform codec can be optimized
flexibly towards arbitrary rate, and the other appealing feature is
that it can be easily optimized for any differentiable loss function,
including perceptual loss used in semantic communications. To
further improve the fidelity, we incorporate residual coding to
mitigate the degradation arising from quantization distortion
at the latent space. Results indicate that achieving the same
performance, the proposed method saves up to 27% coding rates
than widely used adaptive multi-rate wideband (AMR-WB) codec
as well as emerging neural waveform coding methods."

tags: [Speech, semantic]
categories: [Semantic Comm]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
# url: https://twitter.com
# icon_pack: fab
# icon: twitter

links:
- name: IEEE WCNC
  url: 

url_pdf: https://arxiv.org/abs/2212.05294
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
