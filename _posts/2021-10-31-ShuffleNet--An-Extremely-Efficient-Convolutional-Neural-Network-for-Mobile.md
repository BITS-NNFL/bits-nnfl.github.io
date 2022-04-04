---
layout: post
author:
  name: Paper ID 68
  difficulty: Difficulty - easy
share: true
title: ShuffleNet- An Extremely Efficient Convolutional Neural Network for Mobile
categories:
- classification
- easy
tags: []
---
**Abstract** - We introduce an extremely computation-efficient CNN
architecture named ShuffleNet, which is designed specially
for mobile devices with very limited computing power (e.g.,
10-150 MFLOPs). The new architecture utilizes two new
operations, pointwise group convolution and channel shuffle, to greatly reduce computation cost while maintaining
accuracy. Experiments on ImageNet classification and MS
COCO object detection demonstrate the superior performance of ShuffleNet over other structures, e.g. lower top-1
error (absolute 7.8%) than recent MobileNet [12] on ImageNet classification task, under the computation budget of
40 MFLOPs. On an ARM-based mobile device, ShuffleNet
achieves ∼13× actual speedup over AlexNet while maintaining comparable accuracy.

**Paper** - [https://arxiv.org/pdf/1707.01083v2.pdf](https://arxiv.org/pdf/1707.01083v2.pdf)
**Code** - [https://github.com/Mayurji/Image-Classification-PyTorch](https://github.com/Mayurji/Image-Classification-PyTorch)
**Dataset -** [https://github.com/mayurji/image-classification-pytorch](https://github.com/mayurji/image-classification-pytorch)
    