---
layout: page
title:  Publications
cover:  false
menu:   true
order:  2
---


<ul>
{% for paper in site.data.papers.papers %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endfor %}
</ul>

