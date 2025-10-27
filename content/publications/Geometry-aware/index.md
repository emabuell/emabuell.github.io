---
title: 'Geometry-aware training of factorized layers in tensor Tucker format'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Steffen Schotthöfer
  - Gianluca Ceruti
  - Jonas Kusch
  - Francesco Tudisco

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-12-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Neural Information and Processing Syste,s*
publication_short: In NeurIPS

abstract: Reducing parameter redundancies in neural network architectures is crucial for achieving feasible computational and memory requirements during train and inference of large networks. Given its easy implementation and flexibility, one promising approach is layer factorization, which reshapes weight tensors into a matrix format and parameterizes it as the product of two rank-r matrices. However, this family of approaches often requires an initial full-model warm-up phase, prior knowledge of a feasible rank, and it is sensitive to parameter initialization.In this work, we introduce a novel approach to train the factors of a Tucker decomposition of the weight tensors. Our training proposal proves to be optimal in locally approximating the original unfactorized dynamics and stable for the initialization. Furthermore, the rank of each mode is dynamically updated during training.We provide a theoretical analysis of the algorithm, showing convergence, approximation and local descent guarantees. The method's performance is further illustrated through a variety of experiments, showing remarkable training compression rates and comparable or even better performance than the full baseline and alternative layer factorization strategies.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Low-rank, Riemannian gradient flow, Tucker tensor representation, compression

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
  # ids:
    # doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://proceedings.neurips.cc/paper_files/paper/2024/file/ea48cb23a02ec3b895b0b0124307b0ec-Paper-Conference.pdf"
  - type: code
    url: https://openreview.net/attachment?id=aBtcfcrjM3&name=supplementary_material
  # - type: dataset
    # url: https://github.com/HugoBlox/hugo-blox-builder
  - type: slides
    url: https://neurips.cc/media/neurips-2024/Slides/94579_PfsrYQc.pdf
  # - type: source
    # url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
   # url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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