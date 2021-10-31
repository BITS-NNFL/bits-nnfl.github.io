---
layout: post
author:
  name: Paper ID 33
  difficulty: Difficulty - Medium
share: true
title: TSM- Temporal Shift Module for Efficient Video Understanding
categories:
- CV
- medium
tags: []
---
**Abstract** - The explosive growth in video streaming gives rise to
challenges on performing video understanding at high accuracy and low computation cost. Conventional 2D CNNs
are computationally cheap but cannot capture temporal
relationships; 3D CNN based methods can achieve good
performance but are computationally intensive, making it
expensive to deploy. In this paper, we propose a generic
and effective Temporal Shift Module (TSM) that enjoys both
high efficiency and high performance. Specifically, it can
achieve the performance of 3D CNN but maintain 2D CNN’s
complexity. TSM shifts part of the channels along the temporal dimension; thus facilitate information exchanged among
neighboring frames. It can be inserted into 2D CNNs to
achieve temporal modeling at zero computation and zero
parameters. We also extended TSM to online setting, which
enables real-time low-latency online video recognition and
video object detection. TSM is accurate and efficient: it
ranks the first place on the Something-Something leaderboard upon publication; on Jetson Nano and Galaxy Note8,
it achieves a low latency of 13ms and 35ms for online video
recognition. 
**Paper** - [https://arxiv.org/pdf/1811.08383.pdf](https://arxiv.org/pdf/1811.08383.pdf)
**Dataset -** [http://serre-lab.clps.brown.edu/wp-content/uploads/2013/10/hmdb51_org.rar](http://serre-lab.clps.brown.edu/wp-content/uploads/2013/10/hmdb51_org.rar)
    