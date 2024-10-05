---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: ''
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Machine Learning
      tag: ML
    - name: Computer Vision
      tag: CV
    - name: NLP
      tag: NLP
    - name: hi
      tag: NLP

design:
  columns: '1'
  view:  masonry #citation #compact #masonry #card #list
  flip_alt_rows: false
  background:
   
   text_color_light: true
   image: stacked-peaks.svg 
  # background:
  #   color: '#090a0b'
  #   # video:
  #   #   path: 3.mp4

---
<div class="project" style="text-align: center";><a href="project";><h1>
Project</a></div>