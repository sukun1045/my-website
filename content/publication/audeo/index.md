---
title: "Audeo: Audio Generation for a Silent Performance Video (NeurIPS 2020)"
authors:
- admin
- Xiulong Liu
- Eli Shlizerman
date: "2020-06-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS 2020*
publication_short: In *NeurIPS 2020*

abstract: We present a novel system that gets as an input video frames of a musician playing the piano and generates the music for that video. Generation of music from visual cues is a challenging problem and it is not clear whether it is an attainable goal at all. Our main aim in this work is to explore the plausibility of such a transformation and to identify cues and components able to carry the association of sounds with visual events. To achieve the transformation we built a full pipeline named ‘Audeo’ containing three components. We first translate the video frames of the keyboard and the musician hand movements into raw mechanical musical symbolic representation Piano-Roll (Roll) for each video frame which represents the keys pressed at each time step. We then adapt the Roll to be amenable for audio synthesis by including temporal correlations. This step turns out to be critical for meaningful audio generation. As a last step, we implement Midi synthesizers to generate realistic music. Audeo converts video to audio smoothly and clearly with only a few setup constraints. We evaluate Audeo on ‘in the wild’ piano performance videos and obtain that their generated music is of reasonable audio quality and can be successfully recognized with high precision by popular music identification software.

# Summary. An optional shortened abstract.
summary: A novel system that gets as an input video frames of a musician playing the piano and generates the music for that video.

tags:
- Audio-visual
featured: false

links:
- name: Project Page
  url: http://faculty.washington.edu/shlizee/audeo/
- name: Code
  url: https://github.com/shlizee/Audeo
url_pdf: https://arxiv.org/pdf/2006.14348.pdf
url_project: ''
url_video: 'https://www.youtube.com/watch?v=8rS3VgjG7_c'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Audeo Pipeline'
  focal_point: "Left"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

