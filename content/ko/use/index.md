---
# Page title
title: My page
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: section-1
    content:
      title: Section 1
      subtitle: A subtitle
      text: hello {{< video src="my_video.mp4" controls="yes" >}}
      # Display content from the `content/post/` folder
      filters:
        folders:
          - post
    design:
        background:
            # Choose colors such as from https://html-color-codes.info
            gradient_start: '#4bb4e3'
            gradient_end: '#2b94c3'
            # The gradient angle from 0-360 degrees
            gradient_angle: 180
            # Text color (true=light, false=dark, or remove for the dynamic theme color).
            text_color_light: true

    
---

hello