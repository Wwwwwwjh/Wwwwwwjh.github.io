---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: '3rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: junhao-wu
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: /uploads/profile.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: background.jpg
        
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: languages
    content:
      title: Languages
      username: junhao-wu
  - block: experience
    content:
      username: junhao-wu
    design:
      # Hugo date format
      date_format: 'January 2026'
      # Education or Experience section first?
      is_education_first: false
  - block: portfolio
    content:
      title: Projects
      subtitle: ""
      count: 5
      filters:
        tags: []
        categories: []
        exclude_featured: false
    design:
      view: compact
      columns: 1
      full_width: true

  - block: collection
    content:
      title: Events
      subtitle: ""
      # 告诉它读取哪类内容
      page_type: events
      # 显示数量
      count: 5
      # 过滤
      filters:
        tags: []
        categories: []
        featured_only: false
    design:
      view: compact
      columns: 1
      full_width: true

  - block: collection
    content:
      title: Slides
      subtitle: ""
      page_type: slides
      count: 5
      filters:
        folders:
          - slides
    design:
      view: card
      columns: 1
      full_width: true
  - block: skills
    content:
      title: Skills & Hobbies
      username: junhao-wu
  - block: awards
    content:
      title: Awards
      username: junhao-wu
---
