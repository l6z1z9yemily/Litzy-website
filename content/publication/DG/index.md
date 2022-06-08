---
title: Domain Generalization using Pretrained Models without Fine-tuning
publication_types:
  - "3"
authors:
  - admin
  - Kan Ren
  - Xinyang Jiang
  - Bo Li
  - Haipeng Zhang
  - Dongsheng Li
doi: ""
abstract: Fine-tuning pretrained models is a common practice in domain
  generalization (DG) tasks. However, fine-tuning is usually computationally
  expensive due to the ever-growing size of pretrained models. More importantly,
  it may cause over-fitting on source domain and compromise their generalization
  ability as shown in recent works. Generally, pretrained models possess some
  level of generalization ability and can achieve decent performance regarding
  specific domains and samples. However, the generalization performance of
  pretrained models could vary significantly over different test domains even
  samples, which raises challenges for us to best leverage pretrained models in
  DG tasks. In this paper, we propose a novel domain generalization paradigm to
  better leverage various pretrained models, named specialized ensemble learning
  for domain generalization (SEDGE). It first trains a linear label space
  adapter upon fixed pretrained models, which transforms the outputs of the
  pretrained model to the label space of the target domain. Then, an ensemble
  network aware of model specialty is proposed to dynamically dispatch proper
  pretrained models to predict each test sample. Experimental studies on several
  benchmarks show that SEDGE achieves significant performance improvements
  comparing to strong baselines including state-of-the-art method in DG tasks
  and reduces the trainable parameters by ~99% and the training time by ~99.5%.
draft: false
tags:
  - Domain Generalization
  - Ensemble Learning
categories:
  - Domain Generalization
  - Ensemble Learning
projects: []
slides: ""
url_pdf: https://arxiv.org/pdf/2203.04600.pdf
image:
  caption: The comparison of the average performance (x-axis, the higher the
    better) of different algorithms, their training time (y-axis, the smaller
    the better), and the number of their training parameters (the size of the
    marker). We also list the corresponding information (number of training
    parameters, test accuracy, training time) of each algorithm.
  focal_point: ""
  preview_only: false
  filename: sedge.png
summary: A new domain generalization paradigm that leverages pretrained models
  better by dynamically dispatching specialized pretrained model ensemble to
  predict each test sample.
url_dataset: ""
url_project: ""
publication: In *arXiv*
publication_short: ""
url_source: ""
url_video: ""
featured: false
date: 2022-06-06T16:36:26.436Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
