---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Supporting Seamless Virtual Machine Migration via Named Data Networking in
  Cloud Data Center
subtitle: ''
summary: ''
authors:
- admin
- Yonggang Wen
- Xiaohua Jia
- Haiyong Xie
tags:
- Cloud Computing; Virtual Machine Migration
categories: []
date: '2015-12-01'
lastmod: 2022-09-13T23:13:46+08:00
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
publishDate: '2022-09-13T15:13:45.886570Z'
publication_types:
- '2'
abstract: Virtual machine migration has been touted as one of the crucial technologies
  in improving data center efficiency, such as reducing energy cost and maintaining
  load balance. However, traditional approaches could not avoid the service interruption
  completely. Moreover, they often result in longer delay and are prone to failures.
  In this paper, we leverage the emerging named data networking (NDN) to design an
  efficient and robust protocol to support seamless virtual machine migration in cloud
  data center. Specifically, virtual machines (VMs) are named with the services they
  provide. Request routing is based on service names instead of IP addresses that
  are normally bounded with physical machines. As such, services would not be interrupted
  when migrating supported VMs to different physical machines. We further analyze
  the performance of our proposed NDN-based VM migration protocol, and optimize its
  performance via a load balancing algorithm. Our extensive evaluations verify the
  effectiveness and the efficiency of our approach and demonstrate that it is interruption-free.
publication: '*IEEE Transactions on Parallel and Distributed Systems, vol. 26, no. 12, pp. 3485-3497* (中科院小类二区期刊)'
doi: 10.1109/TPDS.2014.2377119
url_code: 'https://github.com/dorisxinyi/NDN-4-VMM'
---
