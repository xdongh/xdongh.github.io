---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: 2A7A96CC-00DE-47C8-9125-36EF3DC8D0A4_1_201_a.jpeg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '💧My Research☀️'
      subtitle: ''
      text: |-
        My research focuses on advancing our understanding and prediction of hydrological systems in the context of climate change and increasing human activity. With global warming and extreme events like floods, droughts, and heat waves posing growing threats to both ecosystems and communities, I aim to enhance the modeling of the hydrological cycle and assess its sensitivity to a changing climate from regional to global scales. By leveraging process-based hydrological models, Earth System Models (ESMs), and statistical approaches, my work seeks to improve the accuracy of predictions that inform critical decisions in water resources management, energy system resilience, and climate adaptation. My research not only addresses fundamental questions in hydrology but also aims to develop practical solutions that contribute to resilience in the face of evolving climate and environmental challenges.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: news
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
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

---
