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
**Buhua Liu**, Shuo Yang, Zhiqiang Xu, Haoyi Xiong, Yiu-ming Cheung, Zeke Xie. Stronger Separability, Stronger Defense: Influence-based Backdoor Detection. Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD), 2025 (**Oral**).

Zipeng Qi\*, **Buhua Liu**\*, Shiyan Zhang, Bao Li, Zhiqiang Xu, Haoyi Xiong, Zeke Xie. A Simple and Efficient Baseline for Zero-Shot Generative Classification. Under review.

Zichen Tang\*, Zhenheng Tang\*, Gaoning Pan, **Buhua Liu**, Xin He, Kunfeng Lai, Xiaowen Chu, Bo Li. Ghost in the Cloud: Your Geo-Distributed Large Language Models Training is Easily Manipulated. International Conference on Learning Representations (ICLR), 2026.

Xindi Yang\*, Zeke Xie\*, Xiong Zhou, Boyu Liu, **Buhua Liu**, Yi Liu, Haoran Wang, Yunfeng Cai, Mingming Sun. Neural Field Classifiers via Target Encoding and Classification Loss. International Conference on Learning Representations (ICLR), 2024.

**Journal**
=====
**Buhua Liu**, Shitong Shao, Bao Li, Lichen Bai, Zhiqiang Xu, Haoyi Xiong, James Kwok, Sumi Helal, Zeke Xie. Alignment of Diffusion Models: Fundamentals, Challenges, and Future. ACM Computing Surveys (CSUR), 2026.

Weichao Lan, Yiu-ming Cheung, Qing Xu, **Buhua Liu**, Zhikai Hu, Mengke Li, Zhenghua Chen. Improve Knowledge Distillation via Label Revision and Data Selection. IEEE Transactions on Cognitive and Developmental Systems, 2025.

Yuzhi Zhao, Lai-Man Po, Xuehui Wang, Qiong Yan, Wei Shen, Yujia Zhang, Wei Liu, Chun-Kit Wong, Chiu-Sing Pang, Weifeng Ou, Wing-Yin Yu, **Buhua Liu**. ChildPredictor: A Child Face Prediction Framework with Disentangled Learning. IEEE Transactions on Multimedia, 2022.
