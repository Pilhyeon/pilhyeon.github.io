---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Exploiting Transferable Knowledge for Fairness-aware Image Classification"
authors: ['Sunhee Hwang$^*$', 'Sungho Park$^*$', '**Pilhyeon Lee**$^*$', 'Seogkyu Jeon', 'Dohyung Kim', 'Hyeran Byun']
date: 2020-11-30T12:00:00+09:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-30T12:00:00+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*15th Asian Conference on Computer Vision* (**ACCV 2020**)"
publication_short: "*15th Asian Conference on Computer Vision* (**ACCV 2020**)"

abstract: "Recent studies have revealed the importance of fairness in machine learning and computer vision systems, in accordance with the concerns about the unintended social discrimination produced by the systems. In this work, we aim to tackle the fairness-aware image classification problem, whose goal is to classify a target attribute (eg, attractiveness) in a fair manner regarding protected attributes (eg, gender, age, race). To this end, existing methods mainly rely on protected attribute labels for training, which are costly and sometimes unavailable for real-world scenarios. To alleviate the restriction and enlarge the scalability of fair models, we introduce a new framework where a fair classification model can be trained on datasets without protected attribute labels (ie, target datasets) by exploiting knowledge from pre-built benchmarks (ie, source datasets). Specifically, when training a target attribute encoder, we encourage its representations to be independent of the features from the pre-trained encoder on a source dataset. Moreover, we design a Group-wise Fair loss to minimize the gap in error rates between different protected attribute groups. To the best of our knowledge, this work is the first attempt to train the fairness-aware image classification model on a target dataset without protected attribute annotations. To verify the effectiveness of our approach, we conduct experiments on CelebA and UTK datasets with two settings: the conventional and the transfer settings. In the both settings, our model shows the fairest results when compared to the existing methods."

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

url_pdf: https://openaccess.thecvf.com/content/ACCV2020/papers/Hwang_Exploiting_Transferable_Knowledge_for_Fairness-aware_Image_Classification_ACCV_2020_paper.pdf
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
