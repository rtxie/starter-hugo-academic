---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Adaptive Online Decision Method for Initial Congestion Window in 5G Mobile
  Edge Computing Using Deep Reinforcement Learning
subtitle: ''
summary: ''
authors:
- admin
- Xiaohua Jia
- Kaishun Wu
tags:
- Congestion Control; Edge Computing; Deep Reinforcement Learning
categories: []
date: '2020-02-01'
lastmod: 2022-09-13T23:13:49+08:00
featured: true
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
publishDate: '2022-09-13T15:13:48.429613Z'
publication_types:
- '2'
abstract: Mobile edge computing provides users with low response time and avoids unnecessary
  data transmission. Due to the deployment of 5G, the emerging edge systems can provide
  gigabit bandwidth. However, network protocols have not evolved together. In TCP,
  the initial congestion window (IW) is such a low value that most short flows still
  stay in slow start phase when finishing, and do not fully utilize available bandwidth.
  Naively increasing IW may result in congestion, which causes long latency. Moreover,
  since the network environment is dynamic, we have a challenging problem-how to adaptively
  adjust IW such that flow completion time is optimized, while congestion is minimized.
  In this paper, we propose an adaptive online decision method to solve the problem,
  which learns the best policy using deep reinforcement learning stably and fast.
  In addition, we propose an approach to further improve the performance by supervised
  learning, using data collected during online learning. We also propose to adopt
  SDN to address the challenges in implementing our method in MEC systems. To evaluate
  our method, we build an MEC simulator based on ns3. Our simulations demonstrate
  that our method performs better than existing methods. It can effectively reduce
  FCT with little congestion caused.
publication: '*IEEE Journal on Selected Areas in Communications, vol. 38, no. 2, pp. 389-403,* (中科院大类一区, CCF A类期刊)'
doi: 10.1109/JSAC.2019.2959187
---
