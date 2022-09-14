---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Energy Saving Virtual Machine Allocation in Cloud Computing
subtitle: ''
summary: ''
authors:
- admin
- Xiaohua Jia
- Kan Yang
- Bo Zhang
tags:
- Cloud Computing; Virtual Machine Allocation
categories: []
date: '2013-07-01'
lastmod: 2022-09-13T23:13:49+08:00
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
publishDate: '2022-09-13T15:13:49.099042Z'
publication_types:
- '1'
abstract: In the data center, a server can work in either active state or power-saving
  state. The power consumption in the power-saving state is almost 0, thus it is always
  desirable to allocate as many VMs as possible to some active servers and leave the
  rest to power-saving state in order to reduce the energy consumption of the data
  center. In this paper, we study such a VM allocation problem. Given a set VMs and
  a set of servers in a data center, each VM has a resource demand (CPU, memory, storage)
  and a starting time and a finishing time, and each server has resource capacity.
  There is an additional energy cost for a server to switch from power-saving state
  to active state. The servers are non-homogeneous. The problem of our concern is
  to allocate the VMs onto servers, such that the VMs resource demands can be met
  and the total energy consumption of servers is minimized. The problem is formulated
  as a boolean integer linear programming problem. A heuristic algorithm is proposed
  to solve the problem. Extensive simulations have been conducted to demonstrate our
  proposed method can significantly save the energy consumption in data centers.
publication: '*2013 IEEE 33rd International Conference on Distributed Computing Systems
  Workshops*'
doi: 10.1109/ICDCSW.2013.37
---
