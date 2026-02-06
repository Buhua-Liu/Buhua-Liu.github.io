---
permalink: /
title: "Buhua Liu"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.highlight-box {
  background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%);
  border-radius: 12px;
  padding: 1.5em;
  margin: 1.5em 0;
  border-left: 4px solid #2563eb;
}
.news-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 1em;
  padding-bottom: 1em;
  border-bottom: 1px solid rgba(0,0,0,0.05);
}
.news-item:last-child {
  border-bottom: none;
  margin-bottom: 0;
  padding-bottom: 0;
}
.news-date {
  min-width: 100px;
  font-weight: 600;
  color: #2563eb;
  font-size: 0.9em;
}
.news-content {
  flex: 1;
}
.highlight {
  background: linear-gradient(120deg, #fef3c7 0%, #fef3c7 100%);
  padding: 0.1em 0.3em;
  border-radius: 3px;
  font-weight: 600;
}
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1em;
  margin: 1.5em 0;
}
.research-card {
  background: linear-gradient(135deg, #f8fafc 0%, #f1f5f9 100%);
  border-radius: 10px;
  padding: 1.2em;
  border: 1px solid rgba(37, 99, 235, 0.15);
  transition: all 0.3s ease;
}
.research-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 25px rgba(37, 99, 235, 0.15);
}
.research-icon {
  font-size: 1.8em;
  margin-bottom: 0.3em;
}
.research-title {
  font-weight: 600;
  color: #2563eb;
  font-size: 0.95em;
}
.pub-card {
  background: #fff;
  border-radius: 12px;
  padding: 1.2em 1.5em;
  margin-bottom: 1.2em;
  box-shadow: 0 2px 15px rgba(0,0,0,0.08);
  border: 1px solid rgba(0,0,0,0.05);
  transition: all 0.3s ease;
}
.pub-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 30px rgba(0,0,0,0.12);
}
.pub-title {
  font-weight: 600;
  color: #1f2937;
  font-size: 1.05em;
  margin-bottom: 0.4em;
}
.pub-authors {
  color: #6b7280;
  font-size: 0.9em;
  margin-bottom: 0.4em;
}
.pub-venue {
  font-style: italic;
  color: #6b7280;
  font-size: 0.9em;
  margin-bottom: 0.6em;
}
.badge {
  display: inline-block;
  padding: 0.2em 0.7em;
  border-radius: 15px;
  font-size: 0.75em;
  font-weight: 600;
  margin-right: 0.4em;
}
.badge-oral {
  background: linear-gradient(135deg, #dc2626 0%, #ef4444 100%);
  color: white;
}
.badge-venue {
  background: linear-gradient(135deg, #2563eb 0%, #1d4ed8 100%);
  color: white;
}
.badge-impact {
  background: linear-gradient(135deg, #f59e0b 0%, #d97706 100%);
  color: white;
}
</style>

I am an MPhil graduate from the Department of Computer Science at [Hong Kong Baptist University](https://www.hkbu.edu.hk/), advised by [Prof. Yiu-ming Cheung](https://www.comp.hkbu.edu.hk/~ymc/). I received my B.Eng. degree from the School of Electronic and Information Engineering at [Huazhong University of Science and Technology](https://www.hust.edu.cn/).

My research focuses on **exploring the capability boundaries of large models**, with particular interests in:

<div class="research-grid">
  <div class="research-card">
    <div class="research-icon">🎨</div>
    <div class="research-title">AIGC & Diffusion Models</div>
  </div>
  <div class="research-card">
    <div class="research-icon">🧠</div>
    <div class="research-title">Multimodal Large Language Models</div>
  </div>
  <div class="research-card">
    <div class="research-icon">🔒</div>
    <div class="research-title">AI Safety & Alignment</div>
  </div>
  <div class="research-card">
    <div class="research-icon">🚀</div>
    <div class="research-title">Practical AI Applications</div>
  </div>
</div>

News
======

<div class="highlight-box">
  <div class="news-item">
    <div class="news-date">2026</div>
    <div class="news-content">Our survey paper on <span class="highlight">Diffusion Model Alignment</span> has been accepted by <strong>ACM Computing Surveys</strong> (IF: 28.0)!</div>
  </div>
  <div class="news-item">
    <div class="news-date">2026</div>
    <div class="news-content">One paper accepted at <span class="highlight">ICLR 2026</span> on distributed LLM training security.</div>
  </div>
  <div class="news-item">
    <div class="news-date">2025</div>
    <div class="news-content">One paper accepted at <span class="highlight">PAKDD 2025</span> (Oral) on backdoor detection!</div>
  </div>
  <div class="news-item">
    <div class="news-date">2025</div>
    <div class="news-content">One paper accepted by <strong>IEEE TCDS</strong> on knowledge distillation.</div>
  </div>
</div>

Selected Publications
======

<div class="pub-card">
  <div class="pub-title">Alignment of Diffusion Models: Fundamentals, Challenges, and Future</div>
  <div class="pub-authors"><strong style="color:#2563eb">Buhua Liu</strong>, Shitong Shao, Bao Li, Lichen Bai, Zhiqiang Xu, Haoyi Xiong, James Kwok, Sumi Helal, Zeke Xie</div>
  <div class="pub-venue">ACM Computing Surveys (CSUR), 2026</div>
  <span class="badge badge-venue">ACM CSUR</span>
  <span class="badge badge-impact">IF: 28.0</span>
</div>

<div class="pub-card">
  <div class="pub-title">Stronger Separability, Stronger Defense: Influence-based Backdoor Detection</div>
  <div class="pub-authors"><strong style="color:#2563eb">Buhua Liu</strong>, Shuo Yang, Zhiqiang Xu, Haoyi Xiong, Yiu-ming Cheung, Zeke Xie</div>
  <div class="pub-venue">Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD), 2025</div>
  <span class="badge badge-venue">PAKDD 2025</span>
  <span class="badge badge-oral">Oral</span>
</div>

<div class="pub-card">
  <div class="pub-title">Ghost in the Cloud: Your Geo-Distributed Large Language Models Training is Easily Manipulated</div>
  <div class="pub-authors">Zichen Tang*, Zhenheng Tang*, Gaoning Pan, <strong style="color:#2563eb">Buhua Liu</strong>, Xin He, Kunfeng Lai, Xiaowen Chu, Bo Li</div>
  <div class="pub-venue">International Conference on Learning Representations (ICLR), 2026</div>
  <span class="badge badge-venue">ICLR 2026</span>
</div>

<a href="/publications/" class="btn-academic" style="display:inline-block; padding:0.5em 1.2em; background:linear-gradient(135deg, #2563eb 0%, #1d4ed8 100%); color:white; border-radius:6px; text-decoration:none; font-weight:500; margin-top:1em;">View All Publications →</a>

Experience
======

**Research Intern** @ Baidu Research, Cognitive Computing Lab (CCL), Beijing
*Advised by [Prof. Zeke Xie](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/XIE-Zeke/zekexie)*

Hobbies
======

When I'm not doing research, I enjoy road trips, hiking, swimming, and badminton.
