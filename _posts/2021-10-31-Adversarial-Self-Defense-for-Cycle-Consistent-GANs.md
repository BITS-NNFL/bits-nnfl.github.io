---
layout: post
author:
  name: Paper ID 49
  difficulty: Difficulty - Medium
share: true
title: Adversarial Self-Defense for Cycle-Consistent GANs
categories:
- CV
- medium
tags: []
---
**Abstract** - The goal of unsupervised image-to-image translation is to map images from one
domain to another without the ground truth correspondence between the two
domains. State-of-art methods learn the correspondence using large numbers of
unpaired examples from both domains and are based on generative adversarial
networks. In order to preserve the semantics of the input image, the adversarial
objective is usually combined with a cycle-consistency loss that penalizes incorrect
reconstruction of the input image from the translated one. However, if the target
mapping is many-to-one, e.g. aerial photos to maps, such a restriction forces the
generator to hide information in low-amplitude structured noise that is undetectable
by human eye or by the discriminator. In this paper, we show how such selfattacking behavior of unsupervised translation methods affects their performance
and provide two defense techniques. We perform a quantitative evaluation of the
proposed techniques and show that making the translation model more robust to the
self-adversarial attack increases its generation quality and reconstruction reliability
and makes the model less sensitive to low-amplitude perturbations.

**Paper** - [https://arxiv.org/pdf/1908.01517v1.pdf](https://arxiv.org/pdf/1908.01517v1.pdf)
**Dataset -** [https://download.visinf.tu-darmstadt.de/data/from_games/](https://download.visinf.tu-darmstadt.de/data/from_games/)
    