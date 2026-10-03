---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

EIPI Lab studies intelligent perception and intelligent decision-making. We design new AI algorithms and turn them into working systems with industry partners. The lab has 8 high-performance GPU servers, with 24 RTX 4090 GPUs and 1,000 CPU cores. They support multimodal perception, deep learning model training, and fast project development.

## Research Directions

<div class="research-grid">
  <div class="research-card">
    <h3>Intelligent Decision-Making</h3>
    <p>We use large language models to build decision systems that fuse multimodal information. They understand meaning across modalities, reason about the situation, plan tasks in complex scenes, assess risk, and support decisions.</p>
  </div>
  <div class="research-card">
    <h3>Intelligent Perception</h3>
    <p>We use deep learning (CNN, YOLO, Transformer) and reinforcement learning to build perception functions. These include speech recognition, object recognition, product defect detection, and anomaly detection.</p>
  </div>
  <div class="research-card">
    <h3>Intelligent Optimization</h3>
    <p>We design efficient optimization algorithms for NP-hard scheduling problems and expensive black-box optimization. We also work on data regression and classification, and on knowledge discovery. Symbolic regression and genetic programming are our core tools.</p>
  </div>
  <div class="research-card">
    <h3>Multi-Agent Simulation</h3>
    <p>We use agent-based technology to simulate and project large complex systems. One example is behavior simulation and analysis of crowds in large airports.</p>
  </div>
</div>

## Industry Projects

We work with industry partners to move these methods into real products and services. Partners include Midea, Digital Guangdong, Guangdong Airport Authority, and Amicro Semiconductor.

<div class="project-list">
{% for p in site.data.projects %}
  <div class="project-card">
    <img src="{{ '/images/research/' | append: p.image | relative_url }}" alt="{{ p.title }}" loading="lazy">
    <div class="project-body">
      <h3>{{ p.title }}</h3>
      <p>{{ p.text }}</p>
      {% if p.partner %}<p class="project-partner">Partner: {{ p.partner }}</p>{% endif %}
    </div>
  </div>
{% endfor %}
</div>

## AI Training

We also run AI training programs for industry. They follow four steps: build awareness of AI, practice with real tools, anchor the tools in the trainees' own scenarios, and provide long-term service. The aim is to help companies upgrade digitally.

<img src="{{ '/images/research/ai-training.png' | relative_url }}" alt="AI agent advanced training class" style="max-width: 100%; border-radius: 6px;">

## Project Inquiries

For industry collaboration, please contact [Prof. Jinghui Zhong](mailto:jinghuizhong@scut.edu.cn).

<style>
.research-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 16px; margin-bottom: 1.5em; }
.research-card, .project-card { border: 1px solid var(--global-border-color, #ddd); border-radius: 8px; padding: 14px 16px; }
.research-card h3, .project-card h3 { margin-top: 0; }
.project-list { display: grid; gap: 16px; }
.project-card { display: flex; flex-wrap: wrap; gap: 16px; align-items: flex-start; }
.project-card img { flex: 0 1 300px; max-width: 100%; border-radius: 4px; }
.project-body { flex: 1 1 300px; min-width: 0; }
.project-body p { margin: 0 0 .5em; }
.project-partner { font-size: .85em; opacity: .75; }
</style>
