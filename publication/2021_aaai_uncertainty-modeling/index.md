---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Weakly-supervised Temporal Action Localization by Uncertainty Modeling"
authors: ['**Pilhyeon Lee**', 'Jinglu Wang', 'Yan Lu', 'Hyeran Byun']
date: 2021-02-02T12:00:00+09:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-02T12:00:00+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "35th AAAI Conference on Artificial Intelligence (**AAAI 2021**)"
publication_short: "*35th AAAI Conference on Artificial Intelligence* (**AAAI 2021**) (**Oral**) (**21%** acceptance rate)"

abstract: "Weakly-supervised temporal action localization aims to learn detecting temporal intervals of action classes with only video-level labels. To this end, it is crucial to separate frames of action classes from the background frames (i.e., frames not belonging to any action classes). In this paper, we present a new perspective on background frames where they are modeled as out-of-distribution samples regarding their inconsistency. Then, background frames can be detected by estimating the probability of each frame being out-of-distribution, known as uncertainty, but it is infeasible to directly learn uncertainty without frame-level labels. To realize the uncertainty learning in the weakly-supervised setting, we leverage the multiple instance learning formulation. Moreover, we further introduce a background entropy loss to better discriminate background frames by encouraging their in-distribution (action) probabilities to be uniformly distributed over all action classes. Experimental results show that our uncertainty modeling is effective at alleviating the interference of background frames and brings a large performance gain without bells and whistles. We demonstrate that our model significantly outperforms state-of-the-art methods on the benchmarks, THUMOS'14 and ActivityNet (1.2 & 1.3). Our code is available at https://github.com/Pilhyeon/WTAL-Uncertainty-Modeling."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2006.07006.pdf
url_code: https://github.com/Pilhyeon/WTAL-Uncertainty-Modeling
url_dataset:
url_poster: https://pilhyeon.netlify.app/publication/2021_aaai_uncertainty-modeling/poster.pdf
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "smart"
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
