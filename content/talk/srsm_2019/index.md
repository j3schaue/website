---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Challenges for imputing missing covariates in meta-regression"
event: "Society for Research Synthesis Methods"
event_url: http://www.srsm.org/2019-meeting-schedule.html
location: Chicago, IL
summary:
abstract: "A common issue in meta-regression is that for some effects, certain covariates may not be collected or reported. Precisely how to handle this issue depends on the reason that covariates are missing from the data. If they are missing at random, one potential solution is multiple imputation (MI), where several different plausible values are imputed for the covariates that are missing. While MI methods and software have found wide use in other fields, methodological work suggests that great care should be taken with how imputations are generated, since generating imputations based on inaccurate or inappropriate models can lead to inaccurate inferences. This presents something of a problem for meta-regression, since the type of data and resulting models encountered in meta-regression is somewhat unique. For example, much of the existing MI theory and software focuses on basic linear regression models, however the variance structure in a meta-regression is considerably more complex than those models. Thus, it stands to reason that the models for generating imputations in a meta-regression would differ from those in a standard linear regression. Unfortunately, there is scant literature on the proper way to do generate imputations for a meta-regression, and few (if any) software offer any implementation or guidance. In this paper, I highlight how the factors that can affect imputation accuracy for meta-regression, and show that ignoring those factors can lead to inaccurate estimation of meta-regression models. I then discuss potential corrections using iterative conditional specifications of the imputation models."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-07-22T13:40:37-05:00
# date_end: 2019-07-22T13:40:37-05:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2019-08-30T13:40:37-05:00

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

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

# Optional filename of your slides within your talk's folder or a URL.
url_slides: srsm2019_schauer.pdf

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ['meta-analysis-missing-data']
---
