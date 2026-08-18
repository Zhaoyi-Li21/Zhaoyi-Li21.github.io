---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi:wave:, I am LI, ZHAOYI (Joey), a Ph.D. student at [University of Science and Technology of China](https://en.ustc.edu.cn/) and [City University of Hong Kong](https://www.cityu.edu.hk/), co-adviced by Dr. [Defu Lian](https://faculty.ustc.edu.cn/liandefu/en/index.htm) (Situated Cognitive Intelligence Research Group @ USTC), Dr. [Ying Wei](https://wei-ying.net/) (Compositional Lifelong Learning Lab @ Zhejiang University), and Dr. [Linqi Song](https://sites.google.com/site/aisquaredlab/about-us/linqi) (Algorithmic Information theory and Artificial Intelligence Lab @ CityU).
Previously, I got my Bachelor degree in Computer Science and Technology at University of Science and Technology of China in 2022.

My research goal is to build highly trustworthy and transparent language models that achieve human-like reasoning and systematic generalization. Specifically, I want to make human beings and neural network systems better understand each other (i.e., high interpretability and good generalization of blackbox deep models). I currently focus on investigating the compositionality of language models, which is about the mechanism that language models decompose complex questions and concepts into primitive ones and re-compose them step-by-step to grasp the complex semantic meaning. I am super curious about whether the end-to-end trained large-scale models are able to grok human-like reasoning skills or not and how to demonstrate it both empirically and theoretically. I would love to discuss on related topics should anyone is interested (always feel free to drop me an email: lizhaoyi777$$AT$$mail.ustc.edu.cn)!

I am currently focusing on the post-training of LLMs for enhancing their reasoning and generalization abilities and seeking opportunities of both industrial and academic research positions (wechat: joeylee2333).


# 🔥 News
- *2026.08*: &nbsp;🎉🎉 Very happy to receive COLM 2026 travel grant.
- *2026.07*: &nbsp;🎉🎉 One paper was accepted by COLM 2026.
- *2026.05*: &nbsp;🎖 Very happy to receive ICML 2026 Gold Reviewer Award. 
- *2026.01*: &nbsp;🎉🎉 Two papers were accepted by ICLR 2026. 
- *2025.12*: &nbsp;🎉🎉 I started an internship journey in [Meituan](https://www.meituan.com/en-US/about-us) <img src='../images/meituan.png' style='width: 6em;'> [LongCat](https://huggingface.co/meituan-longcat) <img src='../images/longcat.png' style='width: 6em;'> Team.
- *2025.08*: &nbsp;🎉🎉 One paper was accepted by EMNLP 2025.
- *2025.02*: &nbsp;🎉🎉 One paper was accepted by ICLR 2025.
- *2024.09*: &nbsp;🎉🎉 One paper was accepted by Machine Learning Journal.
- *2024.09*: &nbsp;🎉🎉 One paper was accepted by EMNLP 2024.
- *2024.05*: &nbsp;🎉🎉 Two papers were accepted by ACL 2024.
- *2023.05*: &nbsp;🎉🎉 My first paper was accepted by ACL 2023. 

# 📝 Selected Papers

<p style="color:#666; font-size:0.92em; margin-top:-8px;">* indicates co-first authorship</p>

<style>
.pub-card {
  background: #fff;
  border: 1px solid #e3e8ef;
  border-radius: 10px;
  padding: 18px 22px;
  margin-bottom: 14px;
  box-shadow: 0 2px 8px rgba(44,62,80,0.06);
  transition: box-shadow 0.2s, transform 0.2s;
  position: relative;
  overflow: hidden;
}
.pub-card::before {
  content: '';
  position: absolute;
  left: 0; top: 0; bottom: 0;
  width: 4px;
  border-radius: 10px 0 0 10px;
  background: #3a7bd5;
  opacity: 0;
  transition: opacity 0.2s;
}
.pub-card:hover {
  box-shadow: 0 6px 20px rgba(44,62,80,0.13);
  transform: translateY(-2px);
}
.pub-card:hover::before { opacity: 1; }

.pub-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-bottom: 9px;
  align-items: center;
}
.badge {
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.4px;
  padding: 2px 9px;
  border-radius: 20px;
  text-transform: uppercase;
  white-space: nowrap;
  display: inline-block;
}
.badge-conf  { background:#dbeeff; color:#1a6fba; border:1px solid #b3d4f5; }
.badge-pre   { background:#f0f2f4; color:#6b7785; border:1px solid #d0d6de; }
.badge-oral  { background:#fdecea; color:#c0392b; border:1px solid #f5c6c2; }
.badge-find  { background:#e8f5e9; color:#2e7d32; border:1px solid #b7dfba; }
.badge-year  { font-size:0.7rem; font-weight:600; color:#9aa5b1; background:none; border:none; padding:0; letter-spacing:0.2px; }

.pub-title {
  font-size: 1rem;
  font-weight: 700;
  color: #1a2332;
  line-height: 1.5;
  margin-bottom: 6px;
}
.pub-authors {
  font-size: 0.855rem;
  color: #556070;
  line-height: 1.65;
  margin-bottom: 12px;
}
.pub-authors .me {
  font-weight: 700;
  color: #1a2332;
}
.pub-links { display:flex; flex-wrap:wrap; gap:7px; }
.pub-btn {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  font-size: 0.78rem;
  font-weight: 600;
  padding: 4px 13px;
  border-radius: 6px;
  text-decoration: none !important;
  border: 1.5px solid;
  transition: background 0.18s, color 0.18s;
  line-height: 1.4;
}
.btn-paper { color:#2471b8; border-color:#2471b8; }
.btn-paper:hover { background:#2471b8; color:#fff; }
.btn-code  { color:#219150; border-color:#219150; }
.btn-code:hover  { background:#219150; color:#fff; }
.btn-blog  { color:#d4720a; border-color:#d4720a; }
.btn-blog:hover  { background:#d4720a; color:#fff; }
</style>

<!-- Paper 1 -->
<div class="pub-card">
  <div class="pub-badges">
    <span class="badge badge-pre">Preprint 2026</span>
  </div>
  <div class="pub-title">Every Coin Has Two Sides: On the Dual Nature of Generalization in On-Policy Distillation of Large Language Models</div>
  <div class="pub-authors"><span class="me">Zhaoyi Li</span>*, Deyang Kong*, Xiangyu Xi*, et. al.</div>
  <div class="pub-links">
    <a class="pub-btn btn-paper" href="https://arxiv.org/abs/2608.16647" target="_blank">📄 Paper</a>
  </div>
</div>

<!-- Paper 1 -->
<div class="pub-card">
  <div class="pub-badges">
    <span class="badge badge-pre">COLM 2026</span>
  </div>
  <div class="pub-title">On the Role of Reasoning Patterns in the Generalization Discrepancy of Long Chain-of-Thought Supervised Fine-Tuning</div>
  <div class="pub-authors"><span class="me">Zhaoyi Li</span>*, Xiangyu Xi*, Zhengyu Chen, Wei Wang, Gangwei Jiang, Ranran Shen, Linqi Song, Ying Wei and Defu Lian</div>
  <div class="pub-links">
    <a class="pub-btn btn-paper" href="https://arxiv.org/abs/2604.01702" target="_blank">📄 Paper</a>
  </div>
</div>

<!-- Paper 2 -->
<div class="pub-card">
  <div class="pub-badges">
    <span class="badge badge-conf">ICLR 2026</span>
  </div>
  <div class="pub-title">Scaling Reasoning Hop Exposes Weaknesses: Demystifying and Improving Hop Generalization in Large Language Models</div>
  <div class="pub-authors"><span class="me">Zhaoyi Li</span>, Jiatong Li, Gangwei Jiang, Linqi Song, Defu Lian and Ying Wei</div>
  <div class="pub-links">
    <a class="pub-btn btn-paper" href="https://openreview.net/forum?id=qK4JKOu0Gx" target="_blank">📄 Paper</a>
    <a class="pub-btn btn-code" href="https://github.com/Zhaoyi-Li21/reasoning_hop_generalization" target="_blank">💻 Code</a>
  </div>
</div>

<!-- Paper 3 -->
<div class="pub-card">
  <div class="pub-badges">
    <span class="badge badge-pre">Preprint 2025</span>
  </div>
  <div class="pub-title">Learning to Substitute Components for Compositional Generalization</div>
  <div class="pub-authors"><span class="me">Zhaoyi Li</span>, Gangwei Jiang, Chenwang Wu, Ying Wei, Defu Lian and Enhong Chen</div>
  <div class="pub-links">
    <a class="pub-btn btn-paper" href="https://arxiv.org/abs/2502.20834" target="_blank">📄 Paper</a>
  </div>
</div>

<!-- Paper 4 -->
<div class="pub-card">
  <div class="pub-badges">
    <span class="badge badge-conf">EMNLP 2024</span>
  </div>
  <div class="pub-title">Mitigating the Language Mismatch and Repetition Issues in LLM-based Machine Translation via Model Editing</div>
  <div class="pub-authors">Weichuan Wang*, <span class="me">Zhaoyi Li</span>*, Defu Lian, Chen Ma, Linqi Song and Ying Wei</div>
  <div class="pub-links">
    <a class="pub-btn btn-paper" href="https://arxiv.org/abs/2410.07054" target="_blank">📄 Paper</a>
    <a class="pub-btn btn-code" href="https://github.com/weichuanW/llm-based-mt-via-model-editing" target="_blank">💻 Code</a>
  </div>
</div>

<!-- Paper 5 -->
<div class="pub-card">
  <div class="pub-badges">
    <span class="badge badge-conf">ACL 2024 Findings</span>
  </div>
  <div class="pub-title">Understanding and Patching Compositional Reasoning in LLMs</div>
  <div class="pub-authors"><span class="me">Zhaoyi Li</span>, Gangwei Jiang, Hong Xie, Linqi Song, Defu Lian and Ying Wei</div>
  <div class="pub-links">
    <a class="pub-btn btn-paper" href="https://arxiv.org/abs/2402.14328" target="_blank">📄 Paper</a>
    <a class="pub-btn btn-code" href="https://github.com/Zhaoyi-Li21/creme" target="_blank">💻 Code</a>
    <a class="pub-btn btn-blog" href="https://zhuanlan.zhihu.com/p/684626522" target="_blank">📝 Blog (中文)</a>
  </div>
</div>

<!-- Paper 6 -->
<div class="pub-card">
  <div class="pub-badges">
    <span class="badge badge-conf">ACL 2024</span>
  </div>
  <div class="pub-title">Benchmarking and Improving Compositional Generalization of Multi-aspect Controllable Text Generation</div>
  <div class="pub-authors">Tianqi Zhong*, <span class="me">Zhaoyi Li</span>*, Quan Wang, Linqi Song, Ying Wei, Defu Lian and Zhendong Mao</div>
  <div class="pub-links">
    <a class="pub-btn btn-paper" href="https://arxiv.org/pdf/2404.04232" target="_blank">📄 Paper</a>
    <a class="pub-btn btn-code" href="https://github.com/tqzhong/CG4MCTG" target="_blank">💻 Code</a>
  </div>
</div>

<!-- Paper 7 -->
<div class="pub-card">
  <div class="pub-badges">
    <span class="badge badge-conf">ACL 2023 Oral Presentation</span>
  </div>
  <div class="pub-title">Learning to Substitute Spans towards Improving Compositional Generalization</div>
  <div class="pub-authors"><span class="me">Zhaoyi Li</span>, Ying Wei and Defu Lian</div>
  <div class="pub-links">
    <a class="pub-btn btn-paper" href="https://aclanthology.org/2023.acl-long.157/" target="_blank">📄 Paper</a>
    <a class="pub-btn btn-code" href="https://github.com/Zhaoyi-Li21/Compgen_l2s2" target="_blank">💻 Code</a>
  </div>
</div>


# 🏆 Honors and Awards
- *2026.08* COLM 2026 Travel Grant.
- *2026.05* ICML 2026 Gold Reviewer.
- *2026.01* "DeChuang" USTC Scholarship for Overseas Visits for Excellent PhD Students.
- *2024.10* China National Scholarship, *USTC, Graduate Students*.
- *2022 ～ 2024* First prize, *USTC Graduate Student Academic Scholarship*.
- *2022.06* Honored as *The Outstanding Bachelor Graduate of USTC*.
- *2022.04* *[YuanQing](https://en.wikipedia.org/wiki/Yang_Yuanqing)* (CEO of [Lenovo](https://www.lenovo.com/ch/en/) Co.) Research Student Scholarship.
- *2020* First prize, *The 20th USTC RoboGame*, Competition Group.
- *2019 ～ 2022* First prize, *USTC Excellent Undergraduate Scholarship*.
- *2019* *USTC Ms.[XIA Peisu](https://en.wikipedia.org/wiki/Xia_Peisu) Scholarship* for Excellent Undergraduates of CS Major.
- *2017.10* First prize, [National (Senior) High School Mathematical Competition of China](https://www.cms.org.cn/en/Home/comp/comp/12.html).
- *2014.5* First prize, [National (Junior) High School Mathematical Competition of China](https://www.cms.org.cn/en/Home/comp/comp/13.html).
   
# 📖 Educations
- *2023.09 - now*, PhD student, Department of Computer Science, City University of Hong Kong. 
- *2022.09 - now*, PhD student, School of Computer Science and Technology, University of Science and Technology of China. 
- *2018.09 - 2022.07*, Undergraduate, School of Computer Science and Technology, University of Science and Technology of China. 

# 💻 Internships
- *2025.12 ~ present*, [Meituan](https://www.meituan.com/en-US/about-us) <img src='../images/meituan.png' style='width: 6em;'>, [LongCat LLM Team](https://huggingface.co/meituan-longcat) <img src='../images/longcat.png' style='width: 6em;'>, Beijing, China.
- *2021.05 - 2021.09*, [Summer Research Internship Programm](https://www.cs.hku.hk/rintern/), Hong Kong University.

# 🎖 Services
- Invited Reviewer:
  - Conference: ARR (2023, 2024, 2025, 2026), NeurIPS (2024,2025), ICLR (2025,2026), ICML (2025,2026), COLM 2026.
  - Workshop: AIM-FM 2024, Compositional Learning 2024, ACL SRW 2025, TrustKDD 2025.
  - Journal: TMLR, TALSP.
- Teaching Assistant:
  - USTC, [01112701 Data Structures and Algorithms](https://icourse.club/course/20657/), 2021 Fall
  - CityU, [CS5481 Data Engineering](https://www.cityu.edu.hk/catalogue/pg/202324/course/CS5481.htm), 2023 Fall
  - CityU, [CS1302 Introduction to Computer Programming](https://www.cityu.edu.hk/catalogue/ug/202021/course/CS1302.htm), 2024 Spring
  - USTC, [AI2501 Mathematical Principles and Algorithms of AI](https://ustc-ai-sgy.github.io/), 2025 Spring

# 🐈‍⬛ Special Links
- Here is the link to the homepage of my girlfriend: [Ranran Shen](https://ranran-shen.github.io/).
