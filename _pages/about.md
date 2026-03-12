---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am <span class="accent-text">Ruikai Li (Ricky)</span>, <i class="fas fa-university"></i> a 2nd-year Ph.D. student at the School of Transportation Science and Engineering, **Beihang University (BUAA)**, advised by <a href="https://scholar.google.com/citations?user=kKHcRDkAAAAJ" class="link-accent">Prof. Zhiyong Cui</a>. Prior to my Ph.D., I received my B.Eng. degree from the joint program between Beijing University of Technology (BJUT) and Beihang University.

<div class="quote-accent">
My research interests focus on <strong>computer vision</strong> and <strong>efficient perception</strong>, including online HD map construction, cross-modal knowledge distillation, 3D semantic occupancy prediction, and driving scene generation. I have published papers at top venues such as ECCV, ICLR, CVPR, and IEEE TPAMI.
</div>

I had the privilege of interning at **Amap (AutoNavi)** (Mentor: <a href="https://scholar.google.com/citations?user=JGi4S0EAAAAJ" class="link-accent">Mu Xu</a>) and **Li Auto** (Mentor: <a href="https://scholar.google.com/citations?user=1J061HIAAAAJ" class="link-accent">Kun Zhan</a>), working on perception algorithms.

Feel free to reach out for research collaboration: `rickyli@buaa.edu.cn`

<div class="highlight-blocks">
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-graduation-cap"></i> Education</h3>
    <ul>
      <li>Ph.D. Student, Beihang University (2024.09 – Present)</li>
      <li>M.Eng., Beihang University (2022.09 – 2024.08)</li>
      <li>B.Eng., BJUT–Beihang Joint Program (2018.09 – 2022.06)</li>
    </ul>
  </div>
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-microscope"></i> Research Interests</h3>
    <ul>
      <li>Online HD Map Construction</li>
      <li>Cross-Modal Knowledge Distillation</li>
      <li>3D Semantic Occupancy Prediction & Scene Generation</li>
    </ul>
  </div>
</div>

# <i class="fas fa-star"></i> Selected Publications

For a full list, please visit <a href="https://scholar.google.com/citations?user=r309swkAAAAJ&hl=en" class="link-accent"><i class="fas fa-graduation-cap"></i> Google Scholar</a>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ECCV 2024</div>
    <img src='images/mapdistill_pipeline.png' alt="MapDistill" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>MapDistill: Boosting Efficient Camera-based HD Map Construction via Camera-LiDAR Fusion Model Distillation</h3>
    <div class="authors">Xiaoshuai Hao*, <strong>Ruikai Li*</strong>, Hui Zhang, et al.</div>
    <div class="venue">ECCV 2024 &middot; CCF-B &middot; Co-first Author</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2407.11682" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/BUAA-RickyLi/MapDistill" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ICLR 2026</div>
    <img src='images/stablehdmap_pipeline.png' alt="StableHDMap" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Stability Under Scrutiny: Benchmarking Representation Paradigms for Online HD Mapping</h3>
    <div class="authors">Hao Shan*, <strong>Ruikai Li*</strong>, Han Jiang, et al.</div>
    <div class="venue">ICLR 2026 &middot; CCF-A &middot; Co-first Author</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2510.10660" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/bhsh0112/MapStableTest" class="btn-accent"><i class="fab fa-github"></i> Code</a>
      <a href="https://stablehdmap.github.io/" class="btn-accent"><i class="fas fa-globe"></i> Project</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">CVPR 2026</div>
    <img src='images/amap_pipeline.png' alt="AMap" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>AMap: Distilling Future Priors for Ahead-Aware Online HD Map Construction</h3>
    <p style="color:#6c757d; font-size:0.85rem; margin:0 0 0.5rem 0;"><i class="fas fa-building"></i> Work done during internship at Amap</p>
    <div class="authors"><strong>Ruikai Li*</strong>, Xinrun Li*, Mengwei Xie, et al.</div>
    <div class="venue">CVPR 2026 &middot; CCF-A &middot; Co-first Author</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2512.19150" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Under Review</div>
    <video src='images/uniscenev2_demo.mp4' autoplay loop muted playsinline width="100%" style="border-radius:4px;"></video>
  </div>
  <div class='paper-box-text'>
    <h3>Scaling Up Occupancy-centric Driving Scene Generation: Dataset and Method</h3>
    <p style="color:#6c757d; font-size:0.85rem; margin:0 0 0.5rem 0;"><i class="fas fa-building"></i> Work done during internship at Li Auto</p>
    <div class="authors">Bohan Li, Xin Jin, Hu Zhu, ..., <strong>Ruikai Li</strong>, et al.</div>
    <div class="venue">Under Review &middot; Contributing Author</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2510.22973" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation/tree/v2" class="btn-accent"><i class="fab fa-github"></i> Code</a>
      <a href="https://arlo0o.github.io/uniscenev2/" class="btn-accent"><i class="fas fa-globe"></i> Project</a>
      <a href="https://huggingface.co/datasets/Arlolo0/Nuplan-Occupancy/tree/main" class="btn-accent"><i class="fas fa-database"></i> Dataset</a>
    </div>
  </div>
</div>

# <i class="fas fa-graduation-cap"></i> Education
- *2024.09 – Present*: **Beihang University (BUAA)**, Ph.D. Student, School of Transportation Science and Engineering.
- *2022.09 – 2024.08*: **Beihang University (BUAA)**, M.Eng., School of Transportation Science and Engineering.
- *2018.09 – 2022.06*: **BJUT–Beihang Joint Program**, B.Eng., School of Software Engineering.

# <i class="fas fa-laptop-code"></i> Industry Experience
- *2025.06 – 2025.12*: **Amap (AutoNavi)**, Research Intern — Efficient online vectorized map construction.
- *2024.12 – 2025.06*: **Li Auto**, Research Intern — Occupancy-centric driving scene generation.

# <i class="fas fa-users"></i> Academic Service
**Reviewer:**
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
- European Conference on Computer Vision (ECCV)
- International Conference on Learning Representations (ICLR)
- AAAI Conference on Artificial Intelligence (AAAI)
- Expert Systems With Applications (ESWA)
- IEEE Transactions on Vehicular Technology (TVT)
