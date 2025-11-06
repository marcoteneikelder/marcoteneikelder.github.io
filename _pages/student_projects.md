---
layout: archive
title: "Student Projects"
permalink: /student_projects/
author_profile: true
---

<span style="color: #3b7c78;"><b>Open student (HIWI) projects</b></span><br>
<li> Towards Greener Inkjet Printing: Cutting-Edge Evaporation Modeling for Energy Reduction<br>
  <b><a href="http://marcoteneikelder.github.io/files/Project_Towards_Greener_Inkjet_Printing.pdf" style="color: #7b2c35 !important;">Project description</a></b>
</li>
<br><br>
Please do not hesitate to contact me if you are interested to work with me (or if you have project ideas).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
