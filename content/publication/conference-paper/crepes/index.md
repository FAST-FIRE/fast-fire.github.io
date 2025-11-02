---
title: 'CREPES: Cooperative RElative Pose Estimation System'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhiren Xun, Jian Huang, Zhehan Li, Zhenjun Ying, Yingjian Wang, Chao Xu, Fei Gao, Yanjun Cao

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-05-29'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-29'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems(ICRA 2023)
publication_short:

abstract: Mutual localization plays a crucial role in multi-robot cooperation. CREPES, a novel system that focuses on six degrees of freedom (DOF) relative pose estimation for multi-robot systems, is proposed in this paper. CREPES has a compact hardware design using active infrared (IR) LEDs, an IR fish-eye camera, an ultra-wideband (UWB) module and an inertial measurement unit (IMU). By leveraging IR light communication, the system solves data association between visual detection and UWB ranging. Ranging measurements from the UWB and directional information from the camera offer relative 3-DOF position estimation. Combining the mutual relative position with neighbors and the gravity constraints provided by IMUs, we can estimate the 6-DOF relative pose from a single frame of sensor measurements. In addition, we design an estimator based on the error-state Kalman filter (ESKF) to enhance system accuracy and robustness. When multiple neighbors are available, a Pose Graph Optimization (PGO) algorithm is applied to further improve system accuracy. We conduct enormous experiments to demonstrate CREPES' accuracy between robot pairs and a team of robots, as well as performance under challenging conditions.

# Summary. An optional shortened abstract.
summary: A cooperative relative pose estimation system for multi-robot systems, leveraging IR light communication and UWB ranging.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2302.01036'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://fast-fire.github.io/CREPES/'
url_slides: ''
url_source: ''
url_video: 'https://www.bilibili.com/video/BV1CW4y1Y79q'

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



