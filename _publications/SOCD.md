---
title: "Offline Critic-Guided Diffusion Policy for Multi-User Delay-Constrained Scheduling"
authors: "Zhuoran Li, <span style='color: #007bff; font-weight: bold;'>Ruishuo Chen</span>, Hai Zhong, and Longbo Huang"
collection: publications
category: preprints
permalink: /publication/SOCD
excerpt: 'Developed SOCD: An offline reinforcement learning algorithm for multi-user delay-constrained scheduling.'
date: 2025-01-22
venue: 'In submission'
venue_short:
paperurl: "https://arxiv.org/pdf/2501.12942?"
---
Effective multi-user delay-constrained scheduling is crucial in various real-world applications, such as instant messaging, live streaming, and data center management. In these scenarios, schedulers must make real-time decisions to satisfy both delay and resource constraints without prior knowledge of system dynamics, which are often time-varying and challenging to estimate. Current learning-based methods typically require interactions with actual systems during the training stage, which can be difficult or impractical, as it is capable of significantly degrading system performance and incurring substantial service costs. To address these challenges, we propose a novel offline reinforcement learning-based algorithm, named \underline{S}cheduling By \underline{O}ffline Learning with \underline{C}ritic Guidance and \underline{D}iffusion Generation (SOCD), to learn efficient scheduling policies purely from pre-collected \emph{offline data}. SOCD innovatively employs a diffusion-based policy network, complemented by a sampling-free critic network for policy guidance. By integrating the Lagrangian multiplier optimization into the offline reinforcement learning, SOCD effectively trains high-quality constraint-aware policies exclusively from available datasets, eliminating the need for online interactions with the system. Experimental results demonstrate that SOCD is resilient to various system dynamics, including partially observable and large-scale environments, and delivers superior performance compared to existing methods.