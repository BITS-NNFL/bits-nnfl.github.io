---
layout: post
author:
  name: Paper ID 43
  difficulty: Difficulty - Easy 
share: true
title: Attention U-Net- Learning Where to Look for the Pancreas
categories:
- CV
- easy 
tags: []
---
**Abstract** - We propose a novel attention gate (AG) model for medical imaging that automatically learns to focus on target structures of varying shapes and sizes. Models
trained with AGs implicitly learn to suppress irrelevant regions in an input image
while highlighting salient features useful for a specific task. This enables us to
eliminate the necessity of using explicit external tissue/organ localisation modules
of cascaded convolutional neural networks (CNNs). AGs can be easily integrated
into standard CNN architectures such as the U-Net model with minimal computational overhead while increasing the model sensitivity and prediction accuracy.
The proposed Attention U-Net architecture is evaluated on two large CT abdominal
datasets for multi-class image segmentation. Experimental results show that AGs
consistently improve the prediction performance of U-Net across different datasets
and training sizes while preserving computational efficiency. The source code for
the proposed architecture is publicly available.
**Paper** - [https://arxiv.org/pdf/1804.03999.pdf](https://arxiv.org/pdf/1804.03999.pdf)
**Code** - [https://github.com/sfczekalski/attention_unet](https://github.com/sfczekalski/attention_unet)
**Dataset -** []()
    