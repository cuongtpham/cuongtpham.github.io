
---
# Homepage
title: ""
date: 2025-08-27
type: landing

design:
  spacing: "4rem"

sections:

  # ==========================================
  # 1. PROFESSIONAL INTRODUCTION
  # ==========================================
  - block: resume-biography-3
    id: home
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: /uploads/resume.pdf
    design:
      css_class: dark
      avatar:
        size: medium
        shape: circle
      background:
        color: black
        image:
          filename: background_black.jpg
          filters:
            brightness: 0.75
          size: cover
          position: center
          parallax: false

  # ==========================================
  # 2. FEATURED WORK
  # ==========================================
  - block: collection
    id: projects
    content:
      title: Featured Work
      subtitle: ""
      text: "Selected engineering, computational, and research projects."
      page_type: project
      count: 3
      archive:
        enable: true
        link: /projects/
        text: View all projects
      filters:
        exclude_featured: false
        exclude_future: true
      offset: 0
      order: desc
    design:
      view: portfolio-card
      columns: 3
      spacing:
        padding: [4rem, 0, 0, 0]

  # ==========================================
  # 3. SELECTED PUBLICATIONS
  # ==========================================
  - block: collection
    id: papers
    content:
      title: Selected Publications
      subtitle: ""
      text: "Selected journal articles, preprints, and submitted research contributions."
      page_type: publication
      count: 5
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: true
      offset: 0
      order: desc
    design:
      view: citation
      spacing:
        padding: [4rem, 0, 0, 0]

  # ==========================================
  # 4. PROFESSIONAL UPDATES
  # ==========================================
  - block: collection
    id: updates
    content:
      title: Professional Updates
      subtitle: ""
      text: "Recent milestones, publications, and professional activities."
      page_type: post
      count: 3
      filters:
        exclude_featured: false
        exclude_future: true
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [4rem, 0, 0, 0]
---
