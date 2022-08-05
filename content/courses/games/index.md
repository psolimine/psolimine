---
title: 'Efficient input placement for the optimal control of networked moments'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: ''

# Author notes (optional)
author_notes: ''

date: ''
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['0']

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract:
  <details>
    <summary><b>View course description</b></summary>
    This advanced elective course provides an introduction to the applied theoretical modeling of games and decision making, designed to be both practical for and accessible to students from a wide range of backgrounds. The course focuses on problems arising in business and economic environments, such as in public economics and industrial organization, with the primary goal of promoting critical and strategic thinking in both professional settings and everyday life.
  </details>
  <details>
    <summary><b>View student feedback</b></summary>
    <details>
      <summary><b>Summer 2021 (face-to-face)</b></summary>
      - Selected student comments:
            - I appreciate that Philip takes a learning forward approach to instructing this class, he is transparent about being 'an easy grader' and it is obvious that he is more focused on learning than he is on his students getting grades. I think this is conducive to a healthy learning environment, at least for me personally. I think I have learned more in this class than 90% of my other economics courses. The assignments are directly correlated with what we learned in class and they are short and to the point. There is no busy work asked of us which allows me to put in ample time into actual important studying/learning with the materials given. He always gives great detailed feedback and follow through points. I also enjoy MobLab.
            - Dr. Solimine was very helpful in teaching us this course, and always offered additional help if we got lost on a problem. I really enjoyed having him as a professor.
            - I really liked how you provided detailed feedback on the exams and problem sets. It really helped me understand and learn from my mistakes.
            - Going to office hours was very helpful, where you gave full in depth explanations of the homework and exams each time for my understanding. The Mob Lab was fun to do because of the practical application of the material we learned was being put to use. I do not like senseless learning... ...with this class each week we learned then you would provide examples, sometimes in games relevance or real life economics issues where game theory could be implemented. With that in mind I thought it helped me be engaged a bit more. 
    </details>
  </details>

# Summary. An optional shortened abstract.
summary: ''

tags: ['Networks','Optimal control', 'Input design']

# Display this page in the Featured widget?
featured: true

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
**Abstract:** We study the optimal control of the mean and variance of the network state vector. We develop an algorithm that uses projected gradient descent to optimize the control input placement, subject to constraints on the state that must be achieved at a given time threshold; seeking an input placement that moves the moment at minimum cost. First, we solve the state-selection problem for a number of variants of the first and second moment, and find solutions related to the eigenvalues of the systems' Gramian matrices. We then nest this state selection into projected gradient descent to design an optimal input augmentation.