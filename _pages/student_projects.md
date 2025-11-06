---
layout: archive
title: "Student Projects"
permalink: /student_projects/
author_profile: true
---

<span style="color: #3b7c78;"><b>Open student (HIWI) projects</b></span><br>
<li> <a href="https://www.uni-regensburg.de/mathematics/mathematics-abels/further-activities/gamm-activity-group-interfacial-and-multiphase-flow/index.html">Towards Greener Inkjet Printing:
Cutting-Edge Evaporation Modeling for
Energy Reduction</a><br>
</li>

Please do not hesitate to contact me if you are interested to work with me (and if you have project ideas).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
