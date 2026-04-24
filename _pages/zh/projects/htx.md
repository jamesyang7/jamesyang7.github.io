---
layout: single
title: "具身智能语言导航系统开发"
permalink: /zh/projects/htx/
author_profile: true
lang: zh
translation_url: /projects/htx/
---

{% include project-detail-styles.html %}

<a class="project-backlink" href="/zh/projects/">&larr; 返回全部项目</a>

<p class="project-detail-summary">
  HTX 项目开发了一套具身智能系统，使四足机器人能够理解语言指令、探索室内环境，
  并完成搜索与抓取任务。
</p>

<figure class="project-detail-hero-media">
  <img src="/images/projects/htx.gif" alt="HTX 项目总览" loading="lazy">
</figure>

## 项目概览

<p class="project-lead">
  该项目面向室内导航与目标抓取场景，构建了一套由语言驱动的机器人系统。
  整个系统将语言理解、语义感知、建图、规划与操作整合在统一框架中，
  使机器人能够从自然语言指令出发，完成目标搜索、路径规划与物体获取。
</p>

<div class="project-metric-grid">
  <article class="project-metric-card">
    <h3 class="project-metric-title">语言理解</h3>
    <p class="project-metric-text">
      机器人能够接收语音或文本指令，并将其转化为可执行的导航与搜索目标。
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">语义建图</h3>
    <p class="project-metric-text">
      系统结合视觉观测、深度信息与机器人位姿，构建语义记忆用于推理与规划。
    </p>
  </article>
  <article class="project-metric-card">
    <h3 class="project-metric-title">导航与抓取</h3>
    <p class="project-metric-text">
      机器人可以在未知环境中搜索目标、规划路径，并利用机械臂完成抓取。
    </p>
  </article>
</div>

<figure class="project-detail-hero-media">
  <img src="/images/projects/htx2.gif" alt="HTX 系统流程与机器人行为" loading="lazy">
</figure>

## 语言导航

<p class="project-lead">
  导航模块融合了语音转文本、视觉语言目标定位、开放词汇检测以及基于 frontier 的探索策略。
  自然语言指令会被解析为目标物体或目标区域，系统在探索过程中持续选择候选观察点与导航目标。
</p>

## 多层感知与推理

<p class="project-lead">
  整个系统采用多层架构，包括实时感知、语义场景记忆以及更高层的深度推理模块。
  这样既能保证机器人在机载端的实时响应，又能支持对历史观测进行更复杂的语义推理。
</p>

## 语义建图与空间记忆

<p class="project-lead">
  项目会逐步构建由三维目标实体与关键帧图像组成的语义场景图。检测到的目标会在跨帧关联后
  合并为持久化地图实体，而关键帧则被保留下来，用于后续推理和导航。
</p>

## 语义 SLAM 与闭环检测

<p class="project-lead">
  为了提升长时程定位能力，系统引入了基于文本线索的闭环检测模块。通过 OCR 提取的场景文字被映射到机器人位姿，
  作为语义地标用于检索、验证以及位姿图优化。
</p>

## 搜索与抓取

<p class="project-lead">
  机器人具备完整的搜索与抓取流程，涵盖实例级感知、抓取姿态对齐、可达性判断、末端对接与操作执行。
  其中两阶段抓取设计会先估计稳定的全局抓取参考，再在近距离执行阶段进一步精细调整。
</p>

## 系统集成

<p class="project-lead">
  整个系统将机载计算平台、RGB-D 传感器、LiDAR、音频输入、语义建图、导航与操作模块整合在一起，
  形成可在真实室内环境中运行的具身智能机器人框架。
</p>
