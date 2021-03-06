---
layout: post
author:
  name: Paper ID 3
  difficulty: Difficulty - Medium
share: true
title: Learning Enriched Features for Real Image Restoration and Enhancement
categories:
- Computer Vision
- Image Enhancement
- medium
tags: []
---
**Abstract** - With the goal of recovering high-quality image content from its degraded version, image restoration enjoys numerous applications, such as in surveillance, computational photography, medical imaging, and remote sensing. Recently, convolutional neural networks (CNNs) have achieved dramatic improvements over conventional approaches for image restoration task. Existing CNN-based methods typically operate either on full-resolution or on progressively low-resolution representations. In the former case, spatially precise but contextually less robust results are achieved, while in the latter case, semantically reliable but spatially less accurate outputs are generated. In this paper, we present a novel architecture with the collective goals of maintaining spatially-precise high-resolution representations through the entire network, and receiving strong contextual information from the low-resolution representations. The core of our approach is a multi-scale residual block containing several key elements: (a) parallel multi-resolution convolution streams for extracting multi-scale features, (b) information exchange across the multi-resolution streams, (c) spatial and channel attention mechanisms for capturing contextual information, and (d) attention based multi-scale feature aggregation. In the nutshell, our approach learns an enriched set of features that combines contextual information from multiple scales, while simultaneously preserving the high-resolution spatial details. Extensive experiments on five real image benchmark datasets demonstrate that our method, named as MIRNet, achieves state-of-the-art results for a variety of image processing tasks, including image denoising, super-resolution and image enhancement.
**Paper** - [https://arxiv.org/abs/2003.06792](https://arxiv.org/abs/2003.06792)
**Code** - [https://github.com/swz30/MIRNet](https://github.com/swz30/MIRNet)
**Dataset -** [https://github.com/shuochsu/deepvideodeblurring](https://github.com/shuochsu/deepvideodeblurring)
    