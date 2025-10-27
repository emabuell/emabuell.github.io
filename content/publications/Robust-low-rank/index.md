---
title: 'Robust low-rank training via approximate orthonormal constraints'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dayana Savostianova
  - admin
  - Gianluca Ceruti
  - Francesco Tudisco

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-12-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems*
publication_short: In NeurIPS

abstract: With the growth of model and data sizes, a broad effort has been made to design pruning techniques that reduce the resource demand of deep learning pipelines, while retaining model performance. In order to reduce both inference and training costs, a prominent line of work uses low-rank matrix factorizations to represent the network weights. Although able to retain accuracy, we observe that low-rank methods tend to compromise model robustness against adversarial perturbations. By modeling robustness in terms of the condition number of the neural network, we argue that this loss of robustness is due to the exploding singular values of the low-rank weight matrices. Thus, we introduce a robust low-rank training algorithm that maintains the network's weights on the low-rank matrix manifold while simultaneously enforcing approximate orthonormal constraints. The resulting model reduces both training and inference costs while ensuring well-conditioning and thus better adversarial robustness, without compromising model accuracy. This is shown by extensive numerical evidence and by our main approximation theorem that shows the computed robust low-rank network well-approximates the ideal full model, provided a highly performing low-rank sub-network exists.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Low-rank, Adversarial attacks, non-linear condition number

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
  # ids:
    # doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://proceedings.neurips.cc/paper_files/paper/2023/file/d073692637b4fb8c4eb4b81f0fa2df7b-Paper-Conference.pdf"
  - type: code
    url: https://github.com/COMPiLELab/CondLR
  # - type: dataset
    # url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
    # url: https://neurips.cc/media/neurips-2024/Slides/94579_PfsrYQc.pdf
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