---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /home/
  - /home.html
  - /ljhuang
layout: archive
--- 

<hr style="width:80%;text-align:left;margin-left:0">

I'm now a Professor at the Institute of Artificial Intelligence, Beihang University.

I work with with [Prof. Hongsheng Li](https://scholar.google.com/citations?user=BN2Ze-QAAAAJ&hl=zh-TW&oi=ao) as a post-doctoral fellow in [Multi-Media Lab (MMLab)](http://mmlab.ie.cuhk.edu.hk/) at The Chinese University of Hong Kong (CUHK) and Centre for Perceptual and Interactive Intelligence (CPII) from 2020 to 2024. 

I recieved my Ph.D. Degree from Institute of Automation, Chinese Academy of Sciences (CASIA) in 2020, advised by [Prof. Liang Wang](https://ia.cas.cn/rcdw/jcqn/202404/t20240422_7129880.html), and my Bachelor and Master Degree from Huazhong University of Science and Technology (HUST) in 2014 and 2017, respectively. 

My current research interests include generative AI and embodied AI.


<br>

<h1 id="publications"> Publications</h1>

<hr style="width:80%;text-align:left;margin-left:0">

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
