---
layout: post
author:
  name: Paper ID 11
  difficulty: Difficulty - Medium
share: true
title: Multitask_AET_With_Orthogonal_Tangent_Regularity_for_Dark_Object_Detection
categories:
- CV
- NN
- medium
tags: []
---
**Abstract** - Dark environment becomes a challenge for computer
vision algorithms owing to insufficient photons and undesirable noise. To enhance object detection in a dark
environment, we propose a novel multitask auto encoding transformation (MAET) model which is able to explore the intrinsic pattern behind illumination translation.
In a self-supervision manner, the MAET learns the intrinsic visual structure by encoding and decoding the realistic illumination-degrading transformation considering
the physical noise model and image signal processing
(ISP). Based on this representation, we achieve the object detection task by decoding the bounding box coordinates and classes. To avoid the over-entanglement of
two tasks, our MAET disentangles the object and degrading features by imposing an orthogonal tangent regularity. This forms a parametric manifold along which multitask predictions can be geometrically formulated by maximizing the orthogonality between the tangents along the
outputs of respective tasks. Our framework can be implemented based on the mainstream object detection architecture and directly trained end-to-end using normal
target detection datasets, such as VOC and COCO. We
have achieved the state-of-the-art performance using synthetic and real-world datasets. Codes will be released at
https://github.com/cuiziteng/MAET.
**Paper** - [https://openaccess.thecvf.com/content/ICCV2021/papers/Cui_Multitask_AET_With_Orthogonal_Tangent_Regularity_for_Dark_Object_Detection_ICCV_2021_paper.pdf](https://openaccess.thecvf.com/content/ICCV2021/papers/Cui_Multitask_AET_With_Orthogonal_Tangent_Regularity_for_Dark_Object_Detection_ICCV_2021_paper.pdf)
**Dataset -** [https://www.kaggle.com/sshikamaru/car-object-detection?select=data](https://www.kaggle.com/sshikamaru/car-object-detection?select=data)
    