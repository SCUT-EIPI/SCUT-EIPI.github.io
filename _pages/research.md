---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
EIPI Lab studies intelligent perception and intelligent decision-making. We design new AI algorithms and turn them into working systems with industry partners.

## Research Directions

### Intelligent Decision-Making

We use large language models to build decision systems that fuse multimodal information. They understand meaning across modalities, reason about the situation, plan tasks in complex scenes, assess risk, and support decisions.

### Intelligent Perception

We use deep learning (CNN, YOLO, Transformer) and reinforcement learning to build perception functions. These include speech recognition, object recognition, product defect detection, and anomaly detection.

### Intelligent Optimization

We design efficient optimization algorithms for NP-hard scheduling problems and expensive black-box optimization. We also work on data regression and classification, and on knowledge discovery. Symbolic regression and genetic programming are our core tools.

### Multi-Agent Simulation

We use agent-based technology to simulate and project large complex systems. One example is behavior simulation and analysis of crowds in large airports.

## Industry Projects

We work with industry partners to move these methods into real products and services.

### Embodied Intelligent Brain (具身智能大脑)

With Zhuhai Amicro (珠海一微科技股份有限公司), we build a new generation of intelligent reception and tour-guide robots on a Unitree humanoid platform. Our AI vision and cognitive decision-making technology forms an embodied brain. It gives the robot natural human-robot interaction and intelligent decision-making. It supports smart museums, exhibition halls, and large public cultural and tourism venues.

The brain connects a large model to the physical world through the Model Context Protocol (MCP). The large model handles perception, decision planning, and task decomposition, and it draws on a memory and knowledge base. A unified protocol layer registers capabilities, manages context, and routes communication. On the physical side, MCP servers wrap vision capture, face recognition, navigation, and motion modules.

<figure>
  <img src="{{ '/images/research/embodied-mcp-architecture.jpg' | relative_url }}" alt="MCP-based architecture of the embodied intelligent brain" style="width: 640px; max-width: 100%;">
  <figcaption>Architecture of the embodied intelligent brain. The large model and knowledge base (digital side) reach the vision, face recognition, navigation, and motion modules (physical side) through MCP.</figcaption>
</figure>

<figure>
  <img src="{{ '/images/research/embodied-quadruped-robot.jpg' | relative_url }}" alt="Quadruped robot platform" style="width: 480px; max-width: 100%;">
  <figcaption>Quadruped robot platform.</figcaption>
</figure>

### Intelligent Decision Brain for Rural Revitalization (乡村振兴智能决策大脑)

Partner: Digital Guangdong Network Construction Co., Ltd. (数字广东网络建设有限公司).

This is a decision system for the whole agricultural chain, from production and processing to sales. It supports intelligent recognition and early warning, harvest decisions, grading, storage recommendation, smart pricing, and logistics optimization. It helps the agricultural industry chain move toward digital and intelligent operation.

The system has two application areas on one algorithm base. Smart agriculture covers production (smart harvesting, disease and pest recognition, field inspection, animal counting), processing (smart sorting, storage decisions), and sales (smart pricing, precision marketing, delivery and logistics optimization). Smart governance covers development planning (a one-map resource view, scheme simulation), a consultation platform (rural cloud clinic and classroom), and a government service assistant (policy interpretation, digital tools). The algorithm base has five parts: cross-modal spatio-temporal perception, a multi-objective adaptive optimization engine, a collaborative decision large model, multi-agent simulation, and an agricultural big-data knowledge graph.

<figure>
  <img src="{{ '/images/research/rural-decision-system.jpg' | relative_url }}" alt="Architecture of the rural revitalization decision system" style="width: 100%; max-width: 760px;">
  <figcaption>Architecture of the rural revitalization decision system.</figcaption>
</figure>

We also built a service agent for villagers and visitors. A livelihood assistant answers questions about public services, for example how to apply for pension insurance, and gives the steps, the place to go, and the phone number. A tourism planning assistant recommends sights and one-day routes on a map. The interface offers voice interaction and an elderly-friendly mode.

<video controls preload="metadata" poster="{{ '/images/research/rural-village-agent-demo-poster.jpg' | relative_url }}" style="width: 100%; max-width: 760px; border: 1px solid var(--global-border-color); border-radius: 4px;">
  <source src="{{ '/images/research/rural-village-agent-demo.mp4' | relative_url }}" type="video/mp4">
</video>
<p style="font-size: 0.85rem; color: var(--eipi-muted);">Demo of the village livelihood and cultural tourism service agent (about 4 minutes).</p>

### Smart Building Brain (智慧楼宇大脑)

Partner: Midea Group Co., Ltd. (美的集团股份有限公司).

A large language model is the core of the system. It is combined with a RAG knowledge base, task planning, and device control. The system makes intelligent decisions, schedules automatically, and interacts in natural language in building scenes. It works through a web page or on mobile devices. It serves smart building management and intelligent operation and maintenance.

The system combines a data layer (device data, user behavior, reservation data) with an intelligent capability layer (user preference learning, periodic tasks, smart recommendation, scene linkage). It controls air conditioning, lighting, curtains, fresh air, and security, and it manages meeting rooms. Users interact by natural language, touch, or mobile devices.

<figure>
  <img src="{{ '/images/research/smart-building-architecture.png' | relative_url }}" alt="Architecture of the smart building brain" style="width: 640px; max-width: 100%;">
  <figcaption>Architecture of the smart building brain.</figcaption>
</figure>

### Crowd Digital Twin and Smart Control System for Large Complex Spaces (大型复杂空间人群数字孪生与智慧管控系统)

Partner: Guangdong Airport Authority (广东省机场管理集团有限公司).

We built a multimodal crowd digital twin platform from more than 60 TB of video data. It monitors passenger flow and density, detects anomalies, and supports management optimization. The platform can predict, detect, and optimize. It serves crowd management and safe operation in large public spaces.

<figure>
  <img src="{{ '/images/research/crowd-airport-counting.png' | relative_url }}" alt="Crowd counting results in airport terminals" style="width: 760px; max-width: 100%;">
  <figcaption>Crowd counting in airport terminals. For each camera view (left), the system estimates a density map (middle) and detects individuals (right).</figcaption>
</figure>

### Defect Detection for Industrial Production Lines (工业产线产品缺陷检测)

AI vision automatically identifies and flags PCB soldering defects. It raises the efficiency and accuracy of quality inspection on production lines. It applies to PCB manufacturing and other industrial quality-inspection scenes.

<figure>
  <img src="{{ '/images/research/pcb-defect-detection.jpg' | relative_url }}" alt="PCB defect detection interface" style="width: 640px; max-width: 100%;">
  <figcaption>Detection interface. Each board on the panel is marked OK or NG, and the banner reports matched and unmatched items.</figcaption>
</figure>

<figure>
  <img src="{{ '/images/research/pcb-defect-heatmap.png' | relative_url }}" alt="Heat map of defect locations over a board layout" style="width: 640px; max-width: 100%;">
  <figcaption>Heat map of detected defect locations over the board layout. Red areas show where defects concentrate.</figcaption>
</figure>

### Edge Safety Terminal for Elevators Based on AI Vision (基于AI视觉技术的电梯边缘智能安全终端)

Partner: Midea Group Co., Ltd. (美的集团股份有限公司).

AI vision algorithms run on the device side on a domestic low-power chip. They recognize electric vehicles, count people, and detect falls. Object detection and tracking are the core technology. The system improves real-time monitoring and risk warning for elevator safety management.

<figure>
  <img src="{{ '/images/research/elevator-edge-board.png' | relative_url }}" alt="Edge test board for the elevator safety terminal" style="width: 320px; max-width: 100%;">
  <figcaption>Edge test board (HongOU PI, Hi3516DV500) that runs the detection models.</figcaption>
</figure>

<figure>
  <img src="{{ '/images/research/elevator-detection-results.png' | relative_url }}" alt="Detection results inside elevator cabins" style="width: 480px; max-width: 100%;">
  <figcaption>Detection results inside elevator cabins. The model finds electric vehicles (orange boxes) and people (blue boxes).</figcaption>
</figure>

### Medical Infusion Monitoring System Based on Computer Vision (基于计算机视觉的医疗输液监测系统)

Partner: Midea Group Co., Ltd. (美的集团股份有限公司).

Computer vision recognizes the infusion state and monitors abnormal events. The system deploys locally on edge devices and targets hospital wards. It improves ward nursing efficiency and intelligent management.

<figure>
  <img src="{{ '/images/research/infusion-monitoring-deployment.png' | relative_url }}" alt="Deployment of the infusion monitoring system in a hospital" style="width: 100%; max-width: 760px;">
  <figcaption>System deployment. Left: bedside screen in the infusion area or ward. Right: door display and nurse station, and the IT room with the management system (HIS integration).</figcaption>
</figure>

## Project Inquiries

For industry collaboration, please contact [Prof. Jinghui Zhong](mailto:jinghuizhong@scut.edu.cn).
