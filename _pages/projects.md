---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>
.projects-intro {
  margin-bottom: 1.35rem;
  color: #5d6f80;
  font-size: 0.98rem;
  line-height: 1.74;
}

.project-list {
  display: grid;
  gap: 22px;
}

.project-card {
  display: grid;
  grid-template-columns: minmax(260px, 340px) minmax(0, 1fr);
  gap: 20px;
  padding: 20px;
  border: 1px solid #dbe7ee;
  border-radius: 24px;
  background: linear-gradient(180deg, #ffffff 0%, #f8fbfd 100%);
  box-shadow: 0 8px 22px rgba(16, 36, 56, 0.05);
  scroll-margin-top: 90px;
}

.project-media {
  display: block;
  aspect-ratio: 16 / 10;
  overflow: hidden;
  border: 1px solid #d9e5ec;
  border-radius: 20px;
  background: #edf4f8;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.3);
}

.project-media img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.project-content {
  display: flex;
  flex-direction: column;
}

.project-tag-row {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 12px;
}

.project-tag {
  display: inline-flex;
  padding: 7px 11px;
  border-radius: 999px;
  background: #eef6fb;
  color: #1f6a92;
  font-size: 0.8rem;
  font-weight: 800;
}

.project-title {
  margin: 0 0 12px;
  color: #173756;
  font-size: 1.14rem;
  font-weight: 800;
  line-height: 1.45;
}

.project-summary {
  margin: 0 0 14px;
  color: #5f7183;
  font-size: 0.95rem;
  line-height: 1.72;
}

.project-links {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: auto;
}

.project-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 82px;
  padding: 10px 14px;
  border: 1px solid transparent;
  border-radius: 999px;
  font-size: 0.87rem;
  font-weight: 800;
  text-decoration: none !important;
}

.project-link.paper {
  background: #eef7f1;
  border-color: #d1e8d9;
  color: #1e6a42 !important;
}

.project-link.details {
  background: #eef6fb;
  border-color: #d4e6f2;
  color: #1c668e !important;
}

.project-link.code {
  background: #f4eefb;
  border-color: #dfd3ee;
  color: #6c409f !important;
}

.project-link.website {
  background: #eef6fb;
  border-color: #d4e6f2;
  color: #1c668e !important;
}

.project-link.publication {
  background: #fff6eb;
  border-color: #f1dfbf;
  color: #9a6225 !important;
}

@media (max-width: 900px) {
  .project-card {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  .project-card {
    padding: 18px 16px;
  }
}
</style>

<p class="projects-intro">
  Representative systems and research directions in multimodal perception, audio-visual fusion, localization,
  crowd-aware navigation, and autonomous robotics. Each project card below now links to a dedicated project page,
  where we can keep the broader story, visual overview, and future demo media separate from the publication list.
</p>

<section class="project-list">
  <article class="project-card" id="m4human">
    <div class="project-media">
      <img src="/images/projects/m4human.svg" alt="Illustration for the M4Human project" loading="lazy">
    </div>

    <div class="project-content">
      <div class="project-tag-row">
        <span class="project-tag">CVPR 2026</span>
        <span class="project-tag">Multimodal Learning</span>
        <span class="project-tag">Human Understanding</span>
      </div>
      <h2 class="project-title">M4Human: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction</h2>
      <p class="project-summary">
        A benchmark-oriented project for multimodal human mesh reconstruction, centered on mmWave radar sensing and large-scale data curation.
        The project supports robust 3D human understanding when purely visual sensing is limited by lighting, occlusion, or viewpoint changes.
      </p>

      <div class="project-links">
        <a class="project-link details" href="/projects/m4human/">View Details</a>
        <a class="project-link publication" href="https://arxiv.org/abs/2512.12378">Paper</a>
        <a class="project-link code" href="https://github.com/FanJunqiao/M4Human">Code</a>
        <a class="project-link website" href="https://fanjunqiao.github.io/M4Human-site/">Website</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="uloc">
    <div class="project-media">
      <img src="/images/projects/uloc.svg" alt="Illustration for the ULoc project" loading="lazy">
    </div>

    <div class="project-content">
      <div class="project-tag-row">
        <span class="project-tag">ICRA 2025</span>
        <span class="project-tag">UWB</span>
        <span class="project-tag">Large-Scale Environments</span>
      </div>
      <h2 class="project-title">ULoc: Learning to Localize in Complex Large-Scale Environments with Ultra-Wideband Ranges</h2>
      <p class="project-summary">
        A learning-based localization project for complex large-scale environments, using ultra-wideband range measurements as a key sensing signal.
        The core goal is to make localization more reliable when map scale, environment complexity, and sensing uncertainty increase.
      </p>

      <div class="project-links">
        <a class="project-link details" href="/projects/uloc/">View Details</a>
        <a class="project-link publication" href="https://arxiv.org/abs/2409.11122">Paper</a>
        <a class="project-link code" href="https://github.com/brytsknguyen/uloc">Code</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="crowd-nav">
    <div class="project-media">
      <img src="/images/projects/crowd-nav.svg" alt="Illustration for crowd navigation research" loading="lazy">
    </div>

    <div class="project-content">
      <div class="project-tag-row">
        <span class="project-tag">ICRA 2025</span>
        <span class="project-tag">RA-L 2025</span>
        <span class="project-tag">Trajectory Planning</span>
      </div>
      <h2 class="project-title">Crowd-Aware Robot Navigation and Spatial-Temporal Planning</h2>
      <p class="project-summary">
        A line of work on safe and efficient robot navigation in human crowds, including dynamic weight adjustment for trajectory planning
        and navigation policies that use surrounding pedestrian behavior as a planning cue.
      </p>

      <div class="project-links">
        <a class="project-link details" href="/projects/crowd-navigation/">View Details</a>
        <a class="project-link publication" href="https://arxiv.org/abs/2412.00555">Trajectory Planning</a>
        <a class="project-link publication" href="https://arxiv.org/abs/2504.10828">People-as-Planners</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="anti-uav">
    <div class="project-media">
      <img src="/images/projects/anti-uav.svg" alt="Illustration for anti-UAV perception research" loading="lazy">
    </div>

    <div class="project-content">
      <div class="project-tag-row">
        <span class="project-tag">ICRA 2024</span>
        <span class="project-tag">Dataset</span>
        <span class="project-tag">Threat Identification</span>
      </div>
      <h2 class="project-title">Multimodal Anti-UAV Perception and Audio-Visual Threat Identification</h2>
      <p class="project-summary">
        A broader research direction on anti-UAV perception, combining dataset construction, multimodal sensing, and audio-visual fusion for drone threat analysis.
        This direction includes both benchmark development and system-level identification pipelines.
      </p>

      <div class="project-links">
        <a class="project-link details" href="/projects/anti-uav/">View Details</a>
        <a class="project-link publication" href="https://arxiv.org/abs/2402.03706">MMAUD Paper</a>
        <a class="project-link code" href="https://github.com/ntu-aris/MMAUD">MMAUD Code</a>
        <a class="project-link publication" href="https://www.sciencedirect.com/science/article/pii/S2949855424000285">AV-FDTI Paper</a>
        <a class="project-link code" href="https://github.com/yizhuoyang/AV-FDTI/">AV-FDTI Code</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="av-pedaware">
    <div class="project-media">
      <img src="/images/projects/av-pedaware.svg" alt="Illustration for the AV-PedAware project" loading="lazy">
    </div>

    <div class="project-content">
      <div class="project-tag-row">
        <span class="project-tag">IROS 2024</span>
        <span class="project-tag">Self-Supervised Learning</span>
        <span class="project-tag">Pedestrian Awareness</span>
      </div>
      <h2 class="project-title">AV-PedAware: Self-Supervised Audio-Visual Fusion for Dynamic Pedestrian Awareness</h2>
      <p class="project-summary">
        A project on self-supervised audio-visual fusion for improving pedestrian awareness in dynamic environments.
        The work explores how complementary sensing can strengthen robot perception when visual cues alone are unstable or incomplete.
      </p>

      <div class="project-links">
        <a class="project-link details" href="/projects/av-pedaware/">View Details</a>
        <a class="project-link publication" href="https://arxiv.org/abs/2411.06789">Paper</a>
        <a class="project-link code" href="https://github.com/yizhuoyang/AV-PedAware">Code</a>
      </div>
    </div>
  </article>
</section>
