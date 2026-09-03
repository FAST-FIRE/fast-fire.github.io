---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
view: compact

sections:

  # Hero carousel: a concise lab name over auto-rotating lab photos.
  - block: slider
    id: hero
    content:
      slides:
        - title: 'CSN-ZJUHI | FAST Lab (FIRE group)'
          content: '@Huzhou Institute of Zhejiang University | Zhejiang University'
          align: center
          background:
            image:
              filename: cover.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#333'
        - title: 'CSN-ZJUHI | FAST Lab (FIRE group)'
          content: '@Huzhou Institute of Zhejiang University | Zhejiang University'
          align: center
          background:
            image:
              filename: crepes.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#333'
        - title: 'CSN-ZJUHI | FAST Lab (FIRE group)'
          content: '@Huzhou Institute of Zhejiang University | Zhejiang University'
          align: center
          background:
            image:
              filename: coni-mpc.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#333'
        - title: 'CSN-ZJUHI | FAST Lab (FIRE group)'
          content: '@Huzhou Institute of Zhejiang University | Zhejiang University'
          align: center
          background:
            image:
              filename: trofybot.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#333'
        - title: 'CSN-ZJUHI | FAST Lab (FIRE group)'
          content: '@Huzhou Institute of Zhejiang University | Zhejiang University'
          align: center
          background:
            image:
              filename: ddr-planner.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#333'
    design:
      slide_height: '480px'
      is_fullscreen: false
      # Crossfade between slides: every slide carries the same text, so the
      # text appears fixed while only the background photos change
      css_class: carousel-fade
      # Automatically transition through slides
      loop: true
      # Duration each slide is shown (in ms)
      interval: 5000

  # Latest news with built-in "All news" archive link
  - block: collection
    id: news
    content:
      title:
      subtitle:
      text:
      count: 8
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

  # Recruiting banner: keep in sync with the About Us page.
  - block: slider
    id: join-us
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
          url: contact/
    design:
      slide_height: '360px'
      is_fullscreen: false
      css_class: join-us-banner
      loop: false
      interval: 2000
---
