---
layout: post
author:
  name: Paper ID 10
  difficulty: Difficulty - Medium
share: true
title: Eformer- Edge Enhancement based Transformer for Medical Image Denoising
categories:
- CV
- NN
- medium
tags: []
---
**Abstract** - In this work, we present Eformer - Edge enhancement based transformer, a novel architecture that builds an encoder-decoder network using transformer blocks for medical image denoising. Non-overlapping window-based self-attention is used in the transformer block that reduces computational requirements. This work further incorporates learnable Sobel-Feldman operators to enhance edges in the image and propose an effective way to concatenate them in the intermediate layers of our architecture. The experimental analysis is conducted by comparing deterministic learning and residual learning for the task of medical image denoising. To defend the effectiveness of our approach, our model is evaluated on the AAPM-Mayo Clinic Low-Dose CT Grand Challenge Dataset and achieves state-of-the-art performance, i.e., 43.487 PSNR, 0.0067 RMSE, and 0.9861 SSIM. We believe that our work will encourage more research in transformer-based architectures for medical image denoising using residual learning.
**Paper** - [https://arxiv.org/abs/2109.08044](https://arxiv.org/abs/2109.08044)
**Dataset -** [https://www.aapm.org/grandchallenge/lowdosect/](https://www.aapm.org/grandchallenge/lowdosect/)
    