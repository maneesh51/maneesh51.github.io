---
title: 'Publications'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Featured Publications
      text: A selection of highlighted research publications.
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      fill_image: true
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: collection
    content:
      title: Complete Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
