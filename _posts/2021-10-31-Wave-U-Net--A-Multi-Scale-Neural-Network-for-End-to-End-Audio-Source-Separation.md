---
layout: post
author:
  name: Paper ID 60
  difficulty: Difficulty - Medium
share: true
title: Wave-U-Net- A Multi-Scale Neural Network for End-to-End Audio Source Separation
categories:
- CNN; Audio Seperation
- medium
tags: []
---
**Abstract** - Models for audio source separation usually operate on the magnitude spectrum, which ignores phase information and makes separation performance dependant on hyper-parameters for the spectral front-end. Therefore, we investigate end-to-end source separation in the time-domain, which allows modelling phase information and avoids fixed spectral transformations. Due to high sampling rates for audio, employing a long temporal input context on the sample level is difficult, but required for high quality separation results because of long-range temporal correlations. In this context, we propose the Wave-U-Net, an adaptation of the U-Net to the one-dimensional time domain, which repeatedly resamples feature maps to compute and combine features at different time scales. We introduce further architectural improvements, including an output layer that enforces source additivity, an upsampling technique and a context-aware prediction framework to reduce output artifacts. Experiments for singing voice separation indicate that our architecture yields a performance comparable to a state-of-the-art spectrogram-based U-Net architecture, given the same data. Finally, we reveal a problem with outliers in the currently used SDR evaluation metrics and suggest reporting rank-based statistics to alleviate this problem.
**Paper** - [https://arxiv.org/abs/1806.03185](https://arxiv.org/abs/1806.03185)
**Code** - [https://github.com/f90/Wave-U-Net](https://github.com/f90/Wave-U-Net)
**Dataset -** [https://sigsep.github.io/datasets/musdb.html](https://sigsep.github.io/datasets/musdb.html)
    