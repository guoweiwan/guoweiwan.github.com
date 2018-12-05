---
layout: page
title: Guowei Wan (万国伟)
cover: false
---

I am currently a senior research and development engineer working in Baidu Intelligent Driving Group (IDG). 
I received my PhD in Computing Science from National University of Defense Technology under the co-supervision of Prof. Sikun Li and Prof. [Baoquan Chen](http://web.siat.ac.cn/~baoquan/). 

My research interests include Computer Vision, Computer Graphics and Robotics, especially in Simultaneous Localization and Mapping (SLAM), Structure from Motion (SFM), 3D Reconstruction, Point Cloud Processing, as well as Mapping and Localization for Autonomous Driving. My research profiles can be found at [Google Scholar](https://scholar.google.com/citations?user=99pnrfMAAAAJ&hl=en).

## Selected Publications

<ul>
{% for spaper in site.data.papers.papers %}
 {% if spaper.selected %}
  <li>
  {% include spaper.html spaper=spaper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

