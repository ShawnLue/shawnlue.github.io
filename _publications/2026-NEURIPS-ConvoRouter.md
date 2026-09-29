---
title: "Adaptive LLM Routing for Multi-Turn Conversations with Continuously Evolving User Queries"
collection: publications
permalink: /publications/ConvoRouter
redirect_from:
  - /publications/DialRouter
excerpt: "ConvoRouter: Adaptive LLM Routing for Multi-Turn Conversations with Continuously Evolving User Queries"
date: 2026-12-06
venue: "NeurIPS"
year: 2026
paperurl: "https://arxiv.org/pdf/2604.12385"
slide: "TBA"
authorlist: "Jiarui Zhang, Xiangyu Liu, Yong Hu, Chaoyue Niu, Hang Zeng, Shaojie Tang, Fan Wu, Guihai Chen"
citation: "Jiarui Zhang, Xiangyu Liu, Yong Hu, Chaoyue Niu, Hang Zeng, Shaojie Tang, Fan Wu, Guihai Chen. 2026. Adaptive LLM Routing for Multi-Turn Conversations with Continuously Evolving User Queries. In Proceedings of the Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS'26), Dec 6-12, 2026, Sydney, Australia."
status: 'pub'
---
**Abstract:**
Multi-turn conversation is the predominant form of interaction with large language models (LLMs), where user queries continuously evolve. However, existing LLM routing methods are primarily designed for single-turn interactions or fixed queries settings, overlooking the dynamic nature of multi-turn conversations and the challenge of delayed rewards, thereby limiting their ability to optimize cumulative performance. To address this challenge, we move from myopic, single-turn selection to long-horizon routing for multi-turn conversation. Accordingly, we propose ConvoRouter, which first performs MCTS to explore conversation branches induced by different LLM selections and collect trajectories with high cumulative rewards. ConvoRouter then learns a lightweight routing policy from search-derived data, augmented with retrieval-based future state approximation, enabling multi-turn routing without online search. Experiments on both open-domain and domain-specific conversation tasks across diverse candidate sets of both open-source and closed-source LLMs demonstrate that ConvoRouter significantly outperforms single LLMs and existing routing baselines in task success rate, while achieving a superior performance-cost trade-off when combined with a cost-aware reward.
