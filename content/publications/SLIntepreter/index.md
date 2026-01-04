---
title: 'SLInterpreter: An Exploratory and Iterative Human-AI Collaborative System for GNN-Based Synthetic Lethal Prediction'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haoran Jiang
  - Shaohan Shi
  - me
  - Jie Zheng
  - Quan Li
  

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-24T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Visualization and Computer Graphics*
publication_short: In *VIS*

abstract: Synthetic Lethal (SL) relationships, though rare among the vast array of gene combinations, hold substantial promise for targeted cancer therapy. Despite advancements in AI model accuracy, there is still a significant need among domain experts for interpretive paths and mechanism explorations that align better with domain-specific knowledge, particularly due to the high costs of experimentation. To address this gap, we propose an iterative Human-AI collaborative framework with two key components:1) Human-Engaged Knowledge Graph Refinement based on Metapath Strategies , which leverages insights from interpretive paths and domain expertise to refine the knowledge graph through metapath strategies with appropriate granularity. 2) Cross-Granularity SL Interpretation Enhancement and Mechanism Analysis, which aids experts in organizing and comparing predictions and interpretive paths across different granularities, uncovering new SL relationships, enhancing result interpretation, and elucidating potential mechanisms inferred by Graph Neural Network (GNN) models. These components cyclically optimize model predictions and mechanism explorations, enhancing expert involvement and intervention to build trust. Facilitated by SLInterpreter, this framework ensures that newly generated interpretive paths increasingly align with domain knowledge and adhere more closely to real-world biological principles through iterative Human-AI collaboration. We evaluate the framework's efficacy through a case study and expert interviews.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - VIS

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/TVCG.2024.3456325

# Custom links
links:
  - type: pdf
    url: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10693324
  - type: demo
    url: https://github.com/jianghr-shanghaitech/SLInterpreter-Demo

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---