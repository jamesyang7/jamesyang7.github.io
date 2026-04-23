---
layout: single
title: "M4Human"
permalink: /projects/m4human/
author_profile: true
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/projects/">&larr; Back to all projects</a>

<div class="project-detail-meta">
  <span class="project-detail-pill">CVPR 2026</span>
  <span class="project-detail-pill">Multimodal Learning</span>
  <span class="project-detail-pill">Human Mesh Reconstruction</span>
</div>

<p class="project-detail-summary">
  M4Human is a benchmark-oriented research project for multimodal human mesh reconstruction with mmWave radar,
  designed to support robust 3D human understanding when visual observations are degraded by lighting, occlusion,
  or viewpoint change.
</p>

<div class="project-detail-links">
  <a class="project-detail-btn paper" href="https://arxiv.org/abs/2512.12378">Paper</a>
  <a class="project-detail-btn code" href="https://github.com/FanJunqiao/M4Human">Code</a>
  <a class="project-detail-btn website" href="https://fanjunqiao.github.io/M4Human-site/">Project Website</a>
  <a class="project-detail-btn secondary" href="/publications/">Related Publications</a>
</div>

<figure class="project-detail-hero-media">
  <img src="/images/projects/m4human.svg" alt="Visual overview of the M4Human project" loading="lazy">
</figure>
<p class="project-detail-caption">
  A visual summary of the benchmark direction: multimodal capture, radar-informed human understanding, and evaluation-ready data design.
</p>

## Overview

<p class="project-lead">
  The core question behind M4Human is how to make multimodal human sensing more reproducible and more useful for the community.
  Instead of only proposing a model, this project emphasizes benchmark construction, sensing diversity, and a cleaner evaluation setup
  for future work on robust human mesh reconstruction.
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">Benchmark Design</h3>
    <p class="project-metric-text">
      Organizes multimodal sensing and annotation into a structured benchmark that can support comparison, ablation, and extension.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Radar-Centric Robustness</h3>
    <p class="project-metric-text">
      Uses mmWave radar as a complementary sensing source for scenarios where pure RGB pipelines become fragile.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Long-Term Value</h3>
    <p class="project-metric-text">
      Supports not only one paper, but a broader research line in multimodal human understanding, representation learning, and sensing fusion.
    </p>
  </article>
</div>

## Visual Highlights

<div class="project-visual-grid">
  <figure class="project-visual-card focus-left">
    <div class="project-visual-media">
      <img src="/images/projects/m4human.svg" alt="M4Human sensing view" loading="lazy">
    </div>
    <figcaption>Radar-informed human reconstruction is positioned as a robust alternative when visual quality drops.</figcaption>
  </figure>
  <figure class="project-visual-card focus-center">
    <div class="project-visual-media">
      <img src="/images/projects/m4human.svg" alt="M4Human benchmark overview" loading="lazy">
    </div>
    <figcaption>The project connects benchmark design, modality alignment, and model evaluation in one pipeline.</figcaption>
  </figure>
  <figure class="project-visual-card focus-right">
    <div class="project-visual-media">
      <img src="/images/projects/m4human.svg" alt="M4Human multimodal representation" loading="lazy">
    </div>
    <figcaption>Multiple sensing streams make the benchmark useful for both perception research and practical deployment studies.</figcaption>
  </figure>
</div>

## Related Output

<div class="project-related-list">
  <article class="project-related-item">
    <div class="project-related-meta">Representative Publication</div>
    <div class="project-related-title">M4Human: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction</div>
    <div class="project-related-authors">J. Fan, Y. Zhou, <strong>Y. Yang</strong>, X. Cui, J. Zhang, L. Xie, J. Yang, C.X. Lu, F. Ding</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://arxiv.org/abs/2512.12378">Paper</a>
      <a class="project-detail-btn code" href="https://github.com/FanJunqiao/M4Human">Code</a>
      <a class="project-detail-btn website" href="https://fanjunqiao.github.io/M4Human-site/">Website</a>
    </div>
  </article>
</div>

<div class="project-note">
  This project page is intentionally separated from the publication list: the goal here is to tell the larger project story,
  collect visuals, and provide a place where future demo GIFs or videos can be added without making the publication page too crowded.
</div>
