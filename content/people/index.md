---
title: About Us
date: 2022-10-24

type: landing

sections:
  # Mission statement moved from the homepage
  - block: markdown
    id: about
    content:
      title: Who We Are
      subtitle: ''
      text: |-
        We are the **Center of Swarm Navigation (CSN)** at **Huzhou Institute of Zhejiang University**, and the **Field Intelligent Robotics Engineering (FIRE)** group of the **Field Autonomous System and Computing Lab (FAST Lab)**.

        Our mission is to create intelligent robot teams that can operate in complex, diverse environments and tackle real-world challenges. We explore novel robotic concepts and push the boundaries of what field robots can achieve.

        Our research spans **multi-robot cooperation**, **novel robot platforms**, and **autonomous navigation**. We also work with a spin-off company to translate research into practical systems and complete the R&D cycle.
    design:
      columns: '1'
      css_class: about-intro
      spacing:
        padding: ['64px', '0', '72px', '0']

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Researchers
          - Grad Students
          - Engineers
          - Administration
          - Employees
          - Visitors
          - Alumni

      # Groups rendered as compact name chips (Alumni are split by study level)
      compact_groups:
          - Visitors
          - Alumni

      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: slider
    content:
      slides:
      - title: 👋 Welcome to join our group
        content: We are eagerly seeking self-motivated, creative, hardworking people to join our team.
        align: right
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '360px'
      is_fullscreen: false
      css_class: join-us-banner
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
