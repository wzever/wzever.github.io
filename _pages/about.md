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

# 👨🏻‍💻 About Me
I am currently a second-year master student with the [School of Computer Science, **Shanghai Jiao Tong University (上海交通大学计算机学院)**](https://www.cs.sjtu.edu.cn). I have been a member of [**ReThinkLab**](https://github.com/Thinklab-SJTU) since 2022 and supervised by [**Prof. Junchi Yan (严骏驰)**](https://thinklab.sjtu.edu.cn) who leads the lab. I obtained my Bachelor of Engineering Degree from the Department of Computer Science and Engineering (**IEEE Honors Class**, subject to a provincial top 0.01% ranking in the College Entrance Exam) of SJTU in 2024. Recently, I have been admitted to [**Shanghai Innovation Institute (上海创智学院)**](https://www.sii.edu.cn), where I'm planning to start my Ph.D. program in 2027.

My research interests include learning to solve complex discrete optimization problems (esp. **neural combinatorial optimization**), generative models, machine learning on graphs, and broader fields towards large decision-making models and scientific intelligence. **More recently, I've also started to explore the intersection of large language models (LLMs) as well as agentic systems with my major research directions.**

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

## 📖 Educations
---
<div class="education-card">
  <div class="education-title"><span class="education-period">2024.09 - now</span><strong>School of Computer Science, SJTU</strong><span>(Master's Program)</span></div>
  <div class="education-metrics">
    <div class="education-detail"><strong>Overall</strong><span>GPA <b>3.91</b></span><span>Ranking <b>top 8%</b> (17/223)</span></div>
    <div class="education-detail"><strong>Courses</strong><span>Above A- <b>10/10</b></span><span>Above A <b>7/10</b></span></div>
  </div>
</div>
<div class="education-card">
  <div class="education-title"><span class="education-period">2020.09 - 2024.06</span><strong>Department of Computer Science and Engineering (IEEE Honors Class), SJTU</strong><span>(B.E. Degree)</span></div>
  <div class="education-metrics">
    <div class="education-detail"><strong>Overall</strong><span>GPA <b>3.92</b></span><span>Grade <b>90.82</b></span><span>Ranking <b>top 10%</b></span></div>
    <div class="education-detail"><strong>Courses</strong><span>Above A- <b>53/61</b></span><span>Above A <b>38/61</b></span></div>
    <div class="education-detail"><strong>Language</strong><span>IELTS <b>7.5</b></span><span>CET-6 <b>646</b></span><span>CET-4 <b>670</b></span></div>
  </div>
</div>

<span class='anchor' id='publications'></span>
{% include_relative pubs.md %}

<span class='anchor' id='-open-source-projects'></span>
## ⚙️ Open Source Projects
---
<div class="project-card">
<p class="project-card-title"><a href="https://github.com/Thinklab-SJTU/awesome-ml4co"><strong>Awesome-ML4CO</strong> <img class="github-stars" src="https://img.shields.io/github/stars/Thinklab-SJTU/awesome-ml4co?style=social" alt="GitHub stars"></a></p>
<p class="project-card-description">A curated collection of literature in the ML4CO field, organized to support researchers in accessing both foundational and recent developments. This repository is maintained with a joint effort by members in SJTU-Thinklab as well as contributors from the community.</p>
</div>

<div class="project-card">
<p class="project-card-title"><a href="https://github.com/Thinklab-SJTU/ML4CO-Kit"><strong>ML4CO-Kit</strong> <img class="github-stars" src="https://img.shields.io/github/stars/Thinklab-SJTU/ML4CO-Kit?style=social" alt="GitHub stars"></a></p>
<p class="project-card-description">A general-purpose toolkit that provides implementations of common algorithms used in ML4CO, along with basic training frameworks, traditional solvers and data generation tools. It aims to simplify the implementation of key techniques and offer a solid base for developing machine learning models for COPs.</p>
</div>

<div class="project-card">
<p class="project-card-title"><a href="https://github.com/Thinklab-SJTU/ML4TSPBench"><strong>ML4TSPBench</strong> <img class="github-stars" src="https://img.shields.io/github/stars/Thinklab-SJTU/ML4TSPBench?style=social" alt="GitHub stars"></a></p>
<p class="project-card-description">A benchmark focusing on exploring the TSP for representativeness. It offers a deep dive into various methodology designs, enabling comparisons and the development of specialized algorithms.</p>
</div>

<div class="project-card">
<p class="project-card-title"><a href="https://github.com/Thinklab-SJTU/ML4CO-Bench-101"><strong>ML4CO-Bench-101</strong> <img class="github-stars" src="https://img.shields.io/github/stars/Thinklab-SJTU/ML4CO-Bench-101?style=social" alt="GitHub stars"></a></p>
<p class="project-card-description">A benchmark that categorizes neural combinatorial optimization (NCO) solvers by solving paradigms, model designs, and learning strategies. It evaluates applicability and generalization of different NCO approaches across a broad range of combinatorial optimization problems to uncover universal insights that can be transferred across various domains of ML4CO.</p>
</div>

<div class="project-card">
<p class="project-card-title"><a href="https://github.com/Thinklab-SJTU/pygmtools"><strong>Pygmtools</strong> <img class="github-stars" src="https://img.shields.io/github/stars/Thinklab-SJTU/pygmtools?style=social" alt="GitHub stars"></a></p>
<p class="project-card-description">A Python graph matching toolkit that implements a comprehensive collection of two-graph matching and multi-graph matching solvers, covering both learning-free solvers as well as learning-based neural graph matching solvers. Our implementation supports numerical backends including Numpy, PyTorch, Jittor, Paddle, runs on Windows, MacOS and Linux, and is friendly to install and configure.</p>
</div>

## 🎖 Honors and Awards
---
- *2025.11* First-class Academic Scholarship of SJTU (研究生学业一等奖学金 **top 10%** in Dept.)
- *2025.10* National Scholarship for Graduate Student (研究生国家奖学金 **top 2%** nationwide)
- *2025.09* Merit Student of Shanghai Jiao Tong University (上海交通大学三好学生 **top 8%** in SJTU) 
- *2024.06* Outstanding Graduate of Shanghai Jiao Tong University (上海交通大学优秀毕业生 **top 10%** in SJTU)
- *2021-2023* (Annual) Academic Excellence Scholarship (上海交通大学优秀奖学金 **top 10%** in Dept.)
- *2022.11* Huatai Securities Technology Scholarship (华泰证券科技奖学金 **40** awarded in SJTU)
- *2021.11* SMC-Takada Scholarship (SMC高田奖学金 **top 5%** in Dept.) 
- *2021.09* Merit Student of Shanghai Jiao Tong University (上海交通大学三好学生 **top 8%** in SJTU) 
- *2021.05* Merit League Member of Shanghai Jiao Tong University (上海交通大学优秀团员 **top 8%** in SJTU)

<span class='anchor' id='academic-services'></span>
## 🔍 Academic Services
---
- **Reviewer**: **ICML'26 (Gold Reviewer)**, **NeurIPS'25-26**, **ICLR'25-27**, **AAAI'27**, **AAMAS'26**.

## 🔥 News
---
- *2026.06*: 🎉 I received a conditional offer from **SII** as a Ph.D. student for 2027 (**national admission rate <5%**)!
- *2026.05*: 🎉 Two papers were accepted by **ICML 2026** and I was awarded the **Gold Reviewer**!
- *2025.10*: 🏅 I was awarded the **National Scholarship for Graduate Student**!
- *2025.09*: 🎉 One paper was accepted by **NeurIPS 2025**!
- *2025.05*: 🎉 One paper was accepted by **ICML 2025**!
- *2025.01*: 🎉 Two papers were accepted by **ICLR 2025**!
- *2024.06*: 🏅 I was awarded the **Outstanding Graduate** of SJTU!
- *2024.01*: 🎉 One paper was accepted by **JMLR**!

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
