---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* H. Topol, H. Demirkoparan, and T. J. Pence: _Modeling Stretch-Dependent Collagen Fiber Density_, **Mech. Res. Commun. 116, 103740** (2021) [Download](https://doi.org/10.1016/j.mechrescom.2021.103740)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
