---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: True
---

{% if True %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Jonas Werner, **Kun Chu**, Cornelius Weber, Stefan Wermter. **LLM-based Interactive Imitation Learning for Robotic Manipulation**, IJCNN 2025. [[Paper]](https://arxiv.org/abs/2504.21769) [[Code]](https://github.com/Tubicor/LLM-iTeach)

**Kun Chu**, Xufeng Zhao, Cornelius Weber, and Stefan Wermter. **LLM+MAP: Bimanual Robot Task Planning using Large Language Models and Planning Domain Definition Language**, arXiv 2025. [[Paper](https://arxiv.org/abs/2503.17309)] [[Code](https://github.com/Kchu/LLM-MAP)]

**Kun Chu**, Xufeng Zhao, Cornelius Weber, Mengdi Li, Wenhao Lu, and Stefan Wermter. **Large Language Models for Orchestrating Bimanual Robots**, Humanoids 2024. [[Paper](https://arxiv.org/abs/2404.02018)] [[Website](https://labor-agent.github.io/)]

Xufeng Zhao, Mengdi Li, Wenhao Lu, Cornelius Weber, Jae Hee Lee, **Kun Chu**, Stefan Wermter. **Enhancing Zero-Shot Chain-of-Thought Reasoning in Large Language Models through Logic**, In 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024). [[Paper](https://arxiv.org/abs/2309.13339)]

**Kun Chu**, Xufeng Zhao, Cornelius Weber, Mengdi Li, Stefan Wermter. **Accelerating Reinforcement Learning of Robotic Manipulations via Feedback from Large Language Models**, In CoRL 2023 Workshop (Oral), arXiv preprint arXiv:2311.02379 (2023). [[Paper](https://openreview.net/forum?id=MBeeqmD8Zk)]

**Kun Chu**, Zhinan Peng, Zhiquan Zhang, Rui Huang, Kecheng Shi, Hong Cheng. **Optimal Event-Triggered $H_{\infty}$ Control for Nonlinear Systems with Completely Unknown Dynamics**, In 2022 41st Chinese Control Conference (CCC), 2022, pp. 2236-2241, doi: 10.23919/CCC55666.2022.9902398. [[Paper](https://ieeexplore.ieee.org/abstract/document/9902398)]

**Kun Chu**, Xianchao Zhu, William Zhu. **Accelerating Lifelong Reinforcement Learning via Reshaping Rewards**, In 2021 IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2021, pp. 619-624, doi: 10.1109/SMC52423.2021.9659064. [[Paper](https://ieeexplore.ieee.org/document/9659064)] [[Code](https://github.com/Kchu/LifelongRL)]