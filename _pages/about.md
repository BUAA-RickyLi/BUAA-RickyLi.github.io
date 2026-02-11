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

我是 <span class="accent-text">李睿楷（Ricky Li）</span>，目前为 <i class="fas fa-university"></i> **北京航空航天大学交通科学与工程学院博士生（硕转博）**。研究方向聚焦于**自动驾驶感知、在线高精地图构建与模型轻量化**。

<div class="quote-accent">
我的目标是构建**高精度、低时延、可部署**的自动驾驶感知系统，让感知与建图算法更高效地服务真实场景。
</div>

欢迎交流科研合作：`rickyli@buaa.edu.cn`

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
  
  <!-- <div class="highlight-block floating-card">
    <h3><i class="fas fa-trophy"></i> 代表奖项</h3>
    <ul>
      <li>第三届迪拜世界自动驾驶挑战赛第一名（2023）</li>
      <li>全国大学生交通运输科技大赛一等奖（2024）</li>
      <li>首都挑战杯银奖（2024）</li>
    </ul>
  </div> -->
</div>

# <i class="fas fa-star"></i> 代表工作

更多论文请见 <a href="https://scholar.google.com/citations?user=r309swkAAAAJ&hl=zh-CN" class="link-accent"><i class="fas fa-graduation-cap"></i> Google Scholar</a>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ECCV 2024</div>
    <img src='images/500x300.png' alt="MapDistill" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>MapDistill: Boosting Efficient Camera-based HD Map Construction via Camera-LiDAR Fusion Model Distillation</h3>
    <div class="authors">Xiaoshuai Hao*, <strong>Ruikai Li*</strong>, Hui Zhang, et al.</div>
    <div class="venue">ECCV 2024, CCF-B, 共同第一作者</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2407.11682" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/BUAA-RickyLi/MapDistill" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ICLR 2026</div>
    <img src='images/500x300.png' alt="StableHDMap" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Stability Under Scrutiny: Benchmarking Representation Paradigms for Online HD Mapping</h3>
    <div class="authors">Hao Shan*, <strong>Ruikai Li*</strong>, Han Jiang, et al.</div>
    <div class="venue">ICLR 2026, 共同第一作者</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2510.10660" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/bhsh0112/MapStableTest" class="btn-accent"><i class="fab fa-github"></i> Code</a>
      <a href="https://stablehdmap.github.io/" class="btn-accent"><i class="fas fa-globe"></i> Project</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Under Review</div>
    <img src='images/500x300.png' alt="AMap" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>AMap: Distilling Future Priors for Ahead-Aware Online HD Map Construction</h3>
    <div class="authors"><strong>Ruikai Li</strong>, Xinrun Li, Mengwei Xie, et al.</div>
    <div class="venue">Under Review, 第一作者</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2512.19150" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Under Review</div>
    <img src='images/500x300.png' alt="UniScenev2" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Scaling Up Occupancy-centric Driving Scene Generation: Dataset and Method</h3>
    <div class="authors">Bohan Li, Xin Jin, Hu Zhu, ..., <strong>Ruikai Li</strong>, et al.</div>
    <div class="venue">Under Review, 参与作者</div>
    <div class="links">
      <a href="https://arxiv.org/abs/2510.22973" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation/tree/v2" class="btn-accent"><i class="fab fa-github"></i> Code</a>
      <a href="https://arlo0o.github.io/uniscenev2/" class="btn-accent"><i class="fas fa-globe"></i> Project</a>
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

# <i class="fas fa-award"></i> 荣誉奖项
- 第三届迪拜世界自动驾驶挑战赛第一名（2023）
- 全国大学生交通运输科技大赛一等奖（2024）
- IVISTA 虚拟仿真挑战赛特等奖
- 首都挑战杯银奖（2024）
