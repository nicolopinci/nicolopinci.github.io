---
title: "Proposals Generation for Weakly Supervised Object Detection in Artwork Images"
authors:
- Federico Milani
- me
- Piero Fraternali
date: "2022-08-06"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-06"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Imaging, 8*(8)"
publication_short: ""

abstract: Object Detection requires many precise annotations, which are available for natural images but not for many non-natural data sets such as artworks data sets. A solution is using Weakly Supervised Object Detection (WSOD) techniques that learn accurate object localization from image-level labels. Studies have demonstrated that state-of-the-art end-to-end architectures may not be suitable for domains in which images or classes sensibly differ from those used to pre-train networks. This paper presents a novel two-stage Weakly Supervised Object Detection approach for obtaining accurate bounding boxes on non-natural data sets. The proposed method exploits existing classification knowledge to generate pseudo-ground truth bounding boxes from Class Activation Maps (CAMs). The automatically generated annotations are used to train a robust Faster R-CNN object detector. Quantitative and qualitative analysis shows that bounding boxes generated from CAMs can compensate for the lack of manually annotated ground truth (GT) and that an object detector, trained with such pseudo-GT, surpasses end-to-end WSOD state-of-the-art methods on ArtDL 2.0 (≈41.5% mAP) and IconArt (≈17% mAP), two artworks data sets. The proposed solution is a step towards the computer-aided study of non-natural images and opens the way to more advanced tasks, e.g., automatic artwork image captioning for digital archive applications.

tags:
- Explainability
- Artificial Intelligence
- Art
featured: true

hugoblox:

links:
  - type: pdf
    url: https://www.mdpi.com/2313-433X/8/8/215/pdf?version=1661252350

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
projects: ["ArtDL"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


