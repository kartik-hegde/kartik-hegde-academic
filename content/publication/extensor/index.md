---
title: "ExTensor: An Accelerator for Sparse Tensor Algebra"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Hadi Asghari-Moghaddam
- Michael Pellauer
- Neal Crago
- Aamer Jaleel
- Edgar Solomonic
- Joel Emer
- Christopher W Fletcher

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-10-12T00:00:00Z"
doi: "https://doi.org/10.1145/3352460.3358275"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In MICRO 19
publication_short: In *MICRO'21*

abstract:  Generalized tensor algebra is a prime candidate for acceleration via customized ASICs. Modern tensors feature a wide range of data sparsity, with the density of non-zero elements ranging from 10−6% to 50%. This paper proposes a novel approach to accelerate tensor kernels based on the principle of hierarchical elimination of com- putation in the presence of sparsity. This approach relies on rapidly inding intersectionsÐsituations where both operands of a multipli- cation are non-zeroÐenabling new data fetching mechanisms and avoiding memory latency overheads associated with sparse kernels implemented in software. We propose the ExTensor accelerator, which builds these novel ideas on handling sparsity into hardware to enable better band- width utilization and compute throughput. We evaluate ExTensor on several kernels relative to industry libraries (Intel MKL) and state-of-the-art tensor algebra compilers (TACO). When bandwidth normalized, we demonstrate an average speedup of 3.4×, 1.3×, 2.8×, 24.9×, and 2.7× on SpMSpM, SpMM, TTV, TTM, and SDDMM ker- nels respectively over a server class CPU.

# Summary. An optional shortened abstract.
summary: ExTensor is an acceletor for Sparse Tensor Algebra, a key class of workloads that powers crucial areas such as deep learning. Key insight behind the design is to hierarchically eliminate ineffectual work that exists due to sparsity to demonstrate significant speed-ups. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'media/ExTensor_final.pdf'
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
  caption: 'Varying Sparsity in Different Areas of Computing'
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
