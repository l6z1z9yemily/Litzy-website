---
title: Semantics from Look and Sound: Learning Chinese Character Representations from Function-Specific Components and Pronunciations
authors:
  - Hang Hu
  - admin
  - Kai Peng
  - Shuai Ling
  - and Haipeng Zhang
author_notes: []
# doi: https://doi.org/10.1016/j.ipm.2022.102892
# publication_short: submitted to CIKM'22
abstract: >-
  Learning the embeddings of Chinese characters has attracted intense attention and has benefited various downstream NLP tasks. Unlike English, each Chinese character serves as a unit of semantics, with contributions from its glyph and pronunciation. Glyphs are formed by semantic and phonetic components. Previous studies exploit shared components between characters to capture the semantic connections at the character level, enhancing their embedding quality. However, they do not distinguish semantic and phonetic components. This on one hand oversimplifies the information delivered in a component as unitary and on other hand, overlooks the phonetic components’ relations with pronunciations in delivering sound-related information. In this paper, we propose a Semantic-Phonetic-Pronunciation Graph Attention (SPPGAT) model based on hierarchical attention, including node-level, sound-level, and aggregation-level attentions. Specifically, the node-level attention learns the importance between a node and its type-specific one-hop neighbors, while the sound-level attention and the aggregation-level attention jointly learn the importance value of information from each type of property. Experiments show that our model surpasses state-of-the-art approaches in common NLP tasks including named entity recognition, part of speech tagging, word segmentation, and text classification.
tags:
  - Natural Language Processing
categories:
  - Natural Language Processing
projects: []
slides: ""
url_pdf: ""
publication_types:
  - "2"
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: ""
summary: A hierarchical-attention-based model which distinguishes the importance of function-specific information at sub-character level.
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
publication: submitted to CIKM'22
featured: false
date: 2022-06-06T16:16:00.649Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
