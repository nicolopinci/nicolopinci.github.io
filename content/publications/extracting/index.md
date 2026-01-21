---
title: 'Extracting latent representations from X-ray spectra. Classification, regression, and accretion signatures of Chandra sources'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Juan Rafael Martinez-Galarza
  - Roberta Amato

date: '2025-10-15'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-15'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Proceedings of Science - ICRC

abstract: The study of X-ray spectra is crucial to understanding the physical nature of astrophysical sources. Machine learning methods can extract compact and informative representations of data from large datasets. The Chandra Source Catalog (CSC) provides a rich archive of X-ray spectral data, which remains largely underexplored in this context. This work aims to develop a compact and physically meaningful representation of Chandra X-ray spectra using deep learning. To verify that the learned representation captures relevant information, we evaluate it through classification, regression, and interpretability analyses. We use a transformer-based autoencoder to compress X-ray spectra. The input spectra, drawn from the CSC, include only high-significance detections. Astrophysical source types and physical summary statistics are compiled from external catalogs. We evaluate the learned representation in terms of spectral reconstruction accuracy, clustering performance on 8 known astrophysical source classes, and correlation with physical quantities such as hardness ratios and hydrogen column density ($N_H$). The autoencoder accurately reconstructs spectra with 8 latent variables. Clustering in the latent space yields a balanced classification accuracy of ca. 40% across the 8 source classes, increasing to ca. 69% when restricted to AGNs and stellar-mass compact objects exclusively. Moreover, latent features correlate with non-linear combinations of spectral fluxes, suggesting that the compressed representation encodes physically relevant information. The proposed autoencoder-based pipeline is a powerful tool for the representation and interpretation of X-ray spectra, providing a compact latent space that supports both classification and the estimation of physical properties. This work demonstrates the potential of deep learning for spectral studies and uncovering new patterns in X-ray data.


tags:
  - Artificial Intelligence
  - Astrophysics
  - Representation learning

# Display this page in the Featured widget?
featured: false


# Custom links
links:
  - type: pdf
    url: https://doi.org/10.48550/arXiv.2510.14102

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: ''
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
