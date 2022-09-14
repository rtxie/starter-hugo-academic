---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Minimum Transmission Data Gathering Trees for Compressive Sensing in Wireless Sensor Networks
subtitle: ''
summary: ''
authors:
- admin
- Xiaohua Jia
tags:
- Compressive Sensing; Wireless Sensor Networks; Data Gathering Trees
categories: []
date: '2011-12-01'
lastmod: 2022-09-13T23:13:52+08:00
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
publishDate: '2022-09-13T15:13:52.400005Z'
publication_types:
- '1'
abstract: Compressive sensing (CS) can reduce the number of data transmissions and
  balance the traffic load throughout networks. However, the total number of data
  transmissions required in CS method is still large. It is observed that there are
  many zero elements in the measurement matrix. In each round of data transmission
  in CS method, the sensor nodes corresponding to the zero elements in the measurement
  matrix do not have their own data to transmit. To further reduce the number of data
  transmissions in the network, we aim to compute a data gathering tree by taking
  advantages of these zero elements in the measurement matrix, such that the total
  number of data transmissions is minimized. We formulate the problem as linear programming
  with boolean variables. The problem is NP-hard. We propose heuristic algorithm to
  compute the Minimum Transmission Tree (MTT) for data gathering in CS methods. The
  MTT algorithm constructs a spanning tree by iteratively including the edge whose
  average incremental transmission cost is minimum. The simulation results demonstrate
  that our algorithm can reduce the number of transmissions significantly, compared
  with the methods using minimum spanning tree (MST), shortest path tree and the CS
  method with nonzero measurement coefficient using MST.
publication: '*2011 IEEE Global Telecommunications Conference - GLOBECOM 2011*'
doi: 10.1109/GLOCOM.2011.6134304
---
