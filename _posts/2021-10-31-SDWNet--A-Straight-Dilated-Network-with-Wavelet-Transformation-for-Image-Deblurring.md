---
layout: post
author:
  name: Paper ID 4
  difficulty: Difficulty - Medium
share: true
title: SDWNet- A Straight Dilated Network with Wavelet Transformation for Image Deblurring
categories:
- Computer Vision
- Image Enhancement
- medium
tags: []
---
**Abstract** - Image deblurring is a classical computer vision problem that aims to recover a sharp image from a blurred image. To solve this problem, existing methods apply the EncodeDecode architecture to design the complex networks to make a good performance. However, most of these methods use repeated up-sampling and down-sampling structures to expand the receptive field, which results in texture information loss during the sampling process and some of them design the multiple stages that lead to difficulties with convergence. Therefore, our model uses dilated convolution to enable the obtainment of the large receptive field with high spatial resolution. Through making full use of the different receptive fields, our method can achieve better performance. On this basis, we reduce the number of up-sampling and down-sampling and design a simple network structure. Besides, we propose a novel module using the wavelet transform, which effectively helps the network to recover clear high-frequency texture details.
**Paper** - [https://arxiv.org/abs/2110.05803](https://arxiv.org/abs/2110.05803)
**Code** - [https://github.com/FlyEgle/SDWNet](https://github.com/FlyEgle/SDWNet)
**Dataset -** [https://github.com/shuochsu/deepvideodeblurring](https://github.com/shuochsu/deepvideodeblurring)
    