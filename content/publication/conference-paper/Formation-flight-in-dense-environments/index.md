---
title: 'Formation Flight in Dense Environments'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lun Quan
  - Longji Yin
  - Tingrui Zhang
  - Mingyang Wang
  - Ruilin Wang
  - Sheng Zhong
  - Yanjun Cao
  - Chao Xu
  - Fei Gao

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2022-01-01'
doi: '10.48550/arXiv.2210.04048'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'ICRA 2022'
publication_short: ''

abstract: Formation flight has a vast potential for aerial robot swarms in various applications. However, existing methods lack the capability to achieve fully autonomous large-scale formation flight in dense environments. To bridge the gap, we present a complete formation flight system that effectively integrates real-world constraints into aerial formation navigation. This paper proposes a differentiable graph-based metric to quantify the overall similarity error between formations. This metric is invariant to rotation, translation, and scaling, providing more freedom for formation coordination. We design a distributed trajectory optimization framework that considers formation similarity, obstacle avoidance, and dynamic feasibility. The optimization is decoupled to make large-scale formation flights computationally feasible. To improve the elasticity of formation navigation in highly constrained scenes, we present a swarm reorganization method that adaptively adjusts the formation parameters and task assignments by generating local navigation goals. A novel swarm agreement strategy called global-remap-local-replan and a formation-level path planner is proposed in this work to coordinate the global planning and local trajectory optimizations. To validate the proposed method, we design comprehensive benchmarks and simulations with other cutting-edge works in terms of adaptability, predictability, elasticity, resilience, and efficiency. Finally, integrated with palm-sized swarm platforms with onboard computers and sensors, the proposed method demonstrates its efficiency and robustness by achieving the largest scale formation flight in dense outdoor environments.

# Summary. An optional shortened abstract.
# summary: A complete formation flight system that effectively integrates real-world constraints into aerial formation navigation, establishing a differentiable graph-based metric to quantify the overall similarity error between formations.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2210.04048'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=lFumt0rJci4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
