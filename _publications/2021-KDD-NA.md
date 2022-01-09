---
title: "Neural Auction: End-to-End Learning of Auction Mechanisms for E-Commerce Advertising"
collection: publications
permalink: /publications/NA
excerpt: "Neural Auction: End-to-End Learning of Auction Mechanisms for E-Commerce Advertising"
date: 2021-08-14
venue: "KDD"
year: 2021
paperurl: "https://arxiv.org/abs/2106.03593"
video: "https://dl.acm.org/doi/10.1145/3447548.3467103#"
slide: "https://shawnlue.github.io/files/KDD-ads-2024.pdf"
authorlist: "Xiangyu Liu, Chuan Yu, Zhilin Zhang, Zhenzhe Zheng, Yu Rong, Hongtao Lv, Da Huo, Yiqing Wang, Dagui Chen, Jian Xu, Fan Wu, Guihai Chen, Xiaoqiang Zhu"
citation: "Xiangyu Liu, Chuan Yu, Zhilin Zhang, Zhenzhe Zheng, Yu Rong, Hongtao Lv, Da Huo, Yiqing Wang, Dagui Chen, Jian Xu, Fan Wu, Guihai Chen, Xiaoqiang Zhu. 2021. Neural Auction: End-to-End Learning of Auction Mechanisms for E-Commerce Advertising. In Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining (KDD'21), Aug 14-18, 2021, Virtual Event, Singapore, 11 pages. https://dl.acm.org/doi/10.1145/3447548.3467103"
status: 'pub'
---
**Abstract:**
In e-commerce advertising, it is crucial to jointly consider various performance metrics, e.g., user experience, advertiser utility, and platform revenue. Traditional auction mechanisms, such as GSP and VCG auctions, can be suboptimal due to their fixed allocation rules to optimize a single performance metric (e.g., revenue or social welfare). Recently, data-driven auctions, learned directly from auction outcomes to optimize multiple performance metrics, have attracted increasing research interests. However, the procedure of auction mechanisms involves various discrete calculation operations, making it challenging to be compatible with continuous optimization pipelines in machine learning. In this paper, we design Deep Neural Auctions (DNAs) to enable end-to-end auction learning by proposing a differentiable model to relax the discrete sorting operation, a key component in auctions. We optimize the performance metrics by developing deep models to efficiently extract contexts from auctions, providing rich features for auction design. We further integrate the game theoretical conditions within the model design, to guarantee the stability of the auctions. DNAs have been successfully deployed in the e-commerce advertising system at Taobao. Experimental evaluation results on both large-scale data set as well as online A/B test demonstrated that DNAs significantly outperformed other mechanisms widely adopted in industry.

**Download: [[PDF]](https://arxiv.org/abs/2106.03593)**
**Video: [[ACM DL]](https://dl.acm.org/action/downloadSupplement?doi=10.1145%2F3447548.3467103&file=neural_auction_endtoend_learning_of-xiangyu_liu-chuan_yu-38958072-wB6A.mp4)**
**Slide: [[Slide]](https://shawnlue.github.io/files/KDD-ads-2024.pdf)**
