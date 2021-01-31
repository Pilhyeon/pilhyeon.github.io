---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Background Suppression Network for Weakly-supervised Temporal Action Localization"
authors: ['**Pilhyeon Lee**', 'Youngjung Uh', 'Hyeran Byun']
date: 2020-02-07T12:00:00+09:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-07T12:00:00+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*34th AAAI Conference on Artificial Intelligence* (**AAAI 2020**)"
publication_short: "*34th AAAI Conference on Artificial Intelligence* (**AAAI 2020**) (**Spotlight**) (**20.6%** acceptance rate)"

abstract: "Weakly-supervised temporal action localization is a very challenging problem because frame-wise labels are not given in the training stage while the only hint is video-level labels: whether each video contains action frames of interest. Previous methods aggregate frame-level class scores to produce video-level prediction and learn from video-level action labels. This formulation does not fully model the problem in that background frames are forced to be misclassified as action classes to predict video-level labels accurately. In this paper, we design Background Suppression Network (BaS-Net) which introduces an auxiliary class for background and has a two-branch weight-sharing architecture with an asymmetrical training strategy. This enables BaS-Net to suppress activations from background frames to improve localization performance. Extensive experiments demonstrate the effectiveness of BaS-Net and its superiority over the state-of-the-art methods on the most popular benchmarks - THUMOS'14 and ActivityNet. Our code and the trained model are available at [https://github.com/Pilhyeon/BaSNet-pytorch](https://github.com/Pilhyeon/BaSNet-pytorch)."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1911.09963.pdf
url_code: https://github.com/Pilhyeon/BaSNet-pytorch
url_dataset:
url_poster: https://pilhyeon.netlify.app/publication/2020_aaai_bas-net/poster.pdf
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
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
