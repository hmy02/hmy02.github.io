---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="text-align: center; margin-bottom: 1.5em;">
  <img src="{{ base_path }}/images/osu-badge.png" alt="The Ohio State University badge" style="height: 90px; margin-right: 20px;">
  <img src="{{ base_path }}/images/bjut-badge.png" alt="Beijing University of Technology badge" style="height: 90px;">
</div>

Education
======

* **The Ohio State University**, Columbus, Ohio, U.S.  
  Ph.D. in Computer Science and Engineering, **expected 2029**  
  Advisor: **John Paparrizos**

* **Beijing University of Technology**, Beijing, China  
  B.S. in Statistics, Minor in Computer Science and Technology, **2024**  
  GPA: **3.93/4.0**, Rank: **2/26**

Research Experience
======

* **Ph.D. Student**, Department of Computer Science and Engineering, The Ohio State University  
  **Aug. 2024 – Present**
  * Working on **time-series anomaly detection**, with a focus on hierarchical, scalable, and interpretable methods
  * Designed and implemented a hierarchical reference-based detection framework for anomalies across multiple temporal resolutions
  * Built end-to-end experimental pipelines and benchmarked methods on large-scale anomaly detection datasets
  * Developed interactive tools for interpreting anomaly scores and understanding model behavior

* **Research Assistant**, School of Artificial Intelligence, Beijing University of Posts and Telecommunications  
  **Mar. 2024 – Aug. 2024**
  * Worked on physics-guided 3D reconstruction and wild inverse rendering with polarization and neural fields
  * Simplified a polarization-based imaging model under strong illumination for robust surface normal recovery
  * Combined classical photometric stereo constraints with neural rendering methods for outdoor inverse rendering
  * Improved reconstruction quality under complex lighting and geometry conditions

* **Undergraduate Researcher**, Institute of Applied Probability and Statistics, Beijing University of Technology  
  **Oct. 2022 – May 2024**
  * Used Gaussian processes as surrogate models for complex computer experiments
  * Proved mathematically that adding a variance term to the loss function can reduce fluctuation while maintaining accuracy
  * Reproduced KO and GOLS calibration methods using data from the MATLAB FEM toolbox
  * Applied GOLS calibration to stochastic computer simulation

* **Undergraduate Researcher**, Tsinghua Statistical Artificial Intelligence & Learning Group  
  **Mar. 2023 – Aug. 2023**
  * Compiled core research papers in continual learning and contributed to an open-source paper list on GitHub
  * Benchmarked HiDe-Prompt against multiple prompt-based continual learning baselines
  * Conducted hyperparameter tuning, recorded experimental results, visualized outputs, and improved code efficiency

Work Experience
======

* **Data Analyst Intern**, JD Research Institute for Consumption and Industrial Development, Beijing, China  
  **Jun. 2022 – Aug. 2022**
  * Analyzed consumer behavior and market trends using web crawling, time-series methods, and machine learning
  * Supported projects related to gifting behavior, fitness equipment markets, and rural home appliance replacement policies

* **Quant Intern**, GuoTai Asset Management Co., Ltd., Active Management Department, Beijing, China  
  **Jun. 2023 – Aug. 2023**
  * Worked on stock trend prediction and quantitative investment using deep learning and multi-task learning
  * Generated alpha factors, conducted backtesting, and analyzed financial text with pretrained language models

Publications
======
<ul>
{% for post in site.publications %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
