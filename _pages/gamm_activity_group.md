---
layout: archive
title: "GAMM Activity Group - Interfacial and Multiphase Flow"
permalink: /gamm_activity_group/
author_profile: true
---
Interfacial and multiphase flow are essential areas of research that underpin a wide variety of applications, from natural sciences to industrial processes. These systems involve interactions between multiple phases—such as gas, liquid, and solid—and components, posing significant challenges for physical modeling, mathematical analysis, and numerical simulation. The field is highly interdisciplinary and often requires the development of new models, which in turn demand mathematical analysis and necessitate innovative numerical methods.
<br><br>
The aim of this activity group is to bring together researchers working in the broad area of interfacial and multiphase flow systems by establishing a collaborative platform for early-career and established researchers. The group meets annually for a workshop, which features research presentations and provides a forum for planning and coordinating joint scientific activities.
<br><br><br>

<span style="color: #3b7c78;"><b>Contact</b></span><br>
<span style="color: #7b2c35 !important;"><b>Chair: </b></span>Dr. ir. Marco ten Eikelder (Darmstadt)<br>
<span style="color: #7b2c35 !important;"><b>Vice Chair: </b></span>Prof. Dr. Barbara Wagner (Berlin)<br>
<span style="color: #7b2c35 !important;"><b>ViceChair: </b></span>Prof. Dr. Helmut Abels (Regensburg)<br>

<li> <a href="https://www.uni-regensburg.de/mathematics/mathematics-abels/further-activities/gamm-activity-group-interfacial-and-multiphase-flow/index.html">GAMM activity group website</a><br>
</li>
<li>
   <a href="https://www.mechanik.tu-darmstadt.de/forschung_mech/gamm_workshop/gamm_workshop.en.jsp">1st GAMM Activity Group Workshop</a><br>
</li>  

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
