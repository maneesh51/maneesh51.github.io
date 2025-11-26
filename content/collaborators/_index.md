---
title: 'Collaboration Circle'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: markdown
    content:
      title: Collaboration Circle
      subtitle: ''
      text: |-
        Meet my amazing collaborators! Click on a tile to explore projects and publications we've worked on together.
    design:
      columns: '1'
  
  - block: collection
    content:
      title: ''
      filters:
        folders:
          - collaborators
    design:
      view: collaborator-grid
      columns: 3
---
