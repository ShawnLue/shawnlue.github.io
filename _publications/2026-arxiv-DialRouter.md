---
title: "From Myopic Selection to Long-Horizon Awareness: Sequential LLM Routing for Multi-Turn Dialogue"
collection: publications
permalink: /publications/DialRouter
excerpt: "DialRouter: Sequential LLM Routing for Multi-Turn Dialogue with Long-Horizon Awareness"
date: 2026-04-18
venue: "arXiv"
year: 2026
paperurl: "https://arxiv.org/pdf/2604.12385"
slide: "TBA"
authorlist: "Jiarui Zhang, Xiangyu Liu, Yong Hu, Chaoyue Niu, Hang Zeng, Shaojie Tang, Fan Wu, Guihai Chen"
citation: "Jiarui Zhang, Xiangyu Liu, Yong Hu, Chaoyue Niu, Hang Zeng, Shaojie Tang, Fan Wu, Guihai Chen. 2026. From Myopic Selection to Long-Horizon Awareness: Sequential LLM Routing for Multi-Turn Dialogue. arXiv preprint arXiv:2604.12385."
status: 'arxiv'
---
**Abstract:**
Multi-turn dialogue is the predominant form of interaction with large language models (LLMs). While LLM routing is effective in single-turn settings, existing methods fail to maximize cumulative performance in multi-turn dialogue due to interaction dynamics and delayed rewards. To address this challenge, we move from myopic, single-turn selection to long-horizon sequential routing for multi-turn dialogue. Accordingly, we propose DialRouter, which first performs MCTS to explore dialogue branches induced by different LLM selections and collect trajectories with high cumulative rewards. DialRouter then learns a lightweight routing policy from search-derived data, augmented with retrieval-based future state approximation, enabling multi-turn routing without online search. Experiments on both open-domain and domain-specific dialogue tasks across diverse candidate sets of both open-source and closed-source LLMs demonstrate that DialRouter significantly outperforms single LLMs and existing routing baselines in task success rate, while achieving a superior performance-cost trade-offs when combined with a cost-aware reward.
