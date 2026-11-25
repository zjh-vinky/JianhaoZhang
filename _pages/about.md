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

**I am currently seeking industry positions and Ph.D. opportunities in large language models. Please feel free to contact me via email.**



# 🔥 News
- *2026.09*: &nbsp;🎉🎉 NADS: Navigator-Guided Data Selection for Mitigating Catastrophic Forgetting in Fine-Tuning is accepted by NeurIPS 2026.
- *2026.08*: &nbsp;🎉🎉 LLM Fine-tuning with an Unconstrained Fine-tuned Teacher is accepted by EMNLP 2026.
- *2026.08*: &nbsp;🎉🎉 Two to Tango: Coupled Task-Reference Selection for Safe LLM Fine-tuning is accepted by EMNLP 2026.
- *2026.04*: &nbsp;🎉🎉 CAKE: Causal-Guided Adaptive Knowledge Editing for LLMs by ACL 2026.
- *2026.04*: &nbsp;🎉🎉 AlphaEdit^+: Model Editing in the Presence of Conflicting and Inconsistent Knowledge by ACL 2026.
- *2026.01*: &nbsp;🎉🎉 Robust LLM Unlearning via Post Judgment and Multi-round Thinking is accepted by ICLR 2026.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2016</div><img src='images/nads.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NADS: Navigator-Guided Data Selection for Mitigating Catastrophic Forgetting in Fine-Tuning](https://arxiv.org/pdf/2610.25751)

**Jianhao Zhang**, Ou Wu, Yi Du^✝

[**Project**](https://github.com/zjh-vinky/NADS) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Developed **NADS**, a framework for mitigating catastrophic forgetting in LLM fine-tuning without access to pre-training data. Leveraged navigator-induced predictive divergence to identify forgetting-aware synthetic data, and integrated utility-diversity selection with selective knowledge distillation to preserve general capabilities while improving target-task adaptation and reducing selection overhead.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2016</div><img src='images/uft.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[LLM Fine-tuning with an Unconstrained Fine-tuned Teacher is accepted](https://aclanthology.org/2026.emnlp-main.1310/)

**Jianhao Zhang**, Ou Wu^✝, Yi Du

[**Project**](https://github.com/zjh-vinky/UFT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **UFT**, a value-guided LLM fine-tuning framework that shifts the teacher's role from knowledge transfer to target-sample value discovery. Constructed dual teachers using the source model and an unconstrained fine-tuned model, and quantified preservation-aware sample utility through behavioral divergence and teacher uncertainty. Integrated utility-weighted task learning with confidence-adaptive dual-teacher distillation to improve target-task adaptation while retaining prior capabilities.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2016</div><img src='images/uft.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Two to Tango: Coupled Task-Reference Selection for Safe LLM Fine-tuning](https://aclanthology.org/2026.emnlp-main.862/)

Xinrui Chen, **Jianhao Zhang**, Ou Wu^✝, Di Gao

[**Project**](https://github.com/ChnIRuI/DualSelect) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **DualSelect**, a coupled task-reference selection framework for safety-aware LLM fine-tuning. Developed a task-conditioned reference selection strategy to identify safety constraints exposed by downstream updates, and jointly selected compatible task samples under a unified minimax objective. Integrated entropy-regularized scoring, lazy reference refresh, and gradient correction to preserve safety alignment while maintaining downstream task utility.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2016</div><img src='images/cake.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[CAKE: Causal-Guided Adaptive Knowledge Editing for LLMs](https://aclanthology.org/2026.acl-long.918/)

Shuxin Li^*, **Jianhao Zhang^{*,✝}**

[**Project**](https://github.com/zjh-vinky/CAKE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **CAKE (Causal-Guided Adaptive Knowledge Editing)**, a causal-guided framework for collaborative multi-layer knowledge editing in LLMs. Introduced a generalized Locate-Weight-Assign-Edit (LWAE) paradigm, leveraging causal tracing scores to identify critical editing layers and adaptively allocate editing residuals according to layer-wise causal efficacy. Formulated residual allocation as a constrained quadratic optimization problem and established a generalized weight shift error bound to mitigate recursive editing errors.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2016</div><img src='images/alphaedit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AlphaEdit+: Model Editing in the Presence of Conflicting and Inconsistent Knowledge](https://aclanthology.org/2026.findings-acl.728/)

Qing Liu^*, **Jianhao Zhang^***, Ou Wu^✝, Michael Ng, Yi Du

[**Project**](https://github.com/zjh-vinky/AlphaEdit_plus) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **AlphaEdit+**, a robust knowledge editing framework for LLMs under conflicting and inconsistent knowledge. Introduced adaptive null-space relaxation through learnable matrix perturbations to resolve conflicts between new and preserved knowledge, and incorporated weighted historical constraints to mitigate interference from previous edits. Further developed a value smoothing algorithm to handle severe knowledge inconsistencies and improve editing robustness while maintaining model coherence.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2016</div><img src='images/port.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust LLM Unlearning via Post Judgment and Multi-round Thinking](https://iclr.cc/virtual/2026/poster/10010525)

Xinrui Chen, Xu Cao, **Jianhao Zhang**, Pinlong Zhao, Di Gao, Ou Wu^✝

[**Project**](https://github.com/ChnIRuI/PoRT_LLM_Unlearning) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed **PoRT**, a robust LLM unlearning framework designed to defend against adversarial attacks without modifying model parameters. Introduced in-context prompt cleaning to neutralize adversarial perturbations and decompose complex queries, followed by confidence-aware post-judgment that jointly evaluates cleaned queries and model responses. Further developed selective multi-round thinking to trigger adaptive self-correction for non-compliant or low-confidence outputs, improving unlearning robustness while preserving general model utility.
</div>
</div>


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
