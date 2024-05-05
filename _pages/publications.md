---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

***Journal articles***
(Corresponding authors are marked with \*)

* Wang, Y., Liu, S., & **Xiao, Q.\* ** (2024+), "Construction of Orthogonal-MaxPro Latin Hypercube Designs", Journal of Quality Technology, Accept.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
