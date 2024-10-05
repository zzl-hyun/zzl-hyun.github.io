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
    - name: Other
      tag: CV


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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rainbow Text Animation</title>
    <style>
        @keyframes rgb {
            0% { color: red; }
            15% { color: orange; }
            30% { color: yellow; }
            37% { color: yellowgreen; }
            45% { color: green; }
            53% { color: cyan; }
            60% { color: blue; }
            75% { color: navy; }
            90% { color: purple; }
            99% { color: hotpink; }
            100% { color: red; }
        }
        #project {
            animation: rgb 3s linear infinite;
        }
        h1 {
            text-align: center;
        }
    </style>
</head>
<body>
    <h1><span id="project"><a href="project">Project</a></span></h1>
</body>
</html>
