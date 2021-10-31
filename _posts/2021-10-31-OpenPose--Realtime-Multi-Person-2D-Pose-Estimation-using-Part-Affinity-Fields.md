---
layout: post
author:
  name: Paper ID 56
  difficulty: Difficulty - Medium
share: true
title: OpenPose- Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields
categories:
- CV
- medium
tags: []
---
**Abstract** - Realtime multi-person 2D pose estimation is a key component in enabling machines to have an understanding of people in images and videos. In this work, we present a realtime approach to detect the 2D pose of multiple people in an image. The proposed method uses a nonparametric representation, which we refer to as Part Affinity Fields (PAFs), to learn to associate body parts with individuals in the image. This bottom-up system achieves high accuracy and realtime performance, regardless of the number of people in the image. In previous work, PAFs and body part location estimation were refined simultaneously across training stages. We demonstrate that a PAF-only refinement rather than both PAF and body part location refinement results in a substantial increase in both runtime performance and accuracy. We also present the first combined body and foot keypoint detector, based on an internal annotated foot dataset that we have publicly released. We show that the combined detector not only reduces the inference time compared to running them sequentially, but also maintains the accuracy of each component individually. This work has culminated in the release of OpenPose, the first open-source realtime system for multi-person 2D pose detection, including body, foot, hand, and facial keypoints.
**Paper** - [https://arxiv.org/pdf/1812.08008v2.pdf](https://arxiv.org/pdf/1812.08008v2.pdf)
**Dataset -** [https://cocodataset.org/ ; http://human-pose.mpi-inf.mpg.de/](https://cocodataset.org/ ; http://human-pose.mpi-inf.mpg.de/)
    