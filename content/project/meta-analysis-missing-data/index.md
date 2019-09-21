---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Missing Data in Meta-Analysis"
summary: ""
authors: []
tags: []
categories: []
date: 2019-09-19T14:30:42-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 
  focal_point: Smart
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

Meta-regression is an important tool that can help highlight where and why an intervention may work.
However, anyone who has tried to fit these models has encountered studies that do not report relevant information, which means that data are often missing.
While missing data is a well-studied statistical problem, recent research has found that blindly applying methods used in other contexts---like multiple imputation---can induce bias in meta-regression models.
Thus, this project develops methods to handle missing data in meta-analyses.
