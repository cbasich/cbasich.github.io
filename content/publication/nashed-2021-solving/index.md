---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Solving Markov decision processes with partial state abstractions
subtitle: '{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/nashed-2021-solving.pdf" "newtab" >}}here{{< /staticref >}}.'
summary: ''
authors:
- Samer B Nashed
- Justin Svegliato
- Matteo Brucato
- Connor Basich
- Rod Grupen
- Shlomo Zilberstein
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-12-02T11:32:31-05:00
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
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-12-02T16:32:31.009231Z'
publication_types:
- '1'
abstract: 'Autonomous systems often use approximate planners that exploit state abstractions to solve large MDPs in
real-time decision-making problems. However, these planners
can eliminate details needed to produce effective behavior in
autonomous systems. We therefore propose a novel model, a
partially abstract MDP, with a set of abstract states that each
compress a set of ground states to condense irrelevant details
and a set of ground states that expand from a set of grounded
abstract states to retain relevant details. This papers offers (1)
a definition of a partially abstract MDP that (2) generalizes
its ground MDP and its abstract MDP and exhibits bounded
optimality depending on its abstract MDP along with (3) a lazy
algorithm for planning and execution in autonomous systems.
The result is a scalable approach that computes near-optimal
solutions to large problems in minutes rather than hours.'
publication: '*IEEE International Conference on Robotics and Automation (ICRA)*'
---
