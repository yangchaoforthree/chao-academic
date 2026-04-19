---
title:          "Discovering Intrinsic Spatial-Temporal Logic Rules to Explain Human Actions"
date:           2024-01-21 00:01:00 +0800
selected:       false
pub:            "The Conference on Neural Information Processing Systems (NeurIPS)"
pub_date:       "2024"
# semantic_scholar_id: 11ac0b5634a282f1a0da204b98e7473d8b480dfb  # use this to retrieve citation count
abstract: >-
  We propose a logic-informed knowledge-driven modeling framework for human movements by analyzing their trajectories. Our approach is inspired by the fact that human actions are usually driven by their intentions or desires, and are influenced by environmental factors such as the spatial relationships with surrounding objects. In this paper, we introduce a set of spatial-temporal logic rules as knowledge to explain human actions. These rules will be automatically discovered from observational data. To learn the model parameters and the rule content, we design an expectation-maximization (EM) algorithm, which treats the rule content as latent variables. The EM algorithm alternates between the E-step and M-step: in the E-step, the posterior distribution over the latent rule content is evaluated; in the M-step, the rule generator and model parameters are jointly optimized by maximizing the current expected log-likelihood. Our model may have a wide range of applications in areas such as sports analytics, robotics, and autonomous cars, where understanding human movements are essential. We demonstrate the model’s superior interpretability and prediction performance on pedestrian and NBA basketball player datasets, both achieving promising results.

cover:          /assets/images/covers/STLR.png
authors:
  - Chengzhi Cao
  - Chao Yang
  - Ruimao Zhang
  - Shuang Li
links:
  Paper: https://proceedings.neurips.cc/paper_files/paper/2023/file/d69fdbe4d13080bb7fa33249ca136976-Paper-Conference.pdf
  # Code: https://github.com
  # Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---
