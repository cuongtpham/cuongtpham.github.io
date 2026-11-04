---
title: "Projects"
date: 2026-11-03
type: landing

design:
  spacing: "0"

sections:

  # ==========================================
  # PAGE TITLE
  # ==========================================
  - block: portfolio-heading
    id: projects-overview
    content:
      title: "Projects"
      text: "Selected projects in structural engineering, computational modeling, artificial intelligence, and natural hazard risk assessment."
    design:
      css_class: portfolio-heading projects-overview
      spacing:
        padding: ["0", "0", "0", "0"]

  # ==========================================
  # PROJECT COLLECTION
  # ==========================================
  - block: collection
    id: selected-projects
    content:
      page_type: project
      count: 0
      filters:
        folders:
          - project
      offset: 0
      order: desc
    design:
      css_class: projects-list
      view: portfolio-card
      columns: 1
      fill_image: false
      show_date: false
      show_read_time: false
      spacing:
        padding: ["0", "0", "0", "0"]
---
