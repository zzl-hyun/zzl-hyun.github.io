---
widget: slider  # Use the Slider widget as this page section
weight: 10 # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 4000
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'
  
content:
  slides:
    - title: 
      content: 
      align: center
      background:
        position: right
        color: '#FFF'
        brightness: 0.7
        media: slide1.jpg
        fit: cover
        height: '30px'
      caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'


    - title: 
      content: 
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: slide2.jpg
        fit: cover
        
    - title: 
      content: contact me
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: slide3.jpg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: click
        url: ../contact/
 
---