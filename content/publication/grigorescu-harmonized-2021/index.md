---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Harmonized Segmentation of Neonatal Brain MRI
subtitle: ''
summary: ''
authors:
- Irina Grigorescu
- Lucy Vanes
- Alena Uus
- Dafnis Batalle
- Lucilio Cordero-Grande
- Chiara Nosarti
- A. David Edwards
- Joseph V. Hajnal
- Marc Modat
- Maria Deprez
tags: []
categories: []
date: '2021-05-01'
lastmod: 2023-01-25T23:05:22Z
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
publishDate: '2023-01-25T23:05:22.156385Z'
publication_types:
- '2'
abstract: Deep learning based medical image segmentation has shown great potential
  in becoming a key part of the clinical analysis pipeline. However, many of these
  models rely on the assumption that the train and test data come from the same distribution.
  This means that such methods cannot guarantee high quality predictions when the
  source and target domains are dissimilar due to different acquisition protocols,
  or biases in patient cohorts. Recently, unsupervised domain adaptation techniques
  have shown great potential in alleviating this problem by minimizing the shift between
  the source and target distributions, without requiring the use of labeled data in
  the target domain. In this work, we aim to predict tissue segmentation maps on T
  2 -weighted magnetic resonance imaging data of an unseen preterm-born neonatal population,
  which has both different acquisition parameters and population bias when compared
  to our training data. We achieve this by investigating two unsupervised domain adaptation
  techniques with the objective of finding the best solution for our problem. We compare
  the two methods with a baseline fully-supervised segmentation network and report
  our results in terms of Dice scores obtained on our source test dataset. Moreover,
  we analyse tissue volumes and cortical thickness measures of the harmonized data
  on a subset of the population matched for gestational age at birth and postmenstrual
  age at scan. Finally, we demonstrate the applicability of the harmonized cortical
  gray matter maps with an analysis comparing term and preterm-born neonates and a
  proof-of-principle investigation of the association between cortical thickness and
  a language outcome measure.
publication: '*Frontiers in Neuroscience*'
url_pdf: https://www.frontiersin.org/articles/10.3389/fnins.2021.662005/full
doi: 10.3389/fnins.2021.662005
---
