---
layout: post
author:
  name: Paper ID 54
  difficulty: Difficulty - Hard
share: true
title: 3D Bounding Box Estimation Using Deep Learning and Geometry
categories:
- CV
- hard
tags: []
---
**Abstract** - We present a method for 3D object detection and pose estimation from a single image. In contrast to current techniques that only regress the 3D orientation of an object, our method first regresses relatively stable 3D object properties using a deep convolutional neural network and then combines these estimates with geometric constraints provided by a 2D object bounding box to produce a complete 3D bounding box. The first network output estimates the 3D object orientation using a novel hybrid discrete-continuous loss, which significantly outperforms the L2 loss. The second output regresses the 3D object dimensions, which have relatively little variance compared to alternatives and can often be predicted for many object types. These estimates, combined with the geometric constraints on translation imposed by the 2D bounding box, enable us to recover a stable and accurate 3D object pose. We evaluate our method on the challenging KITTI object detection benchmark both on the official metric of 3D orientation estimation and also on the accuracy of the obtained 3D bounding boxes. Although conceptually simple, our method outperforms more complex and computationally expensive approaches that leverage semantic segmentation, instance level segmentation and flat ground priors and sub-category detection. Our discrete-continuous loss also produces state of the art results for 3D viewpoint estimation on the Pascal 3D+ dataset. 
**Paper** - [https://arxiv.org/pdf/1612.00496v2.pdf](https://arxiv.org/pdf/1612.00496v2.pdf)
**Dataset -** [http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=2d](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=2d)
    