---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Planning with Intermittent State Observability: Knowing When to Act Blind'
subtitle: ''
summary: ''
authors:
- Connor Basich
- John Peterson
- Shlomo Zilberstein
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-12-02T12:40:27-05:00
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
publishDate: '2022-12-02T17:40:27.331289Z'
publication_types:
- '1'
abstract: 'Contemporary planning models and methods of-
ten rely on constant availability of free state information at
each step of execution. However, autonomous systems are
increasingly deployed in the open world where state information
may be costly or simply unavailable in certain situations. Failing
to account for sensor limitations may lead to costly behavior
or even catastrophic failure. While the partially observable
Markov decision process (POMDP) can be used to model this
problem, solving POMDPs is often intractable. We introduce
a planning model called a semi-observable Markov decision
process (SOMDP) specifically designed for MDPs where state
observability may be intermittent. We propose an approach for
solving SOMDPs that uses memory states to proactively plan
for the potential loss of sensor information while exploiting
the unique structure of SOMDPs. Our theoretical analysis and
empirical evaluation demonstrate the advantages of SOMDPs
relative to existing planning models.'
publication: '*IEEE/RSJ International Conference on Intelligent Robots and Systems*'
---
