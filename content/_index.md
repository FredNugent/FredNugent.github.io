---
# Leave the homepage title empty to use the site title
title: TSO Homepage
date: 2025  
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image: soundwave
          # Add your image background to `assets/media/`.
          filename: 
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "15"
          description: |
            Homeless
        - statistic: "1,000+"
          description: |
            Billionaires
        - statistic: "78"
          description: |
            Children Molested 
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
        The Threefold Social Order as laid our by Dr. Rudolf Steiner is a progressive Social, Poltical and Economic framework that further develops the nascent threefold structuring seen in countries like the United States and France. This podcast will explore the esoteric basis for these systems and ask questions about what it means to be a human being living amongst other human beings. We'll have some fun along the way, and if smiled upon by providence, answer a few metaphysical questions to boot.
       
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
