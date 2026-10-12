---
title: 'Tree-KG: An expandable knowledge graph construction framework for knowledge-intensive domains'

authors:
  - Songjie Niu
  - Kaisen Yang
  - Rui Zhao
  - Yichao Liu
  - Zonglin Li
  - Hongning Wang
  - Wenguang Chen

author_symbols: ['*', '*', '', '', '', '†', '†']
author_notes:
  - Equal contribution
  - Equal contribution
  - ''
  - ''
  - ''
  - Corresponding author
  - Corresponding author
author_legend:
  - symbol: '*'
    label: Equal contribution
  - symbol: '†'
    label: Corresponding authors

date: '2025-07-01'
publishDate: '2025-07-01'
publication_types: ['paper-conference']
publication: In *Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics*
publication_short: In *ACL 2025*

abstract: In knowledge-intensive domains like scientific research, effective decisions rely on organizing and retrieving intricate data. Knowledge graphs (KGs) help by structuring entities, relations, and contextual dependencies, but building KGs in such domains is challenging due to inherent complexity, manual effort, and rapid evolution. Inspired by how humans organize knowledge hierarchically, we propose Tree-KG, an expandable framework that combines structured domain texts with advanced semantic techniques. First, Tree-KG builds a tree-like graph from textbook structures using large language models (LLMs) and domain-specific entities, creating an explicit KG. Then, through iterative expansion with flexible, predefined operators, it uncovers hidden KG while preserving semantic coherence. Experiments demonstrate that Tree-KG consistently surpasses competing methods, achieving the highest F1 scores (12-16% above the second-best), with notable performance (F1 0.81) on the Text-Annotated dataset, highlighting its effectiveness in extracting high-quality information from source texts. Additionally, Tree-KG provides superior structural alignment, domain-specific extraction, and cost-efficiency, delivering robust results with reduced token usage and adaptable, resource-conscious deployment.

featured: true

hugoblox:
  ids:
    doi: 10.18653/v1/2025.acl-long.907

links:
  - type: pdf
    url: https://aclanthology.org/2025.acl-long.907.pdf
  - type: code
    url: https://github.com/thu-pacman/Tree-KG

image:
  filename: featured.jpg
  caption: ''
  focal_point: ''
  preview_only: false
  alt_text: 'Tree-KG paper cover image'

projects: []
slides: ''
---
