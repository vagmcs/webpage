---
title: "Semi-Supervised Online Structure Learning for Composite Event Recognition"
slug: splice
draft: false

# Schedule page publish date (NOT publication's date).
date: "2019-01-09T00:00:00"
publishDate: "2019-01-09T00:00:00"

# Authors
# If you created a profile for a user (e.g. `vagmcs`), use the folder name instead, and should be replaced by their full name and linked to their profile.
authors:
- vagmcs
- A. Artikis
- G. Paliouras

# Digital Object Identifier (DOI)
doi: "10.1007/s10994-019-05794-2"

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated version.
publication: "In *Machine Learning*, 108(7), pp. 1085--1110"
publication_short: "In *Machine Learning*, 108(7), pp. 1085--1110"

# Abstract and optional shortened version.
abstract: Online structure learning approaches, such as those stemming from Statistical Relational Learning, enable the discovery of complex relations in noisy data streams. However, these methods assume the existence of fully-labelled training data, which is unrealistic for most real-world applications. We present a novel approach for completing the supervision of a semi-supervised structure learning task. We incorporate graph-cut minimisation, a technique that derives labels for unlabelled data, based on their distance to their labelled counterparts. In order to adapt graph-cut minimisation to first order logic, we employ a suitable structural distance for measuring the distance between sets of logical atoms. The labelling process is achieved online (single-pass) by means of a caching mechanism, and the Hoeffding bound, a statistical tool to approximate globally-optimal decisions from locally-optimal ones. We evaluate our approach on the task of composite event recognition by using a benchmark dataset for human activity recognition, as well asa real dataset for maritime monitoring. The evaluation suggests that our approach can effectively complete the missing labels and eventually, improve the accuracy of the underlying structure learning system.

# Summary. An optional shortened abstract.
# summary:

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["philosophy"]`.
tags: []

# Is this a selected publication? (true/false)
featured: true

# Links (optional).
url_pdf: ""
url_code: ""
url_dataset: "splice_evaluation-20180205-18_17_25.tar.gz"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

links:
- name: Appendix
  url: "appendix.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: ""
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication to one or more of your projects.
#   Simply enter your project's folder or file name.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - datacron

# Slides (optional).
#   Associate this publication to Markdown slides.
#   Simply enter your slide deck's filename.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
