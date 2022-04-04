---
layout: post
author:
  name: Paper ID 2
  difficulty: Difficulty - Hard
share: true
title: FFA-Net- Feature Fusion Attention Network for Single Image Dehazing
categories:
- Computer Vision
- Attention
- 
- Image Enhancement
- hard
tags: []
---
**Abstract** - In this paper, we propose an end-to-end feature fusion attention network (FFA-Net) to directly restore the haze-free image. The FFA-Net architecture consists of three key components: 1) A novel Feature Attention (FA) module combines Channel Attention with Pixel Attention mechanism, considering that different channel-wise features contain totally different weighted information and haze distribution is uneven on the different image pixels. FA treats different features and pixels unequally, which provides additional flexibility in dealing with different types of information, expanding the representational ability of CNNs. 2) A basic block structure consists of Local Residual Learning and Feature Attention, Local Residual Learning allowing the less important information such as thin haze region or low-frequency to be bypassed through multiple local residual connections, let main network architecture focus on more effective information. 3) An Attentionbased different levels Feature Fusion (FFA) structure, the feature weights are adaptively learned from the Feature Attention (FA) module, giving more weight to important features. This structure can also retain the information of shallow layers and pass it into deep layers
**Paper** - [https://arxiv.org/abs/1911.07559](https://arxiv.org/abs/1911.07559)
**Code** - [https://github.com/zhilin007/FFA-Net](https://github.com/zhilin007/FFA-Net)
**Dataset -** [https://paperswithcode.com/dataset/d-hazy](https://paperswithcode.com/dataset/d-hazy)
    