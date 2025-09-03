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
    id: fapapers
    content:
      title: Publications en Premier Auteur
      
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: article-grid
      columns: 2
       
---
