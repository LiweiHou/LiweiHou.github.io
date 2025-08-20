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
- *2025.08 - Recent*：&nbsp;🇨🇳 *Airon*, Founder & CEO

- *2022.08 - 2025.07*：&nbsp;🇨🇳 *Zoomlion*, AI Scientist/Expert, Project Manager

- *2024.01 – 2024.02*: &nbsp;🇸🇬 *National University of Singapore*, Visiting Scholar.
  
- *2021.07 – 2021.08*: &nbsp;🇨🇳 *Alibaba*, Intern.

- *2020.05 – 2021.3*: &nbsp;🇺🇸 *Amazon*, Remote Intern.
  
- *2017.01 – 2017.06*: &nbsp;🇨🇳 *Tencent*, Intern.

# 🔥 About Airon

Airon is an enterprise service platform driven by artificial intelligence technology, providing data collection and annotation services, AI training services, and AI solution services to over one million enterprises and developers worldwide.

# 📈 News
- *2025.08.19*: &nbsp;🎉 Released the first “Trusted Data Space” product built on federated learning!


# 📝 Selected Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Trusted Data Space</div><img src='../images/trusted.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A secure digital environment where companies can share and use sensitive data with absolute confidence. We ensure provenance, integrity, and control, turning data collaboration into your greatest competitive advantage.
  
- *<span style="color:#548656">Encrypted. Traceable. Governed. Collaborate with 100% confidence!</span>*
- our platform guarantees **99.99% uptime**, delivers **sub-5ms encryption latency** with 10G+ throughput, supports **10,000+ concurrent connections**, and provides instant, cryptographically-verified audit trails for all data operations.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Glass Installation Robot</div><img src='../images/SeRe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Developed the glass installation robot with autonomous alignment functionality, achieving an installation control accuracy of 3mm.

- *Two papers published*
  - [Diffusion-based Self-Supervised Imitation Learning from Imperfect Visual Servoing Demonstrations for Robotic Glass Installation](https:)<span class="rucred">ICRA'25</span>
  - [High-Precision Automated Glass Installation Robot with Dual-Camera Visual Servoing Control](https://ieeexplore.ieee.org/abstract/document/10907684)<span class="rucred">ROBIO'24</span>

</div>
</div>


# 🎖 Honors and Awards
- *2023.01*: &nbsp;🏆 Zoomlion Annual Outstanding Employee

# 🌍 Visitor Map

<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=j2P-1zF4D1SxxgYEb-tcl8IPUhcf145Bw9HPn9DE8nU&cl=ffffff&w=a"></script>


<footer class="site-footer">
  <p>&copy; 2025 Liwei Hou. All rights reserved.</p>
  <p>
    Template adapted from
    <a href="https://github.com/RayeRen/acad-homepage.github.io"
       target="_blank" rel="noopener">Yi Ren</a>.
  </p>
</footer>
