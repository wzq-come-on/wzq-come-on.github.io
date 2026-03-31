---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span id="about-me"></span>

👋 About Me
======
I am a senior undergraduate student at the School of Information Science and Technology, Dalian Maritime University (211), majoring in Computer Science and Technology with a GPA of 3.91/5 (average score: 89.1). I have been admitted to the University of Science and Technology of China (USTC) as a PhD student (recommended waiver) for the class of 2026.

I am very fortunate to be advised by Assoc. Prof. Qian Ma from the School of Information Science and Technology, DMU, and I am now continuing my research at USTC.

My research interests include **Computer Vision**, **AI for Science**, and **Data Mining**, with a focus on multivariate time series imputation and intelligent agent system development. Currently, I am exploring how deep learning can be applied to scientific discovery (AI for Science).

<span id="news"></span>

🔥 News
======
- **2025.10** 🏢 I started my internship as an Algorithm Intern at Neusoft Corporation.
- **2025.09** 🎉 I have been admitted to the University of Science and Technology of China (USTC) as a PhD student (recommended waiver)! 

🎓 Education Experience
======
- **Ph.D. in Computer Science**, University of Science and Technology of China (USTC), 2026.09–Present
- **B.S. in Computer Science and Technology**, Dalian Maritime University (211), 2022.09–2026.06  

🛠️ Skills
======
- Hobbies: Music, Basketball

<span id="publications"></span>

⭐ Selected Works
======
* denotes co-first author, † denotes corresponding author.

### Time Series Imputation
{% assign ts_imputation = site.publications | where: "category", "Time Series Imputation" | sort: "date" | reverse %}
{% for post in ts_imputation %}
  <div class="list__item" style="margin-bottom: 30px;">
    <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
      <!-- Title -->
      <h3 class="archive__item-title" itemprop="headline" style="margin-bottom: 5px;">
        <a href="{{ base_path }}{{ post.url }}" rel="permalink">{{ post.title }}</a>
      </h3>
      
      <!-- Authors -->
      <p style="margin: 0 0 5px 0; font-size: 1.0em;">
        {% if post.authors %}{{ post.authors }}{% endif %}
      </p>

      <!-- Venue & Year -->
      <p style="margin: 0 0 5px 0; font-style: italic; color: #444;">
        {% if post.venue %}
          {{ post.venue }}{% unless post.venue contains post.date | date: "%Y" %}, {{ post.date | date: "%Y" }}{% endunless %}
        {% else %}
          {{ post.date | date: "%Y" }}
        {% endif %}
      </p>

      <!-- Description -->
      {% if post.excerpt %}
        <p style="margin: 5px 0 10px 0; font-size: 0.95em; color: #555;">
          {{ post.excerpt }}
        </p>
      {% endif %}

      <!-- Links -->
      <p style="margin: 10px 0 0 0;">
        {% if post.paperurl and post.paperurl != "#" %}
          <a href="{{ post.paperurl }}" style="text-decoration: none; border: 1px solid #ccc; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; margin-right: 5px; color: #333;">[Paper]</a>
        {% endif %}
        {% if post.codeurl and post.codeurl != "#" %}
          <a href="{{ post.codeurl }}" style="text-decoration: none; border: 1px solid #ccc; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; margin-right: 5px; color: #333;">[Code]</a>
        {% endif %}
        {% if post.link %}
          <a href="{{ post.link }}" style="text-decoration: none; border: 1px solid #ccc; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; margin-right: 5px; color: #333;">[Project]</a>
        {% endif %}
      </p>
    </article>
  </div>
{% endfor %}

<span id="experience"></span>

🏢 Research & Internship Experience
======
### Internship Experience
- **Algorithm Intern**, Neusoft Corporation (Commercial Software Division) (2025.10–2026.01)  
  - Participated in the R&D of an Agent Loop-based automated mobile phone recovery system, responsible for the visual perception and information retrieval subsystem.  
  - Designed and implemented an Adaptive RAG dynamic retrieval module, improving planning stability and decision accuracy of complex recovery processes by over 20%.  
  - Built a high-precision screen element recognition pipeline using YOLOv8 + EasyOCR; Encapsulated visual capabilities into reusable "Vision Tools" for Agent Loop calling.  
  - Constructed abnormal recovery and failure retry logic, realizing Agent’s multi-round closed-loop "observation-reasoning-execution" process.

<span id="honors"></span>

🏆 Honors & Awards
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

📝 Blog
======
{% for post in site.posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}
<a href="/year-archive/">See all posts</a>
