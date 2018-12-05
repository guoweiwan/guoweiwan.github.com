---
layout: page
title: Guowei Wan(万国伟)
cover: false
---

I am currently a senior research and development engineer working in Baidu Intelligent Driving Group (IDG). 
I received my PhD in Computing Science from National University of Defense Technology under the co-supervision of Prof. Sikun Li and Prof. [Baoquan Chen](http://web.siat.ac.cn/~baoquan/). 

My research is in Computer Vision, Simultaneous Localization and Mapping (SLAM), Structure from Motion (SFM), 3D Reconstruction, Point Cloud Processing. My research profiles can be found at [Google Scholar](https://scholar.google.com/citations?user=99pnrfMAAAAJ&hl=en).

## News

* In June, my awesome PhD student [Sorcha Gilroy](http://homepages.inf.ed.ac.uk/s1459276/) 
received an [oustanding paper award](https://naacl2018.wordpress.com/2018/04/11/outstanding-papers/)
[NAACL 2018](http://naacl2018.org/) for a very cool
paper she coauthored on [RNNs as weighted language recognizers](http://aclweb.org/anthology/N18-1205). 
In the same month, she was a finalist in University of Edinburgh 
[3-minute thesis competition](https://www.ed.ac.uk/institute-academic-development/postgraduate/doctoral/3mt/3mt-final).

* Sorcha Gilroy and I gave a tutorial on 
[Graph Formalisms for Meaning Representations](https://bit.ly/GraphFormalismsEMNLP) at
[EMNLP 2018](http://emnlp2018.org/). We taught [a week-long course](https://drive.google.com/drive/folders/1NtdhgieGKpnTvpYiBCUgkE-g0ygKDyE_) on 
the same topic at [NASSLLI 2018](https://www.cmu.edu/nasslli2018/).

## Current Highlights

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

