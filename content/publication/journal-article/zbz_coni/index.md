---
title: "CoNi-MPC: Cooperative Non-inertial Frame Based Model Predictive Control"
authors:
- Baozhe Zhang
- Xinwei Chen
- Zhehan Li
- Giovanni Beltrame
- Chao xu
- Fei Gao
- Yanjun Cao
author_notes:
- "Equal contribution"
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
publication: "IEEE Robotics and Automation Letters (RAL)"
publication_short: 

abstract: This work presents a novel solution for UAV control in cooperative multi-robot systems, which can be used in various scenarios such as leader-following, landing on a moving base, or specific relative motion with a target. Unlike classical methods that tackle UAV control in the world frame, we directly control the UAV in the target coordinate frame, without making motion assumptions about the target. In detail, we formulate a non-linear model predictive controller of a UAV, referred to as the agent, within a non-inertial frame (i.e., the target frame). The system requires the relative states (pose and velocity), the angular velocity and the accelerations of the target, which can be obtained by relative localization methods and ubiquitous MEMS IMU sensors, respectively. This framework eliminates dependencies that are vital in classical solutions, such as accurate state estimation for both the agent and target, prior knowledge of the target motion model, and continuous trajectory re-planning for some complex tasks. We have performed extensive simulations to investigate the control performance with varying motion characteristics of the target. Furthermore, we conducted real robot experiments, employing either simulated relative pose estimation from motion capture systems indoors or directly from our previous relative pose estimation devices outdoors, to validate the applicability and feasibility of the proposed approach.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10287548'
url_code: 'https://github.com/fast-fire/CoNi-MPC/'
url_dataset: ''
url_poster: ''
url_project: 'https://fast-fire.github.io/CoNi-MPC/'
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/i1ZsvC7HDqU'

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



