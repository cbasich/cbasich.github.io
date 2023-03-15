---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A sampling-based optimization approach to handling environmental uncertainty
  for a planetary lander
subtitle: '{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/basich-2021-sampling.pdf" "newtab" >}}here{{< /staticref >}}.'
summary: ''
authors:
- Connor Basich
- Daniel Wang
- Joseph A Russino
- Steve Chien
- Shlomo Zilberstein
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-12-02T12:16:09-05:00
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
publishDate: '2022-12-02T17:16:09.523867Z'
publication_types:
- '0'
abstract: 'Planning for autonomous operation in unknown environments poses a number of technical challenges. The agent must ensure robustness to unknown phenomena, unpredictable variation in execution, and uncertain resources, all while maximizing its objective. These challenges are exacerbated in the context of space missions where uncertainty is often higher, long communication delays necessitate robust autonomous execution, and severely constrained computational resources limit the scope of planning techniques that can be used. We examine this problem in the context of a Europa Lander concept mission where an autonomous lander must collect valuable data and communicate that data back to Earth. We model the problem as a hierarchical task network, framing it as a utility maximization problem constrained by a monotonically decreasing energy resource. We propose a novel deterministic planning framework that uses periodic replanning and sampling-based optimization to better handle model uncertainty and execution variation, while remaining computationally tractable. We demonstrate the efficacy of our framework through simulations of a Europa Lander concept mission in which our approach outperforms several baselines in utility maximization and robustness.'
publication: '*International Conference on Automated Planning and Scheduling (ICAPS)
  PlanRob Workshop*'
---
