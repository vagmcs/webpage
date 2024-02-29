---
title: "A Framework to Evaluate Early Time-Series Classification Algorithms"
draft: false

# Schedule page publish date (NOT publication's date).
date: "2024-02-05T00:00:00"
publishDate: "2024-02-05T00:00:00"

# Authors
# If you created a profile for a user (e.g. `vagmcs`), use the folder name instead, and should be replaced by their full name and linked to their profile.
authors:
- C. Akasiadis
- E. Kladis
- P.F. Kamberi
- short_vagmcs
- E. Alevizos
- A. Artikis

# Digital Object Identifier (DOI)
doi: ""

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
publication_types: ["1"]

# Publication name and optional abbreviated version.
publication: "In *Proceedings of the 27th International Conference on Extending Database Technology*, OpenProceedings"
publication_short: "In *EDBT*, OpenProceedings"

# Abstract and optional shortened version.
abstract: Early Time-Series Classification (ETSC) is the task of predicting the class of incoming time-series by observing as few measurements as possible. Such methods can be employed to obtain classification forecasts in many time-critical applications. However, available techniques are not equally suitable for every problem, since differentiations in the data characteristics can impact performance in terms of earliness, accuracy, F1-score, or training time. We evaluate five existing ETSC algorithms on publicly available data, as well as on two newly introduced datasets originating from the life sciences and maritime domains. Existing ETSC algorithms are also compared against a method that selectively truncates time-series and incorporates state-of-the-art algorithms for full time-series classification. Our main goal is to provide a framework for the evaluation and comparison of ETSC algorithms and to obtain intuition on how such approaches perform on real-life applications. The presented framework can serve as a benchmark for new related approaches.

# Summary. An optional shortened abstract.
# summary:

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["philosophy"]`.
tags: ["early classification", "time-series"]

# Is this a selected publication? (true/false)
featured: true

# Links (optional).
url_pdf: ""
url_code: "https://github.com/Eukla/ETS"
url_dataset: "https://users.iit.demokritos.gr/~vagmcs/datasets/datasets.zip"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

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
  - infore

# Slides (optional).
#   Associate this publication to Markdown slides.
#   Simply enter your slide deck's filename.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

The life-sciences and maritime datasets can be obtained from the ***Dataset*** link in the description of the 
publication. The UCR dataset is a publicly available collection and can be found 
[here](http://www.timeseriesclassification.com/dataset.php).
