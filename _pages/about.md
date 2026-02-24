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

我是 <span class="accent-text">李睿楷（Ricky Li）</span>，<i class="fas fa-university"></i> **北京航空航天大学**交通科学与工程学院2024级博士生（硕转博），导师为 <a href="https://scholar.google.com/citations?user=kKHcRDkAAAAJ" class="link-accent">崔志勇教授</a>（海外优青），所在团队为**车路一体智能交通全国重点实验室**（<a href="https://www.cae.cn/cae/html/main/colys/92472279.html" class="link-accent">王云鹏院士</a>直属团队）。此前，我于北京工业大学-北京航空航天大学双培计划获得工学学士学位。

<div class="quote-accent">
我的研究兴趣聚焦于<strong>自动驾驶感知</strong>与<strong>模型轻量化</strong>，具体包括在线高精地图构建、跨模态知识蒸馏、3D 语义占用预测与自动驾驶世界模型。目前已在 ECCV、ICLR等会议与IEEE-TPAMI、IEEE-TMM等期刊发表/投稿多篇论文。
</div>

我很荣幸曾在**高德地图**（Mentor：<a href="https://scholar.google.com/citations?user=JGi4S0EAAAAJ" class="link-accent">徐牧</a>）与**理想汽车**（Mentor：<a href="https://scholar.google.com/citations?user=1J061HIAAAAJ" class="link-accent">詹锟</a>）从事自动驾驶感知算法研究。

欢迎通过邮件交流科研合作：`rickyli@buaa.edu.cn`

<div class="highlight-blocks">
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-graduation-cap"></i> 教育背景</h3>
    <ul>
      <li>博士（硕转博），北京航空航天大学（2024.09 - 至今）</li>
      <li>硕士，北京航空航天大学（2022.09 - 2024.08）</li>
      <li>本科，北京工业大学-北京航空航天大学双培（2018.09 - 2022.06）</li>
    </ul>
  </div>
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-microscope"></i> 科研方向</h3>
    <ul>
      <li>在线高精地图构建（Online HD Mapping）</li>
      <li>多模态蒸馏与跨模态先验迁移</li>
      <li>自动驾驶 3D 语义占用预测与世界模型</li>
    </ul>
  </div>
</div>

# <i class="fas fa-star"></i> 代表工作

更多论文请见 <a href="https://scholar.google.com/citations?user=r309swkAAAAJ&hl=zh-CN" class="link-accent"><i class="fas fa-graduation-cap"></i> Google Scholar</a>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ECCV 2024</div>
    <img src='images/mapdistill_pipeline.png' alt="MapDistill" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>MapDistill: Boosting Efficient Camera-based HD Map Construction via Camera-LiDAR Fusion Model Distillation</h3>
    <div class="authors">Xiaoshuai Hao*, <strong>Ruikai Li*</strong>, Hui Zhang, et al.</div>
    <div class="venue">ECCV 2024 &middot; CCF-B &middot; 共同第一作者</div>
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
    <div class="venue">ICLR 2026 &middot; 共同第一作者</div>
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
    <p style="color:#6c757d; font-size:0.85rem; margin:0 0 0.5rem 0;"><i class="fas fa-building"></i> 高德地图实习期间完成</p>
    <div class="authors"><strong>Ruikai Li*</strong>, Xinrun Li*, Mengwei Xie, et al.</div>
    <div class="venue">CVPR 2026 &middot; CCF-A &middot; 共同第一作者</div>
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
    <p style="color:#6c757d; font-size:0.85rem; margin:0 0 0.5rem 0;"><i class="fas fa-building"></i> 理想汽车实习期间完成</p>
    <div class="authors">Bohan Li, Xin Jin, Hu Zhu, ..., <strong>Ruikai Li</strong>, et al.</div>
    <div class="venue">Under Review &middot; 参与作者</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2510.22973" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation/tree/v2" class="btn-accent"><i class="fab fa-github"></i> Code</a>
      <a href="https://arlo0o.github.io/uniscenev2/" class="btn-accent"><i class="fas fa-globe"></i> Project</a>
      <a href="https://huggingface.co/datasets/Arlolo0/Nuplan-Occupancy/tree/main" class="btn-accent"><i class="fas fa-database"></i> Dataset</a>
    </div>
  </div>
</div>

# <i class="fas fa-graduation-cap"></i> 教育经历
- *2024.09 - 至今*：北京航空航天大学，博士（硕转博），交通科学与工程学院。
- *2022.09 - 2024.08*：北京航空航天大学，硕士，交通科学与工程学院。
- *2018.09 - 2022.06*：北京工业大学-北京航空航天大学双培计划，本科，软件学院。

# <i class="fas fa-laptop-code"></i> 实习与产业经历
- *2025.06 - 2025.12*：高德地图，自动驾驶模型轻量化（前向有效在线矢量地图构建）。
- *2024.12 - 2025.06*：理想汽车，自动驾驶世界模型（占据栅格中心统一生成框架）。
- *2024.10 - 2024.12*：清华大学智能产业研究院，自动驾驶拓扑理解轻量化。
- *2022.06 - 2023.10*：北京洛必德科技有限公司，感知建图算法（半自动化高精地图标注、实车测试）。

# <i class="fas fa-users"></i> 学术服务
**审稿人：**
- Computer Vision and Pattern Recognition (CVPR)
- European Conference on Computer Vision (ECCV)
- International Conference on Learning Representations (ICLR)
- AAAI Conference on Artificial Intelligence (AAAI)
- Expert Systems With Applications (ESWA)
- IEEE Transactions on Vehicular Technology (TVT)
