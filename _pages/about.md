---
layout: archive
title: "Welcome to My Personal Homepage"
permalink: /
author_profile: true
---

<style>
.page__content > p,
.page__content li,
.page__content .news-content,
.page__content .news-date {
  font-size: 0.97rem;
  line-height: 1.7;
}

.page__content h2 {
  margin-top: 1.55rem;
  margin-bottom: 0.7rem;
}

.news-scroll-box {
  max-height: 260px;
  overflow-y: auto;
  padding: 14px 14px 6px;
  margin-top: 0.5rem;
  margin-bottom: 1.35rem;
  border: 1px solid #dbe7ee;
  border-radius: 18px;
  background: linear-gradient(180deg, #fbfdfe 0%, #f5f9fc 100%);
  box-shadow: 0 10px 24px rgba(16, 36, 56, 0.05);
}

.news-item {
  display: grid;
  grid-template-columns: 88px 1fr;
  column-gap: 16px;
  align-items: start;
  margin-bottom: 12px;
  padding-bottom: 12px;
  border-bottom: 1px solid #e6eef3;
}

.news-item:last-child {
  margin-bottom: 0;
  padding-bottom: 4px;
  border-bottom: 0;
}

.news-date {
  font-weight: 800;
  color: #173756;
  white-space: nowrap;
}

.news-content {
  color: #445566;
}

.news-content a {
  color: #24709a;
  text-decoration: none;
}

.news-content a:hover {
  text-decoration: underline;
}

.news-scroll-box::-webkit-scrollbar {
  width: 8px;
}

.news-scroll-box::-webkit-scrollbar-track {
  background: #eef3f6;
  border-radius: 999px;
}

.news-scroll-box::-webkit-scrollbar-thumb {
  background: #93a8b6;
  border-radius: 999px;
}

.news-scroll-box::-webkit-scrollbar-thumb:hover {
  background: #738a9a;
}

.featured-pub-list {
  display: grid;
  gap: 18px;
  margin: 0.45rem 0 1.35rem;
}

.featured-pub-card {
  display: grid;
  grid-template-columns: 150px minmax(0, 1fr);
  gap: 20px;
  padding: 20px;
  border: 1px solid #dbe7ee;
  border-radius: 22px;
  background: linear-gradient(180deg, #ffffff 0%, #f8fbfd 100%);
  box-shadow: 0 8px 22px rgba(16, 36, 56, 0.05);
}

.featured-pub-media {
  display: block;
  aspect-ratio: 4 / 3;
  overflow: hidden;
  border: 1px solid #d9e5ec;
  border-radius: 12px;
  background: #eef4f8;
}

.featured-pub-media img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.featured-pub-body {
  display: flex;
  flex-direction: column;
}

.featured-pub-title {
  margin: 0 0 8px;
  color: #173756;
  font-size: 1.02rem;
  font-weight: 800;
  line-height: 1.42;
}

.featured-pub-authors {
  margin: 0 0 10px;
  color: #7a8088;
  font-size: 0.93rem;
  font-weight: 700;
  line-height: 1.55;
}

.featured-pub-note {
  margin-bottom: 14px;
  padding: 11px 14px;
  border-radius: 12px;
  background: #f4f7fa;
  color: #2f89d9;
  font-size: 0.92rem;
  font-style: italic;
  font-weight: 700;
  line-height: 1.6;
}

.featured-pub-desc {
  margin: 0 0 14px;
  color: #627485;
  font-size: 0.93rem;
  line-height: 1.68;
}

.featured-pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.featured-pub-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 76px;
  padding: 7px 12px;
  border: 1px solid #d6e2eb;
  border-radius: 6px;
  background: #fff;
  color: #2a78b7 !important;
  font-size: 0.88rem;
  text-decoration: none !important;
}

.featured-pub-link:hover {
  border-color: #9ec7df;
  background: #f7fbfe;
}

.home-links-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px;
  margin: 0.35rem 0 1.2rem;
}

.home-link-card {
  display: block;
  padding: 18px;
  border: 1px solid #dbe7ee;
  border-radius: 20px;
  background: linear-gradient(180deg, #ffffff 0%, #f6fafc 100%);
  box-shadow: 0 8px 22px rgba(16, 36, 56, 0.05);
  text-decoration: none !important;
  transition: transform 0.2s ease, border-color 0.2s ease, box-shadow 0.2s ease;
}

.home-link-card:hover {
  transform: translateY(-2px);
  border-color: #8fc3d8;
  box-shadow: 0 14px 28px rgba(16, 36, 56, 0.08);
}

.home-link-label {
  display: inline-flex;
  padding: 6px 10px;
  border-radius: 999px;
  background: #ecf5fb;
  color: #1f6a92;
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}

.home-link-title {
  display: block;
  margin-top: 12px;
  color: #173756;
  font-size: 1.04rem;
  font-weight: 800;
  line-height: 1.4;
}

.home-link-desc {
  display: block;
  margin-top: 8px;
  color: #647586;
  line-height: 1.65;
}

@media (max-width: 768px) {
  .news-item {
    grid-template-columns: 1fr;
  }

  .news-date {
    margin-bottom: 2px;
  }

  .featured-pub-card {
    grid-template-columns: 1fr;
  }

  .featured-pub-media {
    max-width: 220px;
  }
}
</style>

I am currently a Ph.D. candidate in the School of Electrical and Electronic Engineering at Nanyang Technological University (NTU), under the supervision of [Prof. Lihua Xie](https://dr.ntu.edu.sg/entities/person/Xie-Lihua/).

Prior to joining NTU, I obtained a joint B.Eng. in Electronics and Electrical Engineering with First Class Honours from both the University of Glasgow (UoG) and the University of Electronic Science and Technology of China (UESTC).

## Research Interests
- Multimodal robot perception
- Audio-visual fusion
- Robot audition
- Embodied navigation
- Anomaly detection

## Education
- **Ph.D. Candidate**, School of Electrical and Electronic Engineering, Nanyang Technological University, 2022-Present
- **M.Sc.**, School of Electrical and Electronic Engineering, Nanyang Technological University, 2021-2022
- **B.Eng. (First Class Honours)**, Glasgow College, University of Electronic Science and Technology of China (UESTC), 2017-2021

## News

<div class="news-scroll-box">
  <div class="news-item">
    <div class="news-date">2026/02</div>
    <div class="news-content">
      Our paper <a href="https://arxiv.org/abs/2512.12378"><strong>M4Human</strong></a> was accepted to <em>CVPR 2026</em>.
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">2025/01</div>
    <div class="news-content">
      Our paper <a href="https://arxiv.org/abs/2409.11122"><strong>ULoc</strong></a> was accepted to <em>ICRA 2025</em>.
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">2025/01</div>
    <div class="news-content">
      Our work <a href="https://arxiv.org/abs/2412.00555"><strong>Learning Dynamic Weight Adjustment for Spatial-Temporal Trajectory Planning in Crowd Navigation</strong></a> was accepted to <em>ICRA 2025</em>.
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">2024/06</div>
    <div class="news-content">
      Our paper <a href="https://arxiv.org/abs/2411.06789"><strong>AV-PedAware</strong></a> was accepted to <em>IROS 2024</em>.
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">2024/01</div>
    <div class="news-content">
      Our paper <a href="https://arxiv.org/abs/2402.03706"><strong>MMAUD</strong></a> was accepted to <em>ICRA 2024</em>.
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">2024/01</div>
    <div class="news-content">
      Our paper <strong>A few-shot machinery fault diagnosis framework based on self-supervised signal representation learning</strong> was accepted to <em>IEEE TIM</em>.
    </div>
  </div>
</div>

## Research Highlights

<div class="featured-pub-list">
  <article class="featured-pub-card">
    <div class="featured-pub-media">
      <img src="/images/projects/m4human.svg" alt="Visual summary for M4Human" loading="lazy">
    </div>
    <div class="featured-pub-body">
      <h3 class="featured-pub-title">M4Human: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction</h3>
      <p class="featured-pub-authors">J. Fan, Y. Zhou, <strong>Y. Yang</strong>, X. Cui, J. Zhang, L. Xie, J. Yang, C.X. Lu, F. Ding</p>
      <div class="featured-pub-note">IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026</div>
      <p class="featured-pub-desc">
        A benchmark paper centered on multimodal sensing and radar-based 3D human understanding, with an emphasis on robust perception beyond purely visual settings.
      </p>
      <div class="featured-pub-links">
        <a class="featured-pub-link" href="https://arxiv.org/abs/2512.12378">Paper</a>
        <a class="featured-pub-link" href="https://github.com/FanJunqiao/M4Human">Code</a>
      </div>
    </div>
  </article>

  <article class="featured-pub-card">
    <div class="featured-pub-media">
      <img src="/images/projects/uloc.svg" alt="Visual summary for ULoc" loading="lazy">
    </div>
    <div class="featured-pub-body">
      <h3 class="featured-pub-title">ULoc: Learning to Localize in Complex Large-Scale Environments with UWB Ranges</h3>
      <p class="featured-pub-authors">T.M. Nguyen, <strong>Y. Yang</strong>, T.D. Nguyen, S. Yuan, L. Xie</p>
      <div class="featured-pub-note">IEEE International Conference on Robotics and Automation (ICRA), 2025</div>
      <p class="featured-pub-desc">
        A localization paper that uses ultra-wideband range signals to improve positioning robustness in complex large-scale environments.
      </p>
      <div class="featured-pub-links">
        <a class="featured-pub-link" href="https://arxiv.org/abs/2409.11122">Paper</a>
        <a class="featured-pub-link" href="https://github.com/brytsknguyen/uloc">Code</a>
      </div>
    </div>
  </article>

  <article class="featured-pub-card">
    <div class="featured-pub-media">
      <img src="/images/projects/av-pedaware.svg" alt="Visual summary for AV-PedAware" loading="lazy">
    </div>
    <div class="featured-pub-body">
      <h3 class="featured-pub-title">AV-PedAware: Self-Supervised Audio-Visual Fusion for Dynamic Pedestrian Awareness</h3>
      <p class="featured-pub-authors"><strong>Y. Yang</strong>, S. Yuan, M. Cao, J. Yang, L. Xie</p>
      <div class="featured-pub-note">IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2024</div>
      <p class="featured-pub-desc">
        A self-supervised audio-visual fusion paper for stronger pedestrian awareness in dynamic scenes, with direct relevance to embodied navigation and safe autonomy.
      </p>
      <div class="featured-pub-links">
        <a class="featured-pub-link" href="https://arxiv.org/abs/2411.06789">Paper</a>
        <a class="featured-pub-link" href="https://github.com/yizhuoyang/AV-PedAware">Code</a>
      </div>
    </div>
  </article>
</div>

## Explore

<div class="home-links-grid">
  <a class="home-link-card" href="/publications/">
    <span class="home-link-label">Publications</span>
    <span class="home-link-title">Browse papers, code links, and project pages</span>
    <span class="home-link-desc">A curated list of conference papers and journal articles in multimodal perception, robot learning, and autonomous systems.</span>
  </a>

  <a class="home-link-card" href="/projects/">
    <span class="home-link-label">Projects</span>
    <span class="home-link-title">See selected systems and research directions</span>
    <span class="home-link-desc">A project-oriented view of your work, organized around themes like localization, crowd navigation, and multimodal perception.</span>
  </a>

  <a class="home-link-card" href="/awards/">
    <span class="home-link-label">Awards</span>
    <span class="home-link-title">See scholarships and academic honors</span>
    <span class="home-link-desc">A concise overview of undergraduate distinctions, graduation honors, and merit-based recognitions.</span>
  </a>
</div>

## Contact
Email: [yizhuo001@e.ntu.edu.sg](mailto:yizhuo001@e.ntu.edu.sg)
