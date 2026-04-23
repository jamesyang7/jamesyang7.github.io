---
layout: single
title: "ULoc"
permalink: /projects/uloc/
author_profile: true
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/projects/">&larr; Back to all projects</a>

<div class="project-detail-meta">
  <span class="project-detail-pill">ICRA 2025</span>
  <span class="project-detail-pill">UWB Localization</span>
  <span class="project-detail-pill">Large-Scale Robotics</span>
</div>

<p class="project-detail-summary">
  ULoc studies how to localize reliably in complex large-scale environments using ultra-wideband range measurements,
  with a strong emphasis on deployment-oriented robustness instead of simplified lab conditions.
</p>

<div class="project-detail-links">
  <a class="project-detail-btn paper" href="https://arxiv.org/abs/2409.11122">Paper</a>
  <a class="project-detail-btn code" href="https://github.com/brytsknguyen/uloc">Code</a>
  <a class="project-detail-btn secondary" href="/publications/">Related Publications</a>
</div>

<figure class="project-detail-hero-media">
  <img src="/images/projects/uloc.svg" alt="Visual overview of the ULoc project" loading="lazy">
</figure>
<p class="project-detail-caption">
  ULoc focuses on geometry-aware localization with UWB ranges, targeting environments where scale, clutter, and uncertainty make localization difficult.
</p>

## Overview

<p class="project-lead">
  This project sits at the intersection of sensing, geometric reasoning, and learning-based robotics. The main motivation is simple:
  localization must keep working when the environment becomes messy, the space becomes large, and sensor uncertainty is no longer negligible.
  ULoc turns UWB measurements into a useful signal for robust positioning in these harder settings.
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">Geometry from Ranges</h3>
    <p class="project-metric-text">
      UWB ranges provide compact but informative geometric cues that can complement more fragile localization signals.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Realistic Scale</h3>
    <p class="project-metric-text">
      The project is oriented toward large environments and the failure modes that appear outside tidy benchmark settings.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Deployment Relevance</h3>
    <p class="project-metric-text">
      Stable localization is a foundation for autonomy, navigation, and downstream planning in real robotic systems.
    </p>
  </article>
</div>

## Visual Highlights

<div class="project-visual-grid">
  <figure class="project-visual-card focus-left">
    <div class="project-visual-media">
      <img src="/images/projects/uloc.svg" alt="ULoc range sensing visual" loading="lazy">
    </div>
    <figcaption>Range-based sensing gives the project a geometric backbone that remains useful in complex spaces.</figcaption>
  </figure>
  <figure class="project-visual-card focus-center">
    <div class="project-visual-media">
      <img src="/images/projects/uloc.svg" alt="ULoc environment-scale visual" loading="lazy">
    </div>
    <figcaption>The project is designed for large-scale localization rather than only clean indoor toy settings.</figcaption>
  </figure>
  <figure class="project-visual-card focus-right">
    <div class="project-visual-media">
      <img src="/images/projects/uloc.svg" alt="ULoc deployment visual" loading="lazy">
    </div>
    <figcaption>Localization quality is framed as an enabling capability for real autonomy and system reliability.</figcaption>
  </figure>
</div>

## Related Output

<div class="project-related-list">
  <article class="project-related-item">
    <div class="project-related-meta">Representative Publication</div>
    <div class="project-related-title">ULoc: Learning to Localize in Complex Large-Scale Environments with Ultra-Wideband Ranges</div>
    <div class="project-related-authors">T.M. Nguyen, <strong>Y. Yang</strong>, T.D. Nguyen, S. Yuan, L. Xie</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://arxiv.org/abs/2409.11122">Paper</a>
      <a class="project-detail-btn code" href="https://github.com/brytsknguyen/uloc">Code</a>
    </div>
  </article>
</div>

<div class="project-note">
  The current page uses a clean visual summary and project narrative. If you later have experiment screenshots or localization demo videos,
  they can be dropped directly into this page without changing the overall structure.
</div>
