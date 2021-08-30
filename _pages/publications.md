---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* H. Topol, H. Demirkoparan, and T. J. Pence: _Modeling Stretch-Dependent Collagen Fiber Density_

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
