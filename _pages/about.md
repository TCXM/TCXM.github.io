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

I am currently an undergraduate student majoring computer science at Duke Kunshan University.

My research interest includes multi-agent collaboration, combination of LLMs and task allocation, etc.

# 🔥 News
- *2025.06*: &nbsp;🎉🎉 One papaer is accepted by IROS 2025.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2025</div><img src='images/cocoplan.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoCoPlan: Adaptive Coordination and Communication for Multi-robot Systems in Dynamic and Unknown Environments](https://www.ieee-ras.org/publications/ra-l/submission-procedures)

Xintong Zhang, Junfeng Chen, *Yuxiao Zhu*, and Meng Guo

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

[**Project**](https://tcxm.github.io/DEXTER-LLM/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose DEXTER-LLM, a novel framework for dynamic task planning in unknown environments. Our approach integrates LLM-based multi-stage reasoning, optimization-based task assignment, and adaptive human-in-the-loop verification to tackle the challenges of online adaptability and explainability.
</div>
</div>

# 📖 Educations
- *2023.08 - 2025.09 (now)*, Undergraduate, Duke Kunshan University, Suzhou
- *2020.09 - 2023.06*, Taicang Senior High School of Jiangsu Province, Suzhou
