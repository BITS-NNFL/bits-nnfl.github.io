---
layout: post
author:
  name: Paper ID 8
  difficulty: Difficulty - Easy
share: true
title: CondConv- Conditionally Parameterized Convolutions for Efficient Inference
categories:
- Convolutions
- easy
tags: []
---
**Abstract** - Convolutional layers are one of the basic building blocks of modern deep neural networks. One fundamental assumption is that convolutional kernels should be shared for all examples in a dataset. We propose conditionally parameterized convolutions (CondConv), which learn specialized convolutional kernels for each example. Replacing normal convolutions with CondConv enables us to increase the size and capacity of a network, while maintaining efficient inference. We demonstrate that scaling networks with CondConv improves the performance and inference cost trade-off of several existing convolutional neural network architectures on both classification and detection tasks. On ImageNet classification, our CondConv approach applied to EfficientNet-B0 achieves state-of-the-art performance of 78.3% accuracy with only 413M multiply-adds.
**Paper** - [https://arxiv.org/pdf/1904.04971](https://arxiv.org/pdf/1904.04971)
**Code** - [https://github.com/d-li14/condconv.pytorch](https://github.com/d-li14/condconv.pytorch)
**Dataset -** [cifar-10](cifar-10)
    