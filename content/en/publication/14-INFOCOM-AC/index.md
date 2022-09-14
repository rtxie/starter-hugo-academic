---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Enabling Efficient Access Control with Dynamic Policy Updating for Big Data
 in the Cloud
subtitle: ''
summary: ''
authors:
- Kan Yang
- Xiaohua Jia
- Kui Ren
- admin
- Liusheng Huang
tags:
- Access Control; Cloud Computing
categories: []
date: '2014-04-01'
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
abstract: Due to the high volume and velocity of big data, it is an effective option
  to store big data in the cloud, because the cloud has capabilities of storing big
  data and processing high volume of user access requests. Attribute-Based Encryption
  (ABE) is a promising technique to ensure the end-to-end security of big data in
  the cloud. However, the policy updating has always been a challenging issue when
  ABE is used to construct access control schemes. A trivial implementation is to
  let data owners retrieve the data and re-encrypt it under the new access policy,
  and then send it back to the cloud. This method incurs a high communication overhead
  and heavy computation burden on data owners. In this paper, we propose a novel scheme
  that enabling efficient access control with dynamic policy updating for big data
  in the cloud. We focus on developing an outsourced policy updating method for ABE
  systems. Our method can avoid the transmission of encrypted data and minimize the
  computation work of data owners, by making use of the previously encrypted data
  with old access policies. Moreover, we also design policy updating algorithms for
  different types of access policies. The analysis show that our scheme is correct,
  complete, secure and efficient.
publication: '*IEEE INFOCOM 2014 - IEEE Conference on Computer Communications*'
doi: 10.1109/INFOCOM.2014.6848142
---
