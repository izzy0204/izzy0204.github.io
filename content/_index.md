---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-08-28
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Your author folder in `content/authors/`
      username: admin
      text: |-
        I'm **Isabelle Gatmaitan**, a Filipino-American second-year at the University of Florida, double-majoring in **Data Science & Economics**.  
        My work sits at the intersection of **AI/ML**, **health & accessibility**, and **urban analytics**.

        **Current projects**
        - 🧭 *Mapping Mobility Barriers*: sensor-based wheelchair accessibility mapping to power real-time, equitable wayfinding.
        - 🧪 *PFAS & Education*: modeling associations between environmental exposures and student outcomes.
        - 🗣️ *Clinical NLP (Hoarding Disorder)*: linguistic features + representation learning for healthcare insights.
        - 🩺 *Model Transparency in Dermatology*: automating compliant model cards and documentation.

        I’m passionate about **responsible AI**, **computational methods** (signal processing, computer vision, geospatial), and **translating research into impact**.
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      avatar:
        size: large
        shape: circle
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "📚 Research & Projects"
      subtitle: ""
      text: |-
        I build data-driven systems that improve health, accessibility, and policy decisions.

        **Methods I use:** Python/R, PyTorch, classical & deep learning, statistical modeling, time-series/signal processing, computer vision, geospatial analysis (QGIS/Leaflet), and reproducible science.

        **Interests:** Neuro-AI, epidemiology, clinical informatics, urban analytics, and AI governance.
    design:
      columns: "1"

  - block: collection
    id: projects-featured
    content:
      title: Featured Projects
      text: ""
      filters:
        folders:
          - project
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: projects-recent
    content:
      title: Recent Projects
      text: ""
      filters:
        folders:
          - project
        exclude_featured: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: pubs
    content:
      title: Publications & Write-ups
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Talks & Posters
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: news
    content:
      title: Updates
      subtitle: ""
      text: ""
      page_type: post
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    content:
      title: "🤝 Let’s Collaborate"
      text: |-
        I’m open to research collaborations and internships in **AI for health**, **clinical NLP**, **accessibility tech**, and **urban analytics**.

        **Contact:** [igatmaitan@ufl.edu](mailto:igatmaitan@ufl.edu)  
        **CV:** [Download PDF](uploads/resume.pdf)  
        **GitHub/Portfolio:** Add your links in `content/authors/admin/_index.md`.
    design:
      columns: "1"
---
