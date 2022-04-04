---
layout: post
author:
  name: Paper ID 33
  difficulty: Difficulty - Medium
share: true
title: SING- Symbol-to-Instrument Neural Generator
categories:
- Audio Synthesis
- Autoencoders
- Music Generation
- medium
tags: []
---
**Abstract** - Recent progress in deep learning for audio synthesis opens the way to models that
directly produce the waveform, shifting away from the traditional paradigm of
relying on vocoders or MIDI synthesizers for speech or music generation. Despite
their successes, current state-of-the-art neural audio synthesizers such as WaveNet
and SampleRNN [24, 17] suffer from prohibitive training and inference times
because they are based on autoregressive models that generate audio samples one
at a time at a rate of 16kHz. In this work, we study the more computationally
efficient alternative of generating the waveform frame-by-frame with large strides.
We present SING, a lightweight neural audio synthesizer for the original task of
generating musical notes given desired instrument, pitch and velocity. Our model
is trained end-to-end to generate notes from nearly 1000 instruments with a single
decoder, thanks to a new loss function that minimizes the distances between the
log spectrograms of the generated and target waveforms. On the generalization
task of synthesizing notes for pairs of pitch and instrument not seen during training,
SING produces audio with significantly improved perceptual quality compared to a
state-of-the-art autoencoder based on WaveNet [4] as measured by a Mean Opinion
Score (MOS), and is about 32 times faster for training and 2, 500 times faster for
inference
**Paper** - [https://scontent-bom1-1.xx.fbcdn.net/v/t39.8562-6/240834622_997590737739307_5513666903256671510_n.pdf?_nc_cat=101&ccb=1-5&_nc_sid=ad8a9d&_nc_ohc=OXt8KnyuLlAAX8YgDnG&_nc_ht=scontent-bom1-1.xx&oh=00_AT_m4Ca1BlR5HmgMKdL-LZzYwzDGeBTnmGph7HX4uFwTsw&oe=6241EC7B](https://scontent-bom1-1.xx.fbcdn.net/v/t39.8562-6/240834622_997590737739307_5513666903256671510_n.pdf?_nc_cat=101&ccb=1-5&_nc_sid=ad8a9d&_nc_ohc=OXt8KnyuLlAAX8YgDnG&_nc_ht=scontent-bom1-1.xx&oh=00_AT_m4Ca1BlR5HmgMKdL-LZzYwzDGeBTnmGph7HX4uFwTsw&oe=6241EC7B)
**Code** - [https://github.com/facebookresearch/SING](https://github.com/facebookresearch/SING)
**Dataset -** [https://magenta.tensorflow.org/datasets/nsynth](https://magenta.tensorflow.org/datasets/nsynth)
    