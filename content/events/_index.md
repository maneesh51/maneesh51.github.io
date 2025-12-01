---
title: Recent & Upcoming Talks
# cms_exclude: true
#url: talk

type: landing

# View
# view: card

# # Optional cover image (relative to `assets/media/` folder).
# image:
#   caption: ''
#   filename: ''

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Featured Talks and Posters
      text: A selection of highlighted talks and poster presentations.
      # Conferences, workshops, and scientific outreach activities organization for *science communication*
      filters:
        folders:
          - events
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
      title: Full list of talks and posters
      text: ''
      count: 0
      filters:
        folders:
          - events
        exclude_featured: false
    design:
      view: citation
---
