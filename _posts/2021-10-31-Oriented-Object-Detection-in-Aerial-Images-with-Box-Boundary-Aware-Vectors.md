---
layout: post
author:
  name: Paper ID 47
  difficulty: Difficulty - Hard
share: true
title: Oriented Object Detection in Aerial Images with Box Boundary-Aware Vectors
categories:
- CV
- hard
tags: []
---
**Abstract** - Oriented object detection in aerial images is a challenging task as the objects in aerial images are displayed in arbitrary directions and are usually densely packed. Current oriented object detection methods mainly rely on two-stage anchor-based detectors. However, the anchor-based detectors typically suffer from a severe imbalance issue between the positive and negative anchor boxes. To address this issue, in this work we extend the horizontal keypoint-based object detector to the oriented object detection task. In particular, we first detect the center keypoints of the objects, based on which we then regress the box boundary aware vectors (BBAVectors) to capture the oriented bounding boxes. The box boundary-aware vectors are distributed in the four quadrants of a Cartesian coordinate system for all arbitrarily oriented objects. To relieve the difficulty of learning the vectors in the corner cases, we further classify the oriented bounding boxes into horizontal and rotational bounding boxes. In the experiment, we show that learning the box boundary-aware vectors is superior to directly predicting the width, height, and angle of an oriented bounding box, as adopted in the baseline method. Besides, the proposed method competes favorably with state-of-the-art methods.
**Paper** - [https://arxiv.org/abs/2008.07043](https://arxiv.org/abs/2008.07043)
**Dataset -** [https://captain-whu.github.io/dota/](https://captain-whu.github.io/dota/)
    