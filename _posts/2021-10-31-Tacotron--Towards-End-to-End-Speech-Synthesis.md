---
layout: post
author:
  name: Paper ID 34
  difficulty: Difficulty - Hard
share: true
title: Tacotron- Towards End-to-End Speech Synthesis
categories:
- NLP
- Text-To-Speech
- hard
tags: []
---
**Abstract** - A text-to-speech synthesis system typically consists of multiple stages, such as a text analysis frontend, an acoustic model and an audio synthesis module. Building these components often requires extensive domain expertise and may contain brittle design choices. In this paper, we present Tacotron, an end-to-end generative text-to-speech model that synthesizes speech directly from characters. Given <text, audio> pairs, the model can be trained completely from scratch with random initialization. We present several key techniques to make the sequence-to-sequence framework perform well for this challenging task. Tacotron achieves a 3.82 subjective 5-scale mean opinion score on US English, outperforming a production parametric system in terms of naturalness. In addition, since Tacotron generates speech at the frame level, it's substantially faster than sample-level autoregressive methods.
**Paper** - [https://arxiv.org/abs/1703.10135](https://arxiv.org/abs/1703.10135)
**Dataset -** [https://keithito.com/lj-speech-dataset/](https://keithito.com/lj-speech-dataset/)
    