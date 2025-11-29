---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '0rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: 'About me...'
        experience: 'Work'
        # education: ''
        interests: 'Research interests'
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      css_style: 'margin-top: 0 !important; padding-top: 0 !important;'
      # Reduce spacing
      spacing:
        padding: ['0', 0, '0.5rem', 0]
        margin: ['0', 0, '0', 0]
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy. 😃

  #   design:
  #     columns: '1'
  - block: collection
    id: projects
    content:
      title: Featured Research & Projects
      filters:
        folders:
          - projects
          - outreach
        featured_only: true
    design:
      view: article-grid
      columns: 3
      fill_image: true
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
          
        featured_only: true
    design:
      view: article-grid
      columns: 3
      fill_image: true
  - block: collection
    id: projects
    content:
      title: Upcoming Projects
      filters:
        folders:
          - planned_projects
        featured_only: true
    design:
      view: article-grid
      columns: 1
      fill_image: true
  - block: markdown
    content:
      title: '🔬 Research Areas'
      text: |-
        <div style="display: flex; flex-wrap: wrap; gap: 0.1rem; justify-content: flex-start;">
        {{< button url="/tags/machine-learning/" style="outline" size="sm" >}}Machine Learning{{< /button >}}
        {{< button url="/tags/reservoir-computing/" style="outline" size="sm" >}}Reservoir Computing{{< /button >}}
        {{< button url="/tags/complex-networks/" style="outline" size="sm" >}}Complex Networks{{< /button >}}
        {{< button url="/tags/nonlinear-dynamics/" style="outline" size="sm" >}}Nonlinear Dynamics{{< /button >}}
        {{< button url="/tags/biochemical-networks/" style="outline" size="sm" >}}Biochemical Networks{{< /button >}}
        {{< button url="/tags/cellular-information-processing/" style="outline" size="sm" >}}Cellular Information Processing{{< /button >}}
        {{< button url="/tags/explainable-ai/" style="outline" size="sm" >}}Explainable AI{{< /button >}}
        {{< button url="/tags/bio-inspired-machines/" style="outline" size="sm" >}}Bio-Inspired Machines{{< /button >}}
        </div>
    design:
      columns: '1'
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ''
  #     filters:
  #       folders:
  #         - publications
  #       exclude_featured: false
  #   design:
  #     view: citation
      
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]

  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
