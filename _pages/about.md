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

<style>
  .rucred {
    display: inline-block;
    background-color: rgb(174, 11, 42);
    color: white;
    font-size: 0.8em;
    padding: 2px 6px;
    border-radius: 3px;
    margin-left: 8px;
    font-weight: bold;
    vertical-align: middle;
  }
  .badge {
    font-weight: 600;
    margin-bottom: 5px;
  }
</style>

<style>
  .logo-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2rem; 
  }
  .logo-row img {
    height: 60px;
    width: auto;
    /* 
       border-radius: 6px;
       box-shadow: 0 0 6px rgba(0,0,0,.15); */
  }
</style>

<style>
  .site-footer {
    text-align: center;
    font-size: 0.85em;
    color: rgb(128, 128, 128);
    margin: 2rem 0 1rem; 
  }
  .site-footer a {
    color: inherit;
    text-decoration: underline;
  }
</style>

<span class='anchor' id='about-me'></span>

I hold a PhD from [Central South University](https://www.shanghairanking.com/institution/central-south-university), with my research focusing on robotic learning. Prior to this, I pursued my studies at [Tianjin University](https://www.shanghairanking.com/institution/tianjin-university). 

Currently, I am the founder and CEO of Airon Tech, an AI technology company. My vision is to bring AI to the ground, boost social efficiency, and benefit humanity.

# 💻 Work Experiences
- *2022.08 - 2025.07*：&nbsp;🇨🇳 *Zoomlion*, AI Scientist/Expert, Project Manager

  *- Project1: Bandit Optimization for Homepage Personalization in Online Retail*
  
- *2021.07 – 2021.08*: &nbsp;🇨🇳 *Alibaba*, Intern.

  *- Project: Robotic arm-based automated logistics system*

- *2020.05 – 2021.3*: &nbsp;🇺🇸 *Amazon*, Remote Intern.

  *- Project: Bandit Optimization for Homepage Personalization in Online Retail*
  
- *2017.01 – 2017.06*: &nbsp;🇨🇳 *Tencent*, Intern.

  *- Project: Optimization of User Gaming Experience Based on Reinforcement Learning*

# 🔥 About Airon

Airon is an enterprise service platform driven by artificial intelligence technology, providing data collection and annotation services, AI training services, and AI solution services to over one million enterprises and developers worldwide.

# 📈 News
- *2025.08.19*: &nbsp;🎉 Released the first “Trusted Data Space” product built on federated learning!


# 📝 Selected Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Glass Installation Robot</div><img src='../images/SeRe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Developed the glass installation robot with autonomous alignment functionality, achieving an installation control accuracy of 3mm.

- *Two papers published*
  - [111](https://arxiv.org/pdf/2506.12389)<span class="rucred">ICRA'25</span>
  - [High-Precision Automated Glass Installation Robot with Dual-Camera Visual Servoing Control](https://ieeexplore.ieee.org/abstract/document/10907684)<span class="rucred">ROBIO'24</span>
  
- [**<span style="color:#548656">Watch our promotional video on YouTube!</span>**](https://www.youtube.com/watch?v=lATSWn7t_Xc)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2025</div><img src='../images/TICNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Context-Aware Framework for Integrating Ad Auctions and Recommendations](https://dl.acm.org/doi/pdf/10.1145/3696410.3714779?casa_token=8lqAC8Liak8AAAAA:lbsi8gr5tQAQds4gSyTdM3a7Rl43lK1yXwjDzjOtcXOxydg_JQJfvJxQtUKGAPxbZNspu3OlGT5ZcQ)

Yuchao Ma, Weian Li, Yuejia Dou, **Zhiyuan Su**, Changyuan Yu, Qi Qi

- *Accepted at ACM The Web Conference (WWW) 2025* <span class="rucred">Poster</span>

</div>
</div>


# 🎖 Honors and Awards
- *2023.01*: &nbsp;💰 Zoomlion Annual Outstanding Employee 中联年度优秀员工

# 🌍 Visitor Map

<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=j2P-1zF4D1SxxgYEb-tcl8IPUhcf145Bw9HPn9DE8nU&cl=ffffff&w=a"></script>



<div class="logo-row">
  <img src="../images/ruc_logo.png"      alt="">
  <img src="../images/ucdavis_logo.png"  alt="">
  <img src="../images/dal_logo.png"      alt="">
  <img src="../images/mitacs_logo.png"      alt="">
</div>


<footer class="site-footer">
  <p>&copy; 2025 Liwei Hou. All rights reserved.</p>
  <p>
    Template adapted from
    <a href="https://github.com/RayeRen/acad-homepage.github.io"
       target="_blank" rel="noopener">Yi Ren</a>.
  </p>
</footer>
