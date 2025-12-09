---
title: "AutoCGP: Closed-Loop Concept-Guided Policies from Unlabeled Demonstrations"
collection: publications
permalink: /publication/AutoCGP
excerpt: 'AutoCGP is a framework for training robots to perform complex manipulation tasks by automatically discovering and using "manipulation concepts" (motor skills like grasping, pushing, etc.) without human annotations.'
date: 2025-01-23
venue: 'ICLR'
paperurl: 'https://openreview.net/pdf?id=9ehJCZz4aM'
citation: 'Zhou, Pei, et al. "AutoCGP: Closed-Loop Concept-Guided Policies from Unlabeled Demonstrations." The Thirteenth International Conference on Learning Representations.'
teaser: 'AutoCGP-teaser.jpeg'  # Add this line
---

Training embodied agents to perform complex robotic tasks presents significant challenges due to the entangled factors of task compositionality, environmental diversity, and dynamic changes. In this work, we introduce a novel imitation learning framework to train closed-loop concept-guided policies that enhance long-horizon task performance by leveraging discovered manipulation concepts. Unlike methods that rely on predefined skills and human-annotated labels, our approach allows agents to autonomously abstract manipulation concepts from their proprioceptive states, thereby alleviating misalignment due to ambiguities in human semantics and environmental complexity. Our framework comprises two primary components: an *Automatic Concept Discovery* module that identifies meaningful and consistent manipulation concepts, and a *Concept-Guided Policy Learning* module that effectively utilizes these manipulation concepts for adaptive task execution, including a *Concept Selection Transformer* for concept-based guidance and a *Concept-Guided Policy* for action prediction with the selected concepts. Experiments demonstrate that our approach significantly outperforms baseline methods across a range of tasks and environments, while showcasing emergent consistency in motion patterns associated with the discovered manipulation concepts. Codes are available at: [https://github.com/PeiZhou26/AutoCGP](https://github.com/PeiZhou26/AutoCGP).
