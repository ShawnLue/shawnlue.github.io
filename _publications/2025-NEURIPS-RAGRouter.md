---
title: "RAGRouter: Learning to Route Queries to Multiple Retrieval-Augmented Language Models"
collection: publications
permalink: /publications/RAGRouter
excerpt: "RAGRouter: Learning to Route Queries to Multiple Retrieval-Augmented Language Models"
date: 2025-09-19
venue: "NeurIPS"
year: 2025
paperurl: "https://arxiv.org/pdf/2505.23052"
slide: "TBA"
authorlist: "Jiarui Zhang, Xiangyu Liu, Yong Hu, Chaoyue Niu, Fan Wu, Guihai Chen"
citation: "Jiarui Zhang, Xiangyu Liu, Yong Hu, Chaoyue Niu, Fan Wu, Guihai Chen. 2025. RAGRouter: Learning to Route Queries to Multiple Retrieval-Augmented Language Models. In Proceedings of the Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS'25), Dec 2-7, 2025, San Diego Convention Center, USA, 19 pages."
status: 'pub'
---
**Abstract:**
Retrieval-Augmented Generation (RAG) significantly improves the performance of Large Language Models (LLMs) on knowledge-intensive tasks. However, varying response quality across LLMs under RAG necessitates intelligent routing mechanisms, which select the most suitable model for each query from multiple retrieval-augmented LLMs via a dedicated router model. We observe that external documents dynamically affect LLMs’ ability to answer queries, while existing routing methods, which rely on static parametric knowledge representations, exhibit suboptimal performance in RAG scenarios. To address this, we formally define the new retrieval-augmented LLM routing problem, incorporating the influence of retrieved documents into the routing framework. We propose RAGRouter, a RAG-aware routing design, which leverages document embeddings and RAG capability embeddings with contrastive learning to capture knowledge representation shifts and enable informed routing decisions. Extensive experiments on diverse knowledge-intensive tasks and retrieval settings show that RAGRouter outperforms the best individual LLM by 3.61% on average and existing routing methods by 3.29%–9.33%. With an extended score-threshold-based mechanism, it also achieves strong performance-efficiency trade-offs under low-latency constraints.
