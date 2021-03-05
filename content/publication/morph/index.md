---
title: "ExTensor: An Accelerator for Sparse Tensor Algebra"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Rohit Agrawal
- Yulun Yao
- Christopher W Fletcher

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-10-16T00:00:00Z"
doi: "https://doi.org/10.1109/MICRO.2018.00080"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In MICRO 18
publication_short: In *MICRO'18*

abstract:  The past several years have seen both an explosion in the use of Convolutional Neural Networks (CNNs) and the design of accelerators to make CNN inference practical. In the architecture community, the lion share of effort has targeted CNN inference for image recognition. The closely related problem of video recognition has received far less attention as an accelerator target. This is surprising, as video recognition is more compu- tationally intensive than image recognition, and video traffic is predicted to be the majority of internet traffic in the coming years. This paper fills the gap between algorithmic and hardware advances for video recognition by providing a design space explo- ration and flexible architecture for accelerating 3D Convolutional Neural Networks (3D CNNs)—the core kernel in modern video understanding. When compared to (2D) CNNs used for image recognition, efficiently accelerating 3D CNNs poses a significant engineering challenge due to their large (and variable over time) memory footprint and higher dimensionality

# Summary. An optional shortened abstract.
summary: Morph is a flexible hardware accelerator for 3D-CNNs, a key workload used in video understanding. Key insight behind the design is to design a flexible hardware that allows high degrees of flexibility that allows different mappings of 3D-CNNs that maximizes performance for the given layer of 3D-CNN.. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'media/Morph_final_CR.pdf'
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
  caption: 'Tiled 3D-Convolution'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
