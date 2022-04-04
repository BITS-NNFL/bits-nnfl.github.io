---
layout: post
author:
  name: Paper ID 55
  difficulty: Difficulty - Hard
share: true
title: CausalVAE- Disentangled Representation Learning via Neural Structural Causal Models
categories:
- Generative Models
- hard
tags: []
---
**Abstract** - Learning disentanglement aims at finding a low dimensional representation which consists of multiple explanatory and generative factors of the observational data. The framework of variational autoencoder (VAE) is commonly used to disentangle independent factors from observations. However, in real scenarios, factors with semantics are not necessarily independent. Instead, there might be an underlying causal structure which renders these factors dependent. We thus propose a new VAE based framework named CausalVAE, which includes a Causal Layer to transform independent exogenous factors into causal endogenous ones that correspond to causally related concepts in data. We further analyze the model identifiabitily, showing that the proposed model learned from observations recovers the true one up to a certain degree. Experiments are conducted on various datasets, including synthetic and real word benchmark CelebA. Results show that the causal representations learned by CausalVAE are semantically interpretable, and their causal relationship as a Directed Acyclic Graph (DAG) is identified with good accuracy. Furthermore, we demonstrate that the proposed CausalVAE model is able to generate counterfactual data through "do-operation" to the causal factors.
**Paper** - [https://arxiv.org/abs/2004.08697](https://arxiv.org/abs/2004.08697)
**Code** - [https://github.com/huawei-noah/trustworthyAI/tree/master/Causal_Disentangled_Representation_Learning](https://github.com/huawei-noah/trustworthyAI/tree/master/Causal_Disentangled_Representation_Learning)
**Dataset -** [https://www.crowdhuman.org/](https://www.crowdhuman.org/)
    