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

I am currently a first-year master student at the School of Computer Science, Shanghai Jiao Tong University [(上海交通大学计算机学院)](https://www.cs.sjtu.edu.cn). I have been a member of [ReThinkLab](https://github.com/Thinklab-SJTU) since 2022 and supervised by [Prof. Junchi Yan (严骏驰)](https://thinklab.sjtu.edu.cn) who leads the lab. I obtained my Bachelor of Engineering Degree from the Department of Computer Science and Engineering (IEEE Honors Class) of SJTU in 2024. My recent research interests include neural combinatorial optimization, generative models, and broader fields of machine learning on graphs.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 📖 Educations
- *2024.09 - now*, School of Computer Science, SJTU (pursuing the Master's Degree)
- *2020.09 - 2024.06*, Department of Computer Science and Engineering (IEEE Honors Class), SJTU (B.E. Degree obtained)
    - Overall: ![](https://img.shields.io/badge/GPA-3.92-blue) ![](https://img.shields.io/badge/Grade-90.82-blue) ![](https://img.shields.io/badge/Ranking-top_10%25-blue)
    - Courses: ![](https://img.shields.io/badge/Above_A--_-53/61-orange)  ![](https://img.shields.io/badge/Above_A-38/61-orange)
    - Language: ![](https://img.shields.io/badge/IELTS-7.5-green) ![](https://img.shields.io/badge/CET--6-646-green)
      ![](https://img.shields.io/badge/CET--4-670-green)
  
  <!--  - **GPA**: **3.92/4.3** (or **90.82/100**), **Ranking top 10%**
    - **Courses**: **53/61** above **A-** and **38/61** above **A**
    - **IELTS**: **7.5**, **CET-6**: **646**, **CET-4**: **670** -->

# 🎖 Honors and Awards
- *2024.06* Outstanding Graduate of Shanghai Jiao Tong University (**top 10%** in SJTU)
- *2021-2023* (Annual) Academic Excellence Scholarship (**top 10%** in Dept.)
- *2022.11* Huatai Securities Technology Scholarship (**40** awarded in SJTU)
- *2021.11* SMC-Takada Scholarship (**top 5%** in Dept.) 
- *2021.09* Merit Student of Shanghai Jiao Tong University (**top 8%** in SJTU) 
- *2021.05* Merit League Member of Shanghai Jiao Tong University (**top 8%** in SJTU) 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='https://wzever.github.io/_pages/images/coexpander.png' alt="sym" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(CCF-A) [**COExpander: Adaptive Solution Expansion for Combinatorial Optimization**](https://www.researchgate.net/publication/391363643_COExpander_Adaptive_Solution_Expansion_for_Combinatorial_Optimization) [[PDF](https://www.researchgate.net/profile/Jiale-Ma-9/publication/391363643_COExpander_Adaptive_Solution_Expansion_for_Combinatorial_Optimization/links/6813b80e60241d5140214026/COExpander-Adaptive-Solution-Expansion-for-Combinatorial-Optimization.pdf)][[Code (coming soon) ![](https://img.shields.io/github/stars/Thinklab-SJTU/COExpander?style=social)](https://github.com/Thinklab-SJTU/COExpander)]

Jiale Ma\*, **Wenzheng Pan***, Yang Li, Junchi Yan


- We propose a novel paradigm Adaptive Expansion (AE) and the COExpander solver for NCO solving. It bridges the global prediction (GP) and local construction (LC) paradigms via a partial state prompted heatmap generator with adaptive step sizes for decision-making.
- We re-wrap 5 non-learning baseline solvers and re-cononicalize 29 standard datasets to provide a just and generalizable benchmark for 6 commonly studied COPs.
- Compared with previous neural SOTA, COExpander has reduced the average optimality drop on 6 COPs from 3.81% to 0.66%, with a speedup of 4.0x.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='https://wzever.github.io/_pages/images/unico.png' alt="sym" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(CAAI/Tsinghua-A) [**UniCO: On Unified Combinatorial Optimization via Problem Reduction to Matrix-Encoded General TSP**](https://openreview.net/forum?id=yEwakMNIex) [[PDF](https://openreview.net/pdf?id=yEwakMNIex)] [[Code ![](https://img.shields.io/github/stars/Thinklab-SJTU/UniCO?style=social)](https://github.com/Thinklab-SJTU/UniCO)]

**Wenzheng Pan**\*, Hao Xiong\*, Jiale Ma, Wentao Zhao, Yang Li, Junchi Yan

- We propose the UniCO framework to unify a set of CO problems by reducing them into the general TSP form for effective and simultaneous training.
- This work focuses on the challenging TSPs that are non-metric, asymmetric or discrete distances without explicit node coordinates.
- Two neural TSP solvers are devised w/ and w/o supervision to conquer such matrix-formulated input, respectively: 1) MatPOENet, an RL-based sequential model with pseudo one-hot embedding (POE) scheme and 2) MatDIFFNet, the a Diffusion-based generative model with the mix-noised reference mapping scheme.
- Pioneering experiments have been conducted on ATSP, 2DTSP, HCP- and SAT-distributed general matrix-encoded TSPs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='https://wzever.github.io/_pages/images/UnifyML4TSP.png' alt="sym" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(CAAI/Tsinghua-A) [**Unify ML4TSP: Drawing Methodological Principles for TSP and Beyond from Streamlined Design Space of Learning and Search**](https://openreview.net/forum?id=grU1VKEOLi) [[PDF](https://openreview.net/pdf?id=yEwakMNIex)][[Code ![](https://img.shields.io/github/stars/Thinklab-SJTU/ML4TSPBench?style=social)](https://github.com/Thinklab-SJTU/ML4TSPBench)]

Yang Li, Jiale Ma, **Wenzheng Pan**, Runzhong Wang, Haoyu Geng, Nianzu Yang, Junchi Yan

- We present ML4TSPBench, which advances a unified modular streamline incorporating existing technologies in both learning and search for transparent ablation.
- We demonstrate the desirability of principles like joint probability estimation, symmetry solution representation, and online optimization for learning-based design.
- The strategic decoupling and organic recompositions yield a factory of new and stronger TSP solvers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JMLR </div><img src='https://wzever.github.io/_pages/images/pygmtools.png' alt="sym" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(CCF-A) [**Pygmtools: A Python Graph Matching Toolkit**](https://jmlr.org/papers/v25/23-0572.html) [[PDF](https://jmlr.org/papers/volume25/23-0572/23-0572.pdf)][[Code ![](https://img.shields.io/github/stars/Thinklab-SJTU/pygmtools?style=social)](https://github.com/Thinklab-SJTU/pygmtools)]

Runzhong Wang, Ziao Guo, **Wenzheng Pan**, Jiale Ma, Yikai Zhang, Nan Yang, Qi Liu, Longxuan Wei, Hanxue Zhang, Chang Liu, Zetian Jiang, Xiaokang Yang, Junchi Yan


- Pygmtools is released as a Python graph matching toolkit that implements a comprehensive collection of two-graph matching and multi-graph matching solvers.
- Our implementation supports numerical backends including Numpy, PyTorch, Jittor, Paddle, runs on Windows, MacOS and Linux, with friendly documentations and beginner’s guide,
</div>
</div>

# ⚙️ Projects & Open-source Contributions

- [Awesome-ML4CO ![](https://img.shields.io/github/stars/Thinklab-SJTU/awesome-ml4co?style=social)](https://github.com/Thinklab-SJTU/awesome-ml4co), a curated collection of literature in the ML4CO field, organized to support researchers in accessing both foundational and recent developments. This repository is maintained with a joint effort by members in SJTU-Thinklab as well as contributors from the community.

- [ML4CO-Kit ![](https://img.shields.io/github/stars/Thinklab-SJTU/ML4CO-Kit?style=social)](https://github.com/Thinklab-SJTU/ML4CO-Kit), a general-purpose toolkit that provides implementations of common algorithms used in ML4CO, along with basic training frameworks, traditional solvers and data generation tools. It aims to simplify the implementation of key techniques and offer a solid base for developing machine learning models for COPs.

- [ML4TSPBench ![](https://img.shields.io/github/stars/Thinklab-SJTU/ML4TSPBench?style=social)](https://github.com/Thinklab-SJTU/ML4TSPBench), a benchmark focusing on exploring the TSP for representativeness. It offers a deep dive into various methodology designs, enabling comparisons and the development of specialized algorithms.

- [ML4CO-Bench-101 ![](https://img.shields.io/github/stars/Thinklab-SJTU/ML4CO-Bench-101?style=social)](https://github.com/Thinklab-SJTU/ML4CO-Bench-101), a benchmark that categorizes neural combinatorial optimization (NCO) solvers by solving paradigms, model designs, and learning strategies. It evaluates applicability and generalization of different NCO approaches across a broad range of combinatorial optimization problems to uncover universal insights that can be transferred across various domains of ML4CO.

- [Pygmtools ![](https://img.shields.io/github/stars/Thinklab-SJTU/pygmtools?style=social)](https://github.com/Thinklab-SJTU/pygmtools), a Python graph matching toolkit that implements a comprehensive collection of two-graph matching and multi-graph matching solvers, covering both learning-free solvers as well as learning-based neural graph matching solvers. Our implementation supports numerical backends including Numpy, PyTorch, Jittor, Paddle, runs on Windows, MacOS and Linux, and is friendly to install and configure.

# 🔥 News
- *2025.05*: 🎉 One paper is accepted by **ICML 2025**
- *2025.01*: 🎉 Two papers are accepted by **ICLR 2025**
- *2024.10*: 🔍 I served as a **reviewer** at **ICLR 2025**
- *2024.06*: 🏅 I was awarded the **Outstanding Graduate** of SJTU
- *2024.01*: 🎉 One paper is accepted by **JMLR**

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
