---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: about-biography
    content:
      username: ak-purohit
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'Biography'
        education: 'Education'
        interests: 'Interests'
    design:
      avatar:
        size: medium
        shape: square

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Dr. Aditya Kumar Purohit is a human–computer interaction researcher whose work focuses on trustworthy AI, digital wellbeing, and large language models in society.
        
        His research explores how technology can be designed to foster healthier and more mindful digital experiences.

        Please reach out to collaborate 😃
    design:
      columns: '1'

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
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 5
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
