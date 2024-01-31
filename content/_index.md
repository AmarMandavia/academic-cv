---
# Leave the homepage title empty to use the site title
title:
date: 2024-01-31
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename:  10.25 x 13.25 F.JPG
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        I am a Medical Informatics postdoctoral fellow at the Boston VA Healthcare system and a Catalyst fellow at MIT. My primary program of research takes a critical approach to improving the measurement, classification, and identification of digital phenotypes for adverse health outcomes across individual, interpersonal, and community levels. My secondary line of research is concentrated on the development of a clinical decision-making systems that capitalize on common factors across psychotherapeutic processes to aid in personalized psychotherapy treatment selection. 

        **Interest:** 
        - Risk Predicition
        - Digital Theraputics
        - Healthcare Innovation
        - Problem Areas: 
          - Opioid Crisis
          - Suicide
          - Pscyhosis
          - HIV
          - PTSD
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: event
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
---
