---
layout: post
author:
  name: Paper ID 61
  difficulty: Difficulty - Easy
share: true
title: U2-Net- Going Deeper with Nested U-Structure for Salient Object Detection
categories:
- CV
- Salient Object Detection
- easy
tags: []
---
**Abstract** - In this paper, we design a simple yet powerful deep network architecture, U2-Net, for salient object detection (SOD). The architecture of our U2-Net is a two-level nested U-structure. The design has the following advantages: (1) it is able to capture more contextual information from different scales thanks to the mixture of receptive fields of different sizes in our proposed ReSidual U-blocks (RSU), (2) it increases the depth of the whole architecture without significantly increasing the computational cost because of the pooling operations used in these RSU blocks. This architecture enables us to train a deep network from scratch without using backbones from image classification tasks. We instantiate two models of the proposed architecture, U2-Net (176.3 MB, 30 FPS on GTX 1080Ti GPU) and U2-Net† (4.7 MB, 40 FPS), to facilitate the usage in different environments. Both models achieve competitive performance on six SOD datasets.
**Paper** - [https://arxiv.org/abs/2005.09007](https://arxiv.org/abs/2005.09007)
**Dataset -** [http://saliencydetection.net/duts/](http://saliencydetection.net/duts/)
    