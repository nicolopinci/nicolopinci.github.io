---
title: "Comparing CAM algorithms for the identification of salient image features in iconography artwork analysis"
authors:
- me
- Federico Milani
- Piero Fraternali
- Ricardo da Silva Torres
date: "2021-06-29"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-29"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Imaging, 7*(7)"
publication_short: ""

abstract: Iconography studies the visual content of artworks by considering the themes portrayed in them and their representation. Computer Vision has been used to identify iconographic subjects in paintings and Convolutional Neural Networks enabled the effective classification of characters in Christian art paintings. However, it still has to be demonstrated if the classification results obtained by CNNs rely on the same iconographic properties that human experts exploit when studying iconography and if the architecture of a classifier trained on whole artwork images can be exploited to support the much harder task of object detection. A suitable approach for exposing the process of classification by neural models relies on Class Activation Maps, which emphasize the areas of an image contributing the most to the classification. This work compares state-of-the-art algorithms (CAM, Grad-CAM, Grad-CAM++, and Smooth Grad-CAM++) in terms of their capacity of identifying the iconographic attributes that determine the classification of characters in Christian art paintings. Quantitative and qualitative analyses show that Grad-CAM, Grad-CAM++, and Smooth Grad-CAM++ have similar performances while CAM has lower efficacy. Smooth Grad-CAM++ isolates multiple disconnected image regions that identify small iconographic symbols well. Grad-CAM produces wider and more contiguous areas that cover large iconographic symbols better. The salient image areas computed by the CAM algorithms have been used to estimate object-level bounding boxes and a quantitative analysis shows that the boxes estimated with Grad-CAM reach 55% average IoU, 61% GT-known localization and 31% mAP. The obtained results are a step towards the computer-aided study of the variations of iconographic elements positioning and mutual relations in artworks and open the way to the automatic creation of bounding boxes for training detectors of iconographic symbols in Christian art images.

tags:
- Explainability
- Artificial Intelligence
featured: true

hugoblox:

links:
  - type: pdf
    url: https://www.mdpi.com/2313-433X/7/7/106/pdf?version=1625139253

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


