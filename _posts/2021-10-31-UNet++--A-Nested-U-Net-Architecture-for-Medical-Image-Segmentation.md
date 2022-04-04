---
layout: post
author:
  name: Paper ID 6
  difficulty: Difficulty - Medium
share: true
title: UNet++- A Nested U-Net Architecture for Medical Image Segmentation
categories:
- Computer Vision
- Image Segmentation
- medium
tags: []
---
**Abstract** - In this paper, we present UNet++, a new, more powerful architecture for medical image segmentation. Our architecture is essentially a deeply-supervised encoder-decoder network where the encoder and decoder sub-networks are connected through a series of nested, dense skip pathways. The re-designed skip pathways aim at reducing the semantic gap between the feature maps of the encoder and decoder sub-networks. We argue that the optimizer would deal with an easier learning task when the feature maps from the decoder and encoder networks are semantically similar. We have evaluated UNet++ in comparison with U-Net and wide U-Net architectures across multiple medical image segmentation tasks: nodule segmentation in the low-dose CT scans of chest, nuclei segmentation in the microscopy images, liver segmentation in abdominal CT scans, and polyp segmentation in colonoscopy videos. Our experiments demonstrate that UNet++ with deep supervision achieves an average IoU gain of 3.9 and 3.4 points over U-Net and wide U-Net, respectively.
**Paper** - [https://arxiv.org/abs/1807.10165](https://arxiv.org/abs/1807.10165)
**Code** - [https://paperswithcode.com/method/unet](https://paperswithcode.com/method/unet)
**Dataset -** [https://paperswithcode.com/task/semantic-segmentation](https://paperswithcode.com/task/semantic-segmentation)
    