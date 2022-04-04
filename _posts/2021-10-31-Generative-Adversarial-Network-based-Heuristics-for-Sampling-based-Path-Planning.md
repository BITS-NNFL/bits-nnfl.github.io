---
layout: post
author:
  name: Paper ID 23
  difficulty: Difficulty - Medium
share: true
title: Generative Adversarial Network based Heuristics for Sampling-based Path Planning
categories:
- Path Planning
- Conditional GANs
- medium
tags: []
---
**Abstract** - —Sampling-based path planning is a popular methodology for robot path planning. With a uniform sampling strategy
to explore the state space, a feasible path can be found without the
complex geometric modeling of the configuration space. However,
the quality of initial solution is not guaranteed and the convergence speed to the optimal solution is slow. In this paper, we
present a novel image-based path planning algorithm to overcome
these limitations. Specifically, a generative adversarial network
(GAN) is designed to take the environment map (denoted as
RGB image) as the input without other preprocessing works. The
output is also an RGB image where the promising region (where a
feasible path probably exists) is segmented. This promising region
is utilized as a heuristic to achieve non-uniform sampling for the
path planner. We conduct a number of simulation experiments to
validate the effectiveness of the proposed method, and the results
demonstrate that our method performs much better in terms
of the quality of initial solution and the convergence speed to
the optimal solution. Furthermore, apart from the environments
similar to the training set, our method also works well on the
environments which are very different from the training set.
**Paper** - [https://arxiv.org/pdf/2012.03490.pdf](https://arxiv.org/pdf/2012.03490.pdf)
**Code** - [https://github.com/akanametov/pathgan](https://github.com/akanametov/pathgan)
**Dataset -** [link available in repo](link available in repo)
    