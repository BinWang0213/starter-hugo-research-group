---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 10000

content:
  slides:
    - title: Home of Bin Research Group 
      content: 'Center of Innovation for Particle-laden Flow through Fractured Porous Media'
      align: left
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: lab1_slide.jpg
    - title: Digital rock physics
      content: 'Explore fluid and particle dyanmics at the pore-scale!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: research2.jpg
    - title: Welcome to join us!
      content: 'PhD and Post-doc positions are availabe!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.7
        media: teams.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
