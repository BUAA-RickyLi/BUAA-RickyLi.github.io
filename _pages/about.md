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
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-trophy"></i> 代表奖项</h3>
    <ul>
      <li>第三届迪拜世界自动驾驶挑战赛第一名（2023）</li>
      <li>全国大学生交通运输科技大赛一等奖（2024）</li>
      <li>首都挑战杯银奖（2024）</li>
    </ul>
  </div>
</div>

<!-- # <i class="fas fa-fire"></i> News
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by The 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025). <span class="accent-text">See you in Philadelphia!</span>
- *2024.08*: &nbsp;I have joined <span class="primary-gradient-text">Microsoft</span> as a Research Intern under the guidance of Principal Researcher Justin Ding, where I focus on evaluating and enhancing LLM outputs. -->

# <i class="fas fa-file-alt"></i> 论文与成果

- **MapDistill**: Boosting Efficient Camera-based HD Map Construction via Camera-LiDAR Fusion Model Distillation. *ECCV 2024, CCF-B, 共同第一作者*.
- **E-MLP**: Effortless Online HD Map Construction with Linear Priors. *IEEE IV 2024, 第一作者*.
- **Stability Under Scrutiny**: Benchmarking Representation Paradigms for Online HD Mapping. *ICLR 2026, 共同第一作者*.
- **MapQP**: End-to-End Vectorized HD Map Construction with Relational Queries and Positional Encoding. *T-ITS, 三审中, 第一作者*.
- **OccDistill**: Efficient Camera-based 3D Semantic Occupancy Prediction via Multi-modal Guided Distillation. *TMM, 二审中, 第一作者*.
- **AMap**: Distilling Future Priors for Ahead-Aware Online HD Map Construction. *CVPR 2026 在投, 第一作者*.

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

# <i class="fas fa-file-pdf"></i> 简历

- 简历文件我已读取完成，建议后续放置到站点目录 `assets/` 后在此处添加下载链接。

# <i class="fas fa-blog"></i> 博客

<!-- Local Blog Posts Section -->
{% if site.posts.size > 0 %}
<div class="local-blogs-section">
  <div class="local-blogs-header">
    <h3><i class="fas fa-pen-nib"></i> Latest Posts</h3>
    <a href="{{ '/blog/' | relative_url }}" class="view-all-btn">
      View All Posts <i class="fas fa-arrow-right"></i>
    </a>
  </div>
  <div class="blog-grid">
    {% assign sorted_posts = site.posts | sort: 'date' | reverse %}
    {% for post in sorted_posts limit:3 %}
    <a href="{{ post.url | relative_url }}" class="blog-card-link">
      <div class="blog-card">
        <div class="blog-card-image">
          <div class="blog-badge">{{ post.date | date: "%B, %Y" }}</div>
          {% if post.cover_image %}
          <img src="{{ post.cover_image | relative_url }}" alt="{{ post.title }}">
          {% else %}
          <img src="{{ '/images/default-blog-cover.jpg' | relative_url }}" alt="{{ post.title }}">
          {% endif %}
        </div>
        <div class="blog-card-content">
          <div class="blog-title">{{ post.title }}</div>
          <div class="blog-description">{{ post.description | default: post.excerpt | strip_html | truncate: 120 }}</div>
        </div>
      </div>
    </a>
    {% endfor %}
  </div>
</div>

<div class="external-blogs-divider">
  <span><i class="fas fa-external-link-alt"></i> External Articles</span>
</div>
{% endif %}

<!-- 你后续若需要，我可以帮你把这一部分改为仅展示本地博客文章列表 -->
<div class="blog-grid">
  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">November, 2025</div>
      <img src="images/claude-pipeline.png" alt="Claude Code Skills 和 Subagents 的个人实践">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">Claude Code Skills and Subagents in Practice</div>
      <div class="blog-description">Two production-grade systems: a paywall-crossing paper harvester and a self-iterating AI Scientist, showing how Skills + Subagents scale LLM workflows.</div>
      <div class="blog-links">
        <a href="https://mp.weixin.qq.com/s/_rHrBpRZX_U2Zmt8vRZ22Q" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://jxtse.medium.com/from-chat-tools-to-research-infrastructure-building-production-grade-workflows-with-claude-code-7da19194ab34" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

<div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">June, 2025</div>
      <img src="images/pic06.jpg" alt="The Limits of My Language Mean the Limits of My World">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">The Limits of My Language Mean the Limits of My World</div>
      <div class="blog-description">Drawing on Wittgenstein's philosophy, a recent paper argues that our existing language might be the fundamental bottleneck.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/discovery/item/683c300d000000000f03b1ca?source=webshare&xhsshare=pc_web&xsec_token=AB0PoaiA05YKKE_dU2SOcfxhEzDIPcLsNtqo4slfNuuXw=&xsec_source=pc_share" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://jxtse.medium.com/the-limits-of-my-language-are-the-limits-of-my-world-can-we-ever-truly-understand-ai-f7cc72327dac" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">January, 2025</div>
      <img src="images/pic04.jpg" alt="Beyond the Future of AI">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">Beyond the Future of AI: The Dreams and Deceptions of Cryptocurrency</div>
      <div class="blog-description">My vision of the future: from Bitcoin to an AGI-driven decentralized society. We must design a more sophisticated trust mechanism than blockchain to install “guardrails” for AI.</div>
      <div class="blog-links">
        <a href="https://mp.weixin.qq.com/s/luu2qEzPnYAuryJ9mYoJ6Q" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://jxtse.medium.com/beyond-the-future-of-ai-the-dreams-and-deceptions-of-cryptocurrency-5da8d4bbf69e" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">November, 2024</div>
      <img src="images/pic05.jpg" alt="LexiMind">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">LexiMind: An Open-Source LLM-Powered Vocabulary Builder</div>
      <div class="blog-description">LexiMind is an AI-powered vocabulary builder that integrates LLM-based translation with smart word retention.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/explore/67a48f0d000000001800721c?xsec_token=ABXUfGRE_zHTnXbEyaNmuelNX3M4527lw3zirVu2KJUKA=&xsec_source=pc_user" class="blog-link">
          <i class="fas fa-info-circle"></i> Introduction
        </a>
        <a href="https://github.com/jxtse/LexiMind" class="blog-link">
          <i class="fab fa-github"></i> Project
        </a>
      </div>
    </div>
  </div>

  <!-- <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">July, 2024</div>
      <img src="images/pic02.jpg" alt="NLP Learning Path">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">My NLP Learning Path as a Mathematics Undergraduate Student</div>
      <div class="blog-description">I share my learning path and some insights on natural language processing as a mathematics undergraduate student.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/explore/668a35c8000000001e010600?xsec_token=ABl3IEpctnnXxbjsYlUul3nZBcA622VEEpS6zNOEPrxVI=&xsec_source=pc_user" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://www.linkedin.com/posts/jinxiang-xie_naturallanguageprocessing-nlp-learningpath-activity-7215638435393359872-dPr8?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEmWk88Bhyvl-E41lfo1McNlpiC4YSsk7WQ" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div> -->

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">November, 2023</div>
      <img src="images/pic03.jpg" alt="LLMs Technology">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">LLMs: Cutting-Edge Technology and Future Applications</div>
      <div class="blog-description">My notes from a presentation on LLMs at the Gaoling School of Artificial Intelligence, Renmin University of China.</div>
      <div class="blog-links">
        <a href="https://mp.weixin.qq.com/s?__biz=Mzg5NzczMzM3MA==&mid=2247483926&idx=1&sn=c6dcaf93ec8d7ecaa760df4682589b21" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
      </div>
    </div>
  </div>

</div>
