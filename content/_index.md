---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
view: compact

sections:

  # Hero banner: swarm light-trail photo, headline, and two calls to action
  - block: hero
    id: hero
    content:
      title: Intelligent Robot Swarms for the Real World
      text: |-
        **Center of Swarm Navigation (CSN)** at Huzhou Institute of Zhejiang University\
        — the **FIRE** group of the **FAST Lab**.
      cta:
        label: Explore our research
        url: research/
        icon_pack: fas
        icon: robot
      cta_alt:
        label: Meet the team
        url: people/
    design:
      background:
        image:
          filename: cover.jpg
          filters:
            brightness: 0.55
          size: cover
          position: center
          parallax: false
        text_color_light: true
      spacing:
        padding: ['140px', '0', '140px', '0']

  # Mission statement
  - block: markdown
    id: about
    content:
      title: Who We Are
      subtitle: ''
      text: |-
        We are the **Center of Swarm Navigation (CSN)** at **Huzhou Institute of Zhejiang University**,
        also the **Field Intelligent Robotics Engineering (FIRE)** group of the **Field Autonomous System and Computing Lab (FAST Lab)**.
        Our mission is to create fully intelligent robot teams that are capable of operating in complex and diverse environments to tackle real-world challenges. We are fascinated by novel robotic concepts and excited about pushing the boundaries of robotics’ potential to demonstrate remarkable capabilities. More specifically, our research interests cover multi-robot cooperation, novel robot platforms, and autonomous navigation. We also have a spin-off company dedicated to accelerating the translation of our research achievements into the commercial market, solving real-world tasks, and completing the R&D cycle.
    design:
      columns: '1'

  # Research areas: mirrors the three portfolio sections on the Research page
  - block: features
    id: research-areas
    content:
      title: Research Areas
      items:
        - name: '[Multi-Robot Systems](research/)'
          icon: uav-ugv
          icon_pack: custom
          description: Research on the cooperation of multiple robots, towards swarms.
        - name: '[Novel Robot Platforms](research/)'
          icon: cubetrack
          icon_pack: custom
          description: Novel design and implementation of new robots targeting real-world challenges.
        - name: '[Autonomous Navigation](research/)'
          icon: route
          icon_pack: fas
          description: Perception, planning, and control for full autonomy in the field.

  # Latest news with built-in "All news" archive link
  - block: collection
    id: news
    content:
      title: Latest News
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
      archive:
        enable: true
        text: All news
    design:
      view: card
      columns: '1'

  # Recruiting banner (photo background with overlay text and CTA)
  - block: markdown
    id: join-us
    content:
      title: Join Us
      subtitle: ''
      text: |
        We are eagerly seeking self-motivated, creative, hardworking people to push the boundaries of field robotics with us.

        {{% cta cta_link="./contact/" cta_text="Get in touch →" %}}
    design:
      columns: '1'
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 0.45
          parallax: false
          position: center
          size: cover
        text_color_light: true
      spacing:
        padding: ['120px', '0', '120px', '0']
---
