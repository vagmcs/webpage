---
title: "Parallel Model Exploration for Tumor Treatment Simulations"
draft: false

# Schedule page publish date (NOT publication's date).
date: "2022-02-15T00:00:00"
publishDate: "2022-02-15T00:00:00"

# Authors
# If you created a profile for a user (e.g. `vagmcs`), use the folder name instead, and should be replaced by their full name and linked to their profile.
authors:
- C. Akasiadis
- M. Ponce-de-Leon
- A. Montagud
- vagmcs
- A. Atsidakou
- A. Alevizos
- A. Artikis
- A. Valencia
- G. Paliouras

# Digital Object Identifier (DOI)
doi: "10.1111/coin.12515"

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
publication: "In *Computational Intelligence*, pp. 1379--1401, Wiley"
publication_short: "In *Computational Intelligence*, pp. 1379--1401 Wiley"

# Abstract and optional shortened version.
abstract: Computational systems and methods are often being used in biological research, including the understanding of cancer and the development of treatments. Simulations of tumor growth and its response to different drugs are of particular importance, but also challenging complexity. The main challenges are first to calibrate the simulators so as to reproduce real-world cases, and second, to search for specific values of the parameter space concerning effective drug treatments. In this work, we combine a multi-scale simulator for tumor cell growth and a Genetic Algorithm (GA) as a heuristic search method for finding good parameter configurations in reasonable time. The two modules are integrated into a single workflow that can be executed in parallel on high performance computing infrastructures. In effect, the GA is used to calibrate the simulator, and then to explore different drug delivery schemes. Among these schemes, we aim to find those that minimize tumor cell size and the probability of emergence of drug resistant cells in the future. Experimental results illustrate the effectiveness and computational efficiency of the approach.

# Summary. An optional shortened abstract.
# summary:

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["philosophy"]`.
tags: ["tumor simulations", "high-performance computing", "early classification", "time-series"]

# Is this a selected publication? (true/false)
featured: true

# Links (optional).
url_pdf: "pme_CI_2022.pdf"
url_code: "https://github.com/xarakas/spheroid-tnf-v2-emews"
url_dataset: ""
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
