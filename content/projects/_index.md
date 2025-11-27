---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Featured Research & Projects
      text: Here are a selection of selected research projects, libraries and courses that I have worked on over the years.
      filters:
        folders:
          - projects
    design:
      view: list
      fill_image: true
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: collection
    content:
      title: Planned Research & Projects
      text: Here are a selection of selected research projects, libraries and courses that I have worked on over the years.
      count: 0
      filters:
        folders:
          - planned_projects
    design:
      view: article-grid
      fill_image: true
      columns: 1
      show_date: false
      show_read_time: false
      show_read_more: false
---
