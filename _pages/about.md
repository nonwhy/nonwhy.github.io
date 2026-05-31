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

# About Me

I'm currently a final-year M.Eng. student at Tsinghua University, supervised by Prof. Chun Yuan. Before that, I received my B.S. degree in Computer Science and Technology from Wuhan University in 2023. My research interests include **unified models** and **visual generation**.


# 🔥 News
- *2026.05*: &nbsp;🎉 Two papers accepted at ICML 2026!
- *2026.02*: &nbsp;🎉 Two papers accepted at CVPR 2026!
- *2026.02*: &nbsp;🚀 Released UniRef-Image-Edit — the first to apply GRPO to multi-image composition.
- *2026.01*: &nbsp;🚀 Released UniMRG — to explore how generation enhances understanding in unified models.
- *2026.01*: &nbsp;🚀 Released Skywork UniPic 3.0 — the first open-source multi-image composition framework.
- *2025.12*: &nbsp;🚀 Released MICo-150K — a large-scale multi-image composition dataset.
- *2025.11*: &nbsp;🎉 One paper accepted at TMM!
- *2025.08*: &nbsp;🚀 Released Skywork UniPic 2.0 — the first to apply GRPO to single-image editing.
- *2025.08*: &nbsp;🚀 Released Skywork UniPic 1.0 — a 1.5B unified model supporting understanding, generation, and editing.
- *2025.06*: &nbsp;🎉 One paper accepted at ICCV 2025!
- *2025.03*: &nbsp;🚀 Released PURE — the first MLLM-based image restoration framework.

# 📝 Selected Publications

*indicates equal contribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/uniref.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UniRef-Image-Edit: Towards Scalable and Consistent Multi-Reference Image Editing](https://arxiv.org/abs/2602.14186)

**Hongyang Wei**, et al.

Tech Report, 2026

[arXiv](https://arxiv.org/abs/2602.14186)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/unipic3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Skywork UniPic 3.0: Unified Multi-Image Composition via Sequence Modeling](https://arxiv.org/abs/2601.15664)

**Hongyang Wei**, et al.

Tech Report, 2026

[arXiv](https://arxiv.org/abs/2601.15664) / [Code](https://github.com/SkyworkAI/UniPic)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/unipic2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Skywork UniPic 2.0: Building kontext model with online rl for unified multimodal model](https://arxiv.org/abs/2509.04548)

**Hongyang Wei**, et al.

Tech Report, 2025

[arXiv](https://arxiv.org/abs/2509.04548) / [Code](https://github.com/SkyworkAI/UniPic)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/unipic1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Skywork UniPic 1.0:  Unified autoregressive modeling for visual understanding and generation](https://arxiv.org/abs/2508.03320)

Peiyu Wang, ..., **Hongyang Wei**, et al.

Tech Report, 2025

[arXiv](https://arxiv.org/abs/2508.03320) / [Code](https://github.com/SkyworkAI/UniPic)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/pure.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Perceive, Understand and Restore: Real-World Image Super-Resolution with Autoregressive Multimodal Generative Models](https://openaccess.thecvf.com/content/ICCV2025/html/Wei_Perceive_Understand_and_Restore_Real-World_Image_Super-Resolution_with_Autoregressive_Multimodal_ICCV_2025_paper.html)

**Hongyang Wei**, et al.

ICCV, 2025

[Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Wei_Perceive_Understand_and_Restore_Real-World_Image_Super-Resolution_with_Autoregressive_Multimodal_ICCV_2025_paper.html) / [Code](https://github.com/nonwhy/PURE)

<!-- - Token-level VQ-GAN / Diffusion token modeling for image restoration.
- Token-level Top-k decoding for efficiency. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/unimrg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generation Enhances Understanding in Unified Multimodal Models via Multi-Representation Generation](https://arxiv.org/abs/2601.21406)

Zihan Su * , **Hongyang Wei** * , et al.

ICML, 2026

[arXiv](https://arxiv.org/abs/2601.21406) / [Code](https://github.com/Sugewud/UniMRG)

<!-- - UMM: Unified Multimodal Model for generation and understanding.
- SFT Harmon: GenEval 71.37, 0.30 RecA.
- UniMRG benchmark comparing AR Show-o, AR+MAR, Harmon (AR+Diffusion), OpenUni. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/mico.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MICo-150K: A Comprehensive Dataset Advancing Multi-Image Composition](https://arxiv.org/abs/2512.07348)

Xinyu Wei * , Kangrui Cen * , **Hongyang Wei** * , et al.

CVPR, 2026

[arXiv](https://arxiv.org/abs/2512.07348) / [Code](https://github.com/A113N-W3I/TIIF-Bench)

<!-- - MICo-150K: The largest multi-image composition dataset, covering 3M+ training and 7K+ evaluation samples with 27 categories.
- Compose-by-Retrieval pipeline with GPT-4o, Nano-Banana, Qwen2.5-VL, ArcFace ID.
- MICo-Bench benchmark evaluation on BAGEL, Qwen-Image-Edit, OmniGen2, and Qwen-MICo. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/SpatialReward.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpatialReward: Bridging the Perception Gap in Online RL for Image Editing via Explicit Spatial Reasoning](https://arxiv.org/abs/2602.07458)

Yancheng Long, Yankai Yang, **Hongyang Wei**, et al.

ICML, 2026

[arXiv](https://arxiv.org/abs/2602.07458)

<!-- - Identified Attention Collapse issue in online RL for image editing.
- SpatialReward: bounding box → heatmap → pointwise reward for spatial reasoning.
- 260K Reward dataset, MultiEditReward-Bench, SOTA on EditThinker, OmniGen2, Gedit-Bench: +0.90 GPT-4.1 EditScore (+0.45). -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2026</div><img src='images/tiif.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TIIF-Bench: How Does Your T2I Model Follow Your Instructions?](https://arxiv.org/abs/2506.02161)

Xinyu Wei, Jinrui Zhang, Zeqing Wang, **Hongyang Wei**, et al.

arxiv, 2026

[arXiv](https://arxiv.org/abs/2506.02161) / [Code]()

<!-- - Identified Attention Collapse issue in online RL for image editing.
- SpatialReward: bounding box → heatmap → pointwise reward for spatial reasoning.
- 260K Reward dataset, MultiEditReward-Bench, SOTA on EditThinker, OmniGen2, Gedit-Bench: +0.90 GPT-4.1 EditScore (+0.45). -->
</div>
</div>

# 🎖 Selected Honors and Awards
- *2021.10*: ACM-ICPC Regional Contest (Shenyang Site) Silver Medal🥈
- *2020.10*: National Scholarship at Wuhan University🏅

# 📖 Education
- *2023.09 - 2026.06*, M.E. in Computer Science, Tsinghua University.
- *2019.09 - 2023.07*, B.E. in Computer Science, Wuhan University.

# 💻 Internships
- *2025 - 2026*, [Kuaishou (Kstar)](https://kwai-keye.github.io/), Beijing, China.
- *2025 - 2025*, [Skywork](https://www.skywork.ai/), Beijing, China.
- *2024 - 2025*, [OPPO](https://www.oppo.com/en/discover/technology/oppo-ai/), Shenzhen, China.