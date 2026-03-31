---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span id="news"></span>

News
======
- **[2025.10]** I started my internship as an Algorithm Intern at Neusoft Corporation.
- **[2025.09]** I have been admitted to the University of Science and Technology of China (USTC) as a PhD student (recommended waiver)! 

<span id="about-me"></span>

About Me
======
I am a senior undergraduate student at the School of Information Science and Technology, Dalian Maritime University (211), majoring in Computer Science and Technology with a GPA of 3.91/5 (average score: 89.1). I have been admitted to the University of Science and Technology of China (USTC) as a PhD student (recommended waiver) for the class of 2026.

I am very fortunate to be advised by Assoc. Prof. Qian Ma from the School of Information Science and Technology, DMU, and I am now continuing my research at USTC.

My research interests include **Computer Vision**, **AI for Science**, and **Data Mining**, with a focus on multivariate time series imputation and intelligent agent system development. Currently, I am exploring how deep learning can be applied to scientific discovery (AI for Science).

Education Experience
======
- **Ph.D. in Computer Science**, University of Science and Technology of China (USTC), 2026.09–Present
- **B.S. in Computer Science and Technology**, Dalian Maritime University (211), 2022.09–2026.06  

Skills
======
- Hobbies: Music, Basketball

<span id="publications"></span>

Publications
======
{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<span id="experience"></span>

Research & Internship Experience
======
### Research Projects
- **AttnWGAIN: Attention-Based Imputation Network** (2023.03–2025.07)  
   - Role: First Author  
   - Core Contributions: Proposed the AttnWGAIN model (WGAN+Transformer structure) and joint training task MIT+ORT for IoT multivariate time series missing data imputation; Achieved 5%–26% MAE reduction, 3%–33% RMSE reduction, and over 15% MRE reduction on four real-world datasets; Models trained on imputed data performed excellently in downstream classification tasks.  
   - Outcomes: IEEE Transactions on Consumer Electronics(IF 10.9) accepted; One invention patent under substantive examination.

- **TimeMultiformer: Attention-Based Collaborative Feature Learning** (2025.01–2025.06)  
   - Role: First Author  
   - Core Contributions: Developed TimeMultiformer for multivariate time series imputation; Introduced time-lag matrix and diagonal masked multi-head attention; Combined Transformer and iTransformer to capture spatio-temporal dependencies; Reduced MAE by 2%–16%, RMSE by 10%–26%, MRE by over 10% on four real datasets; Improved ROC-AUC, PR-AUC, and F1 scores in downstream tasks compared to SOTA models.  
   - Outcomes: WAIM2025 (CCF-C) accepted.

- **STIMim: Missing Structure-Aware Time-Series Imputation** (2024.10–Present)  
   - Role: Second Author  
   - Core Contributions: Proposed STIMim framework for structured missing problems in multivariate time series; Integrated VMPM mask distribution alignment mechanism to alleviate training-test distribution shift; Combined iTransformer and Mamba for cross-variable correlation modeling and long-range dependency recovery; Achieved 25.5%/25.0%/26.0% improvement in MAE/RMSE/MRE under random missing conditions, and 15.5%/6.5%/15.2% under structured missing conditions on three real datasets.  
   - Outcomes: Paper under submission to ICDE (CCF-A).

### Internship Experience
- **Algorithm Intern**, Neusoft Corporation (Commercial Software Division) (2025.10–2026.01)  
  - Participated in the R&D of an Agent Loop-based automated mobile phone recovery system, responsible for the visual perception and information retrieval subsystem.  
  - Designed and implemented an Adaptive RAG dynamic retrieval module, improving planning stability and decision accuracy of complex recovery processes by over 20%.  
  - Built a high-precision screen element recognition pipeline using YOLOv8 + EasyOCR; Encapsulated visual capabilities into reusable "Vision Tools" for Agent Loop calling.  
  - Constructed abnormal recovery and failure retry logic, realizing Agent’s multi-round closed-loop "observation-reasoning-execution" process.

<span id="honors"></span>

Honors & Awards
======
- 2025.07 National College Students Information Security and Countermeasure Technology Competition, National First Prize
- 2025.05 Energy Economics Competition, National Special Prize, Provincial First Prize
- 2024.11 National College Students Digital Media Technology Competition, National Second Prize, Provincial First Prize
- 2024.11 Global Campus Artificial Intelligence Algorithm Competition, National Second Prize, Provincial Second Prize
- 2024.08 RoboCon Robot Developer Competition, National Second Prize, Provincial Second Prize
- 2024.06 China Robot and Artificial Intelligence Competition, Provincial Second Prize
- 2024.06 ICPC Silk Road China Invitational Competition, Silver Medal
- 2024.04 Blue Bridge Cup Competition, Provincial Second Prize

<span id="blog"></span>

Blog
======
{% for post in site.posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}
<a href="/year-archive/">See all posts</a>
