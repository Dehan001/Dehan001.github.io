---
title: Investigating the Effectiveness of Graph-based Algorithm for Bangla Text Classification
authors:
- Farhan Dehan
- Md Fahim
- Amin Ahsan Ali
- M Ashraful Amin
- Akmmahbubur Rahman
date: '2023-12-01'
publishDate: '2024-10-17T08:19:38.248305Z'
publication_types:
- paper-conference
publication: '*Proceedings of the First Workshop on Bangla Language Processing (BLP-2023)*'
doi: 10.18653/v1/2023.banglalp-1.12
abstract: In this study, we examine and analyze the behavior of several graph-based
  models for Bangla text classification tasks. Graph-based algorithms create heterogeneous
  graphs from text data. Each node represents either a word or a document, and each
  edge indicates relationship between any two words or word and document. We applied
  the BERT model and different graph-based models including TextGCN, GAT, BertGAT,
  and BertGCN on five different datasets including SentNoB, Sarcasm detection, BanFakeNews,
  Hate speech detection, and Emotion detection datasets for Bangla text. BERT′s model
  bested the TextGCN and the GAT models by a large difference in terms of accuracy,
  Macro F1 score, and weighted F1 score. BertGCN and BertGAT are shown to outperform
  standalone graph models and BERT model. BertGAT excelled in the Emotion detection
  dataset and achieved a 1%-2% performance boost in Sarcasm detection, Hate speech
  detection, and BanFakeNews datasets from BERT′s performance. Whereas, BertGCN outperformed
  BertGAT by 1% for SetNoB, and BanFakeNews datasets while beating BertGAT by 2% for
  Sarcasm detection, Hate Speech, and Emotion detection datasets. We also examined
  different variations in graph structure and analyzed their effects.
links:
- name: URL
  url: https://aclanthology.org/2023.banglalp-1.12
---
<!-- ---
title: "An example preprint / working paper"
authors:
- admin
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Large Language Models

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
