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

**Conference**
======
**Buhua Liu**\*, Zeke Xie\*, Shuo Yang, Yiu-ming Cheung. Stronger Separability, Stronger Defense: Influence-based Backdoor Detection. ICML, under review (average score 5.75)

Xindi Yang, Zeke Xie, Xiong Zhou, Boyu Liu, **Buhua Liu**, Yi Liu, Haoran Wang, Yunfeng Cai, Mingming Sun. Neural Field Classifiers via Target Encoding and Classification Loss. ICLR, 2024

**Journal**
=====
Weichao Lan, Yiu-ming Cheung, Qing Xu, **Buhua Liu**, Zhikai Hu, Mengke Li, Zhenghua Chen. Improve Knowledge Distillation via Label Revision and Data Selection.  Neural Computation, under review

Yuzhi Zhao, Lai-Man Po, Xuehui Wang, Qiong Yan, Wei Shen, Yujia Zhang, Wei Liu, Chun-Kit Wong, Chiu-Sing Pang, Weifeng Ou, Wing-Yin Yu, **Buhua Liu**. ChildPredictor: A Child Face Prediction Framework with Disentangled Learning. IEEE Transactions on Multimedia, 2022
