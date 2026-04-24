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
<!-- 
<p class="projects-intro">
  Representative systems and research directions in multimodal perception, audio-visual fusion, localization,
  crowd-aware navigation, and autonomous robotics. Each project card below now links to a dedicated project page,
  where we can keep the broader story, visual overview, and future demo media separate from the publication list.
</p> -->

<section class="project-list">
  <article class="project-card" id="delta">
    <div class="project-media">
      <img src="/images/projects/delta.gif" alt="Illustration for the Delta project" loading="lazy">
    </div>

    <div class="project-content">
      <h2 class="project-title">Multi-Level Situation Awareness for Safe and Efficient Multi-agent Collaboration in Smart Manufacturing</h2>
      <p class="project-summary">
      In collaboration with Delta Electronics Inc. This project aims to develop solutions for autonomous robot planning in multi-level buildings and dense human crowds. The autonomous algorithm has been successfully tested in HDB buildings near Commonwealth, Singapore.
      </p>
      <div class="project-links">
        <a class="project-link details" href="/projects/delta/">View Details</a>
      </div>
    </div>
  </article>

  <article class="project-card" id="htx​">
    <div class="project-media">
      <img src="/images/projects/htx.gif" alt="Illustration for the ULoc project" loading="lazy">
    </div>

    <div class="project-content">
      <h2 class="project-title">Development of Embodied AI Language-Based Navigation System</h2>
      <p class="project-summary">
        A learning-based localization project for complex large-scale environments, using ultra-wideband range measurements as a key sensing signal.
        The core goal is to make localization more reliable when map scale, environment complexity, and sensing uncertainty increase.
      </p>

      <div class="project-links">
        <a class="project-link details" href="/projects/htx/">View Details</a>
      </div>
    </div>
  </article>

</section>
