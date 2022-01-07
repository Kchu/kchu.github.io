---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Kun Chu**, Xianchao Zhu, William Zhu*. [Accelerating lifelong reinforcement learning via reshaping rewards](https://ieeexplore.ieee.org/document/9659064), 2021 IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2021, pp. 619-624, doi: 10.1109/SMC52423.2021.9659064.