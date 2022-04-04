---
layout: post
author:
  name: Paper ID 19
  difficulty: Difficulty - Medium
share: true
title: StackGAN++- Realistic Image Synthesis with Stacked Generative Adversarial Networks
categories:
- GANs
- Text-to-Image Synthesis
- medium
tags: []
---
**Abstract** - Although Generative Adversarial Networks (GANs) have shown remarkable success in various tasks, they still face challenges in generating high quality images. In this paper, we propose Stacked Generative Adversarial Networks (StackGANs) aimed at generating high-resolution photo-realistic images. First, we propose a two-stage generative adversarial network architecture, StackGAN-v1, for text-to-image synthesis. The Stage-I GAN sketches the primitive shape and colors of a scene based on a given text description, yielding low-resolution images. The Stage-II GAN takes Stage-I results and the text description as inputs, and generates high-resolution images with photo-realistic details. Second, an advanced multi-stage generative adversarial network architecture, StackGAN-v2, is proposed for both conditional and unconditional generative tasks. Our StackGAN-v2 consists of multiple generators and multiple discriminators arranged in a tree-like structure; images at multiple scales corresponding to the same scene are generated from different branches of the tree. StackGAN-v2 shows more stable training behavior than StackGAN-v1 by jointly approximating multiple distributions. Extensive experiments demonstrate that the proposed stacked generative adversarial networks significantly outperform other state-of-the-art methods in generating photo-realistic images
**Paper** - [https://arxiv.org/pdf/1710.10916v3.pdf](https://arxiv.org/pdf/1710.10916v3.pdf)
**Code** - [https://github.com/hanzhanggit/StackGAN-v2](https://github.com/hanzhanggit/StackGAN-v2)
**Dataset -** [links available in repo](links available in repo)
    