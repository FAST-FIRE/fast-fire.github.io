---
title: "Cost-Effective Swarm Navigation System via Close Cooperation"
authors:
- Nanhe Chen
- Zhehan Li
- Lun Quan
- Xinwei Chen
- Chao xu
- Fei Gao
- Yanjun Cao
author_notes:
- "Equal contribution"
date: "2023-10-18T00:00:00Z"
doi: "10.1109/LRA.2023.3325776"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters(RAL)"
publication_short: 

abstract: Multi-robot system is desired to achieve global cost-efficiency by fully utilizing individual advantages. For example, leveraging unmanned aerial vehicles' (UAVs') agility for inspection and ground vehicles' (UGVs') capability for heavy-duty tasks. Coordinating the motion of multiple robots smartly is complex and it becomes more challenging when robots in the swarm are not equipped with sufficient sensors for environmental perception (e.g. in our case only one robot has a depth camera). In this letter, we propose a tightly coupled systematic framework to navigate a swarm composed of UAV and UGVs in unknown scenes. The system has only one depth camera with a field of view for environmental perception. We fully explore the cooperation between robots by proposing a Sequential Exploration and Aiding Localization (SEAL) planning strategy for the UAV and a Collision-Adaptive Trajectory (CAT) optimization for UGVs. The UAV assists UGVs' localization with relative pose estimation and own global localization, meanwhile, it focuses on exploration to provide UGVs with abundant environmental information. The UGV team can navigate safely and autonomously in obstacle-rich environments and even maintain formations with only the wheel odometer and UAV's assistance using CAT optimization. Our method is validated both in simulations and real-world experiments indoors and outdoors.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10545578'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=1Hn2U4-WZ7Q'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**FAST-FIRE**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
slides: example
---



