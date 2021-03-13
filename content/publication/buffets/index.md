---
title: "Buffets: An Efficient and Composable Storage Idiom for Explicit Decoupled Data Orchestration"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Michael Pellauer
- Yakun Sophia Shao
- Jason Clemons 
- Neal Crago
- admin
- Rangharajan Ventakesan
- Stephen W. Keckler
- Christopher W Fletcher
- Joel Emer


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-04-13T00:00:00Z"
doi: "https://doi.org/10.1145/3297858.3304025"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-01-01T00:00:00Z"

# Order that this section appears on the page.
weight: 2

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In ASPLOS 19
publication_short: In *ASPLOS'19*

abstract:  Accelerators spend significant area and effort on custom onchip buffering. Unfortunately, these solutions are strongly tied to particular designs, hampering re-usability across other accelerators or domains. We present buffets, an efficient and composable storage idiom for the needs of accelerators that is independent of any particular design. Buffets have several distinguishing characteristics, including efficient decoupled fills and accesses with fine-grained synchronization, hierarchical composition, and efficient multi-casting. We implement buffets in RTL and show that they only add 2% control overhead over an 8KB RAM. When compared with DMAmanaged double-buffered scratchpads and caches across a range of workloads, buffets improve energy-delay-product by 1.53× and 5.39×, respectively.

# Summary. An optional shortened abstract.
summary: A key issue in hardware accelerator design is re-usability of designs across different accelerators. With Buffets, we present a reusable, composable, and efficient storage idiom for programmable hardware accelerators.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'media/buffet_ASPLOS19.pdf'
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
  caption: 'Buffet Storage Idiom'
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
