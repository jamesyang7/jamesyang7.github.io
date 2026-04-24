---
layout: single
title: "Multi-Level Situation Awareness for Safe and Efficient Multi-agent Collaboration in Smart Manufacturing"
permalink: /projects/delta/
author_profile: true
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/projects/">&larr; Back to all projects</a>


<figure class="project-detail-hero-media">
  <img src="/images/projects/delta.gif" alt="Visual overview of the Delta project" loading="lazy">
</figure>


## Overview

<p class="project-lead">
    In collaboration with Delta Electronics Inc. This project aims to develop solutions for autonomous robot planning in multi-level buildings and dense human crowds. The autonomous algorithm has been successfully tested in HDB buildings near Commonwealth, Singapore.
    <br><br>
    In this project, I am responsible for the perception module of the robots. Specifically, I designed a labor-saving free-space segmentation framework to use large vision models to automatically label the drivable region. Then, this knowledge is distilled to a lightweight network for real-time segmentation. 
    <br><br>
    In addition, I developed a multimodal pedestrian detection and tracking system to further improve the navigation efficiency and safety.
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">Labor-saving Free-space Segmentation</h3>
    <p class="project-metric-text">
      Design an unsupervised labor-saving drivable region segmentation network 
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Illumination-agnostic Segmentation</h3>
    <p class="project-metric-text">
      Develope an illumination-agnostic feature learning module to improve the robustness under different lighting environment.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Human Detection and Tracking</h3>
    <p class="project-metric-text">
     Fuse 2D Lidar data and RGB-D image to detect the position of surrounding pedestrians and estimate their velocities
    </p>
  </article>
</div>


<figure class="project-detail-hero-media">
  <img src="/images/projects/delta2.gif" alt="Visual overview of the Delta project" loading="lazy">
</figure>

<figure class="project-detail-hero-media">
  <img src="/images/projects/delta3.gif" alt="Visual overview of the Delta project" loading="lazy">
</figure>

## Related Output

<div class="project-related-list">
  <article class="project-related-item">
    <div class="project-related-meta">Representative Publication</div>
    <div class="project-related-title">Learning Dynamic Weight Adjustment for Spatial-Temporal Trajectory Planning in Crowd Navigation</div>
    <div class="project-related-authors"> M. Cao*, X. Xu*, <strong>Y. Yang*</strong>, J. Li, T. Jin, P. Wang, T.Y. Hung, G. Lin, L. Xie</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://arxiv.org/abs/2412.00555">Paper</a>
      <a class="project-detail-btn video" href="https://www.youtube.com/watch?v=nSCbNaaF_VM">Vedio</a>
    </div>
  </article>
</div>
