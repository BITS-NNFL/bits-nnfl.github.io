---
layout: post
author:
  name: Paper ID 9
  difficulty: Difficulty - Hard
share: true
title: Conditional Convolutions for Instance Segmentation
categories:
- Computer Vision
- Instance Segmentation
- hard
tags: []
---
**Abstract** - We propose a simple yet effective instance segmentation framework, termed CondInst (conditional convolutions for instance segmentation). Top-performing instance segmentation methods such as Mask R-CNN rely on ROI operations (typically ROIPool or ROIAlign) to obtain the final instance masks. In contrast, we propose to solve instance segmentation from a new perspective. Instead of using instance-wise ROIs as inputs to a network of fixed weights, we employ dynamic instance-aware networks, conditioned on instances. CondInst enjoys two advantages: 1) Instance segmentation is solved by a fully convolutional network, eliminating the need for ROI cropping and feature alignment. 2) Due to the much improved capacity of dynamically-generated conditional convolutions, the mask head can be very compact (e.g., 3 conv. layers, each having only 8 channels), leading to significantly faster inference. We demonstrate a simpler instance segmentation method that can achieve improved performance in both accuracy and inference speed. On the COCO dataset, we outperform a few recent methods including well-tuned Mask RCNN baselines, without longer training schedules needed. 
**Paper** - [https://arxiv.org/pdf/2003.05664](https://arxiv.org/pdf/2003.05664)
**Code** - [https://github.com/aim-uofa/adet](https://github.com/aim-uofa/adet)
**Dataset -** [https://github.com/giddyyupp/coco-minitrain](https://github.com/giddyyupp/coco-minitrain)
    