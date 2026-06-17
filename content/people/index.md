---
title: People
date: 2022-10-24

type: landing

sections:
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

      # Groups rendered as a compact row of name chips (no photo/role/social)
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
            filename: welcome.jpg
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
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---