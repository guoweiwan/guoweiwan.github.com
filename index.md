---
layout: page
title: Guowei Wan (万国伟)
cover: false
---

I am currently a senior research and development engineer working in Baidu Intelligent Driving Group (IDG). 
I received my PhD in Computing Science from National University of Defense Technology under the co-supervision of Prof. Sikun Li and Prof. [Baoquan Chen](http://web.siat.ac.cn/~baoquan/). 

My research is in Computer Vision, Simultaneous Localization and Mapping (SLAM), Structure from Motion (SFM), 3D Reconstruction, Point Cloud Processing. My research profiles can be found at [Google Scholar](https://scholar.google.com/citations?user=99pnrfMAAAAJ&hl=en).

## Selected Publications

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

