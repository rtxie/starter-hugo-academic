---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Efficient Lane-Level Map Building via Vehicle-Based Crowdsourcing
subtitle: ''
summary: ''
authors:
- Jiangang Shu
- Songlei Wang
- Xiaohua Jia
- Weizhe Zhang
- admin
- Hejiao Huang
tags:
- Crowdsourcing; Vehicles
categories: []
date: '2022-05-01'
lastmod: 2022-09-13T23:14:03+08:00
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
publishDate: '2022-09-13T15:14:03.048754Z'
publication_types:
- '2'
abstract: By providing rich context of lane information on roads, lane-level maps
  play a vital role in intelligent transportation systems. Since Global Positioning
  Systems (GPS) have been widely applied to vehicles, vehicle-based crowdsourcing
  offers an economical way to the lane-level map building by collecting and analyzing
  the GPS trajectories of vehicles. However, existing works cannot directly extract
  lane-level road information from raw and interleaved crowdsourcing trajectories,
  and moreover they are time-consuming and inaccurate. In this article, we propose
  a lane-level map building scheme, which can directly extract lane-level road information
  from raw crowdsourcing GPS trajectories with both efficiency and accuracy improvement.
  Consider the global similarity between trajectories, we design an efficient trajectory
  segmentation and clustering algorithm based on improved discrete Fréchet distance
  and entropy theory, which can directly and accurately deal with the interleaved
  and messy trajectories. To improve the efficiency, we employ the Least Square Estimate
  (LSE) to constrain Gaussian Mixture Model (GMM) and design an efficient and accurate
  lane-level road information extraction algorithm. Comprehensive comparative experiments
  and performance evaluation on a real-world trajectory dataset show that the proposed
  scheme outperforms the state-of-the-art works in terms of both efficiency and accuracy.
publication: '*IEEE Transactions on Intelligent Transportation Systems, vol. 23, no. 5, pp. 4049-4062,* (中科院大类一区, CCF B类期刊)'
doi: 10.1109/TITS.2020.3040728
---
