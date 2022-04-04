---
layout: post
author:
  name: Paper ID 42
  difficulty: Difficulty - Hard
share: true
title: ViViT- A Video Vision Transformer
categories:
- CV
- hard
tags: []
---
**Abstract** - We present pure-transformer based models for video classification, drawing upon the recent success of such models in image classification. Our model extracts spatiotemporal tokens from the input video, which are then encoded by a series of transformer layers. In order to handle the long sequences of tokens encountered in video, we propose several, efficient variants of our model which factorise the spatial- and temporal-dimensions of the input. Although transformer-based models are known to only be effective when large training datasets are available, we show how we can effectively regularise the model during training and leverage pretrained image models to be able to train on comparatively small datasets. We conduct thorough ablation studies, and achieve state-of-the-art results on multiple video classification benchmarks including Kinetics 400 and 600, Epic Kitchens, Something-Something v2 and Moments in Time, outperforming prior methods based on deep 3D convolutional networks. To facilitate further research, we will release code and models.
**Paper** - [ViViT: A Video Vision Transformer | IEEE Conference Publication | IEEE Xplore](ViViT: A Video Vision Transformer | IEEE Conference Publication | IEEE Xplore)
**Code** - [rishikksh20/ViViT-pytorch: Implementation of ViViT: A Video Vision Transformer (github.com)](rishikksh20/ViViT-pytorch: Implementation of ViViT: A Video Vision Transformer (github.com))
**Dataset -** [http://serre-lab.clps.brown.edu/wp-content/uploads/2013/10/hmdb51_org.rar](http://serre-lab.clps.brown.edu/wp-content/uploads/2013/10/hmdb51_org.rar)
    