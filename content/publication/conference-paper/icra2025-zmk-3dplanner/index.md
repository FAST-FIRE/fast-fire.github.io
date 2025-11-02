---
title: 'Efficient Trajectory Generation Based on Traversable Planes in 3D Complex Architectural Spaces'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mengke Zhang
  - Zhihao Tian
  - Yaoguang Xia
  - Chao Xu
  - Fei Gao
  - Yanjun Cao

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-05-19'
doi: '10.1109/ICRA55743.2025.11128727'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-19'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication:  2025 IEEE International Conference on Robotics and Automation (ICRA 2025)
publication_short: 

abstract: With the increasing integration of robots into human life, their role in architectural spaces where people spend most of their time has become more prominent. While motion capabilities and accurate localization for automated robots have rapidly developed, the challenge remains to generate efficient, smooth, comprehensive, and high-quality trajectories in these areas. In this paper, we propose a novel efficient planner for ground robots to autonomously navigate in large complex multi-layered architectural spaces. Considering that traversable regions typically include ground, slopes, and stairs, which are planar or nearly planar structures, we simplify the problem to navigation within and between complex intersecting planes. We first extract traversable planes from 3D point clouds through segmenting, merging, classifying, and connecting to build a plane-graph, which is lightweight but fully represents the traversable regions. We then build a trajectory optimization based on motion state trajectory and fully consider special constraints when crossing multi-layer planes to maximize the robot's maneuverability. We conduct experiments in simulated environments and test on a CubeTrack robot in real-world scenarios, validating the method's effectiveness and practicality.
# Summary. An optional shortened abstract.
summary: Efficient Trajectory Generation Based on Traversable Planes in 3D Complex Architectural Spaces

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/11128727'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.bilibili.com/video/BV114QnYiEWf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**FAST-FIRE**](https://pages.fast-fire.space)'
#   focal_point: ''
#   preview_only: false

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



