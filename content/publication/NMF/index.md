---
title: 'A Ranking Model Motivated by Nonnegative Matrix Factorization with Applications to Tennis Tournaments'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Vincent Y. F. Tan
  - Louis Filstroff
  - C \'edric F\'evotte

date: '2019-10-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-10-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases, 2019
publication_short: In *ECML PKDD*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ecmlpkdd2019.org/downloads/paper/44.pdf'
url_code: 'https://github.com/XiaRui1996/btl-nmf'
url_slide: 'https://vyftan.github.io/papers/BTL_NMF_LRMA.pdf'
url_poster: ''


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

We propose a novel ranking model that combines the Bradley-Terry-Luce probability model with a nonnegative matrix factorization framework to model and uncover the presence of latent variables that influence the performance of top tennis players. We derive an efficient, provably convergent, and numerically stable majorization-minimization- based algorithm to maximize the likelihood of datasets under the pro- posed statistical model. The model is tested on datasets involving the outcomes of matches between 20 top male and female tennis players over 14 major tournaments for men (including the Grand Slams and the ATP Masters 1000) and 16 major tournaments for women over the past 10 years. Our model automatically infers that the surface of the court (e.g., clay or hard court) is a key determinant of the performances of male players, but less so for females. Top players on various surfaces over this longitudinal period are also identified in an objective manner.
