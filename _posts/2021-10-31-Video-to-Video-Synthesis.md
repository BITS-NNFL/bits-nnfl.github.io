---
layout: post
author:
  name: Paper ID 21
  difficulty: Difficulty - Easy
share: true
title: Video-to-Video Synthesis
categories:
- Video Synthesis
- easy
tags: []
---
**Abstract** - We study the problem of video-to-video synthesis, whose goal is to learn a mapping function from an input source video (e.g., a sequence of semantic segmentation masks) to an output photorealistic video that precisely depicts the content of the source video. While its image counterpart, the image-to-image translation problem, is a popular topic, the video-to-video synthesis problem is less explored in the literature. Without modeling temporal dynamics, directly applying existing image synthesis approaches to an input video often results in temporally incoherent videos of low visual quality. In this paper, we propose a video-to-video synthesis approach under the generative adversarial learning framework. Through carefully-designed generators and discriminators, coupled with a spatio-temporal adversarial objective, we achieve high-resolution, photorealistic, temporally coherent video results on  a diverse set of input formats including segmentation masks, sketches, and poses. Experiments on multiple benchmarks show the advantage of our method compared to strong baselines. In particular, our model is capable of synthesizing 2K resolution videos of street scenes up to 30 seconds long, which significantly advances the state-of-the-art of video synthesis. Finally, we apply our method to future video prediction, outperforming several competing systems. Code, models, and more results are available at our website.
**Paper** - [https://tcwang0509.github.io/vid2vid/paper_vid2vid.pdf](https://tcwang0509.github.io/vid2vid/paper_vid2vid.pdf)
**Code** - [https://github.com/NVIDIA/vid2vid](https://github.com/NVIDIA/vid2vid)
**Dataset -** [links available in repo](links available in repo)
    