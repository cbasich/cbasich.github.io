---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Competence-Aware Path Planning Via Introspective Perception
subtitle: ''
summary: ''
authors:
- Sadegh Rabiee
- Connor Basich
- Kyle Hollins Wray
- Shlomo Zilberstein
- and Joydeep Biswas
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-12-02T11:32:32-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or mowre of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-12-02T16:32:32.485843Z'
publication_types:
- '2'
abstract: 'Robots deployed in the real world over extended periods of time need to reason about unexpected failures, learn to
predict them, and to proactively take actions to avoid future failures. Existing approaches for competence-aware planning are either model-based, requiring explicit enumeration of known failure
sources, or purely statistical, using state- and location-specific failure statistics to infer competence. We instead propose a structured
model-free approach to competence-aware planning by reasoning
about plan execution failures due to errors in perception, without
requiring a priori enumeration of failure sources or requiring
location-specific failure statistics. We introduce competence-aware
path planning via introspective perception (CPIP), a Bayesian framework to iteratively learn and exploit task-level competence in novel
deployment environments. CPIP factorizes the competence-aware
planning problem into two components. First, perception errors
are learned in a model-free and location-agnostic setting via introspective perception prior to deployment in novel environments.
Second, during actual deployments, the prediction of task-level
failures is learned in a context-aware setting. Experiments in a
simulation show that the proposed CPIP approach outperforms
the frequentist baseline in multiple mobile robot tasks, and is
further validated via real robot experiments in environments with
perceptually challenging obstacles and terrain.'
publication: '*IEEE Robotics and Automation Letters (RA-L)*'
---
