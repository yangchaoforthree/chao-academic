---
title:          "Evolving Minds: Logic-Informed Inference from Temporal Action Patterns"
date:           2025-01-26 00:01:00 +0800
selected:       true
pub:            "The International Conference on Machine Learning (ICML)"
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Oral</span>'
pub_date:       "2025"
# semantic_scholar_id: 11ac0b5634a282f1a0da204b98e7473d8b480dfb  # use this to retrieve citation count
abstract: >-
  Understanding human mental states—such as intentions and desires—is crucial for natural AIhuman collaboration. However, this is challenging because human actions occur irregularly over time, and the underlying mental states that drive these actions are unobserved. To tackle this, we propose a novel framework that combines a logicinformed temporal point process (TPP) with amortized variational Expectation-Maximization (EM). Our key innovation is integrating logic rules as priors to guide the TPP’s intensity function, allowing the model to capture the interplay between actions and mental events while reducing dependence on large datasets. To handle the intractability of mental state inference, we introduce a discrete-time renewal process to approximate the posterior. By jointly optimizing model parameters, logic rules, and inference networks, our approach infers entire mental event sequences and adaptively predicts future actions. Experiments on both synthetic and real-world datasets show that our method outperforms existing approaches in accurately inferring mental states and predicting actions, demonstrating its effectiveness in modeling human cognitive processes.

cover:          /assets/images/covers/Evolving.png
authors:
  - Chao Yang
  - Shuting Cui
  - Yang Yang
  - Shuang Li
links:
  Paper: https://openreview.net/pdf?id=QRms4lx0Fp
  # Code: https://github.com
  # Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---
