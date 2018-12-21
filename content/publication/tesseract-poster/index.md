+++
title = "POSTER: Enabling Fair ML Evaluations for Security"
date = 2018-10-20T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["*Feargus Pendlebury*", "*Fabio Pierazzi*", "Roberto Jordaney", "Johannes Kinder", "Lorenzo Cavallaro"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "*ACM CCS*"
publication_short = ""

# Abstract and optional shortened version.
abstract = """
Academic research on machine learning-based malware classification appears to leave very little room for improvement, boasting F1 performance figures of up to 0.99. Is the problem solved? In this paper, we argue that there is an endemic issue of inflated results due to two pervasive sources of experimental bias: spatial bias is caused by distributions of training and testing data not representative of a real-world deployment; temporal bias is caused by incorrect splits of training and testing sets (e.g., in cross-validation) leading to impossible configurations. To overcome this issue, we propose a set of space and time constraints for experiment design. Furthermore, we introduce a new metric that summarizes the performance of a classifier over time, i.e., its expected robustness in a real-world setting. Finally, we present an algorithm to tune the performance of a given classifier. We have implemented our solutions in TESSERACT, an open source evaluation framework that allows a fair comparison of malware classifiers in a realistic setting. We used TESSERACT to evaluate two well-known malware classifiers from the literature on a dataset of 129K applications, demonstrating the distortion of results due to experimental bias and showcasing significant improvements from tuning.
"""
abstract_short = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["tesseract"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1807.07838"
url_code = ""
url_dataset = ""
url_project = "https://s2lab.kcl.ac.uk/projects/tesseract/"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

<!-- More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code. -->
