---
layout: post
author:
  name: Paper ID 26
  difficulty: Difficulty - Hard
share: true
title: Node2vec- Scalable Feature Learning for Networks
categories:
- Graph-Learning
- hard
tags: []
---
**Abstract** - Prediction tasks over nodes and edges in networks require careful
effort in engineering features used by learning algorithms. Recent
research in the broader field of representation learning has led to
significant progress in automating prediction by learning the features themselves. However, present feature learning approaches
are not expressive enough to capture the diversity of connectivity
patterns observed in networks.
Here we propose node2vec, an algorithmic framework for learning continuous feature representations for nodes in networks. In
node2vec, we learn a mapping of nodes to a low-dimensional space
of features that maximizes the likelihood of preserving network
neighborhoods of nodes. We define a flexible notion of a node’s
network neighborhood and design a biased random walk procedure,
which efficiently explores diverse neighborhoods. Our algorithm
generalizes prior work which is based on rigid notions of network
neighborhoods, and we argue that the added flexibility in exploring
neighborhoods is the key to learning richer representations.
We demonstrate the efficacy of node2vec over existing state-ofthe-art techniques on multi-label classification and link prediction
in several real-world networks from diverse domains. Taken together, our work represents a new way for efficiently learning stateof-the-art task-independent representations in complex networks
**Paper** - [https://arxiv.org/pdf/1607.00653.pdf](https://arxiv.org/pdf/1607.00653.pdf)
**Code** - [https://github.com/aditya-grover/node2vec](https://github.com/aditya-grover/node2vec)
**Dataset -** [https://github.com/benedekrozemberczki/datasets](https://github.com/benedekrozemberczki/datasets)
    