---
title: 'Efficient input placement for the optimal control of networked systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anke Meyer-Baese

# Author notes (optional)
author_notes: ''

date: '2022-12-09'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *61st IEEE Conference on Decision and Control (CDC)*
publication_short: ''

abstract: We study the optimal control of the mean and variance of the network state vector. We develop an algorithm that uses projected gradient descent to optimize the control input placement, subject to constraints on the state that must be achieved at a given time threshold; seeking an input placement that moves the moment at minimum cost. First, we solve the state-selection problem for a number of variants of the first and second moment, and find solutions related to the eigenvalues of the systems' Gramian matrices. We then nest this state selection into projected gradient descent to design an optimal input augmentation.

# Summary. An optional shortened abstract.
summary: ''

tags: ['Networks','Optimal control', 'Input design']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2106.05265'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
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