---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<b>[Quasi-static Folding Mechanical Behavior Analysis and Optimization Design for Composite Tube Hinge](http://www.cjmenet.com.cn/CN/10.3901/JME.2020.05.172)</b> <br>
Holing Ye\*, <b>Bowen Li</b>\*, Xuesong Shi, Yang Zhang<br>
<i>Journal of Mechanical Engineering, DOI: 10.3901/JME.2020.05.172</i>

<b>[Failure analysis of composite tube hinge and optimization design](https://iopscience.iop.org/article/10.1088/1757-899X/531/1/012062)</b> <br>
<b>Bowen Li</b>\*, Hongling Ye, Yang Zhang<br>
<i>IOP Conference Series Materials Science and Engineering, DOI 10.1088/1757-899X/531/1/012062</i>

<b>[Mechanical behavior of composite bistable shell structure and surrogate-based optimal design](https://link.springer.com/article/10.1007/s00158-021-02890-7)</b> <br>
Yang Zhang, Hongling Ye, <b>Bowen Li</b>\* <br>
<i>Structural and Multidisciplinary Optimization, DOI: 10.1007/s00158-021-02890-7</i>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://www.researchgate.net/profile/Bowen-Li-52/research}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
