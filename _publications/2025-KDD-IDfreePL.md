---
title: "Personalized Language Model Learning on Text Data Without User Identifiers"
collection: publications
permalink: /publications/IDfreePL
excerpt: "Personalized Language Model Learning on Text Data Without User Identifiers"
date: 2024-11-16
venue: "KDD"
year: 2025
paperurl: "https://arxiv.org/pdf/2501.06062"
slide: "TBA"
authorlist: "Yucheng Ding, Yangwenjian Tan, Xiangyu Liu, Chaoyue Niu, Fandong Meng, Jie Zhou, Ning Liu, Fan Wu, Guihai Chen"
citation: "Yucheng Ding, Yangwenjian Tan, Xiangyu Liu, Chaoyue Niu, Fandong Meng, Jie Zhou, Ning Liu, Fan Wu, Guihai Chen. 2025. Personalized Language Model Learning on Text Data Without User Identifiers. In Proceedings of the 31th ACM SIGKDD Conference on Knowledge Discovery & Data Mining (KDD'25), Aug 3-7, 2025, Toronto, ON, Canada, 11 pages."
status: 'pub'
---
**Abstract:**
In many practical natural language applications, user data are highly sensitive, requiring anonymous uploads of text data from mobile devices to the cloud without user identifiers. However, the absence of user identifiers restricts the ability of cloud-based language models to provide personalized services, which are essential for catering to diverse user needs. The trivial method of replacing an explicit user identifier with a static user embedding as model input still compromises data anonymization. In this work, we propose to let each mobile device maintain a user-specific distribution to dynamically generate user embeddings, thereby breaking the one-to-one mapping between an embedding and a specific user. We further theoretically demonstrate that to prevent the cloud from tracking users via uploaded embeddings, the local distributions of different users should either be derived from a linearly dependent space to avoid identifiability or be close to each other to prevent accurate attribution. Evaluation on both public and industrial datasets using different language models reveals a remarkable improvement in accuracy from incorporating anonymous user embeddings, while preserving real-time inference requirement. 
