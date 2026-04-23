---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>
.projects-hero {
  padding: 24px 26px;
  border: 1px solid #d7e5ee;
  border-radius: 24px;
  background: linear-gradient(135deg, #12395a 0%, #176d87 58%, #7fc8c2 100%);
  color: #fff;
  box-shadow: 0 18px 40px rgba(18, 57, 90, 0.12);
}

.projects-hero-kicker {
  margin-bottom: 10px;
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.8);
}

.projects-hero p {
  margin: 0;
  max-width: 760px;
  color: rgba(255, 255, 255, 0.92);
  font-size: 0.98rem;
  line-height: 1.72;
}

.projects-hero-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 18px;
}

.projects-hero-tag {
  display: inline-flex;
  padding: 8px 12px;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.14);
  border: 1px solid rgba(255, 255, 255, 0.18);
  color: #fff;
  font-size: 0.86rem;
  font-weight: 700;
}

.projects-hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 18px;
}

.projects-hero-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 11px 16px;
  border-radius: 999px;
  font-weight: 800;
  text-decoration: none !important;
}

.projects-hero-link.primary {
  background: #fff;
  color: #12395a !important;
  box-shadow: 0 8px 20px rgba(9, 25, 40, 0.14);
}

.projects-hero-link.secondary {
  background: rgba(255, 255, 255, 0.12);
  border: 1px solid rgba(255, 255, 255, 0.18);
  color: #fff !important;
}

.projects-note {
  margin-top: 16px;
  margin-bottom: 1.8rem;
  padding: 15px 18px;
  border: 1px solid #dbe7ee;
  border-radius: 16px;
  background: linear-gradient(180deg, #fbfdfe 0%, #f5f9fc 100%);
  color: #536575;
  font-size: 0.94rem;
  line-height: 1.68;
}

.projects-note a {
  color: #24709a;
  text-decoration: none;
}

.projects-note a:hover {
  text-decoration: underline;
}

.project-list {
  display: grid;
  gap: 22px;
}

.project-card {
  display: grid;
  grid-template-columns: minmax(240px, 300px) minmax(0, 1fr);
  gap: 18px;
  padding: 20px;
  border: 1px solid #dbe7ee;
  border-radius: 24px;
  background: linear-gradient(180deg, #ffffff 0%, #f8fbfd 100%);
  box-shadow: 0 8px 22px rgba(16, 36, 56, 0.05);
  scroll-margin-top: 90px;
}

.project-visual {
  position: relative;
  min-height: 220px;
  padding: 20px;
  border-radius: 20px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  color: #fff;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.12);
}

.project-visual::before,
.project-visual::after {
  content: "";
  position: absolute;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.1);
}

.project-visual::before {
  width: 180px;
  height: 180px;
  right: -40px;
  top: -50px;
}

.project-visual::after {
  width: 140px;
  height: 140px;
  left: -30px;
  bottom: -40px;
}

.project-visual-kicker,
.project-visual-meta,
.project-visual-title {
  position: relative;
  z-index: 1;
}

.project-visual-kicker {
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.8);
}

.project-visual-title {
  font-size: 2rem;
  font-weight: 800;
  line-height: 1.05;
}

.project-visual-meta {
  font-size: 0.92rem;
  line-height: 1.6;
  color: rgba(255, 255, 255, 0.88);
}

.project-visual--human {
  background: linear-gradient(135deg, #48246f 0%, #236f91 58%, #7cc8dd 100%);
}

.project-visual--localization {
  background: linear-gradient(135deg, #18445e 0%, #217e8d 58%, #81d3b6 100%);
}

.project-visual--navigation {
  background: linear-gradient(135deg, #734629 0%, #a96b3d 54%, #efc37f 100%);
}

.project-visual--uav {
  background: linear-gradient(135deg, #3a2a6d 0%, #5d44a9 48%, #cf8ef7 100%);
}

.project-visual--pedaware {
  background: linear-gradient(135deg, #1d4662 0%, #2d7e88 55%, #93d2c6 100%);
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

.project-summary,
.project-detail {
  margin: 0 0 12px;
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
  .projects-hero,
  .project-card {
    padding: 18px 16px;
  }

  .projects-hero-actions {
    flex-direction: column;
  }

  .projects-hero-link {
    width: 100%;
  }

  .project-visual {
    min-height: 190px;
  }
}
</style>

<div class="projects-hero">
  <div class="projects-hero-kicker">Selected Projects</div>
  <p>
    A project-oriented view of my research in multimodal perception, audio-visual fusion, robot navigation, and autonomous systems.
    This page is organized around representative systems and research directions rather than individual papers.
  </p>

  <div class="projects-hero-tags">
    <span class="projects-hero-tag">Perception</span>
    <span class="projects-hero-tag">Navigation</span>
    <span class="projects-hero-tag">Audio-Visual Fusion</span>
    <span class="projects-hero-tag">Robotics</span>
  </div>

  <div class="projects-hero-actions">
    <a class="projects-hero-link primary" href="/publications/">View Publications</a>
    <a class="projects-hero-link secondary" href="/cv/">View CV</a>
  </div>
</div>

<div class="projects-note">
  This page is inspired by the clean research-project listing style of
  <a href="https://caomuqing.github.io/projects/">this reference page</a>,
  but adapted to better match the visual language and structure of your own site.
</div>

<section class="project-list">
  <article class="project-card" id="m4human">
    <div class="project-visual project-visual--human">
      <div class="project-visual-kicker">Dataset / Benchmark</div>
      <div class="project-visual-title">M4Human</div>
      <div class="project-visual-meta">Multimodal mmWave radar benchmark for 3D human mesh reconstruction</div>
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
        The project supports research on robust 3D human understanding under sensing conditions where purely visual approaches may be limited.
      </p>
      <p class="project-detail">
        Selected outputs include the CVPR 2026 paper, the public project website, and the released codebase for follow-up experimentation.
      </p>
      <div class="project-links">
        <a class="project-link publication" href="https://arxiv.org/abs/2512.12378">Paper</a>
        <a class="project-link code" href="https://github.com/FanJunqiao/M4Human">Code</a>
        <a class="project-link website" href="https://fanjunqiao.github.io/M4Human-site/">Website</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="uloc">
    <div class="project-visual project-visual--localization">
      <div class="project-visual-kicker">Localization</div>
      <div class="project-visual-title">ULoc</div>
      <div class="project-visual-meta">Learning-based localization with ultra-wideband ranging in large-scale environments</div>
    </div>

    <div class="project-content">
      <div class="project-tag-row">
        <span class="project-tag">ICRA 2025</span>
        <span class="project-tag">UWB</span>
        <span class="project-tag">Large-Scale Environments</span>
      </div>
      <h2 class="project-title">ULoc: Learning to Localize in Complex Large-Scale Environments with Ultra-Wideband Ranges</h2>
      <p class="project-summary">
        A learning-based localization project designed for complex large-scale environments, leveraging ultra-wideband range measurements as a key sensing signal.
        The goal is to make localization more reliable in difficult environments where traditional approaches may struggle.
      </p>
      <p class="project-detail">
        This project connects sensing, representation learning, and navigation-oriented robotics in a way that is directly relevant to autonomous deployment.
      </p>
      <div class="project-links">
        <a class="project-link publication" href="https://arxiv.org/abs/2409.11122">Paper</a>
        <a class="project-link code" href="https://github.com/brytsknguyen/uloc">Code</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="crowd-nav">
    <div class="project-visual project-visual--navigation">
      <div class="project-visual-kicker">Embodied Navigation</div>
      <div class="project-visual-title">Crowd Navigation</div>
      <div class="project-visual-meta">Planning and socially aware motion in dense human environments</div>
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
        and navigation policies that leverage surrounding pedestrian behavior as a planning cue.
      </p>
      <p class="project-detail">
        Together, these works focus on improving social awareness, adaptability, and motion quality for robots operating in dense and dynamic public environments.
      </p>
      <div class="project-links">
        <a class="project-link publication" href="https://arxiv.org/abs/2412.00555">Trajectory Planning</a>
        <a class="project-link publication" href="https://arxiv.org/abs/2504.10828">People-as-Planners</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="anti-uav">
    <div class="project-visual project-visual--uav">
      <div class="project-visual-kicker">Drone Perception</div>
      <div class="project-visual-title">Anti-UAV Suite</div>
      <div class="project-visual-meta">Audio-visual and multimodal perception for drone threat understanding</div>
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
        This includes both benchmark development and system-level identification pipelines.
      </p>
      <p class="project-detail">
        Representative outputs include MMAUD for multimodal anti-UAV data and AV-FDTI for audio-visual drone threat identification.
      </p>
      <div class="project-links">
        <a class="project-link publication" href="https://arxiv.org/abs/2402.03706">MMAUD Paper</a>
        <a class="project-link code" href="https://github.com/ntu-aris/MMAUD">MMAUD Code</a>
        <a class="project-link publication" href="https://www.sciencedirect.com/science/article/pii/S2949855424000285">AV-FDTI Paper</a>
        <a class="project-link code" href="https://github.com/yizhuoyang/AV-FDTI/">AV-FDTI Code</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="av-pedaware">
    <div class="project-visual project-visual--pedaware">
      <div class="project-visual-kicker">Audio-Visual Fusion</div>
      <div class="project-visual-title">AV-PedAware</div>
      <div class="project-visual-meta">Self-supervised fusion for dynamic pedestrian awareness in robotic systems</div>
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
        The work explores how complementary sensing can strengthen robot perception when visual cues alone are insufficient or unstable.
      </p>
      <p class="project-detail">
        This direction is closely aligned with embodied navigation and real-world perception, where robust awareness of nearby people is critical for safe behavior.
      </p>
      <div class="project-links">
        <a class="project-link publication" href="https://arxiv.org/abs/2411.06789">Paper</a>
        <a class="project-link code" href="https://github.com/yizhuoyang/AV-PedAware">Code</a>
      </div>
    </div>
  </article>
</section>
