---
title: 'CV'
date: 2025-07-29
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: markdown
    content:
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Télécharger CV
        url: uploads/fr.pdf
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: resume-skills
    content:
      title: Compétences & Hobbies
      username: admin
    design:
      show_skill_percentage: false
  #- block: resume-awards
  #  content:
  #    title: Awards
  #    username: admin
  - block: resume-languages
    content:
      title: Langues
      username: admin
---
