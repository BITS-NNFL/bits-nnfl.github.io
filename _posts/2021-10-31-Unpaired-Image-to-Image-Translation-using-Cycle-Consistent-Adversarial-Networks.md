---
layout: post
author:
  name: Paper ID 62
  difficulty: Difficulty - Medium
share: true
title: Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks
categories:
- CV
- GAN
- medium
tags: []
---
**Abstract** - Image-to-image translation is a class of vision and
graphics problems where the goal is to learn the mapping
between an input image and an output image using a train-
ing set of aligned image pairs. However, for many tasks,
paired training data will not be available. We present an
approach for learning to translate an image from a source
domain X to a target domain Y in the absence of paired
examples. Our goal is to learn a mapping G : X → Y
such that the distribution of images from G(X) is indistin-
guishable from the distribution Y using an adversarial loss.
Because this mapping is highly under-constrained, we cou-
ple it with an inverse mapping F : Y → X and introduce a
cycle consistency loss to enforce F(G(X)) ≈ X (and vice
versa). Qualitative results are presented on several tasks
where paired training data does not exist, including collec-
tion style transfer, object transfiguration, season transfer,
photo enhancement, etc. Quantitative comparisons against
several prior methods demonstrate the superiority of our
approach.
**Paper** - [https://arxiv.org/pdf/1703.10593.pdf](https://arxiv.org/pdf/1703.10593.pdf)
**Dataset -** [https://people.eecs.berkeley.edu//~taesung_park/cyclegan/datasets/](https://people.eecs.berkeley.edu//~taesung_park/cyclegan/datasets/)
    