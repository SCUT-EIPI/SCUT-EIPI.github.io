---
layout: archive
title: "Repositories"
permalink: /repositories/
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

<div class="wordwrap" style="margin-bottom: 25px; padding: 14px 18px; background-color: #f8f9fa; border-left: 4px solid #0969da; border-radius: 4px; font-size: 0.95em; line-height: 1.6;">
  我们积极倡导开源科学与可复现研究。以下为团队维护的核心开源代码库与配套实践资源。所有最新项目请访问团队官方组织：<a href="https://github.com/SCUT-EIPI" target="_blank"><strong>SCUT-EIPI GitHub Organization</strong></a>。
</div>

## 📦 核心开源项目 (Featured Repositories)

<!-- Repo 1: SL-GEP -->
<div class="repo-card">
  <div class="repo-header">
    <div class="repo-title">
      <a href="https://github.com/SCUT-EIPI/Self-learning-Gene-Expression-Programming" target="_blank">
        <svg class="octicon" viewBox="0 0 16 16" width="20" height="20" fill="currentColor" style="vertical-align: text-bottom; margin-right: 6px;"><path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path></svg>
        Self-learning-Gene-Expression-Programming (SL-GEP)
      </a>
      <span class="repo-badge">Public</span>
    </div>
    <div class="repo-tags">
      <span class="tag-chip">C++</span>
      <span class="tag-chip">IEEE TEVC Classic</span>
      <span class="tag-chip">Symbolic Regression</span>
    </div>
  </div>

  <p class="repo-desc">
    <b>自学习基因表达式编程（SL-GEP）</b>官方算法开源实现与评测基准。SL-GEP 是用于求解复杂符号回归与函数自适应发现的经典进化算法框架。
  </p>

  <div class="repo-features">
    <ul>
      <li><b>核心算法：</b>提供完整的 C/C++ 高性能源码实现，支持自学习突变机制与复杂数学结构搜索。</li>
      <li><b>基准数据集：</b>内置经典符号回归基准（F0-F3 多项式及超越函数、Tower 复杂嵌套函数），每组均包含 10 次独立运行划分的标准化训练与测试集。</li>
      <li><b>评测标准：</b>以均方根误差 (RMSE) 作为核心适应度度量标准，支持收敛阈值设定与高鲁棒性评测。</li>
    </ul>
  </div>

  <div class="repo-citation">
    <b>📄 对应论文引用：</b><br>
    Jinghui Zhong, Yaochu Jin, and Weiwei Cai, "Self-learning gene expression programming," <i>IEEE Transactions on Evolutionary Computation</i>, Vol. 20, No. 1, pp. 65–80, 2016.
  </div>

  <div class="repo-footer">
    <a href="https://github.com/SCUT-EIPI/Self-learning-Gene-Expression-Programming" class="btn-repo" target="_blank">前往 GitHub 仓库 ↗</a>
  </div>
</div>

<br>

<!-- Repo 2: Book Companion Code -->
<div class="repo-card">
  <div class="repo-header">
    <div class="repo-title">
      <a href="https://github.com/SCUT-EIPI/GP-and-its-applications" target="_blank">
        <svg class="octicon" viewBox="0 0 16 16" width="20" height="20" fill="currentColor" style="vertical-align: text-bottom; margin-right: 6px;"><path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path></svg>
        GP-and-its-applications (《遗传编程算法及其应用》配套代码库)
      </a>
      <span class="repo-badge">Public</span>
    </div>
    <div class="repo-tags">
      <span class="tag-chip">Python</span>
      <span class="tag-chip">Jupyter Notebook</span>
      <span class="tag-chip">科学出版社 2026</span>
    </div>
  </div>

  <p class="repo-desc">
    <b>《遗传编程算法及其应用》（科学出版社, 2026）</b>官方随书实践源代码库与教学资源中心。为读者、高校师生及学术同行提供开箱即用的遗传编程与符号推理实验平台。
  </p>

  <div class="repo-features">
    <ul>
      <li><b>全算法覆盖：</b>涵盖标准遗传编程 (SGP)、线性遗传编程 (LGP)、基因表达式编程 (GEP)、多型遗传编程 (Multiform GP) 等主流演化范式。</li>
      <li><b>渐进式 Notebook 实践：</b>从基础程序演化、从数据到公式搜索（F1-F12 基准），到基于 GEP 的规则分类与高维符号建模，均提供保姆级 Jupyter 演示。</li>
      <li><b>教学支持：</b>包含配套课件示例、实验练习与数据集，全面支持高校《计算智能》、《演化计算》与《AI for Science》相关课程教学。</li>
    </ul>
  </div>

  <div class="repo-citation">
    <b>📖 对应专著引用：</b><br>
    钟竞辉. 《遗传编程算法及其应用》[M]. 北京: 科学出版社, 2026.
  </div>

  <div class="repo-footer">
    <a href="https://github.com/SCUT-EIPI/GP-and-its-applications" class="btn-repo" target="_blank">前往 GitHub 仓库 ↗</a>
  </div>
</div>

<style>
.repo-card {
  background: #ffffff;
  border: 1px solid #d0d7de;
  border-radius: 8px;
  padding: 24px;
  margin-bottom: 24px;
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.04);
}

.repo-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 12px;
  margin-bottom: 12px;
}

.repo-title {
  display: flex;
  align-items: center;
  gap: 8px;
}

.repo-title a {
  font-size: 1.2em;
  font-weight: 700;
  color: #0969da;
  text-decoration: none;
}

.repo-title a:hover {
  text-decoration: underline;
}

.repo-badge {
  font-size: 0.75em;
  color: #57606a;
  border: 1px solid #d0d7de;
  padding: 2px 7px;
  border-radius: 12px;
  font-weight: 600;
}

.repo-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}

.tag-chip {
  background: #f6f8fa;
  color: #24292f;
  border: 1px solid #d0d7de;
  border-radius: 4px;
  padding: 2px 8px;
  font-size: 0.8em;
  font-weight: 600;
}

.repo-desc {
  font-size: 0.96em;
  line-height: 1.6;
  color: #24292f;
  margin-bottom: 12px;
}

.repo-features ul {
  margin: 8px 0;
  padding-left: 20px;
  line-height: 1.65;
  font-size: 0.92em;
  color: #424a53;
}

.repo-citation {
  background: #f6f8fa;
  border-left: 3px solid #0969da;
  padding: 10px 14px;
  border-radius: 4px;
  font-size: 0.88em;
  line-height: 1.55;
  color: #33383f;
  margin: 14px 0;
}

.repo-footer {
  margin-top: 14px;
  display: flex;
  justify-content: flex-end;
}

.btn-repo {
  display: inline-block;
  background: #0969da;
  color: #ffffff !important;
  font-size: 0.88em;
  font-weight: 600;
  padding: 6px 16px;
  border-radius: 6px;
  text-decoration: none !important;
  transition: background 0.2s ease;
}

.btn-repo:hover {
  background: #0856b5;
}
</style>
