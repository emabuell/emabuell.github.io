---
title: 'Provable Emergence of Deep Neural Collapse and Low-Rank Bias in $L^2$-Regularized Nonlinear Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Piero Deidda
  - Simone Brugiapaglia
  - Nicola Guglielmi
  - Francesco Tudisco

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2025-08-23T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: ArXiv 
publication_short: ArXiv preprint.

abstract: Recent work in deep learning has shown strong empirical and theoretical evidence of an implicit low-rank bias: weight matrices in deep networks tend to be approximately low-rank. Moreover, removing relatively small singular values during training, or from available trained models, may significantly reduce model size while maintaining or even improving model performance. However, the majority of the theoretical investigations around low-rank bias in neural networks deal with oversimplified models, often not taking into account the impact of nonlinearity. In this work, we first of all quantify a link between the phenomenon of deep neural collapse and the emergence of low-rank weight matrices for a general class of feedforward networks with nonlinear activation. In addition, for the general class of nonlinear feedforward and residual networks, we prove the global optimality of deep neural collapsed configurations and the practical absence of a loss barrier between interpolating minima and globally optimal points, offering a possible explanation for its common occurrence. As a byproduct, our theory also allows us to forecast the final global structure of singular values before training. Our theoretical findings are supported by a range of experimental evaluations illustrating the phenomenon.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Low-rank bias, Deep neural collapse, low-dimensional representations, feature learning

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
  # ids:
    # doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2402.03991"
  # - type: code
    # url: https://openreview.net/attachment?id=5M0ic2RxQZ&name=supplementary_material
  # - type: dataset
    # url: https://github.com/HugoBlox/hugo-blox-builder
  #- type: slides
   # url: https://iclr.cc/media/iclr-2025/Slides/30949.pdf
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