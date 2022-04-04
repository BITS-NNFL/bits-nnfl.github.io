---
layout: post
author:
  name: Paper ID 32
  difficulty: Difficulty - Medium
share: true
title: Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset
categories:
- Computer Vision
- Action Recognition
- Transfer Learning
- medium
tags: []
---
**Abstract** - The paucity of videos in current action classification datasets (UCF-101 and HMDB-51) has made it difficult to identify good video architectures, as most methods obtain similar performance on existing small-scale benchmarks. This paper re-evaluates state-of-the-art architectures in light of the new Kinetics Human Action Video dataset. Kinetics has two orders of magnitude more data, with 400 human action classes and over 400 clips per class, and is collected from realistic, challenging YouTube videos. We provide an analysis on how current architectures fare on the task of action classification on this dataset and how much performance improves on the smaller benchmark datasets after pre-training on Kinetics.
We also introduce a new Two-Stream Inflated 3D ConvNet (I3D) that is based on 2D ConvNet inflation: filters and pooling kernels of very deep image classification ConvNets are expanded into 3D, making it possible to learn seamless spatio-temporal feature extractors from video while leveraging successful ImageNet architecture designs and even their parameters. We show that, after pre-training on Kinetics, I3D models considerably improve upon the state-of-the-art in action classification, reaching 80.9% on HMDB-51 and 98.0% on UCF-101.
**Paper** - [https://arxiv.org/abs/1705.07750](https://arxiv.org/abs/1705.07750)
**Code** - [https://github.com/deepmind/kinetics-i3d](https://github.com/deepmind/kinetics-i3d)
**Dataset -** [https://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/](https://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/)
    