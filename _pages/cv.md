---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **Ph.D. in Computer Science**, Peking University &nbsp; · &nbsp; *2015 – 2020*
  - School of Electronics Engineering and Computer Science (EECS)
  - Key Laboratory of Machine Perception and Intelligence
  - Advisor: Prof. Ying Tan
- **B.S. in Intelligence Science and Technology**, Nankai University &nbsp; · &nbsp; *2011 – 2015*
- **Dual B.A. in Business Administration**, Tianjin University &nbsp; · &nbsp; *2012 – 2015*

## Experience

- **Senior Researcher**, WeChat AI, Tencent &nbsp; · &nbsp; *2021 – Present*
  - LLMs and their applications: personalization, privacy-aware interaction, retrieval-augmented generation routing, device–cloud collaborative deployment.
- **Senior Algorithm Engineer**, Alibaba Group — Display Advertising &nbsp; · &nbsp; *2020 – 2021*
  - Learning-based mechanism design and auction optimization for display advertising.
- **Research Intern**, Alibaba Group &nbsp; · &nbsp; *2019*
  - Reinforcement learning and mechanism design for e-commerce advertising.
- **Research Intern**, [Horizon Robotics](https://en.horizon.ai/) &nbsp; · &nbsp; *2016 – 2019*
  - Reinforcement learning for autonomous driving and game AI.

## Academic Collaborations

- Device–Cloud LLM applications with [Dr. Chaoyue Niu](https://scholar.google.com/citations?hl=en&user=SHb5q08AAAAJ&view_op=list_works&sortby=pubdate), Shanghai Jiao Tong University. *2023 – Present*
- Learning-based mechanism design in e-commerce advertising with [Dr. Zhenzhe Zheng](https://zhengzhenzhe220.github.io/), Shanghai Jiao Tong University. *2020 – 2021*

## Research Interests

- **LLMs and their Applications** — personalization, privacy-aware interaction, retrieval-augmented generation routing, device–cloud collaborative deployment.
- **Reinforcement Learning** — multi-agent coordination, representation learning, exploration.
- **Mechanism Design & Learning-based Auctions** — for online advertising systems.

## Selected Publications

See the [Publications](/publications/) page for the complete list.

<ul class="pub-list">
{% assign sorted_publications = site.publications | sort: "date" | reverse %}
{% for post in sorted_publications %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Academic Services

- **Program Committee / Conference Reviewer**: WWW 2022, WCCI 2022, ECML-PKDD 2022, IJCAI 2023, KDD 2023, NeurIPS 2023, IJCAI 2024, KDD 2025, ICML 2026.
- **Journal Reviewer**: IEEE Transactions on Cybernetics (TCYB), Natural Computing.
