---
title: ""
date: 2026-09-10
type: landing

design:
  spacing: "5rem"

sections:
  # Biography and introduction
  - block: resume-biography-3
    content:
      username: admin
      text: ""
    design:
      background:
        color: "#f8fafc"

  # Research overview
  - block: markdown
    content:
      title: Research
      subtitle: Machine learning for language, health, and biological structure
      text: |-
        My research brings together **natural language processing**, **biomedical AI**, and **scientific image analysis**.

        - **Clinical and Social NLP** — I develop annotation and machine-learning methods for studying mental-health discourse, demographic information, clinical risk factors, and the contextual meaning of substance-use references.

        - **Large Language Models** — I evaluate prompting and classification approaches, emphasizing reliability, interpretability, and performance in low-resource settings.

        - **Cryo-EM and Cryo-ET Analysis** — I build reproducible pipelines for protein structure validation, β-strand centerline analysis, and deep-learning-based filament segmentation.

        Across these areas, my goal is to create computational methods that are technically rigorous, scientifically meaningful, and useful for interdisciplinary research.
    design:
      columns: "1"
      background:
        color: "#ffffff"

  # Featured publications
  - block: collection
    id: papers
    content:
      title: Selected Publications
      subtitle: ""
      text: Peer-reviewed research spanning clinical NLP, language-model evaluation, low-resource language processing, and cryo-electron tomography.
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      background:
        color: "#f8fafc"

  # Research projects
  - block: block: collection
    id: projects
    content:
      title: Research Projects
      subtitle: ""
      text: Selected projects in language technology, biomedical AI, and computational structural biology.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 2
      background:
        color: "#ffffff"

  # Contact section
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: Research collaboration and academic opportunities
      text: |-
        I am interested in research collaborations involving **clinical NLP**, **large language models**, **low-resource language processing**, and **cryo-EM/cryo-ET analysis**.

        Email: [fd02629@georgiasouthern.edu](mailto:fd02629@georgiasouthern.edu)

        [LinkedIn](https://www.linkedin.com/in/farhan-noor-dehan-6554ba21a/) · [GitHub](https://github.com/Dehan001) · [Google Scholar](https://scholar.google.com/citations?user=neAnNCwAAAAJ&hl=en)
    design:
      columns: "1"
      background:
        color: "#f8fafc"
---