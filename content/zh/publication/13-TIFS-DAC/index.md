---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'DAC-MACS: Effective Data Access Control for Multiauthority Cloud Storage Systems'
subtitle: ''
summary: ''
authors:
- Kan Yang
- Xiaohua Jia
- Kui Ren
- Bo Zhang
- admin
tags:
- Access Control; Cloud Computing
categories: []
date: '2013-11-01'
lastmod: 2022-09-13T23:13:47+08:00
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
publishDate: '2022-09-13T15:13:46.506410Z'
publication_types:
- '2'
abstract: Data access control is an effective way to ensure data security in the cloud.
  However, due to data outsourcing and untrusted cloud servers, the data access control
  becomes a challenging issue in cloud storage systems. Existing access control schemes
  are no longer applicable to cloud storage systems, because they either produce multiple
  encrypted copies of the same data or require a fully trusted cloud server. Ciphertext-policy
  attribute-based encryption (CP-ABE) is a promising technique for access control
  of encrypted data. However, due to the inefficiency of decryption and revocation,
  existing CP-ABE schemes cannot be directly applied to construct a data access control
  scheme for multiauthority cloud storage systems, where users may hold attributes
  from multiple authorities. In this paper, we propose data access control for multiauthority
  cloud storage (DAC-MACS), an effective and secure data access control scheme with
  efficient decryption and revocation. Specifically, we construct a new multiauthority
  CP-ABE scheme with efficient decryption, and also design an efficient attribute
  revocation method that can achieve both forward security and backward security.
  We further propose an extensive data access control scheme (EDAC-MACS), which is
  secure under weaker security assumptions.
publication: '*IEEE Transactions on Information Forensics and Security, vol. 8, no. 11, pp. 1790-1801,* (中科院小类二区期刊)'
doi: 10.1109/TIFS.2013.2279531
---
