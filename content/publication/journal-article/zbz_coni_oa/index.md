---
title: "Global-State-Free Obstacle Avoidance for Quadrotor Control in Air-Ground Cooperation"
authors:
- Baozhe Zhang
- Xinwei Chen
- Qingcheng Chen
- Giovanni Beltrame
- Chao xu
- Fei Gao
- Yanjun Cao
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-05-08T00:00:00Z"
doi: "110.1109/LRA.2025.3568314"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters (RAL)"
publication_short: 

abstract: " CoNi-MPC [Zhang et al. (2023)] provides an efficient framework for UAV control in air-ground cooperative tasks by relying exclusively on relative states, eliminating the need for global state estimation. However, its lack of environmental information poses significant challenges for obstacle avoidance. To address this issue, we propose a novel obstacle avoidance algorithm, Cooperative Non-inertial frame-based Obstacle Avoidance (CoNi-OA), designed explicitly for UAV-UGV cooperative scenarios without reliance on global state estimation or obstacle prediction. CoNi-OA uniquely utilizes a single frame of raw LiDAR data from the UAV to generate a modulation matrix, which directly adjusts the quadrotor's velocity to achieve obstacle avoidance. This modulation-based method enables real-time generation of collision-free trajectories within the UGV's non-inertial frame, significantly reducing computational demands (less than 5 ms per iteration) while maintaining safety in dynamic and unpredictable environments. The key contributions of this work include: 1) a modulation-based obstacle avoidance algorithm specifically tailored for UAV-UGV cooperation in non-inertial frames without global states; 2) rapid, real-time trajectory generation based solely on single-frame LiDAR data, removing the need for obstacle modeling or prediction; and 3) adaptability to both static and dynamic environments, thus extending applicability to featureless or unknown scenarios. "

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10993292'
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



