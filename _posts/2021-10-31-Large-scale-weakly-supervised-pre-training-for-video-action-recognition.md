---
layout: post
author:
  name: Paper ID 74
  difficulty: Difficulty - Hard
share: true
title: Large-scale weakly-supervised pre-training for video action recognition
categories:
- Computer Vision
- Action Recognition
- hard
tags: []
---
**Abstract** - Summary: Explores pre-training on large datasets for action recogniton. Mainly focuses on pre-training of R(2+1)D netoworks, Abstract:Current fully-supervised video datasets consist of only a few hundred thousand videos and fewer than a thousand domain-specific labels. This hinders the progress towards advanced video architectures. This paper presents an in-depth study of using large volumes of web videos for pre-training video models for the task of action recognition. Our primary empirical finding is that pre-training at a very large scale (over 65 million videos), despite on noisy social-media videos and hashtags, substantially improves the state-of-the-art on three challenging public action recognition datasets. Further, we examine three questions in the construction of weakly-supervised video action datasets. First, given that actions involve interactions with objects, how should one construct a verb-object pre-training label space to benefit transfer learning the most? Second, frame-based models perform quite well on action recognition; is pre-training for good image features sufficient or is pre-training for spatio-temporal features valuable for optimal transfer learning? Finally, actions are generally less well-localized in long videos vs. short videos; since action labels are provided at a video level, how should one choose video clips for best performance, given some fixed budget of number or minutes of videos?

**Paper** - [https://arxiv.org/abs/1905.00561](https://arxiv.org/abs/1905.00561)
**Code** - [https://github.com/irhum/R2Plus1D-PyTorch](https://github.com/irhum/R2Plus1D-PyTorch)
**Dataset -** [https://github.com/microsoft/computervision-recipes/tree/master/scenarios/action_recognition](https://github.com/microsoft/computervision-recipes/tree/master/scenarios/action_recognition)
    