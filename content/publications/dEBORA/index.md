---
title: 'dEBORA: Efficient Bilevel Optimization-based low-Rank Adaptation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sara Venturini
  - Francesco Rinaldi
  - Francesco Tudisco

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2025-04-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Internation conference on Learning Representations*
publication_short: In ICLR

abstract: Low-rank adaptation methods are a popular approach for parameter-efficient fine-tuning of large-scale neural networks. However, selecting the optimal rank for each layer remains a challenging problem that significantly affects both performance and efficiency. In this paper, we introduce a novel bilevel optimization strategy that simultaneously trains both matrix and tensor low-rank adapters, dynamically selecting the optimal rank for each layer. Our method avoids the use of implicit differentiation in the computation of the hypergradient, and integrates a stochastic away-step variant of the Frank-Wolfe algorithm, eliminating the need for projection and providing identifiability guarantees of the optimal rank structure. This results in a highly efficient and cost-effective training scheme that adaptively allocates the parameter budget across the network layers. On top of a detailed theoretical analysis of the method, we provide different numerical experiments showcasing its effectiveness.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Low-rank
  - Bilevel-optimization
  - Fine-tuning 
  - LoRA

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
  # ids:
    # doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://openreview.net/pdf?id=5M0ic2RxQZ"
  - type: code
    url: https://openreview.net/attachment?id=5M0ic2RxQZ&name=supplementary_material
  # - type: dataset
    # url: https://github.com/HugoBlox/hugo-blox-builder
  - type: slides
    url: https://iclr.cc/media/iclr-2025/Slides/30949.pdf
  # - type: source
    # url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
   # url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---