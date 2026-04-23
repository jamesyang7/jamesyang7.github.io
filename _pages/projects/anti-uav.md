---
layout: single
title: "Anti-UAV Perception"
permalink: /projects/anti-uav/
author_profile: true
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/projects/">&larr; Back to all projects</a>

<div class="project-detail-meta">
  <span class="project-detail-pill">ICRA 2024</span>
  <span class="project-detail-pill">Audio-Visual Fusion</span>
  <span class="project-detail-pill">Threat Identification</span>
</div>

<p class="project-detail-summary">
  This project direction studies drone understanding from multiple sensing channels, combining benchmark construction,
  multimodal perception, and audio-visual fusion for more reliable anti-UAV analysis.
</p>

<div class="project-detail-links">
  <a class="project-detail-btn paper" href="https://arxiv.org/abs/2402.03706">MMAUD Paper</a>
  <a class="project-detail-btn code" href="https://github.com/ntu-aris/MMAUD">MMAUD Code</a>
  <a class="project-detail-btn paper" href="https://www.sciencedirect.com/science/article/pii/S2949855424000285">AV-FDTI Paper</a>
  <a class="project-detail-btn code" href="https://github.com/yizhuoyang/AV-FDTI/">AV-FDTI Code</a>
</div>

<figure class="project-detail-hero-media">
  <img src="/images/projects/anti-uav.svg" alt="Visual overview of the anti-UAV perception project" loading="lazy">
</figure>
<p class="project-detail-caption">
  The anti-UAV project family combines sensing, benchmarking, and fused perception to better identify miniature drone threats in realistic scenarios.
</p>

## Overview

<p class="project-lead">
  A single sensing modality is often not enough for reliable drone understanding. This project therefore looks at anti-UAV perception as a multimodal problem,
  where visual cues, audio signatures, and dataset design all matter. The result is a project direction that supports both community benchmarking and system-level threat analysis.
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">Benchmark Foundation</h3>
    <p class="project-metric-text">
      MMAUD provides a multimodal dataset and evaluation basis for miniature drone perception research.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Fused Threat Understanding</h3>
    <p class="project-metric-text">
      AV-FDTI explores how audio and visual observations can be combined for stronger identification performance.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">System Perspective</h3>
    <p class="project-metric-text">
      Together the outputs support a broader anti-UAV pipeline, from data to perception to practical analysis.
    </p>
  </article>
</div>

## Visual Highlights

<div class="project-visual-grid">
  <figure class="project-visual-card focus-left">
    <div class="project-visual-media">
      <img src="/images/projects/anti-uav.svg" alt="Anti-UAV benchmark visual" loading="lazy">
    </div>
    <figcaption>Benchmark construction matters because the anti-UAV problem is multimodal and operationally varied.</figcaption>
  </figure>
  <figure class="project-visual-card focus-center">
    <div class="project-visual-media">
      <img src="/images/projects/anti-uav.svg" alt="Anti-UAV sensing fusion visual" loading="lazy">
    </div>
    <figcaption>Audio-visual fusion strengthens the representation of drone identity and behavior beyond any one modality alone.</figcaption>
  </figure>
  <figure class="project-visual-card focus-right">
    <div class="project-visual-media">
      <img src="/images/projects/anti-uav.svg" alt="Anti-UAV system visual" loading="lazy">
    </div>
    <figcaption>The larger goal is a reliable anti-UAV perception pipeline that remains usable for real system development.</figcaption>
  </figure>
</div>

## Related Outputs

<div class="project-related-list">
  <article class="project-related-item">
    <div class="project-related-meta">ICRA 2024</div>
    <div class="project-related-title">MMAUD: A Comprehensive Multi-Modal Anti-UAV Dataset for Modern Miniature Drone Threats</div>
    <div class="project-related-authors">S. Yuan, <strong>Y. Yang</strong>, T.H. Nguyen, T.M. Nguyen, J. Yang, F. Liu, J. Li, H. Wang</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://arxiv.org/abs/2402.03706">Paper</a>
      <a class="project-detail-btn code" href="https://github.com/ntu-aris/MMAUD">Code</a>
    </div>
  </article>
  <article class="project-related-item">
    <div class="project-related-meta">Journal of Automation and Intelligence</div>
    <div class="project-related-title">AV-FDTI: Audio-Visual Fusion for Drone Threat Identification</div>
    <div class="project-related-authors"><strong>Y. Yang</strong>, S. Yuan, J. Yang, T.H. Nguyen, M. Cao, T.M. Nguyen, H. Wang, L. Xie</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://www.sciencedirect.com/science/article/pii/S2949855424000285">Paper</a>
      <a class="project-detail-btn code" href="https://github.com/yizhuoyang/AV-FDTI/">Code</a>
    </div>
  </article>
</div>

<div class="project-note">
  This page separates the overall anti-UAV project narrative from individual papers so you can later add demo videos, system photos, or benchmark screenshots
  without making any single publication entry carry the whole story.
</div>
