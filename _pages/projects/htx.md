---
layout: single
title: "Development of Embodied AI Language-Based Navigation System"
permalink: /projects/htx/
author_profile: true
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/projects/">&larr; Back to all projects</a>

<p class="project-detail-summary">
  HTX develops an embodied AI system that enables a quadruped robot to understand language commands, explore indoor environments, and complete search-and-fetch tasks.
</p>

<figure class="project-detail-hero-media">
  <img src="/images/projects/htx.gif" alt="Visual overview of the HTX project" loading="lazy">
</figure>

## Overview

<p class="project-lead">
  This project builds a language-driven robotic system for indoor navigation and object retrieval. The system combines language understanding, semantic perception, mapping, planning, and manipulation in a unified pipeline. :contentReference[oaicite:0]{index=0}
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">Language Understanding</h3>
    <p class="project-metric-text">
      The robot accepts voice or text instructions and converts them into actionable navigation and search goals.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Semantic Mapping</h3>
    <p class="project-metric-text">
      The system constructs semantic memory from visual observations, depth, and robot poses for reasoning and planning.
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">Navigation and Fetching</h3>
    <p class="project-metric-text">
      The robot searches for target objects, plans paths in unknown environments, and performs object fetching with an onboard manipulator.
    </p>
  </article>
</div>

<figure class="project-detail-hero-media">
  <img src="/images/projects/htx2.gif" alt="HTX system pipeline and robot behavior" loading="lazy">
</figure>

## Language-Based Navigation

<p class="project-lead">
  The navigation module integrates speech-to-text, vision-language grounding, open-vocabulary detection, and frontier-based exploration. Natural language instructions are parsed into object or place targets, and the system selects candidate viewpoints and navigation goals during exploration. 
</p>

## Multi-Layer Perception and Reasoning

<p class="project-lead">
  The system adopts a multi-layer architecture with real-time perception, semantic scene memory, and deep reasoning. This allows the robot to maintain fast onboard responsiveness while also supporting higher-level reasoning over stored observations. :contentReference[oaicite:2]{index=2}
</p>

## Semantic Mapping and Spatial Memory

<p class="project-lead">
  The project incrementally builds a semantic scene graph composed of 3D objects and keyframe images. Detected objects are associated across frames and merged into persistent map entities, while selected keyframes are stored for downstream reasoning and navigation. :contentReference[oaicite:3]{index=3}
</p>

## Semantic SLAM and Loop Closure

<p class="project-lead">
  To improve long-term localization, the system incorporates a text-cue-based loop closure module. OCR-extracted scene text is associated with robot poses and used as semantic landmarks for retrieval, verification, and pose graph optimization. 
</p>

## Search and Fetching

<p class="project-lead">
  The robot is equipped with a search-and-fetch pipeline that combines instance-level perception, grasp alignment, reachability checking, last-mile docking, and manipulation execution. A two-stage grasping design first computes a stable global grasp reference and then refines it for close-range execution. :contentReference[oaicite:5]{index=5}
</p>

## System Integration

<p class="project-lead">
  The complete system integrates onboard compute, RGB-D sensing, LiDAR, audio input, semantic mapping, navigation, and manipulation into a unified embodied AI framework for real-world indoor robotic tasks. 
</p>