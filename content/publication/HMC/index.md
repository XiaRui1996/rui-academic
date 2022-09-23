---
title: 'A Hybrid Causal Structure Learning Algorithm for Mixed-type Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yan Li
  - admin
  - Chunchen Liu
  - Sun Liang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Association for the Advancement of Artificial Intelligence, 2022
publication_short: In *AAAI(2022)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.aaai.org/AAAI22Papers/AAAI-12541.LiY.pdf'
url_code: 'https://github.com/DAMO-DI-ML/AAAI2022-HCM'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Learned causal graph from credit data set'
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

Inferring the causal structure of a set of random variables is a crucial problem in many disciplines of science. Over the past two decades, various approaches have been pro- posed for causal discovery from observational data. How- ever, most of the existing methods are designed for either purely discrete or continuous data, which limit their practical usage. In this paper, we target the problem of causal struc- ture learning from observational mixed-type data. Although there are a few methods that are able to handle mixed-type data, they suffer from restrictions, such as linear assump- tion and poor scalability. To overcome these weaknesses, we formulate the causal mechanisms via mixed structure equa- tion model and prove its identifiability under mild condi- tions. A novel locally consistent score, named CVMIC, is proposed for causal directed acyclic graph (DAG) structure learning. Moreover, we propose an efficient conditional inde- pendence test, named MRCIT, for mixed-type data, which is used in causal skeleton learning and final pruning to further improve the computational efficiency and precision of our model. Experimental results on both synthetic and real-world data demonstrate that our proposed hybrid model outperforms the other state-of-the-art methods. Our source code is available at https://github.com/DAMO-DI-ML/AAAI2022-HCM.
