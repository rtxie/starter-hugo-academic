---
# Documentation: https://wowchemy.com/docs/managing-content/

title: QoS-Aware Scheduling of Remote Rendering for Interactive Multimedia Applications in Edge Computing
subtitle: ''
summary: ''
authors:
- admin
- Junhong Fang
- Junmei Yao
- Kai Liu
- Xiaohua Jia
- Kaishun Wu

tags:
- Edge Computing; Task Scheduling; Remote Rendering
categories: []
date: '2022-12-01'
lastmod: 2022-09-13T23:14:02+08:00
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
publishDate: '2022-09-13T15:14:01.590973Z'
publication_types:
- '2'
abstract: Leveraging emerging edge computing and 5G networks, researchers proposed
  to offload the 3D rendering of interactive multimedia applications (e.g., virtual
  reality and cloud gaming) onto edge servers. For high resource utilization, multiple
  rendering tasks run in the same GPU server and compete against each other for the
  computation resource. Each task has its requirement for performance, i.e., QoS target.
  A significant problem is how to schedule tasks so that each preset QoS is met and
  the performance of all tasks are maximized. We make the following contributions.
  First, we formulate the problem into a QoS constrained max-min utility problem.
  Second, we find that using the common natural logarithm as a utility function overly
  promotes one performance but demotes another. To avoid this phenomenon, we design
  a special utility function. Third, we propose an efficient scheduling algorithm,
  consisting of a resolution adjustment algorithm and a frame rate fair scheduling
  algorithm, both of which interact with each other. The former selects resolutions
  for tasks and the latter decides which task to process. We evaluate our method with
  actual rendering data, and the simulations demonstrate that our method can effectively
  improve task performance as well as satisfy QoS simultaneously.
publication: '*IEEE Transactions on Parallel and Distributed Systems, vol. 33, no. 12, pp. 3816-3832,* (中科院大类二区, CCF A类期刊)'
doi: 10.1109/TPDS.2022.3172121
---
