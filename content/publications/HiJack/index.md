---
title: 'HIJACK: Learning-based Strategies for Sound Classification Robustness to Adversarial Noise'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Derek Sweet
  - admin
  - Francesca Meneghello

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-08-07T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-07T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Smart Computing*
publication_short: In IEEE SMARTCOMP

abstract: The effective deployment of smart service systems within homes, workspaces and cities, requires gaining context and situational awareness to take action when changes are detected. To this end, sound classification systems are widely adopted and integrated into several smart devices to continuously monitor the environment. However, sound classification algorithms are prone to adversarial attacks that pose a considerable security threat to smart service systems where they are integrated. In this paper, we devise HIJACK, a novel machine learning framework entailing five neural network strategies to enforce the robustness of sound classification systems to adversarial noise injection. The HIJACK methodologies can be applied to any neural network-based sound classifier and consist of tailored transformations of the input audio during training along with specific additional layers added to the neural network architecture. To assess the noise robustness provided by the HIJACK strategies, we design a measure based on a L2-adversarial attack to sound classification – identified as the normalized fast gradient method (NFGM) – that constructs the adversarial noise by maximizing the sound mis-classification probability. We assessed the robustness of HIJACK to the proposed NFGM attack on a publicly available dataset. The results show that the combination of the five HIJACK strategies allows reaching robustness to adversarial noise 58 times larger than state-of-the-art neural networks for sound classification, guaranteeing a classification accuracy above 83%.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Adversarial deep-learning
  - speech-recognition systems

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
# hugoblox:
  # ids:
    # doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://ieeexplore.ieee.org/abstract/document/10207676"
  # - type: code
    # url: https://github.com/ScSteffen/Publication-GeoLoRA-Geometric-integration-for-parameter-efficient-fine-tuning
  # - type: dataset
    # url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
    # url: https://neurips.cc/media/neurips-2022/Slides/53825_SZbm58f.pdf
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