---
title: 'Colag: A collaborative air-ground framework for perception-limited ugvs’ navigation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhehan Li
  - Rui Mao
  - Nanhe Chen
  - Chao Xu
  - Fei Gao
  - Yanjun Cao
 

# Author notes (optional)
author_notes:
  - 'Equal contribution'


date: '2024-05-29'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-29'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2024 IEEE International Conference on Robotics and Automation (ICRA 2024)
publication_short: 

abstract: Perception is necessary for autonomous navigation in an unknown area crowded with obstacles. It's challenging for a robot to navigate safely without any sensors that can sense the environment, resulting in a blind robot, and becomes more difficult when comes to a group of robots. However, it could be costly to equip all robots with expensive perception or SLAM systems. In this paper, we propose a novel system named ColAG, to solve the problem of autonomous navigation for a group of blind UGVs by introducing cooperation with one UAV, which is the only robot that has full perception capabilities in the group. The UAV uses SLAM for its odometry and mapping while sharing this information with UGVs via limited relative pose estimation. The UGVs plan their trajectories in the received map and predict possible failures caused by the uncertainty of its wheel odometry and unknown risky areas. The UAV dynamically schedules waypoints to prevent UGVs from collisions, formulated as a Vehicle Routing Problem with Time Windows to optimize the UAV's trajectories and minimize time when UGVs have to wait to guarantee safety. We validate our system through extensive simulation with up to 7 UGVs and real-world experiments with 3 UGVs.

# Summary. An optional shortened abstract.
summary: A collaborative air-ground framework for perception-limited UGVs' navigation, where a UAV provides perception capabilities to a group of blind UGVs.

tags: [MRS]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2310.13324'
url_code: 'https://github.com/FAST-FIRE/ColAG'
url_dataset: ''
url_poster: ''
url_project: 'https://fast-fire.github.io/ColAG/'
url_slides: ''
url_source: ''
url_video: 'https://www.bilibili.com/video/BV1by421a73g'

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



