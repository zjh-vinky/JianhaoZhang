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

I am currently a master's student at the Hangzhou Institute for Advanced Study, University of Chinese Academy of Sciences, and received my bachelor's degree from Hunan University of Arts and Science.

My research interests include LLM post-training, agentic reinforcement learning, and recursive self-improvement (RSI), with a focus on developing more capable, reliable, and self-improving large language models.

I have published 6 papers at the top international AI conferences such as NeurIPS, ICLR, ACL, and EMNLP. I also interned at ByteDance from June to October 2026.

**I am currently seeking industry positions and Ph.D. opportunities in large language models. Please feel free to contact me via email ([zhangjianhao24@mails.ucas.ac.cn](mailto:zhangjianhao24@mails.ucas.ac.cn), [zhangjianhao0205@gmail.com](mailto:zhangjianhao0205@gmail.com)).**



# 🔥 News
- *2026.09*: &nbsp;🎉🎉 NADS: Navigator-Guided Data Selection for Mitigating Catastrophic Forgetting in Fine-Tuning is accepted by NeurIPS 2026.
- *2026.08*: &nbsp;🎉🎉 LLM Fine-tuning with an Unconstrained Fine-tuned Teacher is accepted by EMNLP 2026.
- *2026.08*: &nbsp;🎉🎉 Two to Tango: Coupled Task-Reference Selection for Safe LLM Fine-tuning is accepted by EMNLP 2026.
- *2026.04*: &nbsp;🎉🎉 CAKE: Causal-Guided Adaptive Knowledge Editing for LLMs by ACL 2026.
- *2026.04*: &nbsp;🎉🎉 AlphaEdit</sup>+</sup>: Model Editing in the Presence of Conflicting and Inconsistent Knowledge by ACL 2026.
- *2026.01*: &nbsp;🎉🎉 Robust LLM Unlearning via Post Judgment and Multi-round Thinking is accepted by ICLR 2026.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/nads.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NADS: Navigator-Guided Data Selection for Mitigating Catastrophic Forgetting in Fine-Tuning](https://arxiv.org/pdf/2610.25751)

**Jianhao Zhang**, Ou Wu, Yi Du<sup>†</sup>

[**Project**](https://github.com/zjh-vinky/NADS) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **NADS**, a framework for mitigating catastrophic forgetting in LLM fine-tuning through navigator-guided data selection and utility-diversity-aware knowledge distillation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026</div><img src='images/uft.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[LLM Fine-tuning with an Unconstrained Fine-tuned Teacher is accepted](https://aclanthology.org/2026.emnlp-main.1310/)

**Jianhao Zhang**, Ou Wu<sup>†</sup>, Yi Du

[**Project**](https://github.com/zjh-vinky/UFT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **UFT**, introducing dual-teacher value estimation through behavioral divergence and teacher uncertainty, combined with utility-weighted learning and adaptive knowledge distillation to balance task adaptation and capability preservation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026</div><img src='images/dualselect.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Two to Tango: Coupled Task-Reference Selection for Safe LLM Fine-tuning](https://aclanthology.org/2026.emnlp-main.862/)

Xinrui Chen, **Jianhao Zhang**, Ou Wu<sup>†</sup>, Di Gao

[**Project**](https://github.com/ChnIRuI/DualSelect) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **DualSelect**, jointly optimizing task-data and safety-reference selection through task-conditioned reference modeling and a unified minimax objective, integrating entropy-regularized scoring and gradient correction to balance safety alignment and task utility.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/cake.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[CAKE: Causal-Guided Adaptive Knowledge Editing for LLMs](https://aclanthology.org/2026.acl-long.918/)

Shuxin Li<sup>*</sup>, **Jianhao Zhang<sup>*,✝</sup>**

[**Project**](https://github.com/zjh-vinky/CAKE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **CAKE**, a causal-guided multi-layer knowledge editing framework, introducing the LWAE paradigm to identify critical editing layers and adaptively allocate editing residuals based on layer-wise causal efficacy.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/alphaedit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AlphaEdit+: Model Editing in the Presence of Conflicting and Inconsistent Knowledge](https://aclanthology.org/2026.findings-acl.728/)

Qing Liu<sup>*</sup>, **Jianhao Zhang<sup>*</sup>**, Ou Wu<sup>†</sup>, Michael Ng, Yi Du

[**Project**](https://github.com/zjh-vinky/AlphaEdit_plus) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **AlphaEdit+**, a robust knowledge editing framework that integrates adaptive null-space relaxation, weighted historical constraints, and value smoothing to resolve conflicting and inconsistent knowledge while improving editing robustness and preserving model coherence.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/port.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust LLM Unlearning via Post Judgment and Multi-round Thinking](https://iclr.cc/virtual/2026/poster/10010525)

Xinrui Chen, Xu Cao, **Jianhao Zhang**, Pinlong Zhao, Di Gao, Ou Wu<sup>†</sup>

[**Project**](https://github.com/ChnIRuI/PoRT_LLM_Unlearning) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **PoRT**, a parameter-free LLM unlearning framework integrating in-context prompt cleaning, confidence-aware post-judgment, and selective multi-round thinking to defend against adversarial attacks and improve unlearning robustness while preserving general model utility.
</div>
</div>


# 🎖 Honors and Awards
- *2026.10* National Scholarship (Master). 
- *2022.10* National Scholarship (Undergraduate). 

# 📖 Educations
- *2024.09 - 2027.06 (Expected)*, Master, University of Chinese Academy of Sciences, Hangzhou.
- *2019.09 - 2023.06*, Undergraduate, Hunan University of Arts and Science, Changde.


# 💻 Internships
- *2026.06 - 2026.10*, ByteDance, GMPT AdsCore, Shanghai.
