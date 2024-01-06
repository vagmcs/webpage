---
title: "Scalable Semi-Supervised Structure Learning for Event Recognition"
draft: false

# Schedule page publish date (NOT publication's date).
date: "2023-12-11T00:00:00"
publishDate: "2023-12-11T00:00:00"

# Authors
# If you created a profile for a user (e.g. `vagmcs`), use the folder name instead, and should be replaced by their full name and linked to their profile.
authors:
- vagmcs

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
publication_types: ["7"]

# Publication name and optional abbreviated version.
publication: ""
publication_short: ""

# Abstract and optional shortened version.
abstract: Symbolic event recognition systems often rely on knowledge bases of event definitions, expressed in first-order logic, to detect event occurrences over time. Logical frameworks for representing and reasoning about events provide robust temporal reasoning and enable the automated discovery of event rules via Inductive Logic Programming (ILP). Although existing structure learning approaches ease the discovery of such rules in noisy data streams, they assume the existence of fully-labelled training sequences, which is unrealistic for most real-life applications. In this thesis we address the issue of scalable semi-supervised learning for event recognition. We propose two novel techniques for inferring the missing supervision on training sequences and enable learning event rules in the Event Calculus. First, we propose SPLICE, a framework that employs a graph-based method to derive labels for unlabelled data, based on their distance to their labelled counterparts. In order to adapt the graph-based method to first-order logic, we use a suitable structural distance for measuring the distance between sets of logical atoms. The labelling process is achieved online (single-pass) by means of a caching mechanism and the Hoeffding bound for filtering contradicting examples. However, SPLICE labelling may be compromised since its structural measure is agnostic of the feature semantics. Moreover, there is no guarantee about the quality of the labelling found in the local graphs that are built as the data stream in. To that end, we also propose SPLICE+, a second method that improves upon SPLICE by employing a hybrid measure combining an optimised structural distance, and a data-driven one. The former is guided by feature selection, while the latter is a mass-based dissimilarity. In addition, SPLICE+ improves the graph construction process, by storing a synopsis of the past, in order to achieve more informed labelling on the local graphs. We evaluate our approach on the task of complex event recognition by using a benchmark dataset for human activity recognition, a dataset for maritime monitoring, as well as a dataset for fleet management.

# Summary. An optional shortened abstract.
# summary:

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["philosophy"]`.
tags: []

# Is this a selected publication? (true/false)
featured: true

# Links (optional).
url_pdf: "phd.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: "slides.pdf"
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
