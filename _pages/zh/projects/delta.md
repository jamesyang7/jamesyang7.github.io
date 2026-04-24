---
layout: single
title: "面向智慧制造的多层态势感知与安全高效多机器人协作"
permalink: /zh/projects/delta/
author_profile: true
lang: zh
translation_url: /projects/delta/
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/zh/projects/">&larr; 返回全部项目</a>

<p class="project-detail-summary">
  该项目与 Delta Electronics Inc. 合作开展，面向多层建筑和密集人群环境中的自主机器人规划与协同，
  已经在新加坡 Commonwealth 附近的 HDB 楼宇中完成实际部署测试。
</p>

<figure class="project-detail-hero-media">
  <img src="/images/projects/delta.gif" alt="Delta 项目总览" loading="lazy">
</figure>

## 项目概览

<p class="project-lead">
  该项目旨在为多层楼宇和复杂人群环境中的机器人系统开发自主规划与感知能力。在这个项目中，
  我主要负责机器人的感知模块。具体而言，我设计了一套节省人工标注成本的可行驶区域分割框架，
  利用大视觉模型自动生成可行驶区域标签，再将知识蒸馏到轻量化网络中，以支持实时分割。
  此外，我还开发了多模态行人检测与跟踪系统，以进一步提升导航过程中的效率与安全性。
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">低人工成本可行驶区域分割</h3>
    <p class="project-metric-text">
      设计一种无需大量人工标注的可行驶区域分割框架，提高真实部署中的数据利用效率。
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">光照无关分割鲁棒性</h3>
    <p class="project-metric-text">
      通过光照无关特征学习模块，提高系统在不同照明条件下的分割稳定性。
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">行人检测与跟踪</h3>
    <p class="project-metric-text">
      融合 2D LiDAR 与 RGB-D 图像，估计周围行人的位置与速度，为安全导航提供支持。
    </p>
  </article>
</div>

<figure class="project-detail-hero-media">
  <img src="/images/projects/delta2.gif" alt="Delta 项目系统展示" loading="lazy">
</figure>

<figure class="project-detail-hero-media">
  <img src="/images/projects/delta3.gif" alt="Delta 项目部署展示" loading="lazy">
</figure>

## 相关成果

<div class="project-related-list">
  <article class="project-related-item">
    <div class="project-related-meta">代表性论文</div>
    <div class="project-related-title">Learning Dynamic Weight Adjustment for Spatial-Temporal Trajectory Planning in Crowd Navigation</div>
    <div class="project-related-authors">M. Cao*, X. Xu*, <strong>Y. Yang*</strong>, J. Li, T. Jin, P. Wang, T.Y. Hung, G. Lin, L. Xie</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://arxiv.org/abs/2412.00555">论文</a>
      <a class="project-detail-btn video" href="https://www.youtube.com/watch?v=nSCbNaaF_VM">视频</a>
    </div>
  </article>
</div>
