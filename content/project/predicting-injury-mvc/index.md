---
title: Predicting Injury Severity in Older Adults
summary: Determining accuracy of predicting injury in older adults after a motor vehicle collision
tags:
- R
date: "2019-07-24T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

**Principal Investigator: Dr. Thomas Hartka, UVa Dept. of Emergency Medicine**

Previous research has shown that older adults are more susceptible to severe injury than their younger counterparts after being involved in a motor vehicle collision. Dr. Hartka was interested in determining whether there are age-related differences in the accuracy of severe injury prediction following a motor vehicle collision. Using R, I developed age-specific logistic regression models and assessed their accuracy, and generated unique graphs and animations to visualize the data more effectively.


Code I wrote for this project can be found on [Github](https://github.com/cagancayco/MVC).

<style>
.column {
  float: left;
  width: 50%;
  height: 50%;
  padding: 20px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>

<div class="row">
  <div class="column">
    <img src="/files/mvc-riskcurve-beltuse.gif" style="width:100%"></img>
  </div>
  
  <div class="column">
    <img src="/files/mvc-riskcurve-pdof.gif" style="width:100%"></img>
  </div>
</div>

