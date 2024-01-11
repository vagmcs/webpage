---
title: "Online Semi-Supervised Learning of Composite Event Rules by Combining Structure and Mass-Based Predicate Similarity"
slug: splice_plus
draft: false

# Schedule page publish date (NOT publication's date).
date: "2023-11-01T00:00:00"
publishDate: "2020-06-22T00:00:00"

# Authors
# If you created a profile for a user (e.g. `vagmcs`), use the folder name instead, and should be replaced by their full name and linked to their profile.
authors:
- vagmcs
- A. Artikis
- G. Paliouras

# Digital Object Identifier (DOI)
doi: "10.1007/s10994-023-06447-1"

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
publication: "In *Machine Learning*"
publication_short: "In *Machine Learning*"

# Abstract and optional shortened version.
abstract: Symbolic event recognition systems detect event occurrences using first-order logic rules. Although existing online structure learning approaches ease the discovery of such rules in noisy data streams, they assume the existence of fully labelled training data. SPLICE is a recent online graph-based approach that estimates the labels of unlabelled data and makes it possible to learn such rules from semi-supervised training sequences of logical interpretations. However, SPLICE labelling depends significantly on the metric used to compute the distances of unlabelled examples to their labelled counterparts. Moreover, there is no guarantee about the quality of the labelling found in the local graphs that are built as the data stream in. In this paper, we propose a new online learning method, which includes an enhanced hybrid measure that combines an optimised structural distance, and a data-driven one. The former is guided by feature selection targeted to kNN classification, while the latter is a mass-based dissimilarity. Additionally, the enhanced SPLICE method, improves the graph construction process, by storing a synopsis of the past, in order to achieve more informed labelling on the local graphs. We evaluate our approach by learning Event Calculus theories for the tasks of human activity recognition, maritime monitoring, and fleet management. The evaluation suggests that our approach outperforms its predecessor, in terms of inferring the missing labels and improving the predictive accuracy of the underlying structure learning system.


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
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# links:
# - name: Appendix
#   url: "appendix.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication to one or more of your projects.
#   Simply enter your project's folder or file name.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [infore]

# Slides (optional).
#   Associate this publication to Markdown slides.
#   Simply enter your slide deck's filename.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
