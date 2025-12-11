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

  - block: markdown
    id: news
    content:
      title: '📰 Latest News'
      text: |-
        <div class="news-container" style="max-height: 280px; overflow-y: auto; padding-right: 0px; border-left: -3px solid var(--primary); padding-left: 0px; font-size: 0.85rem;">
          <ul style="list-style: none; padding: 0; margin: 0;">
            <li style="margin-bottom: 0px; padding-bottom: 12px; border-bottom: 1px solid var(--border-color);">
              <span style="color: var(--muted-foreground); font-size: 0.75rem;">10 Dec 2025</span><br>
              🎤 Presented “Hierarchical Reasoning Model„ By Sapient Intelligence, Singapore, 2025 in <strong>ML-Journal Club</strong> at CPS-ME, TU Berlin</em>.
            </li>
            <li style="margin-bottom: 0px; padding-bottom: 12px; border-bottom: 1px solid var(--border-color);">
              <span style="color: var(--muted-foreground); font-size: 0.75rem;">Sep 2025</span><br>
              🎤 Invited as <strong>Keynote Speaker</strong> at the <a href="/events/gacm-2025/">11th GACM Colloquium</a> in TU Braunschweig to present on <em>Foundations, Theory and Applications of Reservoir Computing</em>.
            </li>
            <li style="margin-bottom: 12px; padding-bottom: 12px; border-bottom: 1px solid var(--border-color);">
              <span style="color: var(--muted-foreground); font-size: 0.75rem;">Aug 2025</span><br>
              📄 New paper published in <em>Chaos</em>: <a href="/publications/chaos-node-pruning/">Task-specific node pruning enhances computational efficiency of reservoir computing networks</a>.
            </li>
            <li style="margin-bottom: 12px; padding-bottom: 12px; border-bottom: 1px solid var(--border-color);">
              <span style="color: var(--muted-foreground); font-size: 0.75rem;">Jun 2025</span><br>
              📊 Poster presentation at the <a href="/events/pks-workshop-2025/">PKS Workshop on Large-scale Dynamical Systems</a> at MPI Dresden on <em>Efficient Network Generation with Performance-Dependent Evolution</em>.
            </li>
            <li style="margin-bottom: 12px; padding-bottom: 12px; border-bottom: 1px solid var(--border-color);">
              <span style="color: var(--muted-foreground); font-size: 0.75rem;">Dec 2024</span><br>
              📄 New paper in <em>Nonlinear Dynamics</em>: <a href="/publications/reservoir-computing-2024/">Predicting multi-parametric dynamics using reservoir computing and minimal data</a>.
            </li>
            <li style="margin-bottom: 12px; padding-bottom: 12px; border-bottom: 1px solid var(--border-color);">
              <span style="color: var(--muted-foreground); font-size: 0.75rem;">Oct 2024</span><br>
              🚀 Launched <a href="/projects/pytorch/">PyReCo</a> - a Python library for Reservoir Computing now available on PyPI.
            </li>
            <li style="margin-bottom: 12px; padding-bottom: 12px; border-bottom: 1px solid var(--border-color);">
              <span style="color: var(--muted-foreground); font-size: 0.75rem;">Mar 2024</span><br>
              🎤 Presented at the <a href="/events/gamm-2024/">94th GAMM Annual Meeting</a> in Magdeburg, Germany.
            </li>
            <li style="margin-bottom: 0; padding-bottom: 0; border-bottom: none;">
              <span style="color: var(--muted-foreground); font-size: 0.75rem;">Apr 2023</span><br>
              🔬 Joined the <a href="/projects/dfg-spp-2353/">DFG SPP 2353 Project</a> on Dynamics-Informed Reservoir Computing at TU Berlin.
            </li>
          </ul>
        </div>
    design:
      columns: '0'
      spacing:
        padding: ['0.0rem', 0, '0.0rem', 0]


  - block: collection
    id: projects
    content:
      title: Featured Research & Projects
      filters:
        folders:
          - projects
          - outreach
          - events

        featured_only: true
    design:
      view: article-grid
      columns: 3
      fill_image: true
      spacing:
        padding: ['0.0rem', 1, '0.0rem', 0]

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
      spacing:
        padding: ['0.0rem', 0, '0.0rem', 0]
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
      spacing:
        padding: ['0.0rem', 0, '0.0rem', 0]
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
      spacing:
        padding: ['0.0rem', 0, '0.0rem', 0]
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
