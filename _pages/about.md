---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


Hi there, I am Yuan Wu (吴渊). I am currently a second-year Ph.D. student at [PCALab](http://www.patternrecognition.asia/), School of Computer Science and Engineering, Nanjing University of Science and Technology, supervised by [Prof. Jian Yang](https://scholar.google.com.hk/citations?user=6CIDtZQAAAAJ&hl=en). My research interests lie in 3D computer vision, with a particular focus on 3D perception and scene understanding. If you're interested in my work, feel free to reach out with any questions or suggestions! 😊



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='projects/AAAI_STDNet.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

SpatioTemporal Difference Network for Video Depth Super-Resolution (**Oral**)

<a href="https://scholar.google.com/citations?user=VogTuQkAAAAJ&hl=zh-CN&oi=sra" style="text-decoration: none;">Zhengxue Wang</a>, 
<strong>Yuan Wu</strong>, 
<a href="http://implus.github.io/" style="text-decoration: none;">Xiang Li</a>,
<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a>  &#9993;, 
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang</a> &#9993;

<div class="paper-links">
  <a href="https://arxiv.org/pdf/2508.01259?" target="_blank">
    <img src="https://img.shields.io/badge/arXiv-PDF-B31B1B?logo=arxiv&logoColor=white" />
  </a>
  <a href="https://github.com/yanzq95/STDNet" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/yanzq95/STDNet" target="_blank">
    <img src="https://img.shields.io/github/stars/yanzq95/STDNet" />
  </a>
</div>

- We propose STDNet, a novel framework for video depth super-resolution. STDNet introduces spatial and temporal difference mechanisms to mitigate long-tailed effects in video depth super-resolution. This design enables precise depth calibration and motion compensation, leading to state-of-the-art performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='projects/NIPS25_LIAR.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

See through the Dark: Learning Illumination-affined Representations for Nighttime Occupancy Prediction

**Yuan Wu** *, 
<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a> *, 
Yigong Zhang &#9993;, 
<a href="http://implus.github.io/" style="text-decoration: none; ">Xiang Li</a>, 
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang</a> &#9993;

<div class="paper-links">
  <a href="https://arxiv.org/pdf/2505.20641" target="_blank">
    <img src="https://img.shields.io/badge/arXiv-PDF-B31B1B?logo=arxiv&logoColor=white" />
  </a>
  <a href="https://github.com/yanzq95/LIAR" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/yanzq95/LIAR" target="_blank">
    <img src="https://img.shields.io/github/stars/yanzq95/LIAR" />
  </a>
</div>

- Existing vision-based methods perform well on daytime benchmarks but struggle in nighttime scenarios due to limited visibility and challenging lighting conditions. We introduce LIAR, a novel framework that learns illumination-affined representations for nighttime occupacy prediction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2025</div><img src='projects/ICRA25_DHD.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

Deep Height Decoupling for Precise Vision-based 3D Occupancy Prediction

**Yuan Wu** *, 
<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a> * &#9993;, 
<a href="https://scholar.google.com/citations?user=VogTuQkAAAAJ&hl=zh-CN&oi=sra" style="text-decoration: none;">Zhengxue Wang</a>, 
<a href="http://implus.github.io/" style="text-decoration: none;">Xiang Li</a>, 
<a href="https://fpthink.github.io/" style="text-decoration: none;">Le Hui</a>, 
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang</a> &#9993;

<div class="paper-links">
  <a href="https://arxiv.org/pdf/2409.07972?" target="_blank">
    <img src="https://img.shields.io/badge/arXiv-PDF-B31B1B?logo=arxiv&logoColor=white" />
  </a>
  <a href="https://github.com/yanzq95/DHD" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/yanzq95/DHD" target="_blank">
    <img src="https://img.shields.io/github/stars/yanzq95/DHD" />
  </a>
</div>

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- For the first time, we introduce the explicit height prior into the vision-based 3D occupancy predition task. Owing to the novel deep height decoupling and sampling stratagy, our model achieves state-of-the-art performance even with minimal input cost.
</div>
</div>


# 🎖 Honors and Awards
- *2024.06*: Outstanding Graduates of Nanjing University of Science and Technology

  
# 📖 Educations
- *2024.09 - present*: Ph.D. student, School of Computer Science and Engineering, Nanjing University of Science and Technology
- *2020.09 - 2024.06*: B.Eng., School of Intelligent Manufacturing, Nanjing University of Science and Technology

