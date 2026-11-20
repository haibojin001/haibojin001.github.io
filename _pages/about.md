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

I am Haibo Jin, a PhD student in Information Sciences at the University of Illinois Urbana-Champaign, advised by Prof. [Haohan Wang](https://haohanwang.github.io/) in the [DREAM Lab](https://dream.ischool.illinois.edu/).

My research focuses on:

- **Trustworthy AI**: safety evaluation and red-teaming of large language models.
- **Agentic AI**: LLM-based multi-agent systems built from reusable primitives.
- **Generative engine optimization**: how LLM-based search ranks and recommends content.
- **Tools for real-world impact**: [Heelo](https://www.heelo.dev/) and [TopCited AI](https://topcited.ai/), platforms that put these methods in users' hands.

If you are seeking any form of academic cooperation, please feel free to email me at [haibojin001@gmail.com](mailto:haibojin001@gmail.com).

<span class='anchor' id='news'></span>
# 🔥 News

<div class="news-box" markdown="0">
<ul class="news-list">
  <li><time>Oct. 2026</time><span>Our follow-up work on GUARD is accepted to Transactions on Machine Learning Research (TMLR).</span></li>
  <li><time>Oct. 2026</time><span>Two new first-author preprints: <a href="https://arxiv.org/abs/2610.09079" target="_blank" rel="noopener">LEGO</a> (large-scale repository engineering via reusable code primitives) and <a href="https://arxiv.org/abs/2610.07832" target="_blank" rel="noopener">HERMES</a> (harness engineering via modular dev-primitives).</span></li>
  <li><time>June 2026</time><span>We released <a href="https://topcited.ai/" target="_blank" rel="noopener">TopCited AI</a>, a generative engine optimization (GEO) platform that helps brands get recommended and cited by AI-powered search engines and large language models.</span></li>
  <li><time>June 2026</time><span>We released <a href="https://www.heelo.dev/" target="_blank" rel="noopener">Heelo</a>, an execution layer for AI agents: a unified API that lets agents handle real-world tasks such as placing orders, booking travel, sending outreach, and posting to social media.</span></li>
  <li><time>May 2026</time><span>Received the ICML 2026 Gold Reviewer Award, placing among the top reviewers of the conference.</span></li>
  <li><time>May 2026</time><span>Started as an Applied Scientist Intern at Amazon Prime Video.</span></li>
  <li><time>Feb. 2026</time><span>Agent Primitives: Reusable Latent Building Blocks for Multi-Agent Systems is accepted to ICML 2026.</span></li>
  <li><time>Oct. 2025</time><span>Welcome to visit Neurips'25 <a href="https://llm-inductive-abilities.vercel.app/" target="_blank" rel="noopener">Paper</a> website.</span></li>
  <li><time>Sept. 2025</time><span>Evaluating the Inductive Abilities of Large Language Models: Why Chain-of-Thought Reasoning Sometimes Hurts More Than Helps is accepted by NeurIPS'25.</span></li>
  <li><time>Aug. 2025</time><span>Exploring the Vulnerability of the Content Moderation Guardrail in Large Language Models via Intent Manipulation is accepted by EMNLP'25.</span></li>
  <li><time>July 2025</time><span>Welcome to visit <a href="https://llm-revolve.netlify.app/" target="_blank" rel="noopener">Revolve</a> website.</span></li>
  <li><time>June 2025</time><span>Revolve: Optimizing AI Systems by Tracking Response Evolution in Textual Optimization is accepted by ICML'25.</span></li>
  <li><time>Dec. 2024</time><span>Welcome to our survey paper: Advances and Challenges in Foundation Agents: From Brain-Inspired Intelligence to Evolutionary, Collaborative, and Safe Systems.</span></li>
  <li><time>Nov. 2024</time><span>Welcome to visit <a href="https://llm-moderation-attack.vercel.app/" target="_blank" rel="noopener">JAM</a> website.</span></li>
  <li><time>Sept. 2024</time><span>Jailbreaking Large Language Models Against Moderation Guardrails via Cipher Characters is accepted by NeurIPS'24.</span></li>
  <li><time>Aug. 2024</time><span>Fight Perturbations with Perturbations: Defending Adversarial Attacks via Neuron Influence is accepted by IEEE Transactions on Dependable and Secure Computing (TDSC).</span></li>
  <li><time>July 2024</time><span>CatchBackdoor: Backdoor Detection via Critical Trojan Neural Path Fuzzing is accepted by ECCV'24.</span></li>
  <li><time>July 2024</time><span>EditShield: Protecting Unauthorized Image Editing by Instruction-guided Diffusion Models is accepted by ECCV'24.</span></li>
  <li><time>June 2024</time><span>Welcome to visit <a href="https://chonghan-chen.com/llm-jailbreak-zoo-survey/" target="_blank" rel="noopener">JailbreakZoo</a> website.</span></li>
  <li><time>May 2024</time><span>Welcome to my <a href="https://haibojin001.github.io/" target="_blank" rel="noopener">new homepage</a>.</span></li>
  <li><time>Apr. 2024</time><span>Receive a TA/RA offer from the School of Information Sciences, University of Illinois Urbana-Champaign.</span></li>
  <li><time>Mar. 2024</time><span>Welcome to visit <a href="https://github.com/Allen-piexl/JailbreakZoo" target="_blank" rel="noopener">JailbreakZoo</a>, a dedicated repository focused on the jailbreaking of large models (LMs), encompassing both large language models (LLMs) and vision language models (VLMs).</span></li>
  <li><time>Jan. 2024</time><span>Start my trip at the University of Illinois Urbana-Champaign as a visiting scholar.</span></li>
</ul>
</div>

<span class='anchor' id='publications'></span>
# 📝 Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML'26</div><img src='images/agent-primitives-icml26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Agent Primitives: Reusable Latent Building Blocks for Multi-Agent Systems**

**Haibo Jin**, Peng Kuang, Ye Yu, Xiaopeng Yuan, Haohan Wang

The 43rd International Conference on Machine Learning (ICML'26)

[PDF](https://arxiv.org/pdf/2602.03695) / [Code](https://github.com/haibojin001/AgentPrimitives)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS'26</div><img src='images/kv-prm-neurips26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**KV-PRM: Efficient Process Reward Modeling via KV-Cache Transfer for Multi-Agent Test-Time Scaling**

Peng Kuang, **Haibo Jin**, Xiaoyu Han, Yanli Wang, Xiaopeng Yuan, Ye Yu, Kaidi Xu, Haohan Wang

The 40th Annual Conference on Neural Information Processing Systems (NeurIPS'26)

[PDF](https://arxiv.org/pdf/2607.09153)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL'26</div><img src='images/cort-acl26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Learning to Conceal Risk: Controllable Multi-turn Red Teaming for LLMs in the Financial Domain**

Gang Cheng, **Haibo Jin**, Wenbin Zhang, Haohan Wang, Jun Zhuang

The 64th Annual Meeting of the Association for Computational Linguistics (ACL'26)

[PDF](https://arxiv.org/pdf/2509.10546) / [Code](https://github.com/gcheng128/CoRT)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR</div><img src='images/guard-tmlr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GUARD: Guideline Upholding Test through Adaptive Role-play and Jailbreak Diagnostics for LLMs**

**Haibo Jin**, Ruoxi Chen, Peiyan Zhang, Andy Zhou, Zelei Cheng, Haohan Wang

Transactions on Machine Learning Research (TMLR)

[PDF](https://openreview.net/pdf?id=ubIcFJcQlQ) / [arXiv](https://arxiv.org/abs/2508.20325)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EACL'26</div><img src='images/crafting-adv-eacl26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Crafting Adversarial Inputs for Large Vision-Language Models Using Black-Box Optimization**

Jiwei Guan, **Haibo Jin**, Haohan Wang

Findings of the European Chapter of the Association for Computational Linguistics (EACL'26)

[PDF](https://aclanthology.org/2026.findings-eacl.246.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EACL'26</div><img src='images/now-you-hear-me-eacl26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Now You Hear Me: Audio Narrative Attacks Against Large Audio-Language Models**

Ye Yu, **Haibo Jin**, Yaoning Yu, Jun Zhuang, Haohan Wang

The 19th Conference of the European Chapter of the Association for Computational Linguistics (EACL'26)

[PDF](https://aclanthology.org/2026.eacl-long.278.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLM'26</div><img src='images/break-me-if-you-can-colm26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Break Me If You Can: Self-Jailbreaking of Aligned LLMs via Lexical Insertion Prompting**

Devang Kulshreshtha*, Hang Su*, **Haibo Jin**, Chinmay Hegde, Haohan Wang

The Third Annual Conference on Language Modeling (COLM'26)

[PDF](https://arxiv.org/pdf/2601.02670)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS'25 Workshop</div><img src='images/premise-neurips25ws.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PREMISE: Scalable and Strategic Prompt Optimization for Efficient Mathematical Reasoning in Large Models**

Ye Yu, Yaoning Yu, **Haibo Jin**, Haohan Wang

NeurIPS 2025 Workshop on Efficient Reasoning

[PDF](https://arxiv.org/pdf/2506.10716)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS'25</div><img src='images/20830_Evaluating_the_Inductive.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**Evaluating the Inductive Abilities of Large Language Models: Why Chain-of-Thought Reasoning Sometimes Hurts More Than Helps**

**Haibo Jin**, Peiyan Zhang, Man Luo, Haohan Wang
  
The 39th Conference on Neural Information Processing Systems (NeurIPS'25)

[PDF](https://openreview.net/pdf?id=yRxX01oRIi) / [Code](https://github.com/haibojin001/llm_inductive)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP'25</div><img src='images/2025.findings-emnlp.114.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**Exploring the Vulnerability of the Content Moderation Guardrail in Large Language Models via Intent Manipulation**

Jun Zhuang, **Haibo Jin**, Ye Zhang, Zhengjian Kang, Wenbin Zhang, Gaby G Dagher, Haohan Wang
  
The 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP'25)

[PDF](https://aclanthology.org/2025.findings-emnlp.114.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML'25</div><img src='images/10240_Revolve_Optimizing_AI_Sy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**Revolve: Optimizing AI Systems by Tracking Response Evolution in Textual Optimization**

Peiyan Zhang, **Haibo Jin**, Leyang Hu, Xinnuo Li, Liying Kang, Man Luo, Yangqiu Song, Haohan Wang
  
The 42nd International Conference on Machine Learning (ICML'25)

[PDF](https://openreview.net/pdf?id=4vb9BDTIDh) / [Code](https://github.com/Peiyance/REVOLVE)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS'24</div><img src='images/Jailbreak_NIPS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**Jailbreaking Large Language Models Against Moderation Guardrails via Cipher Characters**

**Haibo Jin**, Andy Zhou, Joe D Menke, Haohan Wang
  
The 38th Conference on Neural Information Processing Systems (NeurIPS'24)

[PDF](https://arxiv.org/pdf/2405.20413) / [Code](https://github.com/Allen-piexl/llm_moderation_attack)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV'24</div><img src='images/06326.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CatchBackdoor: Backdoor Detection via Critical Trojan Neural Path Fuzzing**

**Haibo Jin**, Ruoxi Chen, Jinyin Chen, Haibin Zheng, Yang Zhang, Haohan Wang

The 18th European Conference on Computer Vision (ECCV'24)

[PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06326.pdf) / [Code](https://github.com/Allen-piexl/CatchBackdoor)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV'24</div><img src='images/07991.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**EditShield: Protecting Unauthorized Image Editing by Instruction-guided Diffusion Models**

Ruoxi Chen, **Haibo Jin**, Yixin Liu, Jinyin Chen, Haohan Wang, Lichao Sun

The 18th European Conference on Computer Vision (ECCV'24)

[PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07991.pdf) / [Code](https://github.com/Allen-piexl/Editshield)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SeT LLM@ICLR'24</div><img src='images/SetLLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GUARD: Role-playing to Generate Natural-language Jailbreakings to Test Guideline Adherence of Large Language Models**

**Haibo Jin**, Ruoxi Chen, Andy Zhou, Yang Zhang, Haohan Wang

ICLR 2024 Workshop on Secure and Trustworthy Large Language Models (SeT LLM@ICLR'24)

[PDF](https://arxiv.org/pdf/2402.03299) / [Code](https://github.com/Allen-piexl/GUARD) / [Talk](https://www.youtube.com/watch?v=Do7K1fDGSRQ) / [DOI](https://doi.org/10.48550/arXiv.2402.03299)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASE'23</div><img src='images/ASE2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CertPri: Certifiable Prioritization for Deep Neural Networks via Movement Cost in Feature Space**

Haibin Zheng, Jinyin Chen, **Haibo Jin**

The 38th IEEE/ACM International Conference on Automated Software Engineering (ASE'23)

[Paper](https://ieeexplore.ieee.org/document/10298498) / [Code](https://github.com/haibinzheng/CertPri) / [DOI](https://doi.org/10.1109/ASE56229.2023.00126)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Information Sciences'23</div><img src='images/DeepSensor23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Excitement surfeited turns to errors: Deep learning testing framework based on excitable neurons**

**Haibo Jin**, Ruoxi Chen, Haibin Zheng, Jinyin Chen, Yao Cheng, Yue Yu, Tieming Chen, Xianglong Liu 

Information Sciences, 2023, 637: 118936

[Code](https://github.com/Allen-piexl/DeepSensor/) / [DOI](https://doi.org/10.1016/j.ins.2023.118936)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Information Sciences'22</div><img src='images/ROBY22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ROBY: Evaluating the adversarial robustness of a deep model by its decision boundaries**

**Haibo Jin**, Jinyin Chen, Haibin Zheng, Zhen Wang, Jun Xiao, Shanqing Yu, Zhaoyan Ming

Information Sciences, 2022, 587: 97-122

[Code](https://github.com/Allen-piexl/ROBY) / [DOI](https://doi.org/10.1016/j.ins.2021.12.021)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TDSC'24</div><img src='images/NIP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Fight Perturbations with Perturbations: Defending Adversarial Attacks via Neuron Influence**

Ruoxi Chen, **Haibo Jin**, Haibin Zheng, Jinyin Chen, Zhenguang Liu

IEEE Transactions on Dependable and Secure Computing, 2024

[Paper](https://ieeexplore.ieee.org/document/10640242) / [Code](https://github.com/Allen-piexl/NIP-Neuron-level-Inverse-Perturbation)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Computers & Security'24</div><img src='images/advcheck23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AdvCheck: Characterizing adversarial examples via local gradient checking**

Ruoxi Chen, **Haibo Jin**, Jinyin Chen, Haibin Zheng, Shilian Zheng, Xiaoniu Yang, Xing Yang

Computers & Security, 2024, 136: 103540

[Code](https://github.com/Allen-piexl/AdvCheck) / [DOI](https://doi.org/10.1016/j.cose.2023.103540)

</div>
</div>
<span class='anchor' id='honors-and-awards'></span>

# 🎖️ Honors and Awards
- *2026.05*: &nbsp; Gold Reviewer Award, ICML 2026 (placing among the top reviewers of the conference).
- *2025.10*: &nbsp; Scholar Award, NeurIPS 2025 (Financial Assistance Program).

<span class='anchor' id='educations'></span>

# 📖 Educations
- *2025.08 - now*: &nbsp; PhD Candidate, Information Sciences, University of Illinois Urbana-Champaign, Illinois, US.

<span class='anchor' id='internships'></span>

# 💻 Internships
- *2026.05 - now*: &nbsp; Applied Scientist Intern, Amazon Prime Video.
- *2023.04 - 2025.08*: &nbsp; Visiting scholar at [DREAM Lab](https://dream.ischool.illinois.edu/), University of Illinois Urbana-Champaign, US. (Supervisor: [Haohan Wang](https://haohanwang.github.io/))

<span class='anchor' id='service'></span>

# 🔖 Service
- *2026*: &nbsp; ICML 2026, NeurIPS 2026, CVPR 2026, AAAI 2026, AAAI 2027, ICLR 2027, AISTATS 2027, KDD 2027, TMLR, IEEE T-IFS, IJHCI, LP4FM @ NeurIPS 2026
- *2025*: &nbsp; ICLR 2025, AISTATS 2025, ICML 2025, NeurIPS 2025, ResponsibleFM @ NeurIPS 2025
- *2024*: &nbsp; NeurIPS 2024, ICML 2024, WWW 2024, SeT LLM @ ICLR 2024
