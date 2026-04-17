---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-entry {
  display: flex;
  align-items: flex-start;
  gap: 14px;
  margin-bottom: 1.2em;
}

.cv-logo {
  width: 54px;
  height: 54px;
  object-fit: contain;
  flex-shrink: 0;
  margin-top: 2px;
}

.cv-content {
  flex: 1;
}

.cv-content h3 {
  margin: 0 0 0.2em 0;
  font-size: 1.05em;
  line-height: 1.3;
}

.cv-meta {
  margin: 0 0 0.35em 0;
  color: #555;
  line-height: 1.4;
}

.cv-content ul {
  margin-top: 0.25em;
  margin-bottom: 0;
}

.cv-content li {
  margin-bottom: 0.2em;
  line-height: 1.5;
}

.cv-publications ul {
  margin-top: 0.4em;
}

.cv-publications li {
  margin-bottom: 0.5em;
  line-height: 1.6;
}
</style>

<div style="text-align: center; margin-bottom: 1.5em;">
  <img src="{{ base_path }}/images/osu-logo.png" alt="The Ohio State University logo" style="height: 85px; margin-right: 18px;">
  <img src="{{ base_path }}/images/bjut-logo.png" alt="Beijing University of Technology logo" style="height: 85px;">
</div>

Education
======

<div class="cv-entry">
  <img class="cv-logo" src="{{ base_path }}/images/osu-logo.png" alt="OSU logo">
  <div class="cv-content">
    <h3>The Ohio State University</h3>
    <p class="cv-meta">Columbus, Ohio, U.S. | Ph.D. in Computer Science and Engineering | Expected 2029</p>
    <ul>
      <li>Advisor: John Paparrizos</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <img class="cv-logo" src="{{ base_path }}/images/bjut-logo.png" alt="BJUT logo">
  <div class="cv-content">
    <h3>Beijing University of Technology</h3>
    <p class="cv-meta">Beijing, China | B.S. in Statistics, Minor in Computer Science and Technology | 2024</p>
    <ul>
      <li>GPA: 3.93/4.0, Rank: 2/26</li>
    </ul>
  </div>
</div>

Research Experience
======

<div class="cv-entry">
  <img class="cv-logo" src="{{ base_path }}/images/osu-logo.png" alt="OSU logo">
  <div class="cv-content">
    <h3>Ph.D. Student, Department of Computer Science and Engineering, The Ohio State University</h3>
    <p class="cv-meta">Aug. 2024 – Present</p>
    <ul>
      <li>Working on time-series anomaly detection, with a focus on hierarchical, scalable, and interpretable methods.</li>
      <li>Designed and implemented a hierarchical reference-based detection framework for anomalies across multiple temporal resolutions.</li>
      <li>Built end-to-end experimental pipelines and benchmarked methods on large-scale anomaly detection datasets.</li>
      <li>Developed interactive tools for interpreting anomaly scores and understanding model behavior.</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <img class="cv-logo" src="{{ base_path }}/images/bupt-logo.png" alt="BUPT logo">
  <div class="cv-content">
    <h3>Research Assistant, School of Artificial Intelligence, Beijing University of Posts and Telecommunications</h3>
    <p class="cv-meta">Mar. 2024 – Aug. 2024</p>
    <ul>
      <li>Worked on physics-guided 3D reconstruction and wild inverse rendering with polarization and neural fields.</li>
      <li>Simplified a polarization-based imaging model under strong illumination for robust surface normal recovery.</li>
      <li>Combined classical photometric stereo constraints with neural rendering methods for outdoor inverse rendering.</li>
      <li>Improved reconstruction quality under complex lighting and geometry conditions.</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <img class="cv-logo" src="{{ base_path }}/images/bjut-logo.png" alt="BJUT logo">
  <div class="cv-content">
    <h3>Undergraduate Researcher, Institute of Applied Probability and Statistics, Beijing University of Technology</h3>
    <p class="cv-meta">Oct. 2022 – May 2024</p>
    <ul>
      <li>Used Gaussian processes as surrogate models for complex computer experiments.</li>
      <li>Proved mathematically that adding a variance term to the loss function can reduce fluctuation while maintaining accuracy.</li>
      <li>Reproduced KO and GOLS calibration methods using data from the MATLAB FEM toolbox.</li>
      <li>Applied GOLS calibration to stochastic computer simulation.</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <img class="cv-logo" src="{{ base_path }}/images/tsinghua-logo.png" alt="Tsinghua logo">
  <div class="cv-content">
    <h3>Undergraduate Researcher, Tsinghua Statistical Artificial Intelligence &amp; Learning Group</h3>
    <p class="cv-meta">Mar. 2023 – Aug. 2023</p>
    <ul>
      <li>Compiled core research papers in continual learning and contributed to an open-source paper list on GitHub.</li>
      <li>Benchmarked HiDe-Prompt against multiple prompt-based continual learning baselines.</li>
      <li>Conducted hyperparameter tuning, recorded experimental results, visualized outputs, and improved code efficiency.</li>
    </ul>
  </div>
</div>

Work Experience
======

<div class="cv-entry">
  <img class="cv-logo" src="{{ base_path }}/images/jd-logo.png" alt="JD logo">
  <div class="cv-content">
    <h3>Data Analyst Intern, JD Research Institute for Consumption and Industrial Development</h3>
    <p class="cv-meta">Beijing, China | Jun. 2022 – Aug. 2022</p>
    <ul>
      <li>Analyzed consumer behavior and market trends using web crawling, time-series methods, and machine learning.</li>
      <li>Supported projects related to gifting behavior, fitness equipment markets, and rural home appliance replacement policies.</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <img class="cv-logo" src="{{ base_path }}/images/guotai-logo.png" alt="GuoTai logo">
  <div class="cv-content">
    <h3>Quant Intern, GuoTai Asset Management Co., Ltd., Active Management Department</h3>
    <p class="cv-meta">Beijing, China | Jun. 2023 – Aug. 2023</p>
    <ul>
      <li>Worked on stock trend prediction and quantitative investment using deep learning and multi-task learning.</li>
      <li>Generated alpha factors, conducted backtesting, and analyzed financial text with pretrained language models.</li>
    </ul>
  </div>
</div>

Publications
======

<div class="cv-publications">
  <ul>
  {% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
</div>
