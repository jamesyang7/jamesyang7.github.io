---
layout: single
title: "AV-PedAware"
permalink: /projects/av-pedaware/
author_profile: true
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/projects/">&larr; Back to all projects</a>

<div class="project-detail-meta">
  <span class="project-detail-pill">IROS 2024</span>
  <span class="project-detail-pill">Self-Supervised Learning</span>
  <span class="project-detail-pill">Pedestrian Awareness</span>
</div>

<p class="project-detail-summary">
  AV-PedAware explores self-supervised audio-visual fusion for pedestrian awareness in dynamic scenes,
  with a particular focus on improving robot perception when visual information alone is unstable or incomplete.
</p>

<div class="project-detail-links">
  <a class="project-detail-btn paper" href="https://arxiv.org/abs/2411.06789">Paper</a>
  <a class="project-detail-btn code" href="https://github.com/yizhuoyang/AV-PedAware">Code</a>
  <a class="project-detail-btn secondary" href="/publications/">Related Publications</a>
</div>

<figure class="project-detail-hero-media">
  <img src="/images/projects/av-pedaware.svg" alt="Visual overview of the AV-PedAware project" loading="lazy">
</figure>
<p class="project-detail-caption">
  The project is centered on dynamic pedestrian understanding, using self-supervised audio-visual fusion to improve awareness for embodied robots.
</p>

## Overview

<p class="project-lead">
  Pedestrian awareness is a core perception problem for robots operating around people. AV-PedAware treats it as a multimodal learning problem,
  where audio cues can strengthen the robot's understanding of nearby human motion and scene risk. The self-supervised setup is especially important,
  because it reduces the dependence on dense labels while still learning useful fused representations.
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">Self-Supervised Fusion</h3>
    <p class="project-metric-text">
      The project leverages self-supervision to build useful fused representations without relying entirely on expensive annotation.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Pedestrian-Centric Perception</h3>
    <p class="project-metric-text">
      The sensing objective is tightly connected to whether the robot can stay aware of people in dynamic environments.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Embodied Relevance</h3>
    <p class="project-metric-text">
      Better awareness leads to safer navigation, smoother interaction, and stronger perception in challenging operating conditions.
    </p>
  </article>
</div>

## Visual Highlights

<div class="project-visual-grid">
  <figure class="project-visual-card focus-left">
    <div class="project-visual-media">
      <img src="/images/projects/av-pedaware.svg" alt="AV-PedAware fusion visual" loading="lazy">
    </div>
    <figcaption>Audio and visual observations are treated as complementary clues for nearby human activity.</figcaption>
  </figure>
  <figure class="project-visual-card focus-center">
    <div class="project-visual-media">
      <img src="/images/projects/av-pedaware.svg" alt="AV-PedAware awareness visual" loading="lazy">
    </div>
    <figcaption>The project is about awareness in dynamic scenes, not only object recognition in static images.</figcaption>
  </figure>
  <figure class="project-visual-card focus-right">
    <div class="project-visual-media">
      <img src="/images/projects/av-pedaware.svg" alt="AV-PedAware embodied visual" loading="lazy">
    </div>
    <figcaption>The learned fused representation is directly relevant to embodied robots sharing space with pedestrians.</figcaption>
  </figure>
</div>

## Related Output

<div class="project-related-list">
  <article class="project-related-item">
    <div class="project-related-meta">IROS 2024</div>
    <div class="project-related-title">AV-PedAware: Self-Supervised Audio-Visual Fusion for Dynamic Pedestrian Awareness</div>
    <div class="project-related-authors"><strong>Y. Yang</strong>, S. Yuan, M. Cao, J. Yang, L. Xie</div>
    <div class="project-related-links">
      <a class="project-detail-btn paper" href="https://arxiv.org/abs/2411.06789">Paper</a>
      <a class="project-detail-btn code" href="https://github.com/yizhuoyang/AV-PedAware">Code</a>
    </div>
  </article>
</div>

<div class="project-note">
  This project page is set up to hold richer qualitative material later, such as GIFs, sequence visualizations, or demo videos from navigation experiments.
</div>
