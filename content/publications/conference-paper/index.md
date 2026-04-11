---
title: 'Tree-KG: An expandable knowledge graph construction framework for knowledge-intensive domains'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Songjie Niu
  - Kaisen Yang
  - Rui Zhao
  - Yichao Liu
  - Zonglin Li
  - Hongning Wang
  - Wenguang Chen

#date: '2025-7'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics*
publication_short: In *ACL*

abstract: In knowledge-intensive domains like scientific research, effective decisions rely on organizing and retrieving intricate data. Knowledge graphs (KGs) help by structuring entities, relations, and contextual dependencies, but building KGs in such domains is challenging due to inherent complexity, manual effort, and rapid evolution. Inspired by how humans organize knowledge hierarchically, we propose Tree-KG, an expandable framework that combines structured domain texts with advanced semantic techniques. First, Tree-KG builds a tree-like graph from textbook structures using large language models (LLMs) and domain-specific entities, creating an explicit KG. Then, through iterative expansion with flexible, predefined operators, it uncovers hidden KG while preserving semantic coherence. Experiments demonstrate that Tree-KG consistently surpasses competing methods, achieving the highest F1 scores (12–16% above the second-best), with notable performance (F1 0.81) on the Text-Annotated dataset, highlighting its effectiveness in extracting high-quality information from source texts. Additionally, Tree-KG provides superior structural alignment, domain-specific extraction, and cost-efficiency, delivering robust results with reduced token usage and adaptable, resource-conscious deployment.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.18653/v1/2025.acl-long.907

# Custom links
links:
  - type: pdf
    url: "https://aclanthology.org/2025.acl-long.907.pdf"
  - type: code
    url: https://github.com/thu-pacman/Tree-KG
  #- type: dataset
  #  url: https://github.com/HugoBlox/kit
  #- type: slides
  #  url: https://www.slideshare.net/
  #- type: source
  #  url: https://github.com/HugoBlox/kit
  #- type: video
  #  url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
