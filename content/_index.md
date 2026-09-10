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
      title: Research Focus
      subtitle: NLP, biomedical AI, and computational structural biology
      text: |-
        I build machine-learning systems for two complementary research areas. In **clinical and social NLP**, I study LLM evaluation, demographic information extraction, and the contextual interpretation of mental-health discourse. In **biomedical image analysis**, I work with cryo-EM and cryo-ET data to develop reproducible pipelines for segmentation, model-map validation, and structural analysis.

        My goal is to develop careful, interpretable methods that connect strong computational modeling with meaningful scientific questions.
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