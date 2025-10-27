---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm an undergraduate student majoring computer science at Duke Kunshan University. I am recently collaborating with Prof. [Meng Guo (国萌)](https://mengguo.github.io/personal_site/) and his team, especially Dr. [Junfeng Chen (陈俊锋)](https://junfengchen-robotics.github.io/) from Peking University. I am a member of [Edge Intelligence Lab](https://sites.duke.edu/edgeintelligence/) supervised by Prof. [Bing Luo (罗冰)](https://luobing1008.github.io/index.html).

My research interests focus on adaptive coordination and communication in multi-robot systems, particularly under challenging conditions such as intermittent connectivity, limited communication, and unknown environments. I specialize in developing frameworks that optimize task planning, dynamic allocation, and communication strategies for heterogeneous robotic fleets (e.g., UAVs/UGVs) using LLM, optimization, and tree-search algorithms. My work emphasizes creating robust, scalable, and explainable solutions for real-world applications, including large-scale 3D exploration, inspection, and interaction. Through high-fidelity simulations and innovative algorithmic designs, I aim to address practical challenges in dynamic scenarios while ensuring reliable system performance.

# 🔥 News
- *2025.06*: &nbsp;🎉🎉 One papaer is accepted by IROS 2025.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Science Robotics 2025</div><img src='images/dexter_llm_plus.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLMs Meet Formal Methods for Robot Swarms: Reliable, Explainable and Efficient Human-in-the-loop Planning in Unknown Environments](https://www.science.org/journal/scirobotics)

Junfeng Chen, **Yuxiao Zhu**, An Zhuo, Xintong Zhang, Shuo Zhang, Meng Guo, and Zhongkui Li.

[**Video**](https://www.youtube.com/watch?v=dwQUosh9Kds&feature=youtu.be) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a formal method and LLM framework for coordinating large fleets of heterogeneous robots in open and dynamic environments. Our approach integrates model-checking-based task planning with LLM-powered reasoning and interaction, ensuring adaptability, explainability, and optimal mission execution. Validated through simulations and real-world deployments, it proves effective for disaster response, infrastructure inspection, and dynamic surveillance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2025</div><img src='images/cocoplan.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoCoPlan: Adaptive Coordination and Communication for Multi-robot Systems in Dynamic and Unknown Environments](https://www.ieee-ras.org/publications/ra-l/submission-procedures)

Xintong Zhang, Junfeng Chen, **Yuxiao Zhu**, and Meng Guo

[**Project**](https://junfengchen-robotics.github.io/SLEI3D/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose CoCoPlan, a unified framework that co-optimizes collaborative task planning and intermittent communication for multi-robot systems. Our approach integrates the branch-and-bound task encoding, adaptive efficiency objectives, and optimized event scheduling to handle dynamic environments under limited connectivity in both office and disaster-response scenarios.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ASE 2025</div><img src='images/slei3d.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SLEI3D: Simultaneous Exploration and Inspection via Heterogeneous Fleets under Limited Communication](https://www.ieee-ras.org/publications/t-ase/information-for-authors-t-ase)

Junfeng Chen, **Yuxiao Zhu**, Xintong Zhang, and Meng Guo

[**Project**](https://junfengchen-robotics.github.io/SLEI3D/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose SLEI3D, a planning and coordination framework for heterogeneous multi-robot systems to perform simultaneous 3D exploration, inspection, and real-time reporting in unknown environments. Our approach integrates adaptive inspection and intermittent communication protocols with a multi-layer, multi-rate planning mechanism for robust coordination.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='images/dexter_llm.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DEXTER-LLM: Dynamic and Explainable Coordination of Multi-Robot Systems in Unknown Environments via Large Language Models](https://arxiv.org/pdf/2508.14387)

**Yuxiao Zhu**, Junfeng Chen, Xintong Zhang, Meng Guo, Zhongkui Li

[**Project Homepage**](https://tcxm.github.io/DEXTER-LLM/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose DEXTER-LLM, a novel framework for dynamic task planning in unknown environments. Our approach integrates LLM-based multi-stage reasoning, optimization-based task assignment, and adaptive human-in-the-loop verification to tackle the challenges of online adaptability and explainability.
</div>
</div>

# 📖 Educations
- *2023.08 - 2025.11 (now)*, Undergraduate, Duke Kunshan University, Suzhou
- *2020.09 - 2023.06*, Taicang Senior High School of Jiangsu Province, Suzhou
