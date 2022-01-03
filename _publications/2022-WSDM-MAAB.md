---
title: "A Cooperative-Competitive Multi-Agent Framework for Auto-bidding in Online Advertising"
collection: publications
permalink: /publications/MAAB
excerpt: "A Cooperative-Competitive Multi-Agent Framework for Auto-bidding in Online Advertising"
date: 2022-02-21
venue: "WSDM"
year: 2022
paperurl: "https://arxiv.org/abs/2106.06224"
authorlist: "Chao Wen, Miao Xu, Zhilin Zhang, Zhenzhe Zheng, Yuhui Wang, Xiangyu Liu, Yu Rong, Dong Xie, Xiaoyang Tan, Chuan Yu, Jian Xu, Fan Wu, Guihai Chen, Xiaoqiang Zhu"
citation: "Chao Wen, Miao Xu, Zhilin Zhang, Zhenzhe Zheng, Yuhui Wang, Xiangyu Liu, Yu Rong, Dong Xie, Xiaoyang Tan, Chuan Yu, Jian Xu, Fan Wu, Guihai Chen, Xiaoqiang Zhu. 2020. A Cooperative-Competitive Multi-Agent Framework for Auto-bidding in Online Advertising. To appear in the Proceedings of the 15th ACM International Conference on Web Search and Data Mining (WSDM), 2022"
status: 'pub'
---
**Abstract:**
In online advertising, auto-bidding has become an essential tool for advertisers to optimize their preferred ad performance metrics by simply expressing high-level campaign objectives and constraints. Previous works designed auto-bidding tools from the view of single-agent, without modeling the mutual influence between agents. In this paper, we instead consider this problem from a distributed multi-agent perspective, and propose a general \underline{M}ulti-\underline{A}gent reinforcement learning framework for \underline{A}uto-\underline{B}idding, namely MAAB, to learn the auto-bidding strategies. First, we investigate the competition and cooperation relation among auto-bidding agents, and propose a temperature-regularized credit assignment to establish a mixed cooperative-competitive paradigm.

By carefully making a competition and cooperation trade-off among agents, we can reach an equilibrium state that guarantees not only individual advertiser's utility but also the system performance (social welfare). Second, to avoid the potential collusion behaviors of bidding low prices underlying the cooperation, we further propose bar agents to set a personalized bidding bar for each agent, and then alleviate the degradation of revenue. Third, to deploy MAAB to the large-scale advertising system with millions of advertisers, we propose a mean-field approach. By grouping advertisers with the same objective as a mean auto-bidding agent, the interactions among advertisers are greatly simplified, making it practical to train MAAB efficiently. Extensive experiments on the offline industrial dataset and Alibaba advertising platform demonstrate that our approach outperforms several baseline methods in terms of social welfare and revenue.

**Download: [[PDF]](https://arxiv.org/abs/2106.06224)**
