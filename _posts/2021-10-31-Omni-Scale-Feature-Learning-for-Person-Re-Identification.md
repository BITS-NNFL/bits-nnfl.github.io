---
layout: post
author:
  name: Paper ID 8
  difficulty: Difficulty - Easy
share: true
title: Omni-Scale Feature Learning for Person Re-Identification
categories:
- CV
- NN
- easy
tags: []
---
**Abstract** - As an instance-level recognition problem, person re-identification (ReID) relies on discriminative features, which not only capture different spatial scales but also encapsulate an arbitrary combination of multiple scales. We call features of both homogeneous and heterogeneous scales omni-scale features. In this paper, a novel deep ReID CNN is designed, termed Omni-Scale Network (OSNet), for omni-scale feature learning. This is achieved by designing a residual block composed of multiple convolutional streams, each detecting features at a certain scale. Importantly, a novel unified aggregation gate is introduced to dynamically fuse multi-scale features with input-dependent channel-wise weights. To efficiently learn spatial-channel correlations and avoid overfitting, the building block uses pointwise and depthwise convolutions. By stacking such block layer-by-layer, our OSNet is extremely lightweight and can be trained from scratch on existing ReID benchmarks. Despite its small model size, OSNet achieves state-of-the-art performance on six person ReID datasets, outperforming most large-sized models, often by a clear margin. Code and models are available at: \url{this https URL}.
**Paper** - [https://arxiv.org/abs/1905.00953](https://arxiv.org/abs/1905.00953)
**Dataset -** [https://github.com/kaiyangzhou/deep-person-reid](https://github.com/kaiyangzhou/deep-person-reid)
    