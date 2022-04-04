---
layout: post
author:
  name: Paper ID 1
  difficulty: Difficulty - Medium
share: true
title: Deep Multi-scale Convolutional Neural Network for Dynamic Scene Deblurring
categories:
- Computer Vision
- 
- Image Enhancement
- medium
tags: []
---
**Abstract** - Non-uniform blind deblurring for general dynamic scenes is a challenging computer vision problem as blurs arise not only from multiple object motions but also from camera shake, scene depth variation. To remove these complicated motion blurs, conventional energy optimization based methods rely on simple assumptions such that blur kernel is partially uniform or locally linear. Moreover, recent machine learning based methods also depend on synthetic blur datasets generated under these assumptions. This makes conventional deblurring methods fail to remove blurs where blur kernel is difficult to approximate or parameterize (e.g. object motion boundaries). In this work, we propose a multi-scale convolutional neural network that restores sharp images in an end-to-end manner where blur is caused by various sources. Together, we present multiscale loss function that mimics conventional coarse-to-fine approaches. Furthermore, we propose a new large-scale dataset that provides pairs of realistic blurry image and the corresponding ground truth sharp image that are obtained by a high-speed camera. With the proposed model trained on this dataset, we demonstrate empirically that our method achieves the state-of-the-art performance in dynamic scene deblurring not only qualitatively, but also quantitatively.
**Paper** - [https://openaccess.thecvf.com/content_cvpr_2017/papers/Nah_Deep_Multi-Scale_Convolutional_CVPR_2017_paper.pdf](https://openaccess.thecvf.com/content_cvpr_2017/papers/Nah_Deep_Multi-Scale_Convolutional_CVPR_2017_paper.pdf)
**Code** - [https://github.com/SeungjunNah/DeepDeblur-PyTorch](https://github.com/SeungjunNah/DeepDeblur-PyTorch)
**Dataset -** [https://github.com/shuochsu/deepvideodeblurring](https://github.com/shuochsu/deepvideodeblurring)
    