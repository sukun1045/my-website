---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Predict & Cluster: Unsupervised Skeleton Based Action Recognition"
authors:
- admin
- Xiulong Liu
- Eli Shlizerman
date: 2019-11-27T17:38:04-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-27T17:38:04-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "CVPR"
publication_short: "CVPR"

abstract: "We propose a novel system for unsupervised skeleton-based action recognition. Given inputs of body keypoints sequences obtained during various movements, our system associates the sequences with actions. Our system is based on an encoder-decoder recurrent neural network, where the encoder learns a separable feature representation within its hidden states formed by training the model to perform prediction task. We show that according to such unsupervised training the decoder and the encoder self-organize their hidden states into a feature space which clusters similar movements into the same cluster and distinct movements into distant clusters. Current state-of-the-art methods for action recognition are strongly supervised, i.e., rely on providing labels for training. Unsupervised methods have been proposed, however, they require camera and depth inputs (RGB+D) at each time step. In contrast, our system is fully unsupervised, does not require labels of actions at any stage, and can operate with body keypoints input only. Furthermore, the method can perform on various dimensions of body keypoints (2D or 3D) and include additional cues describing movements. We evaluate our system on three extensive action recognition benchmarks with different number of actions and examples. Our results outperform prior unsupervised skeleton-based methods, unsupervised RGB+D based methods on cross-view tests and while being unsupervised have similar performance to supervised skeleton-based action recognition."

# Summary. An optional shortened abstract.
summary: "We propose a novel system for unsupervised skeleton-based action recognition."

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

url_pdf: 'https://arxiv.org/pdf/1911.12409.pdf'
url_code: 'https://github.com/shlizee/Predict-Cluster'
url_video: 'https://www.youtube.com/watch?v=-dcCFUBRmwE'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "teaser"
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
