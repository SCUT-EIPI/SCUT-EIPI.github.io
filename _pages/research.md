---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
EIPI Lab works on intelligent perception and intelligent decision-making. We develop new methods in evolutionary computation, machine learning, and large language models. We test them on scientific and engineering problems, and we deploy them as working systems with industry partners.

## Research Directions

### Intelligent Decision-Making

We build decision systems that use large language models to fuse multimodal information. The systems understand meaning across modalities, reason about the situation, plan tasks in complex scenes, assess risk, and support decisions. We also check what the models produce. For example, TriVAL validates the semantic specification, the mathematical formulation, and the solver code in automatic optimization modeling.

### Intelligent Perception

We develop perception functions with deep learning (CNN, YOLO, Transformer) and reinforcement learning. They include speech recognition, object recognition, product defect detection, and anomaly detection. We also care about deployment. Several of our models run on edge devices, including domestic low-power chips, for elevator safety and hospital infusion monitoring.

### Intelligent Optimization

We design efficient algorithms for NP-hard scheduling problems, expensive black-box optimization, data regression and classification, and knowledge discovery. Evolutionary computation is our main tool. Our work includes genetic programming and symbolic regression, which find explicit mathematical expressions from data. It also includes evolutionary multitasking, which transfers knowledge among related optimization tasks, and law-driven search for closed-form solutions of partial differential equations.

### Multi-Agent Simulation

We use agent-based models to simulate and project the behavior of large complex systems. A typical case is crowd simulation in large airports. We combine simulation with optimization and learning, for example to plan crowd paths, place fences, and control crowd inflow.

## Industry Projects

We work with industry partners to move these methods into real products and services.

### Embodied Intelligent Brain (具身智能大脑)

With Zhuhai Amicro (珠海一微科技股份有限公司), we build a new generation of intelligent reception and tour-guide robots on a Unitree humanoid platform. Our AI vision and cognitive decision-making technology forms an embodied brain. It gives the robot natural human-robot interaction and intelligent decision-making. It supports smart museums, exhibition halls, and large public cultural and tourism venues.

<div class="fig-row fig-row--multi">
  <img src="{{ '/images/research/embodied-mcp-architecture.jpg' | relative_url }}" alt="Embodied intelligent brain architecture">
  <img src="{{ '/images/research/embodied-quadruped-robot.jpg' | relative_url }}" alt="Robot platform">
</div>

### Intelligent Decision Brain for Rural Revitalization (乡村振兴智能决策大脑)

Partner: Digital Guangdong Network Construction Co., Ltd. (数字广东网络建设有限公司). This is a decision system for the whole agricultural chain, from production and processing to sales. It supports intelligent recognition and early warning, harvest decisions, grading, storage recommendation, smart pricing, and logistics optimization. It helps the agricultural industry chain move toward digital and intelligent operation.

<div class="fig-row fig-row--single">
  <img src="{{ '/images/research/rural-decision-system.jpg' | relative_url }}" alt="Rural revitalization decision system">
</div>

<div class="fig-row fig-row--single">
  <video controls preload="metadata" poster="{{ '/images/research/rural-village-agent-demo-poster.jpg' | relative_url }}">
    <source src="{{ '/images/research/rural-village-agent-demo.mp4' | relative_url }}" type="video/mp4">
  </video>
</div>

### Smart Building Brain (智慧楼宇大脑)

Partner: Midea Group Co., Ltd. (美的集团股份有限公司). A large language model is the core of the system. It is combined with a RAG knowledge base, task planning, and device control. The system makes intelligent decisions, schedules automatically, and interacts in natural language in building scenes. It works through a web page or on mobile devices. It serves smart building management and intelligent operation and maintenance.

<div class="fig-row fig-row--single">
  <img src="{{ '/images/research/smart-building-architecture.png' | relative_url }}" alt="Smart building brain architecture">
</div>

### Crowd Digital Twin and Smart Control System for Large Complex Spaces (大型复杂空间人群数字孪生与智慧管控系统)

Partner: Guangdong Airport Authority (广东省机场管理集团有限公司). We built a multimodal crowd digital twin platform from more than 60 TB of video data. It monitors passenger flow and density, detects anomalies, and supports management optimization. The platform can predict, detect, and optimize. It serves crowd management and safe operation in large public spaces.

<div class="fig-row fig-row--multi">
  <img src="{{ '/images/research/crowd-airport-counting.png' | relative_url }}" alt="Crowd counting in airport terminals">
  <img src="{{ '/images/research/crowd-density-heatmap.png' | relative_url }}" alt="Crowd density heat map">
</div>

### Defect Detection for Industrial Production Lines (工业产线产品缺陷检测)

AI vision automatically identifies and flags PCB soldering defects. It raises the efficiency and accuracy of quality inspection on production lines. It applies to PCB manufacturing and other industrial quality-inspection scenes.

<div class="fig-row fig-row--single">
  <img src="{{ '/images/research/pcb-defect-detection.jpg' | relative_url }}" alt="PCB defect detection interface">
</div>

### Edge Safety Terminal for Elevators Based on AI Vision (基于AI视觉技术的电梯边缘智能安全终端)

Partner: Midea Group Co., Ltd. (美的集团股份有限公司). AI vision algorithms run on the device side on a domestic low-power chip. They recognize electric vehicles, count people, and detect falls. Object detection and tracking are the core technology. The system improves real-time monitoring and risk warning for elevator safety management.

<div class="fig-row fig-row--multi">
  <img src="{{ '/images/research/elevator-edge-board.png' | relative_url }}" alt="Edge test board">
  <img src="{{ '/images/research/elevator-detection-results.png' | relative_url }}" alt="Detection results in elevator cabins">
</div>

### Medical Infusion Monitoring System Based on Computer Vision (基于计算机视觉的医疗输液监测系统)

Partner: Midea Group Co., Ltd. (美的集团股份有限公司). Computer vision recognizes the infusion state and monitors abnormal events. The system deploys locally on edge devices and targets hospital wards. It improves ward nursing efficiency and intelligent management.

<div class="fig-row fig-row--single">
  <img src="{{ '/images/research/infusion-monitoring-deployment.png' | relative_url }}" alt="Infusion monitoring system deployment">
</div>
