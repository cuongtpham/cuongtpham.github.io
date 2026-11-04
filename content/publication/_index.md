---
title: "Publications"
type: landing

design:
  spacing: "0"

sections:
  - block: portfolio-heading
    id: overview
    content:
      title: "Publications"
      text: ""
    design:
      css_class: portfolio-heading pubs-overview
      spacing:
        padding: ["0", "0", "0", "0"]

  - block: collection
    id: journal-articles
    content:
      title: "Peer-Reviewed Journal Articles"
      page_type: publication
      count: 0
      filters:
        folders:
          - publication
        publication_type: article-journal
        exclude_future: false
      offset: 0
      order: desc
    design:
      css_class: pubs-group
      view: citation
      spacing:
        padding: ["0", "0", "0", "0"]

  - block: collection
    id: preprints
    content:
      title: "Preprints"
      page_type: publication
      count: 0
      filters:
        folders:
          - publication
        tag: Preprint
        exclude_future: false
      offset: 0
      order: desc
    design:
      css_class: pubs-group
      view: citation
      spacing:
        padding: ["0", "0", "0", "0"]

  - block: collection
    id: manuscripts
    content:
      title: "Under Review & Submitted"
      page_type: publication
      count: 0
      filters:
        folders:
          - publication
        tag: Submitted Manuscript
        exclude_future: false
      offset: 0
      order: desc
    design:
      css_class: pubs-group
      view: citation
      spacing:
        padding: ["0", "0", "0", "0"]
---
