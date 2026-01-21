---
title: "Anomaly detection in quasi-periodic energy consumption data series: a comparison of algorithms"
authors:
- Niccolò Zangrando
- Piero Fraternali
- Marco Petri
- me
- Sergio Luis Herrera González
date: "2022-12-01"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-01"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Energy Informatics*"
publication_short: ""

abstract: The diffusion of domotics solutions and of smart appliances and meters enables the monitoring of energy consumption at a very fine level and the development of forecasting and diagnostic applications. Anomaly detection (AD) in energy consumption data streams helps identify data points or intervals in which the behavior of an appliance deviates from normality and may prevent energy losses and break downs. Many statistical and learning approaches have been applied to the task, but the need remains of comparing their performances with data sets of different characteristics. This paper focuses on anomaly detection on quasi-periodic energy consumption data series and contrasts 12 statistical and machine learning algorithms tested in 144 different configurations on 3 data sets containing the power consumption signals of fridges. The assessment also evaluates the impact of the length of the series used for training and of the size of the sliding window employed to detect the anomalies. The generalization ability of the top five methods is also evaluated by applying them to an appliance different from that used for training. The results show that classical machine learning methods (Isolation Forest, One-Class SVM and Local Outlier Factor) outperform the best neural methods (GRU/LSTM autoencoder and multistep methods) and generalize better when applied to detect the anomalies of an appliance different from the one used for training.

tags:
- Industrial informatics
- Artificial Intelligence
featured: false

hugoblox:

links:
  - type: pdf
    url: https://link.springer.com/content/pdf/10.1186/s42162-022-00230-7.pdf

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
projects: ["PRECEPT"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


