---
title: "Predicting Machine Failures from Multivariate Time Series: An Industrial Case Study"
authors:
- me
- Francesca Forbicini
- Piero Fraternali
date: "2024-05-22"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-22"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Machines, 12*(6)"
publication_short: ""

abstract: Non-neural machine learning (ML) and deep learning (DL) are used to predict system failures in industrial maintenance. However, only a few studies have assessed the effect of varying the amount of past data used to make a prediction and the extension in the future of the forecast. This study evaluates the impact of the size of the reading window and of the prediction window on the performances of models trained to forecast failures in three datasets of (1) an industrial wrapping machine working in discrete sessions, (2) an industrial blood refrigerator working continuously, and (3) a nitrogen generator working continuously. A binary classification task assigns the positive label to the prediction window based on the probability of a failure to occur in such an interval. Six algorithms (logistic regression, random forest, support vector machine, LSTM, ConvLSTM, and Transformers) are compared on multivariate time series. The dimension of the prediction windows plays a crucial role and the results highlight the effectiveness of DL approaches in classifying data with diverse time-dependent patterns preceding a failure and the effectiveness of ML approaches in classifying similar and repetitive patterns preceding a failure.

tags:
- Industrial informatics
- Artificial Intelligence
featured: false

hugoblox:

links:
  - type: pdf
    url: https://www.mdpi.com/2075-1702/12/6/357/pdf?version=1716369577

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Source: https://unsplash.com/it/foto/fotografia-ravvicinata-di-ingranaggi-in-metallo-nero-hsPFuudRg5I"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["PRECEPT"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


