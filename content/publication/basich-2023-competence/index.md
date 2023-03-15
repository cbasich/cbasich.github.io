---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Competence-Aware Systems
subtitle: ''
summary: ''
authors:
  - Connor Basich
  - Justin Svegliato
  - Kyle H. Wray
  - Stefan Witwicki
  - Joydeep Biswas
  - and Shlomo Zilberstein
tags: []
categories: []
date: '2023-01-01'
lastmod: 2022-12-02T12:16:10-05:00
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
publishDate: '2022-12-02T17:16:09.932049Z'
publication_types:
- '2'
abstract: 'Building autonomous systems for deployment in the open world has been a longstanding objective in both artificial intelligence
and robotics. The open world, however, presents challenges that question some of the assumptions often made in contemporary AI
models. Autonomous systems that operate in the open world face complex, non-stationary environments wherein enumerating all
situations the system may face over the course of its deployment is intractable. Nevertheless, these systems are expected to operate
safely and reliably for extended durations. Consequently, AI systems often rely on some degree of human assistance to mitigate
risks while completing their tasks, and are hence better treated as semi-autonomous systems. In order to reduce unnecessary reliance
on humans and optimize autonomy, we propose a novel introspective planning model—competence-aware systems (CAS)—that
enables a semi-autonomous system to reason about its own competence and allowed level of autonomy by leveraging human
feedback or assistance. A CAS learns to adjust its level of autonomy based on experience and interactions with a human authority
so as to reduce improper reliance on the human and optimize the degree of autonomy it employs in any given circumstance. To
handle situations in which the initial CAS model has insufficient state information to properly discriminate feedback received from
humans, we introduce a methodology called iterative state space refinement that gradually increases the granularity of the state
space online. The approach exploits information that exists in the standard CAS model and requires no additional input from the
human. The result is an agent that can more confidently predict the correct feedback from the human authority in each level of
autonomy, enabling it learn its competence in a larger portion of the state space.'
publication: '*Artificial Intelligence*'
---
