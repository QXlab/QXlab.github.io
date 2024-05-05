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
(Corresponding authors marked by \*)

* Wang, Y., Liu, S., & __Xiao, Q.\*__ (2024+), Construction of Orthogonal-MaxPro Latin Hypercube Designs, _Journal of Quality Technology_, Accept.
* __Xiao, Q.__, Wang, Y., Mandal, A. & Deng, X.\* (2024), [Modeling and active learning for experiments with quantitative-sequence factors](https://www.tandfonline.com/doi/full/10.1080/01621459.2022.2123335), _Journal of the American Statistical Association_, 119: 407-421.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
