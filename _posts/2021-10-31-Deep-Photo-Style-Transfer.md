---
layout: post
author:
  name: Paper ID 29
  difficulty: Difficulty - Medium
share: true
title: Deep Photo Style Transfer
categories:
- Computer Vision
- GANs
- medium
tags: []
---
**Abstract** - This paper introduces a deep-learning approach to photographic style transfer that handles a large variety of image content while faithfully transferring the reference style. Our approach builds upon the recent work on painterly transfer that separates style from the content of an image by considering different layers of a neural network. However, as is, this approach is not suitable for photorealistic style transfer. Even when both the input and reference images are photographs, the output still exhibits distortions reminiscent of a painting. Our contribution is to constrain the transformation from the input to the output to be locally affine in colorspace, and to express this constraint as a custom fully differentiable energy term. We show that this approach successfully suppresses distortion and yields satisfying photorealistic style transfers in a broad variety of scenarios, including transfer of the time of day, weather, season, and artistic edits.
**Paper** - [https://arxiv.org/abs/1703.07511](https://arxiv.org/abs/1703.07511)
**Code** - [https://github.com/LouieYang/deep-photo-styletransfer-tf](https://github.com/LouieYang/deep-photo-styletransfer-tf)
**Dataset -** [https://github.com/luanfujun/deep-photo-styletransfer/tree/master/examples](https://github.com/luanfujun/deep-photo-styletransfer/tree/master/examples)
    