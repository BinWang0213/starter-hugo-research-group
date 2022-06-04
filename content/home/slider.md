---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '350px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 10000

content:
  slides:
    - title: Home of Bin Research Group 
      content: 'Center of Innovation for Particle-laden Flow through Porous Media'
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: lab1.jpg
    - title: Digital rock physics
      content: 'Explore fluid and particle dyanmics at the pore-scale!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: research2.png
    - title: Welcome to join us!
      content: 'PhD position is availabe!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: teams.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
