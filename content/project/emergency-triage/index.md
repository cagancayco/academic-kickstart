---
title: Automated Emergency Triage
summary: Using TensorFlow to determine triage level in the emergency department
tags:
- Machine Learning
- MATLAB
- Python
- R

date: "2019-07-24T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

# links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

**Principal Investigator: Dr. Thomas Hartka, UVa Dept. of Emergency Medicine**

Before patients are admitted to the emergency room, they are assigned a triage level based on the severity of their health problems. This is accomplished using the Emergency Severity Index (ESI), an emergency department triage algorithm that classifies patient cases into five different levels of urgency. Researchers are interested in using machine learning to develop a model to predict patient triage level. This model would not only analyze the typical vital signs that are used in the ESI, but also demographic data and patients’ history of health.

My main contributions to this project are:

* **Cleansing the data in R** using the dplyr and mice packages

* **Developing preliminary neural networks with Python and TensorFlow** to predict patient triage level

* **Generating word clouds in MATLAB** for symptoms at each triage level

<br></br>

Code written by me for this project can be found on [Github](https://github.com/cagancayco/ed-triage).
