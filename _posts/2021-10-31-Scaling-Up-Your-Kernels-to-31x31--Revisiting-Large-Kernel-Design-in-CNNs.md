---
layout: post
author:
  name: Paper ID 5
  difficulty: Difficulty - Medium
share: true
title: Scaling Up Your Kernels to 31x31- Revisiting Large Kernel Design in CNNs
categories:
- Computer Vision
- 
- Image Classification
- medium
tags: []
---
**Abstract** - We revisit large kernel design in modern convolutional neural networks (CNNs). Inspired by recent advances of vision transformers (ViTs), in this paper, we demonstrate that using a few large convolutional kernels instead of a stack of small kernels could be a more powerful paradigm. We suggested five guidelines, e.g., applying re-parameterized large depth-wise convolutions, to design efficient high-performance large-kernel CNNs. Following the guidelines, we propose RepLKNet, a pure CNN architecture whose kernel size is as large as 31x31, in contrast to commonly used 3x3. RepLKNet greatly closes the performance gap between CNNs and ViTs, e.g., achieving comparable or superior results than Swin Transformer on ImageNet and a few typical downstream tasks, with lower latency. RepLKNet also shows nice scalability to big data and large models, obtaining 87.8% top-1 accuracy on ImageNet and 56.0% mIoU on ADE20K, which is very competitive among the state-of-the-arts with similar model sizes. Our study further reveals that, in contrast to small-kernel CNNs, large-kernel CNNs have much larger effective receptive fields, and higher shape bias rather than texture bias. 
**Paper** - [https://arxiv.org/pdf/2203.06717v2.pdf](https://arxiv.org/pdf/2203.06717v2.pdf)
**Code** - [https://github.com/DingXiaoH/RepLKNet-pytorch](https://github.com/DingXiaoH/RepLKNet-pytorch)
**Dataset -** [https://paperswithcode.com/dataset/cifar-100](https://paperswithcode.com/dataset/cifar-100)
    