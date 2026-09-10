---
title: ""
date: 2026-09-10
type: landing

design:
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
    design:
      background:
        color: "#f8fafc"

  - block: markdown
    content:
      title: Research
      subtitle: Machine learning for language, health, and biological structure
      text: |-
        My research brings together **natural language processing**, **biomedical AI**, and **scientific image analysis**.

        - **Clinical and Social NLP** — I develop annotation and machine-learning methods for studying mental-health discourse, demographic information, clinical risk factors, and the contextual meaning of substance-use references.

        - **Large Language Models** — I evaluate prompting and classification approaches, with an emphasis on reliability, interpretability, and low-resource settings.

        - **Cryo-EM and Cryo-ET Analysis** — I build reproducible pipelines for protein structure validation, β-strand centerline analysis, and deep-learning-based filament segmentation.

        Across these areas, my goal is to create computational methods that are technically rigorous, scientifically meaningful, and useful for interdisciplinary research.
    design:
      columns: "1"
      background:
        color: "#ffffff"

  - block: collection
    id: papers
    content:
      title: Selected Publications
      text: Peer-reviewed work spanning clinical NLP, language-model evaluation, low-resource NLP, and cryo-electron tomography.
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      background:
        color: "#f8fafc"

  - block: collection
    content:
      title: All Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      background:
        color: "#ffffff"

  - block: collection
    id: projects
    content:
      title: Research Projects
      text: Current and selected research directions.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 2
      background:
        color: "#f8fafc"
---