---
title: "HiMaCon: Discovering Hierarchical Manipulation Concepts from Unlabeled Multi-Modal Data"
collection: publications
permalink: /publication/HiMaCon
excerpt: 'HiMaCon is a self-supervised framework that learns hierarchical "manipulation concepts" from unlabeled multi-modal robot demonstrations without human annotation.'
date: 2025-09-19
venue: 'NeurIPS'
paperurl: 'https://arxiv.org/pdf/2510.11321'
citation: 'Liu, Ruizhe, et al. "$\textit {HiMaCon:} $ Discovering Hierarchical Manipulation Concepts from Unlabeled Multi-Modal Data." The Thirty-ninth Annual Conference on Neural Information Processing Systems.'
teaser: 'HiMaCon-teaser.jpeg'  # Add this line
---

Effective generalization in robotic manipulation requires representations that capture invariant patterns of interaction across environments and tasks. We present a self-supervised framework for learning hierarchical manipulation concepts that encode these invariant patterns through cross-modal sensory correlations and multi-level temporal abstractions without requiring human annotation.
Our approach combines a cross-modal correlation network that identifies persistent patterns across sensory modalities with a multi-horizon predictor that organizes representations hierarchically across temporal scales. Manipulation concepts learned through this dual structure enable policies to focus on transferable relational patterns while maintaining awareness of both immediate actions and longer-term goals. Empirical evaluation across simulated benchmarks and real-world deployments demonstrates significant performance improvements with our concept-enhanced policies.  Analysis reveals that the learned concepts resemble human-interpretable manipulation primitives despite receiving no semantic supervision. This work advances both the understanding of representation learning for manipulation and provides a practical approach to enhancing robotic performance in complex scenarios.
Code is available at: [https://github.com/zrllrz/HiMaCon](https://github.com/zrllrz/HiMaCon).