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


Hi, I'm Zhengxue Wang (王正学). I'm currently a Ph.D. student at PCALab, in the School of Computer Science and Engineering at Nanjing University of Science and Technology, supervised by <a href="https://scholar.google.com.hk/citations?user=6CIDtZQAAAAJ&hl=en" style="text-decoration: none;">Prof. Jian Yang</a> and co-supervised by <a href="http://yanzq95.github.io/" style="text-decoration: none;">Dr. Zhiqiang Yan</a>. My research interests lie in image restoration and depth perception, including depth super-resolution, completion, and estimation. If you're interested in my work or have any questions or suggestions, feel free to reach out! 😊

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='projects/AAAI_STDNet.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

SpatioTemporal Difference Network for Video Depth Super-Resolution (**Oral**)

<strong>Zhengxue Wang</strong>, 
<a href="https://rayn-wu.github.io/" style="text-decoration: none;">Yuan Wu</a>,
<a href="http://implus.github.io/" style="text-decoration: none;">Xiang Li</a>,
<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a>  &#9993;, 
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang</a> &#9993;

{% include paper_links.html
  arxiv="https://arxiv.org/pdf/2508.01259?"
  github="yanzq95/STDNet"
%}

- We propose STDNet, a novel framework for video depth super-resolution. STDNet introduces spatial and temporal difference mechanisms to mitigate long-tailed effects in video depth super-resolution. This design enables precise depth calibration and motion compensation, leading to state-of-the-art performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='projects/NIPS25_data_case.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

Event-Driven Dynamic Scene Depth Completion

<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a>, 
<a href="https://gogojjh.github.io/" style="text-decoration: none;">Jianhao Jiao</a>,
<strong>Zhengxue Wang</strong>, 
<a href="https://www.comp.nus.edu.sg/~leegh/" style="text-decoration: none;">Gim Hee Lee</a>

{% include paper_links.html
  arxiv="https://arxiv.org/abs/2505.13279"
%}
- We introduce EventDC, the first depth completion framework that tackles the challenges of dynamic scenes by harnessing the unique strengths of event data. To mitigate the adverse effects of fast ego-motion and object motion, EventDC incorporates two event-driven modules. Furthermore, to support research in this area, we construct the first benchmark for event-based depth completion comprising one real-world and two synthetic datasets. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='projects/DuCos.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

DuCos: Duality Constrained Depth Super-Resolution via Foundation Model

<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a>, 
<strong>Zhengxue Wang</strong>, 
<a href="https://www.haoyed.com/" style="text-decoration: none;">Haoye Dong</a>, 
<a href="https://sites.google.com/view/junlineu/" style="text-decoration: none;">Jun Li</a>, 
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang</a>,
<a href="https://www.comp.nus.edu.sg/~leegh/" style="text-decoration: none;">Gim Hee Lee</a>
{% include paper_links.html
  arxiv="https://openaccess.thecvf.com/content/ICCV2025/html/Yan_DuCos_Duality_Constrained_Depth_Super-Resolution_via_Foundation_Model_ICCV_2025_paper.html"
  github="https://github.com/yanzq95/DuCos"
%}
We introduce DuCos, a novel depth super-resolution framework grounded in Lagrangian duality theory, 
			  offering a flexible integration of multiple constraints and reconstruction objectives to enhance accuracy and robustness. 
			  Our DuCos is the first to significantly improve generalization across diverse scenarios with foundation models as prompts. 
			  Crucially, these prompts are seamlessly embedded into the Lagrangian constraint term, forming a synergistic and principled framework.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='projects/DORNet.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

DORNet: A Degradation Oriented and Regularized Network for Blind Depth Super-Resolution (**Oral**)

<strong>Zhengxue Wang</strong> *, 
<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a> * &#9993, 
<a href="https://jspan.github.io/" style="text-decoration: none;">Jinshan Pan</a>, 
<a href="https://guangweigao.github.io/" style="text-decoration: none;">Guangwei Gao</a>,
<a href="https://cszn.github.io/" style="text-decoration: none;">Kai Zhang</a>,
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang</a>  &#9993
{% include paper_links.html
  arxiv="https://openaccess.thecvf.com/content/CVPR2025/html/Wang_DORNet_A_Degradation_Oriented_and_Regularized_Network_for_Blind_Depth_CVPR_2025_paper.html"
  github="https://github.com/yanzq95/DORNet"
%}
For the first time, we introduce a Degradation Oriented and Regularized Network (DORNet) designed for real-world depth super-resolution, addressing the challenges posed by unconventional and unknown degradations. 
				  The core concept involves estimating implicit degradation representations to achieve effective RGB-D fusion. This degradation learning process is self-supervised.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='projects/SigNet.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

Completion as Enhancement: A Degradation-Aware Selective Image Guided Network for Depth Completion

<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a>, 
<strong>Zhengxue Wang</strong>, 
<a href="https://scholar.google.com/citations?user=ORn7aZcAAAAJ&hl=zh-CN&oi=sra" style="text-decoration: none;">Kun Wang</a>, 
<a href="https://sites.google.com/view/junlineu/" style="text-decoration: none;">Jun Li </a>, &#9993
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang </a> &#9993
{% include paper_links.html
  arxiv="https://openaccess.thecvf.com/content/CVPR2025/html/Yan_Completion_as_Enhancement_A_Degradation-Aware_Selective_Image_Guided_Network_for_CVPR_2025_paper.html"
%}
We propose a novel degradation-aware framework SigNet that transforms depth completion into depth enhancement for the first time. 
			  SigNet eliminates the mismatch and ambiguity caused by direct convolution over irregularly sampled sparse data. 
			  Meanwhile, it builds a self-supervised degradation bridge between coarse depth and targeted dense depth for effective RGB-D fusion.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2025</div><img src='projects/ICRA25_DHD.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

Deep Height Decoupling for Precise Vision-based 3D Occupancy Prediction

<a href="https://rayn-wu.github.io/" style="text-decoration: none;">Yuan Wu *</a>,
<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a> * &#9993;, 
<strong>Zhengxue Wang</strong>, 
<a href="http://implus.github.io/" style="text-decoration: none;">Xiang Li</a>, 
<a href="https://fpthink.github.io/" style="text-decoration: none;">Le Hui</a>, 
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang</a> &#9993;

{% include paper_links.html
  arxiv="https://arxiv.org/pdf/2409.07972?"
  github="yanzq95/DHD"
%}
- For the first time, we introduce the explicit height prior into the vision-based 3D occupancy predition task. Owing to the novel deep height decoupling and sampling stratagy, our model achieves state-of-the-art performance even with minimal input cost.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='projects/SGNet_performance.jpg' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

SGNet: Structure Guided Network via Gradient-Frequency Awareness for Depth Map Super-Resolution

<strong>Zhengxue Wang</strong>, 
<a href="http://yanzq95.github.io/" style="text-decoration: none;">Zhiqiang Yan</a> &#9993;, 
<a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" style="text-decoration: none;">Jian Yang</a> &#9993;

{% include paper_links.html
  arxiv="https://arxiv.org/pdf/2312.05799v3.pdf"
  github="https://github.com/yanzq95/SGNet"
%}
SGNet introduces a novel perspective that exploits the gradient and frequency domains for the structure enhancement of DSR task,
				  surpassing the five state-of-the-art methods by 16% (RGB-D-D), 24% (Middlebury), 21% (Lu) and 15% (NYU-v2) in average.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2022</div><img src='projects/LBNet.png' alt="sym" style="width: auto; height: auto;"></div></div>
<div class='paper-box-text' markdown="1">

Lightweight Bimodal Network for Single-Image Super-Resolution via Symmetric CNN and Recursive Transformer (**Short Oral**)

<a href="https://guangweigao.github.io/" style="text-decoration: none;">Guangwei Gao *</a>,
<strong>Zhengxue Wang</strong> *, 
<a href="https://junchenglee.com" style="text-decoration: none;">Juncheng Li</a>, 
<a href="https://github.com/24wenjie-li" style="text-decoration: none;">Wenjie Li</a>, 
<a style="text-decoration: none;">Yi Yu</a>, 
<a style="text-decoration: none;">Tieyong Zeng</a>

{% include paper_links.html
  arxiv="https://arxiv.org/abs/2204.13286"
  github="https://github.com/wzx0826/LBNet"
%}
LBNet introduces a lightweight bimodal network that integrates a CNN for local feature extraction with a recursive Transformer for global dependency modeling. It reduces computational and memory costs while more effectively enhancing texture details in single-image super-resolution.
</div>
</div>



# ✒️ Academic Service
- Conference reviewer: CVPR, ICCV, ECCV, AAAI, IJCAI, BMVC
- Journal reviewer: TIP, TNNLS, PR
  
# 📖 Educations
- *2023.03 - present*: Ph.D. student, School of Computer Science and Engineering, Nanjing University of Science and Technology
- *2019.09 - 2022.05*: M.S. degree, College of Automation and College of Artificial Intelligence from the Nanjing University of Posts and Telecommunications

