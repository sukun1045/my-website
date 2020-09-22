---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Clustering and Recognition of Spatiotemporal Features through Interpretable Embedding of Sequence to Sequence Recurrent Neural Networks"
authors:
- admin
- Eli Shlizerman
date: 2019-05-29T18:00:34-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-05-29T18:00:34-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers AI"
publication_short: "Frontiers AI"

abstract: "Encoder-decoder recurrent neural network models (RNN Seq2Seq) have achieved great success in ubiquitous areas of computation and applications. It was shown to be successful in modeling data with both temporal and spatial dependencies for translation or prediction tasks. In this study, we propose an embedding approach to visualize and interpret the representation of data by these models. Furthermore, we show that the embedding is an effective method for unsupervised learning and can be utilized to estimate the optimality of model training. In particular, we demonstrate that embedding space projections of the decoder states of RNN Seq2Seq model trained on sequences prediction are organized in clusters capturing similarities and differences in the dynamics of these sequences. Such performance corresponds to an unsupervised clustering of any spatio-temporal features and can be employed for time-dependent problems such as temporal segmentation, clustering of dynamic activity, selfsupervised classification, action recognition, failure prediction, etc. We test and demonstrate the application of the embedding methodology to time-sequences of 3D human body poses. We show that the methodology provides a high-quality unsupervised categorization of movements."

# Summary. An optional shortened abstract.
summary: "interpretable embedding for RNN Seq2Seq"

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

url_pdf: https://arxiv.org/pdf/1905.12176.pdf
url_code: https://github.com/shlizee/interpretseq2seq

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
