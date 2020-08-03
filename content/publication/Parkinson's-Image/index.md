---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An Explainable Machine Learning Model for Early Detection of Parkinson's Disease using LIME on DaTscan Imagery"
authors: [Pavan Rajkumar Magesh, Richard Delwin Myloth, Rijo Jackson Tom]
date: 2020-07-29T19:04:56+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-29T19:04:56+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to Computers in Biology and Medicine"
publication_short: ""

abstract: "Parkinson's disease (PD) is a degenerative and progressive neurological condition. Early diagnosis can improve treatment for patients and is performed through dopaminergic imaging techniques like the SPECT DaTscan. In this study, we propose a machine learning model that accurately classifies any given DaTscan as having Parkinson's disease or not, in addition to providing a plausible reason for the prediction. This is kind of reasoning is done through the use of visual indicators generated using Local Interpretable Model-Agnostic Explainer (LIME) methods. DaTscans were drawn from the Parkinson's Progression Markers Initiative database and trained on a CNN (VGG16) using transfer learning, yielding an accuracy of 95.2%, a sensitivity of 97.5%, and a specificity of 90.9%. Keeping model interpretability of paramount importance, especially in the healthcare field, this study utilises LIME explanations to distinguish PD from non-PD, using visual superpixels on the DaTscans. It could be concluded that the proposed system, in union with its measured interpretability and accuracy may effectively aid medical workers in the early diagnosis of Parkinson's Disease."

# Summary. An optional shortened abstract.
summary: "Developed a neural network model using transfer learning on the VGG16 CNN architecture to diagnose Parkinson's Disease by analysing the varying sizes of the putamen and caudate regions of the brain visualised in SPECT DaTscans. (Click title for more info)"

tags: [Parkinson’s Disease, Convolutional Neural Network, Computer-aided Diagnosis,
Interpretability, Explainable AI]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "./Parkinson's-Image.pdf"
url_code: "https://github.com/PavanRajkumar/Parkinsons-DaTscan"
url_dataset: "https://www.ppmi-info.org/"
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: "SPECT DaTscan"
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
