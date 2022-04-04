---
layout: post
author:
  name: Paper ID 20
  difficulty: Difficulty - Hard
share: true
title: Unpaired Portrait Drawing Generation via Asymmetric Cycle Mapping
categories:
- Computer Vision
- Image-to-Image Translation
- GANs
- 
- hard
tags: []
---
**Abstract** - Portrait drawing is a common form of art with high abstraction and expressiveness. Due to its unique characteristics, existing methods achieve decent results only with paired training data, which is costly and time-consuming to obtain. In this paper, we address the problem of automatic transfer from face photos to portrait drawings with unpaired  training data. We observe that due to the significant imbalance of information richness between photos and drawings, existing unpaired transfer methods such as CycleGAN tend to embed invisible reconstruction information indiscriminately in the whole drawings, leading to important facial features partially missing in drawings. To address this problem, we propose a novel asymmetric cycle mapping that enforces the reconstruction information to be visible (by a truncation loss) and only embedded in selective facial regions (by a relaxed forward cycle-consistency loss). Along with localized discriminators for the eyes, nose and lips, our method well preserves all important facial features in the generated portrait drawings. By introducing a style classifier and taking the style vector into account, our method can learn to generate portrait drawings in multiple styles using a single network. Extensive experiments show that our model outperforms state-of-the-art methods.

**Paper** - [https://openaccess.thecvf.com/content_CVPR_2020/papers/Yi_Unpaired_Portrait_Drawing_Generation_via_Asymmetric_Cycle_Mapping_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yi_Unpaired_Portrait_Drawing_Generation_via_Asymmetric_Cycle_Mapping_CVPR_2020_paper.pdf)
**Code** - [https://github.com/yiranran/Unpaired-Portrait-Drawing](https://github.com/yiranran/Unpaired-Portrait-Drawing)
**Dataset -** [links available in repo](links available in repo)
    