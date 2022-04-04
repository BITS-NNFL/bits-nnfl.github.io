---
layout: post
author:
  name: Paper ID 14
  difficulty: Difficulty - Medium
share: true
title: Superhuman Accuracy on the SNEMI3D Connectomics Challenge
categories:
- 1. 3D Computer Vision
- 2. Medical Imaging
- medium
tags: []
---
**Abstract** - For the past decade, convolutional networks have been used for 3D reconstruction of neurons from electron microscopic (EM) brain images. Recent years have seen great improvements in accuracy, as evidenced by submissions to the SNEMI3D benchmark challenge. Here we report the first submission to surpass the estimate of human accuracy provided by the SNEMI3D leaderboard. A variant of 3D U-Net is trained on a primary task of predicting affinities between nearest neighbor voxels, and an auxiliary task of predicting long-range affinities. The training data is augmented by simulated image defects. The nearest neighbor affinities are used to create an oversegmentation, and then supervoxels are greedily agglomerated based on mean affinity. The resulting SNEMI3D score exceeds the estimate of human accuracy by a large margin. While one should be cautious about extrapolating from the SNEMI3D benchmark to real-world accuracy of large-scale neural circuit reconstruction, our result inspires optimism that the goal of full automation may be realizable in the future
**Paper** - [https://arxiv.org/pdf/1706.00120](https://arxiv.org/pdf/1706.00120)
**Code** - [https://github.com/zudi-lin/pytorch_connectomics](https://github.com/zudi-lin/pytorch_connectomics)
**Dataset -** [wget http://hp06.mindhackers.org/rhoana_product/dataset/snemi.zip](wget http://hp06.mindhackers.org/rhoana_product/dataset/snemi.zip)
    