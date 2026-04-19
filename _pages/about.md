---
layout: archive
title: ""
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
  - /aboutme
  - /_pages/about
---

{% include base_path %}

<div class="hero">
  <h1 class="hero__name">Xiangyu Liu <span class="hero__name-alt">· 刘翔宇</span></h1>
  <p class="hero__tagline">Senior Researcher @ WeChat AI, Tencent · Ph.D. from Peking University</p>
</div>

## About

I am a Senior Researcher at **WeChat AI, Tencent**. I received my Ph.D. in July 2020 from the **Key Laboratory of Machine Perception and Intelligence, School of EECS, Peking University**, under the supervision of Prof. Ying Tan. Before that, I earned a B.S. in Intelligence Science and Technology from **Nankai University** and a dual B.A. in Business Administration from **Tianjin University** in 2015.

My current research focuses on **Large Language Models and their Applications** — in particular, **personalization**, **privacy-aware interaction**, **retrieval-augmented generation**, and **device–cloud collaborative deployment**. Earlier work spans **reinforcement learning**, **mechanism design**, and **evolutionary computation**, with applications in e-commerce advertising and game AI.

> *Nothing is more practical than a good theory.*

## News

- **2026-04** &nbsp; Paper on automated privacy annotation in LLM interactions accepted to **KDD'26** (Datasets & Benchmarks Track).
- **2025-09** &nbsp; **RAGRouter** accepted to **NeurIPS 2025** — learning to route queries across retrieval-augmented LLMs.
- **2025-05** &nbsp; Paper on ID-free personalized LM learning accepted to **KDD 2025**.

<div class="hiring-call" markdown="1">
**📣 &nbsp; Hiring research interns** &nbsp;—&nbsp; I am looking for motivated students to work on **memory agents for on-device LLM assistants**, with a concrete landing scenario on **smart keyboards**. Strong background in LLMs / agents / systems / ML preferred. Remote or on-site in Beijing. Drop me an [email](mailto:liuxiangyu.george@gmail.com) with your CV and a short note on why you are interested.
</div>

## Research Interests

- **LLMs and their Applications** &nbsp;*(current focus)*
  - **Memory agent for on-device assistants** — persistent, personalized long-term memory for LLM agents (e.g., smart keyboards).
  - **Personalization without identifiers** — learning user-adaptive models from anonymous text data. (KDD'25)
  - **Privacy-aware interaction** — detecting and annotating privacy leakage in LLM dialogues to enable on-device protection. (KDD'26)
  - **Retrieval-augmented routing** — learning to route queries across multiple retrieval-augmented LLMs for quality–efficiency trade-off. (NeurIPS'25)
  - **Device–cloud collaborative deployment** — splitting computation and knowledge between mobile devices and the cloud.
- **Reinforcement Learning** — multi-agent coordination, representation learning, exploration.
- **Mechanism Design & Learning-based Auctions** — for online advertising systems.

## Selected Publications

<ul class="pub-list pub-list--selected">
{% assign selected_keys = "APA,RAGRouter,IDfreePL,NA,DeepGSP,ARE" | split: "," %}
{% for key in selected_keys %}
  {% for post in site.publications %}
    {% if post.permalink contains key %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
{% endfor %}
</ul>

A full list is available on the [Publications](/publications/) page and on [Google Scholar](https://scholar.google.com/citations?user=qPRsI4kAAAAJ&hl=en).

## Academic Collaborations & Industry Experience

- **Research collaboration**, Shanghai Jiao Tong University — Device–cloud LLM applications with [Dr. Chaoyue Niu](https://scholar.google.com/citations?hl=en&user=SHb5q08AAAAJ&view_op=list_works&sortby=pubdate). *2023 – Present*
- **Research collaboration**, Shanghai Jiao Tong University — Learning-based mechanism design for e-commerce advertising with [Dr. Zhenzhe Zheng](https://zhengzhenzhe220.github.io/). *2020 – 2021*
- **Senior Algorithm Engineer**, Alibaba Group — Display Advertising — Learning-based mechanism design and auction optimization. *2020 – 2021*
- **Research Intern**, Alibaba — Reinforcement learning in e-commerce. *2019*
- **Research Intern**, [Horizon Robotics](https://en.horizon.ai/) — Reinforcement learning for autonomous vehicles and game AI. *2016 – 2019*

## Academic Services

- **Program Committee / Conference Reviewer**: WWW 2022, WCCI 2022, ECML-PKDD 2022, IJCAI 2023, KDD 2023, NeurIPS 2023, IJCAI 2024, KDD 2025, ICML 2026.
- **Journal Reviewer**: IEEE Transactions on Cybernetics (TCYB), Natural Computing.

## Contact

- Email &nbsp; · &nbsp; [liuxiangyu.george@gmail.com](mailto:liuxiangyu.george@gmail.com)
- WeChat &nbsp; · &nbsp; `shawnlue_lxy93`
- GitHub &nbsp; · &nbsp; [@ShawnLue](https://github.com/ShawnLue)
