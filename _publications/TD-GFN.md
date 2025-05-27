---
title: "Proxy-Free GFlowNet"
authors: "<span style='color: #007bff; font-weight: bold;'>Ruishuo Chen</span>, Xun Wang, Rui Hu, Zhuoran Li, and Longbo Huang"
collection: publications
category: preprints
permalink: /publication/TD-GFN
excerpt: 'TD-GFN: a proxy-free framework for training GFlowNets from offline data, achieving superior efficiency and performance without out-of-dataset reward queries.'
date: 2025-05-16
venue: 'In submission'
venue_short:
paperurl: "https://arxiv.org/pdf/2505.20110"
---
Generative Flow Networks (GFlowNets) are a promising class of generative models designed to sample diverse, high-reward structures by modeling distributions over compositional objects. In many real-world applications, obtaining the reward function for such objects is expensive, time-consuming, or requires human input, making it necessary to train GFlowNets from historical datasets. Most existing methods adopt a model-based approach, learning a proxy model from the dataset to approximate the reward function. However, this strategy inherently ties the quality of the learned policy to the accuracy of the proxy, introducing additional complexity and uncertainty into the training process. To overcome these limitations, we propose **Trajectory-Distilled GFlowNet (TD-GFN)**, a *proxy-free* training framework that eliminates the need for out-of-dataset reward queries. Our method is motivated by the key observation that different edges in the associated directed acyclic graph (DAG) contribute unequally to effective policy learning. TD-GFN leverages inverse reinforcement learning to estimate edge-level rewards from the offline dataset, which are then used to ingeniously prune the DAG and guide backward trajectory sampling during training. This approach directs the policy toward high-reward regions while reducing the complexity of model fitting. Empirical results across multiple tasks show that TD-GFN trains both efficiently and reliably, significantly outperforming existing baselines in convergence speed and sample quality.