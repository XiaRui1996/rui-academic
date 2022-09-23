---
title: 'The Gaussian Process Latent Autoregressive Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wessel Bruinsma
  - William Tebbutt
  - Richard E. Turner


date: '2020-10-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 3rd Symposium on Advances in Approximate Bayesian Inference
publication_short: In *3rd AABI*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=kvq3WKXvwQ_'
url_code: 'https://github.com/XiaRui1996/GPLAR'
url_vedio: 'https://www.youtube.com/watch?v=BrBc8lbEKgc'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Graphical models for GPAR, GPLAR and bi-GPLAR.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

Many real-world prediction problems involve modelling the dependencies between multiple different outputs across the input space. Multi-output Gaussian Processes (MOGP) are a particularly important approach to such problems. In this paper, we build on the Gaussian Process Autoregressive Regression (GPAR) model which is one of the best performing MOGP models, but which fails when observation noise is large, when there are missing data, and when non-Gaussian observation models are required. We extend the original GPAR model to handle these settings and provide a variational inference procedure similar to that used in deep Gaussian Processes which replaces the ad hoc denoising approximation used in the original work. We show that the new approach naturally handles noisy outputs, missing data and that it also enables the model to handle heterogeneous non-Gaussian observation models.
