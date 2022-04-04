---
layout: post
author:
  name: Paper ID 22
  difficulty: Difficulty - Easy
share: true
title: DeepVO- Towards End-to-End Visual Odometry with Deep Recurrent Convolutional Neural Networks
categories:
- Visual Odometry
- Robotics
- easy
tags: []
---
**Abstract** - This paper studies monocular visual odometry (VO) problem. Most of existing VO algorithms are developed under a standard pipeline including feature extraction, feature matching, motion estimation, local optimisation, etc. Although some of them have demonstrated superior performance, they usually need to be carefully designed and specifically fine-tuned to work well in different environments. Some prior knowledge is also required to recover an absolute scale for monocular VO. This paper presents a novel end-to-end framework for monocular VO by using deep Recurrent Convolutional Neural Networks (RCNNs) 1 . Since it is trained and deployed in an end-to-end manner, it infers poses directly from a sequence of raw RGB images (videos) without adopting any module in the conventional VO pipeline. Based on the RCNNs, it not only automatically learns effective feature representation for the VO problem through Convolutional Neural Networks, but also implicitly models sequential dynamics and relations using deep Recurrent Neural Networks. Extensive experiments on the KITTI VO dataset show competitive performance to state-ofthe-art methods, verifying that the end-to-end Deep Learning technique can be a viable complement to the traditional VO systems.
**Paper** - [https://arxiv.org/pdf/1709.08429v1.pdf](https://arxiv.org/pdf/1709.08429v1.pdf)
**Code** - [https://github.com/fshamshirdar/DeepVO](https://github.com/fshamshirdar/DeepVO)
**Dataset -** [link available in repo](link available in repo)
    