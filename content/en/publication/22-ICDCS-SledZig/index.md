---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SledZig: Boosting Cross-Technology Coexistence for Low-Power Wireless Devices'
subtitle: ''
summary: ''
authors:
- Junmei Yao
- Haolang Huang
- admin
- Xiaolong Zheng
- Kaishun Wu
tags:
- Cross-Technology Communications; Wireless Networks
categories: []
date: '2022-07-10'
lastmod: 2022-09-13T23:13:48+08:00
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
publishDate: '2022-09-13T15:13:47.729185Z'
publication_types:
- '1'
abstract: With the rapid growth of Internet of Things, the number of heterogeneous wireless devices working in the same frequency band increases dramatically, leading to severe crosstechnology interference. To enable coexistence, researchers have proposed a large number of mechanisms to manage interference. However, existing mechanisms have severe modifications in either the physical or MAC (medium access control) layers, making them hard to be deployed on commercial devices. In this paper, we design and implement SledZig to boost crosstechnology coexistence for low-power devices through both enabling more transmission opportunities and avoiding interference. SledZig is fully compatible with the standard in both physical and MAC layers. It decreases the WiFi signal power on the channel of low-power devices while keeps the WiFi transmission power unchanged, through making constellation points in the overlapped subcarriers have the lowest power, which can be achieved by just encoding the WiFi payload. We implement SledZig on hardware testbed and evaluate its performance under different settings. Experiment results show that SledZig can effectively increase ZigBee transmissions and improve its performance over a WiFi channel under various WiFi data traffic, with as low as 6.94% WiFi throughput loss.
publication: '*IEEE ICDCS 2022 - 42nd IEEE International Conference on Distributed Computing Systems* (CCF B类会议, Acceptance rate:19.9%)'
doi: 
---
