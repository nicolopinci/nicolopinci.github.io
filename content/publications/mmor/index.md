---
title: "Multimodal multi-output ordinal regression for discovering gravitationally-lensed transients"
authors:
- me
- Piero Fraternali
date: "2025-06-20"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-20"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Machine Learning: Science and Technology*"
publication_short: ""

abstract: > Gravitational lenses are caused by massive astronomical objects that distort space-time, bending light. They can distort transient astrophysical events, such as supernovae (SN), which are the subject of extensive study. However, gravitationally-lensed supernovae are rare, with only a few detected so far. Future astronomical surveys will collect huge amounts of data, calling for automated and accurate discovery techniques to find them. Still, only a few works aim to discover gravitationally-lensed supernovae, most use only a few classes to characterize candidate observations, and only a few exploit spatial and temporal information. This work introduces Hydra, a novel pipeline designed to process spatio-temporal data for identifying and counting astronomical objects, including gravitational lenses and transients. Hydra performs two tasks: (i) counting the occurrences of 7 types of astronomical objects within each observation and (ii) classifying candidate events and objects (e.g. gravitational lenses and transient events). Across four datasets, Hydra achieves an average macro F1 score higher than 79% for the counting task and macro F1 scores ranging from ca. 59% to ca. 94% for classification. These results demonstrate its potential for improving automated discovery in future astronomical surveys and for counting objects in multimodal data.

tags:
- Astrophysics
- Artificial Intelligence
- Gravitational lenses
featured: true

hugoblox:

links:
  - type: pdf
    url: https://iopscience.iop.org/article/10.1088/2632-2153/ade360/pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
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


