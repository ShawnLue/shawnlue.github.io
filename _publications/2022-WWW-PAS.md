---
title: "On Designing a Two-stage Auction for Online Advertising"
collection: publications
permalink: /publications/PAS
excerpt: "On Designing a Two-stage Auction for Online Advertising"
date: 2022-04-29
venue: "WWW"
year: 2022
paperurl: "https://arxiv.org/abs/2111.05555"
authorlist: "Yiqing Wang, Xiangyu Liu, Zhenzhe Zheng, Zhilin Zhang, Miao Xu, Chuan Yu, Fan Wu"
citation: "Yiqing Wang, Xiangyu Liu, Zhenzhe Zheng, Zhilin Zhang, Miao Xu, Chuan Yu and Fan Wu. 2022. On Designing a Two-stage Auction for Online Advertising. To appear in The Web Conference 2022, Virtual Event / Lion, France, April 25-29, 2022"
status: 'pub'
---
**Abstract:**
For the scalability of industrial online advertising systems, a twostage auction architecture is widely used to enable efficient ad allocation on a large set of corpus within a limited response time. The current deployed two-stage ad auction usually retrieves an ad subset by a coarse ad quality metric in a pre-auction stage, and then determines the auction outcome by a refined metric in the subsequent stage. However, this simple and greedy solution suffers from serious performance degradation, as it regards the decision in each stage separately, leading to an improper ad selection metric for the pre-auction stage. In this work, we explicitly investigate the relation between the coarse and refined ad quality metrics, and design a two-stage ad auction by taking the decision interaction between the two stages into account. We decouple the design of the two-stage auction by solving a stochastic subset selection problem in the pre-auction stage and conducting a general second price (GSP) auction in the second stage. We demonstrate that this decouple still preserves the incentive compatibility of the auction mechanism. As the proposed formulation of the pre-auction stage is an NPhard problem, we propose a scalable approximation solution by defining a new subset selection metric, namely Pre-Auction Score (PAS). Experiment results on both public and industrial dataset demonstrate the significant improvement on social welfare and revenue of the proposed two-stage ad auction, than the intuitive greedy two-stage auction and other baselines.

**Download: [[PDF]](https://arxiv.org/abs/2111.05555)**
