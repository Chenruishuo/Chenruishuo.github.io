---
title: "Provably and Practically Efficient Adversarial Imitation Learning with General Function Approximation"
authors: "Tian Xu*, Zhilong Zhang*, <span style='color: #007bff; font-weight: bold;'>Ruishuo Chen</span>, Yihao Sun, and Yang Yu"
collection: publications
category: conferences
permalink: /publication/OPT-AIL
excerpt: 'Developed OPT-AIL: First provably efficient adversarial imitation learning with general function approximation, achieving SOTA performance through simplified optimization.'
date: 2024-09-26
venue: 'The Thirty-eighth Annual Conference on Neural Information Processing Systems'
venue_short: '<span style="color: #28a745;">[NeurIPS]</span>'
paperurl: "https://arxiv.org/pdf/2411.00610"
---
As a prominent category of imitation learning methods, adversarial imitation learning (AIL) has garnered significant practical success powered by neural network approximation. However, existing theoretical studies on AIL are primarily limited to simplified scenarios such as tabular and linear function approximation and involve complex algorithmic designs that hinder practical implementation, highlighting a gap between theory and practice. In this paper, we explore the theoretical underpinnings of online AIL with general function approximation. We introduce a new method called optimization-based AIL (OPT-AIL), which centers on performing online optimization for reward functions and optimism-regularized Bellman error minimization for Q-value functions. Theoretically, we prove that OPT-AIL achieves polynomial expert sample complexity and interaction complexity for learning near-expert policies. To our best knowledge, OPT-AIL is the first provably efficient AIL method with general function approximation. Practically, OPT-AIL only requires the approximate optimization of two objectives, thereby facilitating practical implementation. Empirical studies demonstrate that OPT-AIL outperforms previous state-of-the-art deep AIL methods in several challenging tasks.