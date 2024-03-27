---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if True %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Xufeng Zhao, Mengdi Li, Wenhao Lu, Cornelius Weber, Jae Hee Lee, **Kun Chu**, Stefan Wermter. **Enhancing Zero-Shot Chain-of-Thought Reasoning in Large Language Models through Logic**, The 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (COLING 2024). [[Paper](https://arxiv.org/abs/2309.13339)]

**Kun Chu**, Xufeng Zhao, Cornelius Weber, Mengdi Li, Stefan Wermter. **Accelerating Reinforcement Learning of Robotic Manipulations via Feedback from Large Language Models**, CoRL 2023 Workshop (Oral), arXiv preprint arXiv:2311.02379 (2023). [[Paper](https://openreview.net/forum?id=MBeeqmD8Zk)]

**Kun Chu**, Zhinan Peng*, Zhiquan Zhang, Rui Huang, Kecheng Shi, Hong Cheng. **Optimal Event-Triggered $H_{\infty}$ Control for Nonlinear Systems with Completely Unknown Dynamics**, 2022 41st Chinese Control Conference (CCC), 2022, pp. 2236-2241, doi: 10.23919/CCC55666.2022.9902398. [[Paper](https://ieeexplore.ieee.org/abstract/document/9902398)]

**Kun Chu**, Xianchao Zhu, William Zhu*. **Accelerating lifelong reinforcement learning via reshaping rewards**, 2021 IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2021, pp. 619-624, doi: 10.1109/SMC52423.2021.9659064. [[Paper](https://ieeexplore.ieee.org/document/9659064)] [[Code](https://github.com/Kchu/LifelongRL)]