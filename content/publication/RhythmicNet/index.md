---
title: "How Does it Sound? Generation of Rhythmic Soundtracks for Human Movement Videos (NeurIPS 2021)"
authors:
- admin
- Xiulong Liu
- Eli Shlizerman
date: "2021-06-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS 2021*
publication_short: In *NeurIPS 2021*

abstract: One of the primary purposes of video is to capture people and their unique activities. It is often the case that the experience of watching the video can be enhanced by adding a musical soundtrack that is in-sync with the rhythmic features of these activities. How would this soundtrack sound? Such a problem is challenging since little is known about capturing the rhythmic nature of free body movements. In this work, we explore this problem and propose a novel system, called _**‘RhythmicNet’**_, which takes as an input a video with human movements and generates a soundtrack for it. RhythmicNet works directly with human movements, by extracting skeleton keypoints and implementing a sequence of models translating them to rhythmic sounds. RhythmicNet follows the natural process of music improvisation which includes the prescription of streams of the beat, the rhythm and the melody. In particular, RhythmicNet first infers the music beat and the style pattern from body keypoints per each frame to produce the rhythm. Next, it implements a transformerbased model to generate the hits of drum instruments and implements a U-net based model to generate the velocity and the offsets of the instruments. Additional types of instruments are added to the soundtrack by further conditioning on generated drum sounds. We evaluate RhythmicNet on large scale video datasets that include body movements with inherit sound association, such as dance, as well as ’in the wild’ internet videos of various movements and actions. We show that the method can generate plausible music that aligns with different types of human movements.

# Summary. An optional shortened abstract.
summary: A novel system that gets as an input video frames of a human motion and generates the soundtrack for that video.

tags:
- Audio-visual
featured: false

links:
- name: Project Page
  url: https://github.com/shlizee/RhythmicNet
- name: Code
  url: https://github.com/shlizee/RhythmicNet
url_pdf: https://proceedings.neurips.cc/paper/2021/file/f4e369c0a468d3aeeda0593ba90b5e55-Paper.pdf
url_project: ''
url_video: https://github.com/shlizee/RhythmicNet

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'RythimicNet Teaser'
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


