---
layout: single
title: "Crowd Navigation"
permalink: /projects/crowd-navigation/
author_profile: true
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/projects/">&larr; Back to all projects</a>

<div class="project-detail-meta">
  <span class="project-detail-pill">ICRA 2025</span>
  <span class="project-detail-pill">RA-L 2025</span>
  <span class="project-detail-pill">Crowd-Aware Planning</span>
</div>

<p class="project-detail-summary">
  This project direction focuses on robot motion in human crowds, covering trajectory planning that adapts over time
  and navigation strategies that use surrounding pedestrian behavior as planning guidance.
</p>

<div class="project-detail-links">
  <a class="project-detail-btn paper" href="https://arxiv.org/abs/2412.00555">Trajectory Planning Paper</a>
  <a class="project-detail-btn paper" href="https://arxiv.org/abs/2504.10828">People-as-Planners Paper</a>
  <a class="project-detail-btn secondary" href="/publications/">Related Publications</a>
</div>

<figure class="project-detail-hero-media">
  <img src="/images/projects/crowd-nav.svg" alt="Visual overview of the crowd navigation project" loading="lazy">
</figure>
<p class="project-detail-caption">
  The project studies safe, adaptive, and socially aware robot motion in crowded public spaces where scene structure changes over time.
</p>

## Overview

<p class="project-lead">
  Crowd navigation becomes difficult when the robot must simultaneously remain efficient, respect human motion, and update its priorities as the scene evolves.
  This project treats crowd-aware navigation as a dynamic decision problem rather than a fixed optimization objective, and links that idea to both planning and policy learning.
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">Dynamic Objectives</h3>
    <p class="project-metric-text">
      One part of the project studies how trajectory weights should change as the crowd configuration and interaction risk change.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">People as Signals</h3>
    <p class="project-metric-text">
      Another part explores how surrounding human behavior can act as an informative planning cue for the robot.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Embodied Usefulness</h3>
    <p class="project-metric-text">
      The overall direction aims at behavior that is both safer and more practical for real navigation systems.
    </p>
  </article>
</div>

## Visual Highlights

<div class="project-visual-grid">
  <figure class="project-visual-card focus-left">
    <div class="project-visual-media">
      <img src="/images/projects/crowd-nav.svg" alt="Crowd navigation planning visual" loading="lazy">
    </div>
    <figcaption>Trajectory design must adapt to moving pedestrians rather than treating the scene as static.</figcaption>
  </figure>
  <figure class="project-visual-card focus-center">
    <div class="project-visual-media">
      <img src="/images/projects/crowd-nav.svg" alt="Crowd navigation policy visual" loading="lazy">
    </div>
    <figcaption>The project combines learning-based planning with richer interpretations of social motion structure.</figcaption>
  </figure>
  <figure class="project-visual-card focus-right">
    <div class="project-visual-media">
      <img src="/images/projects/crowd-nav.svg" alt="Crowd navigation interaction visual" loading="lazy">
    </div>
    <figcaption>Human-aware navigation is framed as a balance between safety, efficiency, and natural interaction.</figcaption>
  </figure>
</div>

## Related Outputs

<div class="project-related-list">
  <article class="project-related-item">
    <div class="project-related-meta">ICRA 2025</div>
    <div class="project-related-title">Learning Dynamic Weight Adjustment for Spatial-Temporal Trajectory Planning in Crowd Navigation</div>
    <div class="project-related-authors">M. Cao, X. Xu, <strong>Y. Yang</strong>, J. Li, T. Jin, P. Wang, T.Y. Hung, G. Lin, L. Xie</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://arxiv.org/abs/2412.00555">Paper</a>
    </div>
  </article>
  <article class="project-related-item">
    <div class="project-related-meta">RA-L 2025</div>
    <div class="project-related-title">Following Is All You Need: Robot Crowd Navigation Using People As Planners</div>
    <div class="project-related-authors">Y. Liao, X. Xu, P. Bai, <strong>Y. Yang</strong>, M. Cao, S. Yuan, L. Xie</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://arxiv.org/abs/2504.10828">Paper</a>
    </div>
  </article>
</div>

<div class="project-note">
  This is intentionally presented as a broader project direction rather than a single-paper page, because the underlying story is about one research theme
  growing across multiple outputs in crowd-aware planning and socially informed navigation.
</div>
