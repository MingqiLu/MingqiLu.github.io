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

I am a second year Ph.D. student at Northeastern University, advised by Prof. [Zhengzhong Jin](https://zhengzhongjin.github.io/). Before that, I was an undergraduate student at Yao Class, Tsinghua University.

My research interests lie in theoretical computer science, with a focus on cryptography.

Email: lu.mingqi (at) northeastern (dot) edu

# 📝 Publications 

- **SNARKs from LWE via Non-black-box Reductions (or: How to rewind non-interactively)**  
  Zhengzhong Jin, **Mingqi Lu**, Bo Peng  
  **STOC 2026**

- **Memory-sample lower bounds for LWE**  
  **Mingqi Lu**, Junzhao Yang  
  **CRYPTO 2024**