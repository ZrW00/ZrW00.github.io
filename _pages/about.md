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

# 🙋‍♂️ About Me

- I am a four-year Ph.D. candidate at <span style="color:purple">**the School of Cyber Science and Engineering, Shanghai Jiao Tong University**</span>, advised by <span style="color:purple">**[Prof. Gongshen Liu](https://www.cs.sjtu.edu.cn/jiaoshiml/liugongshen.html)**</span> and <span style="color:purple">**[Asst. Prof. Zhuosheng Zhang](https://bcmi.sjtu.edu.cn/home/zhangzs/)**</span>. 
- Currently, I am also supervised by <span style="color:purple">**[Professor Wynne Hsu](https://www.comp.nus.edu.sg/~whsu/)**</span>, <span style="color:purple">**[Professor Lee Mong Li](https://www.comp.nus.edu.sg/~leeml/)**</span>, and <span style="color:purple">**[Senior Research Fellow Hao Fei](https://haofei.vip/#)**</span> at School of Computing, National University of Singapore (NUS).
- I received my B.S. degree from of Cyber Science and Engineering, Wuhan University in 2022.
- My general research interest lies in <span style="color:purple">**Large Language Model Powered Agents**</span> and <span style="color:purple">**Security of Large Language Models**(Backdoor)</span>.
- **Call for Collaboration**: If you're a Ph.D./Master/Bachelor student and interested in working with me, feel free to email me. 欢迎对我的研究感兴趣的同学邮件/微信联系我合作，尤其欢迎计划选择刘功申/张倬胜教授作为导师的本科生/硕士生。


<span class='anchor' id='#-news'></span>

# 🔥 News
- *2025.11.08*: &nbsp;One Paper has been accepted at AAAI 2026 🎉🎉. 
- *2025.08.22*: &nbsp;One Paper has been accepted at EMNLP 2025 🎉🎉. 
- *2025.07.24*: &nbsp;One Paper has been accepted at ICCV 2025 🎉🎉. 
- *2025.05.15*: &nbsp;One Paper has been accepted at ACL 2025 🎉🎉. 
- *2025.02.26*: &nbsp;One Paper has been published at TNNLS 🎉🎉. 
- *2024.12.25*: &nbsp;One Paper has been accepted at Journal of Cyber Security 🎉🎉. 
- *2024.12.15*: &nbsp;One Paper has been accepted at NAACL 2025 🎉🎉. 
- *2024.12.01*: &nbsp;One Paper has been accepted at COLING 2025 🎉🎉. 
- *2024.08.10*: &nbsp;One Paper has been published at ACL 2024 🎉🎉. 

<span class='anchor' id='-publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/AAAI2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GEM: Gaussian Embedding Modeling for Out-of-Distribution Detection in GUI Agents](https://arxiv.org/abs/2505.12842)

Zheng Wu, Pengzhou Cheng, **Zongru Wu**, Lingzhong Dong, Zhuosheng Zhang 

-  In this work, we observe that the in-distribution input semantic space of GUI agents exhibits a clustering pattern with respect to the distance from the centroid. Based on the finding, we propose GEM, a novel method based on fitting a Gaussian mixture model over input embedding distances extracted from the GUI Agent that reflect its capability boundary. 
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/EMNLP2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents](https://aclanthology.org/2025.findings-emnlp.411/)

Pengzhou Cheng, Haowen Hu, Zheng Wu, **Zongru Wu**, Tianjie Ju, Daizong Ding, Zhuosheng Zhang, Gongshen Liu 

- We propose AgentGhost—a stealthy and effective red-teaming backdoor attack framework, which reveals that GUI agents powered by MLLMs are vulnerable to backdoor attacks induced by interaction-level triggers. AgentGhost achieves 99.7% attack success with only 1% utility degradation, while our tailored defense reduces the attack success rate to 22.1%.
</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/ICCV2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Can Knowledge be Transferred from Unimodal to Multimodal? Investigating the Transitivity of Multimodal Knowledge Editing](https://iccv.thecvf.com/virtual/2025/poster/230)

Lingyong Fang, Xinzhong Wang, Depeng Wang, **Zongru Wu**, Ya Guo, Huijia Zhu, Zhuosheng Zhang, Gongshen Liu

- Multimodal Large Language Models (MLLMs) contain a substantial amount of factual knowledge, which may become outdated or inaccurate over time. Consequently, various knowledge editing techniques have been proposed to update the knowledge encoded within these models. Previous approaches maintain modality consistency during both the editing and testing phases. However, in practical applications, it is desirable for knowledge to be transferable across different modalities, which can enhance the robustness of knowledge editing and potentially allow for cost-effective editing of multimodal knowledge using textual information. To address this, we introduce the concept of Transitivity of Multimodal Knowledge Editing (TMKE) and design corresponding evaluation criteria. Subsequently, we construct a corresponding TMKE Benchmark through an automated pipeline. We evaluate three MLLMs and five knowledge editing methods, uncovering limitations in the current models and methods concerning transitivity. Additionally, we analyze the intrinsic representations of the model during the editing process based on Knowledge Neurons to interpret the experimental phenomena.
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/ACL2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OS-Kairos: Adaptive Interaction for MLLM-Powered GUI Agents](https://aclanthology.org/2025.findings-acl.348/)

Pengzhou Cheng, Zheng Wu, **Zongru Wu**, Aston Zhang, Zhuosheng Zhang, Gongshen Liu

- By predicting confidence levels at each interaction step, we are releasing an adaptive GUI agent (OS-Kairos) that alleviates the over-execution of autonomous GUI agents, and significantly improves task success rates in complex scenarios.
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/queryInferenceDemo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Smoothing Grounding and Reasoning for MLLM-Powered GUI Agents with Query-Oriented Pivot Tasks](https://arxiv.org/abs/2503.00401)

**Zongru Wu**, Pengzhou Cheng, Zheng Wu, Tianjie Ju, Zhuosheng Zhang, Gongshen Liu

- We propose a pivot task name query inference to smooth coordinate-oriented grounding and action-oriented reasoning, enhancing the comprehension of user intent and imporoving the performance of MLLM-powered GUI agents in resource-constrained scenarios.
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS</div><img src='images/TNNLS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Backdoor Attacks and Countermeasures in Natural Language Processing Models: A Comprehensive Security Review](https://ieeexplore.ieee.org/document/10905032)

Pengzhou Cheng, **Zongru Wu**, Wei Du, Haodong Zhao, Wei Lu, Gongshen Liu

- We provide the natural language processing (NLP) community with a timely review of backdoor attacks and countermeasures. 
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2025</div><img src='images/NAACL2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SynGhost: Invisible and Universal Task-agnostic Backdoor Attack via Syntactic Transfer](https://openreview.net/forum?id=C4N3PLwOwM&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3Daclweb.org%2FNAACL%2F2025%2FConference%2FAuthors%23your-submissions))

Pengzhou Cheng, Wei Du, **Zongru Wu**, Fengwei Zhang, Libo Chen, Zhuosheng Zhang, Gongshen Liu

- We propose maxEntropy, an entropy-based poisoning filter that accurately detects existing task-agnostic backdoors. To further expose the vulnerabilities in PLMs, we propose SynGhost, an invisible and universal task-agnostic backdoor.
</div>
</div> 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2025</div><img src='images/COLING2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Gracefully Filtering Backdoor Samples for Generative Large Language Models without Retraining](https://aclanthology.org/2025.coling-main.220/)

**Zongru Wu**, Pengzhou Cheng, Lingyong Fang, Zhuosheng Zhang, Gongshen Liu

- We reveal a distinct separation between the gradients of backdoor and clean samples in the frequency space. Based on this, we propose Gradient Clustering in the Frequency Space for Backdoor Sample Filtering (GraCeFul), which leverages sample-wise gradients in the frequency space to effectively identify backdoor samples without requiring retraining LLMs.
</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/ACL2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Acquiring Clean Language Models from Backdoor Poisoned Datasets by Downscaling Frequency Space](https://aclanthology.org/2024.acl-long.441/)

**Zongru Wu**, Zhuosheng Zhang, Pengzhou Cheng, Gongshen Liu 

- We conduct Fourier Analysis to the clean and backdoor mapping and reveal the low-frequency bias on backdoor mapping, which results in the faster convergence of backdoor mapping. Based on this phenomenon, we propose a novel approach that encourages language models to prioritize clean mapping by downscaling in the frequency space, thus efficiently reducing the average success rate of backdoor attacks.
</div>
</div> 

<span class='anchor' id='-tutorials-and-contributions'></span>

# 🛠️ Tutorials and Contributions
- Participating: <span style="color:purple">**《大模型开发全流程》Course Series**</span> [Link](https://www.hiascend.com/edu/growth/lm-development#classification-floor-1).
- Participating: <span style="color:purple">**Dive into LLMs《动手学大模型》Course Series**</span> <a class="github-button" href="https://github.com/Lordog/dive-into-llms" data-icon="octicon-star" data-show-count="true" aria-label="Star dive-into-llms on GitHub">dive-into-llms</a>

<span class='anchor' id='-honors-and-awards'></span>

# 🎖 Honors and Awards
- *2024.12* The Shanghai Jiao Tong University First-Class Cybersecurity Scholarship.
- *2023.10* The Shanghai Jiao Tong University Excellent Student Award.
- *2022.06* Excellent Bachelor's Thesis of Wuhan University.
- *2022.05* Outstanding Graduates of Wuhan University.
- *2021.08* The Second Place Winner Award of the 14th National College Student Information Security Contest
(CISCN2021).
- *2021* The Meritorious Winner in the Mathematical Contest in Modeling (MCM).


<span class='anchor' id='-educations'></span>

# 📖 Educations
- *2025.10 - (now)*, National University of Singapore, visiting PhD Student. -  SCHOOL OF COMPUTING (SoC).
- *2022.09 - (now)*, Shanghai Jiao Tong University, Ph.D. - SCHOOL OF CYBER SCIENCE AND ENGINEERING.
- *2018.09 - 2022.06*, Wuhan University, Bachelor of Engineering - SCHOOL OF CYBER SCIENCE AND ENGINEERING.

<span class='anchor' id='-academic-service'></span>

# 🎓 Academic Service
- Conference Reviewer: ACL ARR 2024, NAACL ARR 2025, IJCNN 2025, ACL ARR 2025, EMNLP ARR 2025, CHI 2026, ICLR 2026.
- Journal Reviewer: Pattern Recognition, IJHCI, TALLIP.
- Teaching Assistant: "Operating System", Spring 2024, Spring 2025.