---
layout: post
author:
  name: Paper ID 62
  difficulty: Difficulty - medium
share: true
title: 3D U-Net- Learning Dense Volumetric Segmentation from Sparse Annotation
categories:
- 3D segmentation
- medium
tags: []
---
**Abstract** - This paper introduces a network for volumetric segmentation that learns from sparsely annotated volumetric images. We outline two attractive use cases of this method: (1) In a semi-automated
setup, the user annotates some slices in the volume to be segmented.
The network learns from these sparse annotations and provides a dense
3D segmentation. (2) In a fully-automated setup, we assume that a representative, sparsely annotated training set exists. Trained on this data
set, the network densely segments new volumetric images. The proposed
network extends the previous u-net architecture from Ronneberger et
al. by replacing all 2D operations with their 3D counterparts. The implementation performs on-the-fly elastic deformations for efficient data
augmentation during training. It is trained end-to-end from scratch, i.e.,
no pre-trained network is required. We test the performance of the proposed method on a complex, highly variable 3D structure, the Xenopus
kidney, and achieve good results for both use cases
**Paper** - [https://github.com/wolny/pytorch-3dunet/tree/master/pytorch3dunet](https://github.com/wolny/pytorch-3dunet/tree/master/pytorch3dunet)
**Code** - [https://github.com/wolny/pytorch-3dunet](https://github.com/wolny/pytorch-3dunet)
**Dataset -** [https://github.com/wolny/pytorch-3dunet/tree/master/resources](https://github.com/wolny/pytorch-3dunet/tree/master/resources)
    