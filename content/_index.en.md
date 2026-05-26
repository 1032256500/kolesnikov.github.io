---
title: ''
summary: ''
date: 2022-10-24
type: landing
translationKey: home

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About
        education: Education
        interests: Interests
    design:
      background:
        gradient_mesh:
          enable: true

      name:
        size: md

      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '📚 About Me'
      subtitle: ''
      text: |-
        I am a beginner developer and entrepreneur. I am interested in software architecture, backend development, process automation, artificial intelligence, and cybersecurity.

        I work on the FTM project together with my team. This project helps me apply technical, managerial, and entrepreneurial skills in practice.

        This website contains information about my education, interests, skills, experience, projects, and study-related publications.
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
      title: Recent & Upcoming Events
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
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
