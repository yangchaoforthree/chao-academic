---
title:          "Discovering Logic-Informed Intrinsic Rewards to Explain Human Policies"
date:           2025-01-27 00:01:00 +0800
selected:       false
pub:            "ICML Workshop (PRAL)"
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Oral</span>'
pub_date:       "2025"
# semantic_scholar_id: 11ac0b5634a282f1a0da204b98e7473d8b480dfb  # use this to retrieve citation count
abstract: >-
  In high-stakes fields like healthcare, it is crucial to distill valuable strategic insights from expert clinicians. This paper focuses on extracting these knowledge-based insights from demonstrations provided by experts, where we represent the knowledge as a set of logical rules. Our learning framework is built upon the classic Inverse Reinforcement Learning (IRL). We assume that experts, like clinicians, are rational, and the treatments they choose are the best choices based on their logical understanding of the situation. Our algorithm can automatically extract these logical rules from their demonstrations. We introduce a neural logic tree generator, which is trained to generate logical statements step by step, starting from the goal and working backward. This mirrors the way humans engage in backward reasoning. Similarly, we interpret policy planning as a forward reasoning process, where the optimal policy is determined by finding the best path forward based on the provided rules. The neural logic tree generator and the policy are learned using the IRL until convergence. This process ultimately leads to the discovery of the most effective strategic rules. As a bonus, our algorithm also allows us to recover the reward function. In our experiments, we demonstrate that our method excels at discovering meaningful logical rules, particularly in the context of healthcare.

cover:          /assets/images/covers/IRL-TPP.png
authors:
  - Chengzhi Cao *
  - Yinghao Fu
  - Chao Yang
  - Shuang Li
links:
  Paper: https://openreview.net/pdf?id=mXDB3wuXhN
  # Code: https://github.com
  # Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---
