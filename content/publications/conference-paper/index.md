---
title: 'GeoLoRA: Geometric integration for parameter-efficient fine-tuning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Steffen Schotthöfer
  - admin
  - Gianluca Ceruti
  - Francesco Tudisco
  - Jonas Kusch

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

abstract: Low-Rank Adaptation (LoRA) has become a widely used method for parameter-efficient fine-tuning of large-scale, pre-trained neural networks. However, LoRA and its extensions face several challenges, including the need for rank adaptivity, robustness, and computational efficiency during the fine-tuning process. We introduce GeoLoRA, a novel approach that addresses these limitations by leveraging dynamical low-rank approximation theory. GeoLoRA requires only a single backpropagation pass over the small-rank adapters, significantly reducing computational cost as compared to similar dynamical low-rank training methods and making it faster than popular baselines such as AdaLoRA. This allows GeoLoRA to efficiently adapt the allocated parameter budget across the model, achieving smaller low-rank adapters compared to heuristic methods like AdaLoRA and LoRA, while maintaining critical convergence, descent, and error-bound theoretical guarantees. The resulting method is not only more efficient but also more robust to varying hyperparameter settings. We demonstrate the effectiveness of GeoLoRA on several state-of-the-art benchmarks, showing that it outperforms existing methods in both accuracy and computational efficiency.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Low-rank, Riemannian gradient flow, Fine-tuning, LoRA

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
  # ids:
    # doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://openreview.net/pdf?id=bsFWJ0Kget"
  - type: code
    url: https://github.com/ScSteffen/Publication-GeoLoRA-Geometric-integration-for-parameter-efficient-fine-tuning
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
title: 'Low-rank lottery tickets: finding efficient low-rank neural networks via matrix differential equations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Steffen Schotthöfer
  - admin
  - Jonas Kusch
  - Gianluca Ceruti
  - Francesco Tudisco

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-12-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems*
publication_short: In NeurIPS

abstract: Neural networks have achieved tremendous success in a large variety of applications. However, their memory footprint and computational demand can render them impractical in application settings with limited hardware or energy resources. In this work, we propose a novel algorithm to find efficient low-rank subnetworks. Remarkably, these subnetworks are determined and adapted already during the training phase and the overall time and memory resources required by both training and evaluating them is significantly reduced. The main idea is to restrict the weight matrices to a low-rank manifold and to update the low-rank factors rather than the full matrix during training. To derive training updates that are restricted to the prescribed manifold, we employ techniques from dynamic model order reduction for matrix differential equations. Moreover, our method automatically and dynamically adapts the ranks during training to achieve a desired approximation accuracy.The efficiency of the proposed method is demonstrated through a variety of numerical experiments on fully-connected and convolutional networks.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Low-rank, Riemannian gradient flow, compression

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
  # ids:
    # doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://proceedings.neurips.cc/paper_files/paper/2022/file/7e98b00eeafcdaeb0c5661fb9355be3a-Paper-Conference.pdf"
  - type: code
    url: https://github.com/COMPiLELab/DLRT-Net
  # - type: dataset
    # url: https://github.com/HugoBlox/hugo-blox-builder
  - type: slides
    url: https://neurips.cc/media/neurips-2022/Slides/53825_SZbm58f.pdf
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

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
