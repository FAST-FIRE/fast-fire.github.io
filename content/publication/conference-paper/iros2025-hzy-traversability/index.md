---
title: 'Real-time Spatial-temporal Traversability Assessment via Feature-based Sparse Gaussian Process'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhenyu Hou
  - Senming Tan
  - Zhihao Zhang
  - Long Xu
  - Mengke Zhang
  - Zhaoqi He
  - Chao Xu
  - Fei Gao
  - Yanjun Cao

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: '2025-10-10'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-10'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE/RSJ International Conference on Intelligent Robots and Systems, 2025(IROS 2025)
publication_short: 

abstract: Terrain analysis is critical for the practical application of ground mobile robots in real-world tasks, especially in outdoor unstructured environments. In this paper, we propose a novel spatial-temporal traversability assessment method, which aims to enable autonomous robots to effectively navigate through complex terrains. Our approach utilizes sparse Gaussian processes (SGP) to extract geometric features (curvature, gradient, elevation, etc.) directly from point cloud scans. These features are then used to construct a highresolution local traversability map. Then, we design a spatialtemporal Bayesian Gaussian kernel (BGK) inference method to dynamically evaluate traversability scores, integrating historical and real-time data while considering factors such as slope, flatness, gradient, and uncertainty metrics. GPU acceleration is applied in the feature extraction step, and the system achieves real-time performance. Extensive simulation experiments across diverse terrain scenarios demonstrate that our method outperforms SOTA approaches in both accuracy and computational efficiency. Additionally, we develop an autonomous navigation framework integrated with the traversability map and validate it with a differential driven vehicle in complex outdoor environments. Our code will be open-source for further research and development by the community,https://github.com /ZJU-FAST-Lab/FSGP_BGK.

# Summary. An optional shortened abstract.
summary: FSGP-BGK is a real-time, GPU-accelerated spatiotemporal traversability method that extracts geometry from point clouds via sparse GPs and fuses history with BGK to yield high-res maps, outperforming SOTA.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.48550/arXiv.2503.04134'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com /ZJU-FAST-Lab/FSGP_BGK'
url_slides: ''
url_source: ''
url_video: 'https://percyhzy.github.io/IROS2025-website/'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**FAST-FIRE**](https://pages.fast-fire.space)'
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
slides: example
---



