---
title: "Automated Annotation of Privacy Information in User Interactions with Large Language Models"
collection: publications
permalink: /publications/Automated_Annotation
excerpt: "Automated Annotation of Privacy Information in User Interactions with Large Language Models"
date: 2026-08-09
venue: "KDD"
year: 2026
paperurl: "https://arxiv.org/pdf/2505.20910"
slide: "TBA"
authorlist: "Hang Zeng, Xiangyu Liu, Yong Hu, Chaoyue Niu, Fan Wu, Shaojie Tang, Guihai Chen"
citation: "Hang Zeng, Xiangyu Liu, Yong Hu, Chaoyue Niu, Fan Wu, Shaojie Tang, Guihai Chen. 2026. Automated Annotation of Privacy Information in User Interactions with Large Language Models. In Proceedings of the 32nd SIGKDD Conference on Knowledge Discovery and Data Mining - Datasets and Benchmarks Track (KDD'26), Aug 9-13, 2026, Jeju Korea."
status: 'pub'
---
**Abstract:**
Users interacting with large language models (LLMs) under their real identifiers often unknowingly risk disclosing private information. Automatically notifying users whether their queries leak privacy and which phrases leak what private information has therefore become a practical need. Existing privacy detection methods, however, were designed for different objectives and application domains, typically tagging personally identifiable information (PII) in anonymous content, which is insufficient in real-name interaction scenarios with LLMs. In this work, to support the development and evaluation of privacy detection models for LLM interactions that are deployable on local user devices, we construct a large-scale multilingual dataset with 249K user queries and 154K annotated privacy phrases. In particular, we build an automated privacy annotation pipeline with strong LLMs to automatically extract privacy phrases from dialogue datasets and annotate leaked information. We also design evaluation metrics at the levels of privacy leakage, extracted privacy phrase, and privacy information. We further establish baseline methods using light-weight LLMs with both tuning-free and tuning-based methods, and report a comprehensive evaluation of their performance. Evaluation results reveal a gap between current performance and the requirements of real-world LLM applications, motivating future research into more effective local privacy detection methods grounded in our dataset.
