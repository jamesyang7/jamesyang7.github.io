---
layout: single
title: "CV"
permalink: /cv/
author_profile: false
---

<style>
#main {
  max-width: 1400px;
}

#main .page {
  float: none !important;
  width: 100% !important;
  max-width: none !important;
  margin: 0 auto !important;
  padding-left: 0 !important;
  padding-right: 0 !important;
}

#main .page > .page__inner-wrap > header,
#main .page > .page__inner-wrap > footer.page__meta {
  display: none;
}

#main .page__inner-wrap,
#main .page__content {
  float: none !important;
  width: 100% !important;
  max-width: 100% !important;
  margin: 0 !important;
}

.cv-wrapper {
  width: min(1280px, 100%);
  margin: 0 auto;
  padding: 0 clamp(12px, 2vw, 28px) 32px;
  display: grid;
  gap: 18px;
  box-sizing: border-box;
}

.cv-hero {
  padding: clamp(24px, 4vw, 42px);
  border-radius: 24px;
  background: linear-gradient(135deg, #12395a 0%, #176d87 55%, #7fc8c2 100%);
  color: #fff;
  box-shadow: 0 20px 50px rgba(18, 57, 90, 0.16);
}

.cv-hero-kicker {
  margin-bottom: 10px;
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.78);
}

.cv-hero h1 {
  margin: 0 0 12px;
  font-size: clamp(2rem, 4vw, 3rem);
  line-height: 1.05;
  color: #fff;
}

.cv-hero p {
  margin: 0;
  max-width: 760px;
  font-size: 1rem;
  line-height: 1.72;
  color: rgba(255, 255, 255, 0.92);
}

.cv-hero-actions,
.cv-hero-links {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.cv-hero-actions {
  margin-top: 22px;
}

.cv-hero-links {
  margin-top: 16px;
}

.cv-download-btn,
.cv-secondary-link,
.cv-chip-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  border-radius: 999px;
  text-decoration: none !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease, background-color 0.2s ease, border-color 0.2s ease;
}

.cv-download-btn {
  padding: 12px 20px;
  background: #ffffff;
  color: #12395a !important;
  font-weight: 800;
  box-shadow: 0 10px 25px rgba(9, 25, 40, 0.15);
}

.cv-secondary-link,
.cv-chip-link {
  border: 1px solid rgba(255, 255, 255, 0.22);
  background: rgba(255, 255, 255, 0.12);
  color: #fff !important;
}

.cv-secondary-link {
  padding: 12px 20px;
  font-weight: 700;
}

.cv-chip-link {
  padding: 9px 14px;
  font-size: 0.92rem;
}

.cv-download-btn:hover,
.cv-secondary-link:hover,
.cv-chip-link:hover {
  transform: translateY(-1px);
}

.cv-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
}

.cv-section {
  padding: 20px 22px;
  border: 1px solid #d9e4ec;
  border-radius: 20px;
  background: linear-gradient(180deg, #ffffff 0%, #f7fafc 100%);
  box-shadow: 0 8px 24px rgba(16, 36, 56, 0.05);
}

.cv-section-title {
  margin: 0 0 16px;
  padding-bottom: 10px;
  border-bottom: 2px solid #8bc5d7;
  font-size: 1.15rem;
  font-weight: 800;
  color: #173756;
}

.cv-item + .cv-item {
  margin-top: 16px;
  padding-top: 16px;
  border-top: 1px solid #e5edf3;
}

.cv-edu-item {
  display: grid;
  grid-template-columns: minmax(0, 1fr) auto;
  gap: 14px;
  align-items: start;
}

.cv-item-title {
  margin-bottom: 4px;
  font-size: 1rem;
  font-weight: 700;
  line-height: 1.45;
  color: #173756;
}

.cv-item-subtitle {
  font-size: 0.94rem;
  line-height: 1.62;
  color: #5f7183;
}

.cv-item-meta {
  display: inline-flex;
  align-items: center;
  white-space: nowrap;
  padding: 6px 12px;
  border-radius: 999px;
  background: #eaf4fb;
  color: #266f95;
  font-size: 0.82rem;
  font-weight: 800;
}

.cv-tag-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.cv-tag {
  display: inline-flex;
  align-items: center;
  padding: 9px 12px;
  border: 1px solid #d6e6f1;
  border-radius: 999px;
  background: #eef6fb;
  color: #244b6a;
  font-size: 0.9rem;
  font-weight: 600;
  line-height: 1.4;
}

.cv-publication-list {
  list-style: none;
  margin: 0;
  padding: 0;
  display: grid;
  gap: 12px;
}

.cv-publication-list li {
  display: grid;
  grid-template-columns: minmax(0, 1fr) auto;
  gap: 12px;
  align-items: start;
  padding: 14px 16px;
  border: 1px solid #e3ebf2;
  border-radius: 16px;
  background: #fff;
}

.cv-publication-list a {
  color: #173756;
  text-decoration: none;
  font-weight: 700;
  line-height: 1.6;
}

.cv-publication-list a:hover {
  text-decoration: underline;
}

.cv-publication-venue {
  display: inline-flex;
  align-items: center;
  white-space: nowrap;
  padding: 7px 11px;
  border-radius: 999px;
  background: #e9f5f6;
  color: #0f6672;
  font-size: 0.82rem;
  font-weight: 800;
}

.cv-note-list {
  display: grid;
  gap: 12px;
}

.cv-note-item {
  padding: 14px 16px;
  border: 1px solid #e5edf3;
  border-radius: 16px;
  background: #fff;
}

.cv-contact-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 12px;
}

.cv-contact-card {
  display: block;
  padding: 14px 16px;
  border: 1px solid #dbe6ee;
  border-radius: 16px;
  background: #fff;
  color: inherit;
  text-decoration: none !important;
  box-shadow: 0 4px 14px rgba(16, 36, 56, 0.04);
  transition: transform 0.2s ease, border-color 0.2s ease, box-shadow 0.2s ease;
}

.cv-contact-card:hover {
  transform: translateY(-1px);
  border-color: #8bc5d7;
  box-shadow: 0 8px 18px rgba(16, 36, 56, 0.08);
}

.cv-contact-label {
  display: block;
  margin-bottom: 4px;
  font-size: 0.76rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #708295;
}

.cv-contact-value {
  display: block;
  color: #173756;
  font-size: 0.96rem;
  font-weight: 700;
  line-height: 1.5;
  overflow-wrap: anywhere;
}

@media (max-width: 900px) {
  .cv-grid,
  .cv-contact-grid,
  .cv-publication-list li,
  .cv-edu-item {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  #main {
    padding-left: 0.75rem;
    padding-right: 0.75rem;
  }

  .cv-wrapper {
    padding: 0 0 24px;
    gap: 14px;
  }

  .cv-section {
    padding: 18px 16px;
    border-radius: 18px;
  }

  .cv-hero {
    border-radius: 20px;
  }

  .cv-hero-actions,
  .cv-hero-links {
    flex-direction: column;
  }

  .cv-download-btn,
  .cv-secondary-link,
  .cv-chip-link {
    width: 100%;
  }
}
</style>

<div class="cv-wrapper">
  <section class="cv-hero">
    <div class="cv-hero-kicker">Curriculum Vitae</div>
    <h1>Yizhuo Yang</h1>
    <p>
      Ph.D. student in Electrical and Electronic Engineering at Nanyang Technological University, working on
      multimodal robot perception, robot audition, audio-visual fusion, and embodied navigation for autonomous systems.
    </p>

    <div class="cv-hero-actions">
      <a class="cv-download-btn" href="/files/CV_Yizhuo_Yang.pdf" target="_blank" rel="noopener noreferrer">Download PDF</a>
      <a class="cv-secondary-link" href="mailto:yizhuo001@e.ntu.edu.sg">Contact by email</a>
    </div>

    <div class="cv-hero-links">
      <a class="cv-chip-link" href="https://github.com/jamesyang7" target="_blank" rel="noopener noreferrer">GitHub</a>
      <a class="cv-chip-link" href="https://scholar.google.com/citations?user=d2aOcXsAAAAJ&hl=zh-CN" target="_blank" rel="noopener noreferrer">Google Scholar</a>
      <a class="cv-chip-link" href="https://orcid.org/0009-0000-9139-1542" target="_blank" rel="noopener noreferrer">ORCID</a>
    </div>
  </section>

  <section class="cv-section">
    <div class="cv-section-title">Education</div>

    <div class="cv-item cv-edu-item">
      <div>
        <div class="cv-item-title">Ph.D. in Electrical and Electronic Engineering</div>
        <div class="cv-item-subtitle">Nanyang Technological University, Singapore</div>
      </div>
      <div class="cv-item-meta">2022 - Present</div>
    </div>

    <div class="cv-item cv-edu-item">
      <div>
        <div class="cv-item-title">M.Sc. in Electrical and Electronic Engineering</div>
        <div class="cv-item-subtitle">Nanyang Technological University, Singapore</div>
      </div>
      <div class="cv-item-meta">2021 - 2022</div>
    </div>

    <div class="cv-item cv-edu-item">
      <div>
        <div class="cv-item-title">B.Eng. (First Class Honours) in Electronics and Electrical Engineering</div>
        <div class="cv-item-subtitle">Glasgow College, University of Electronic Science and Technology of China (UESTC)</div>
      </div>
      <div class="cv-item-meta">2017 - 2021</div>
    </div>
  </section>

  <div class="cv-grid">
    <section class="cv-section">
      <div class="cv-section-title">Research Interests</div>
      <div class="cv-tag-list">
        <span class="cv-tag">Multimodal robot perception</span>
        <span class="cv-tag">Audio-visual fusion</span>
        <span class="cv-tag">Robot audition</span>
        <span class="cv-tag">Embodied navigation</span>
        <span class="cv-tag">Anomaly detection for autonomous robots</span>
      </div>
    </section>

    <section class="cv-section">
      <div class="cv-section-title">Skills</div>
      <div class="cv-tag-list">
        <span class="cv-tag">Python</span>
        <span class="cv-tag">PyTorch</span>
        <span class="cv-tag">ROS</span>
        <span class="cv-tag">MATLAB</span>
        <span class="cv-tag">Machine learning</span>
        <span class="cv-tag">Multimodal perception systems</span>
        <span class="cv-tag">Experiment design</span>
        <span class="cv-tag">Academic writing</span>
      </div>
    </section>
  </div>

  <section class="cv-section">
    <div class="cv-section-title">Selected Publications</div>
    <ul class="cv-publication-list">
      <li>
        <a href="https://arxiv.org/abs/2411.06789" target="_blank" rel="noopener noreferrer">AV-PedAware: Self-Supervised Audio-Visual Fusion for Dynamic Pedestrian Awareness</a>
        <span class="cv-publication-venue">IROS 2023</span>
      </li>
      <li>
        <a href="https://www.sciencedirect.com/science/article/pii/S2949855424000285" target="_blank" rel="noopener noreferrer">AV-FDTI: Audio-visual fusion for drone threat identification”, Journal of Automation and Intelligence</a>
        <span class="cv-publication-venue">JAI 2024</span>
      </li>
      <li>
        <a href="https://arxiv.org/abs/2402.03706" target="_blank" rel="noopener noreferrer">MMAUD: A Comprehensive Multi-Modal Anti-UAV Dataset for Modern Miniature Drone Threats</a>
        <span class="cv-publication-venue">ICRA 2024</span>
      </li>
      <li>
        <a rel="noopener noreferrer">A Few-Shot Machinery Fault Diagnosis Framework Based on Self-Supervised Signal Representation Learning</a>
        <span class="cv-publication-venue">TIM 2024</span>
      </li>
      <li>
        <a href="https://arxiv.org/abs/2409.11122" target="_blank" rel="noopener noreferrer">ULoc: Learning to Localize in Complex Large-Scale Environments with Ultra-Wideband Ranges</a>
        <span class="cv-publication-venue">ICRA 2025</span>
      </li>
    </ul>
  </section>

  <div class="cv-grid">
    <section class="cv-section">
      <div class="cv-section-title">Awards and Honors</div>
      <div class="cv-note-list">
        <div class="cv-note-item">
          <div class="cv-item-title">National Scholarship</div>
          <div class="cv-item-subtitle">Awarded for outstanding academic performance and comprehensive achievements.</div>
        </div>
        <div class="cv-note-item">
          <div class="cv-item-title">Outstanding Student Scholarship (3 times)</div>
          <div class="cv-item-subtitle">Received multiple times for excellent academic performance and overall achievements.</div>
        </div>
        <div class="cv-note-item">
          <div class="cv-item-title">Outstanding Graduate</div>
          <div class="cv-item-subtitle">Recognized upon graduation for academic excellence and overall performance.</div>
        </div>
        <div class="cv-note-item">
          <div class="cv-item-title">Outstanding Undergraduate Thesis</div>
          <div class="cv-item-subtitle">Awarded for excellence in undergraduate thesis work.</div>
        </div>
      </div>
    </section>

    <section class="cv-section">
      <div class="cv-section-title">Contact</div>
      <div class="cv-contact-grid">
        <a class="cv-contact-card" href="mailto:yizhuo001@e.ntu.edu.sg">
          <span class="cv-contact-label">Email</span>
          <span class="cv-contact-value">yizhuo001@e.ntu.edu.sg</span>
        </a>
        <a class="cv-contact-card" href="https://github.com/jamesyang7" target="_blank" rel="noopener noreferrer">
          <span class="cv-contact-label">GitHub</span>
          <span class="cv-contact-value">github.com/jamesyang7</span>
        </a>
        <a class="cv-contact-card" href="https://scholar.google.com/citations?user=d2aOcXsAAAAJ&hl=zh-CN" target="_blank" rel="noopener noreferrer">
          <span class="cv-contact-label">Google Scholar</span>
          <span class="cv-contact-value">View profile</span>
        </a>
        <a class="cv-contact-card" href="https://orcid.org/0009-0000-9139-1542" target="_blank" rel="noopener noreferrer">
          <span class="cv-contact-label">ORCID</span>
          <span class="cv-contact-value">0009-0000-9139-1542</span>
        </a>
      </div>
    </section>
  </div>
</div>
