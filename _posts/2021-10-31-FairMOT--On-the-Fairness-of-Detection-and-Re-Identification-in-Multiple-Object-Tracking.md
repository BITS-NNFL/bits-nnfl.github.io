---
layout: post
author:
  name: Paper ID 58
  difficulty: Difficulty - Hard
share: true
title: FairMOT- On the Fairness of Detection and Re-Identification in Multiple Object Tracking
categories:
- Computer Vision; Object tracking
- hard
tags: []
---
**Abstract** - Multi-object tracking (MOT) is an important problem in computer vision which has a wide range of applications. Formulating MOT as multi-task learning of object detection and re-ID in a single network is appealing since it allows joint optimization of the two tasks and enjoys high computation efficiency. However, we find that the two tasks tend to compete with each other which need to be carefully addressed. In particular, previous works usually treat re-ID as a secondary task whose accuracy is heavily affected by the primary detection task. As a result, the network is biased to the primary detection task which is not fair to the re-ID task. To solve the problem, we present a simple yet effective approach termed as FairMOT based on the anchor-free object detection architecture CenterNet. Note that it is not a naive combination of CenterNet and re-ID. Instead, we present a bunch of detailed designs which are critical to achieve good tracking results by thorough empirical studies. The resulting approach achieves high accuracy for both detection and tracking. The approach outperforms the state-of-the-art methods by a large margin on several public datasets. The source code and pre-trained models are released at https://github.com/ifzhang/FairMOT.
**Paper** - [https://arxiv.org/abs/2004.01888](https://arxiv.org/abs/2004.01888)
**Code** - [https://github.com/ifzhang/FairMOT](https://github.com/ifzhang/FairMOT)
**Dataset -** [https://cocodataset.org/#home](https://cocodataset.org/#home)
    