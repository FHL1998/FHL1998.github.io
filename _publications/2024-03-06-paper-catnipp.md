---
title: "CAtNIPP: Context-aware attention-based network for informative path planning"
collection: publications
category: conferences
permalink: /publication/2024-03-06-catnipp
excerpt: 'This work is oral presented at the 6th Conference on Robot Learning (CoRL) 2024. Informative Path Planning (IPP) is a challenging problem that requires balancing exploration and exploitation under resource constraints. CAtNIPP introduces a fully reactive, deep reinforcement learning-based solution using self-attention to guide efficient path planning. By learning to form a global context and make adaptive local decisions, CAtNIPP outperforms traditional IPP methods in both performance and computation speed, with demonstrated results on real hardware.'
date: 2024-03-06
venue: 'Proceedings of Machine Learning Research'
paperurl: 'https://proceedings.mlr.press/v205/cao23b/cao23b.pdf'
citation: 'Cao, Y., Wang, Y., Vashisth, A., Fan, H. &amp; Sartoretti, G.A.. (2023). CAtNIPP: Context-Aware Attention-based Network for Informative Path Planning. <i>Proceedings of The 6th Conference on Robot Learning</i>, in <i>Proceedings of Machine Learning Research</i> 205:1928-1937'
---

Informative path planning (IPP) is an NP-hard problem, which aims at planning a path allowing an agent to build an accurate belief about a quantity of interest throughout a given search domain, within constraints on resource budget (e.g., path length for robots with limited battery life). IPP requires frequent online replanning as this belief is updated with every new measurement (i.e., adaptive IPP), while balancing short-term exploitation and longer-term exploration to avoid suboptimal, myopic behaviors. Encouraged by the recent developments in deep reinforcement learning, we introduce CAtNIPP, a fully reactive, neural approach to the adaptive IPP problem. CAtNIPP relies on self-attention for its powerful ability to capture dependencies in data at multiple spatial scales. Specifically, our agent learns to form a context of its belief over the entire domain, which it uses to sequence local movement decisions that optimize short- and longer-term search objectives. We experimentally demonstrate that CAtNIPP significantly outperforms state-of-the-art non-learning IPP solvers in terms of solution quality and computing time once trained, and present experimental results on hardware.
