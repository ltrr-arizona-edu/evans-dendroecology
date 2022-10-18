---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Population Modeling"
summary: ""
authors: []
tags: []
categories: []
weight: 11
date: 2022-09-22T11:01:39-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Population Viability Analysis has been called the "flagship technology" of conservation biology (by Michael Soule). Kent Holsinger, Eric Menges, and I collaborated together for some years to develop a novel approach to population viability analysis (PVA): we built a hierarchical Bayesian (hB) model that draws upon data from all parts of the life cycle simultaneously to estimate vital rates and their covariation as a function of time-since-fire and random year effects. A unique feature of this model is a year effect that connects five submodels (generalized linear mixed models) into a single large model (with ~1,340 parameters). This work was published in a series of papers in Population Ecology, Ecological Monographs, and Theoretical Population Biology, and is featured as a case study in Mike Dietze's book "Ecological Forecasting" (see its Ch. 7). Its descendants include my current work aimed at creating demography-based species distribution models, and the use of a Bayesian models to fuse together tree-ring and forest inventory data to analyze forest carbon dynamics.