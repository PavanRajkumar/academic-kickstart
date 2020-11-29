---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Choosing the Best Set of Features for a ML Model for Software Risk Prediction Based on Model Accuracy"
authors: 
date: 2020-09-12T05:13:38+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-26T05:13:38+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Paper under review"
publication_short: ""

abstract: "Trying to minimize the number of software failures is one of the most
important goals in the area of software project management. In software
development, which is a part of software project management, incremental
changes are typically made to an existing set of code and documents that
may be initially empty. This goal becomes more crucial due to short
delivery schedules that constrain coding, inspection and testing. In this
paper, we use an approach to determine an optimal or nearly optimal set
of features to use in creating or training a machine learning model. We do
this by creating subsets of a base set of features in this domain, training
a ML model on the set of features and training them on the data set. We
can then pick the set that gives the best results."

# Summary. An optional shortened abstract.
summary: "Identified which features of a commit (like lines added, deleted etc.) has the most impact on determining a commit's bug risk. Utilised SHAP explanations to determine these characteristic features which allowed us to increase their weightage and improve performance of a commit risk classifier."

tags: [Git, Commits, Version Control System, Risk Estimation, Machine Learning]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "./softwareRisk2.pdf"
url_code: "https://github.com/PavanRajkumar/Software-Risk"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Bug Prediction"
  focal_point: "Smart"
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
