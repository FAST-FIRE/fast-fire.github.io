---
title: 'EAR-SLAM: Environment-aware robust localization system for terrestrial-aerial bimodal vehicles'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenjun He; Xingpeng Wang; Pengfei Wang; Tianfu Zhang; Chao Xu; Fei Gao; Yanjun Cao*

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2025-05-13T00:00:00Z'
doi: '10.1109/ICRA55743.2025.11128310'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2025 IEEE International Conference on Robotics and Automation (ICRA 2025)
publication_short: 

abstract: Terrestrial-aerial bimodal vehicles (TABVs) can fly to avoid obstacles and move safely on the ground to save energy, offering enhanced adaptability and flexibility in various challenging environments. However, a robust localization approach becomes a bottleneck to stably applying the TABVs in real-world tasks. Besides the general limitations of visual SLAM methods, large FoV differences between the two modes, abrupt motion strikes in mode transitions, and unstable attitude in ground mode pose great challenges. In this paper, we present an environment-aware robust localization system specifically designed for passive-wheel-based TABVs, which feature two passive wheels alongside a standard quadrotor. The localization system tightly integrates data from multiple sensors, including a stereo camera, Inertial Measurement Units (IMUs), encoders, and single-point laser distance sensors. First, we introduce a terrain-aware odometer model that accurately estimates terrain slope and vehicle's velocity. Then, we propose an anomaly-aware method that senses anomalous sensors and dynamically adjusts the optimization weights accordingly. By explicitly estimating the environmental conditions, such as ground terrain slopes and visual information qualities, the robot can achieve accurate and robust localization results on the ground. To validate our localization approach, we conducted extensive experiments across various challenging scenarios, demonstrating the effectiveness and reliability of our system for real-world applications.

# Summary. An optional shortened abstract.
summary: Terrestrial-aerial bimodal vehicles (TABVs) have air-ground advantages but face localization bottlenecks due to FoV differences, abrupt mode-transition motion, unstable ground attitude and visual SLAM limits.An environment-aware robust localization system for passive-wheel-based TABVs is proposed, fusing data from stereo cameras, IMUs, encoders and single-point laser sensors.It includes a terrain-aware odometer model and an anomaly-aware method, with extensive experiments proving its effectiveness in accurate ground localization.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Image credit: [**EAR-SLAM**](https://ieeexplore.ieee.org/abstract/document/11128310)'
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



