---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* Beta Decay of Molecular Tritium
   Y.-T. Lin *et at.* (the TRIMS Collaboration)
   [Phys. Rev. Lett. 124, 222502 (2020)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.124.222502)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
