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

Hi:wave:, I am Zhaoyi (Joey) Li, a computer science Ph.D. student at [University of Science and Technology of China](https://en.ustc.edu.cn/) and [City University of Hong Kong](https://www.cityu.edu.hk/), co-adviced by Dr. [Ying Wei](https://wei-ying.net/), Dr. [Defu Lian](https://scholar.google.com.hk/citations?user=QW0ad4sAAAAJ&hl=en) and Dr. [Linqi Song](https://sites.google.com/site/aisquaredlab/about-us/linqi).
Previously, I got my Bachelor degree in Computer Science and Technology at University of Science and Technology of China in 2022.

My research goal is about building trustworthy and transparent AI models that achieve human-like reasoning and systematic generalization. Specifically, I want to make human beings and neural network systems better understand each other (i.e., high interpretability and good generalization of blackbox deep models). I currently focus on investigating the compositionality of language models, which is about the mechanism that language models decompose complex questions and concepts into primitive ones and re-compose them step-by-step to grasp the complex semantic meaning. I am super curious about whether the end-to-end trained large-scale deep models are able to grok human-like reasoning skills or not and how to demonstrate it both empirically and theoretically. I would love to discuss on related topics should anyone is interested (always feel free to drop me an email: lizhaoyi777\[AT\]mail.ustc.edu.cn)!


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Two paper were accepted by ICLR 2026, Congratulations to Cheng. 
- *2025.12*: I started an internship journey in [Meituan](https://www.meituan.com/en-US/about-us) <img src='../images/meituan.png' style='width: 6em;'>.
- *2025.08*: &nbsp;🎉🎉 One paper was accepted by EMNLP 2025, Congratulations to Gangwei. 
- *2025.02*: &nbsp;🎉🎉 One paper was accepted by ICLR 2025 (Oral), Congratulations to Gangwei. 
- *2024.09*: &nbsp;🎉🎉 One paper was accepted by Machine Learning Journal, Congratulations to Ruimeng. 
- *2024.09*: &nbsp;🎉🎉 One paper was accepted by EMNLP 2024, Congratulations to Weichuan. 
- *2024.05*: &nbsp;🎉🎉 Two papers were accepted by ACL 2024, Congratulations to Tianqi. 
- *2023.05*: &nbsp;🎉🎉 My first paper was accepted by ACL 2023 (Oral). 

# 📝 Selected Publications and Preprints
($\*$ indicates the co-first authorship)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/iclr_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<ins>Scaling Reasoning Hop Exposes Weaknesses: Demystifying and Improving Hop Generalization in Large Language Models</ins> (**Preprint'2025**)

**Zhaoyi Li**, Jiatong Li, Gangwei Jiang, Linqi Song, Defu Lian and Ying Wei

[**Paper**](https://openreview.net/forum?id=qK4JKOu0Gx) 
- Recent studies reveal a sharp performance drop in LLMs' reasoning hop generalization scenarios, where the required number of reasoning steps exceeds training distributions while the underlying algorithm remains unchanged. In this work, we find that erroneous predictions stem from internal competition mechanisms: certain attention heads, termed erroneous processing heads (ep heads), tip the balance by amplifying incorrect reasoning trajectories while suppressing correct ones. Notably, removing individual ep heads during inference can often restore the correct predictions. Motivated by these insights, we propose test-time correction of reasoning, a lightweight intervention method that dynamically identifies and deactivates ep heads in the reasoning process.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/arxiv2025_1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<ins>Learning to Substitute Components for Compositional Generalization</ins> (**Preprint'2025**)

**Zhaoyi Li**, Gangwei Jiang, Chenwang Wu, Ying Wei, Defu Lian and Enhong Chen

[**Paper**](https://arxiv.org/abs/2502.20834) 
- The extension paper of the ACL 2023 conference paper. We develop CompSub, LCS and LCS-ICL, a series of automated data augmentation schemes to enhance the compositional generalization capacity of language models, including small models trained from the scratch (LSTMs and Transformers), pre-trained language models (BART) and large foundation language models (LLaMA2 and LLaMA3, with in-context learning). Besides, we provide theoretical insights on the work mechanism of the proposed algorithms.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/emnlp2024_mt.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<ins>Mitigating the Language Mismatch and Repetition Issues in LLM-based Machine Translation via Model Editing</ins> (**EMNLP'2024**)

Weichuan Wang$^\*$, **Zhaoyi Li**$^\*$, Defu Lian, Chen Ma, Linqi Song and Ying Wei

[**Paper**](https://arxiv.org/abs/2410.07054) [**Code**](https://github.com/weichuanW/llm-based-mt-via-model-editing) 
- We investigate two common types of issues, Language Mismatch and Repetition, in LLM-based machine translation systems. We mitigate such issues to some extent by the refined model editing methods without hurting the general abilities of LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 Findings</div><img src='images/acl2024_new.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<ins>Understanding and Patching Compositional Reasoning in LLMs</ins> (**ACL'2024 Findings**)

**Zhaoyi Li**, Gangwei Jiang, Hong Xie, Linqi Song, Defu Lian and Ying Wei

[**Paper**](https://arxiv.org/abs/2402.14328) [**Code**](https://github.com/Zhaoyi-Li21/creme) [**Blog(in Chinese)**](https://zhuanlan.zhihu.com/p/684626522)
- We interpret the internal mechanism of compositional step-by-step reasoning on multi-hop factual knowledge inside large language models and propose a light-weight method based on model editing to patch their compositional reasoning errors.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/acl2024a.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<ins>Benchmarking and Improving Compositional Generalization of Multi-aspect Controllable Text Generation</ins> (**ACL'2024**)

Tianqi Zhong$^\*$, **Zhaoyi Li**$^\*$, Quan Wang, Linqi Song, Ying Wei, Defu Lian and Zhendong Mao

[**Paper**](https://arxiv.org/pdf/2404.04232) [**Code**](https://github.com/tqzhong/CG4MCTG)
- We propose CompMCTG, systematically unveiling the shortcoming of current multi-aspect controllable text generation methods on compositional generalization. Besides, we propose MetaMCTG, a meta-learning based training framework to improve the compositional generalization performance of current methods.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023 Oral</div><img src='images/acl2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<ins>Learning to Substitute Spans towards Improving Compositional Generalization</ins> (**ACL'2023 Oral**)

**Zhaoyi Li**, Ying Wei and Defu Lian

[**Paper**](https://aclanthology.org/2023.acl-long.157/) [**Code**](https://github.com/Zhaoyi-Li21/Compgen_l2s2)
- We propose L2S2, a adversarial learning based text data augmentation scheme to improve the compositional generalization performance of neural sequence models (including LSTMs, Transformers and Pre-trained LMs). 
</div>
</div>

# 🏆 Honors and Awards
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
- *2025.12 ~ present*, [Meituan](https://www.meituan.com/en-US/about-us) <img src='../images/meituan.png' style='width: 6em;'>, LongCat LLM Team, Beijing, China.
- *2021.05 - 2021.09*, [Summer Research Internship Programm](https://www.cs.hku.hk/rintern/), Department of Computer Science, Hong Kong University.

# 🎖 Services
- Invited Reviewer:
  - Conference: EMNLP (2023, 2025), NeurIPS (2024,2025), ICLR (2025,2026), ICML 2025.
  - Workshop: AIM-FM 2024, Compositional Learning 2024, ACL SRW 2025, TrustKDD 2025.
  - Journal: TMLR, TALSP.
- Teaching Assistant:
  - USTC, [01112701 Data Structures and Algorithms](https://icourse.club/course/20657/), 2021 Fall
  - CityU, [CS5481 Data Engineering](https://www.cityu.edu.hk/catalogue/pg/202324/course/CS5481.htm), 2023 Fall
  - CityU, [CS1302 Introduction to Computer Programming](https://www.cityu.edu.hk/catalogue/ug/202021/course/CS1302.htm), 2024 Spring
  - USTC, [AI2501 Mathematical Principles and Algorithms of AI](https://ustc-ai-sgy.github.io/), 2025 Spring

# 🐈‍⬛ Special Links
- Here is the link to the homepage of my girlfriend: [Ranran Shen](https://ranran-shen.github.io/).
