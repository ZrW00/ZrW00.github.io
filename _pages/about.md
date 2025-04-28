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

- I am a third-year Ph.D. candidate at <span style="color:purple">**the School of Cyber Science and Engineering, Shanghai Jiao Tong University**</span>, advised by <span style="color:purple">**Prof. Gongshen Liu**</span> and <span style="color:purple">**Asst. Prof. Zhuosheng Zhang**</span>. 
- I got my B.S. degree from of Cyber Science and Engineering, Wuhan University in 2022.
- My general research interest lies in <span style="color:purple">**Large Language Model Powered Agents**</span> and <span style="color:purple">**Security of Large Language Models**(Backdoor)</span>.
- **Call for Collaboration**: If you're a Ph.D./Master/Bachelor student and interested in working with me, feel free to email me. 欢迎对我的研究感兴趣的同学邮件/微信联系我合作，尤其欢迎计划选择刘功申/张倬胜教授作为导师的本科生/硕士生。


<span class='anchor' id='#-news'></span>

# 🔥 News
- *2025.02.26*: &nbsp;One Paper has been published at TNNLS 🎉🎉. 
- *2024.12.25*: &nbsp;One Paper has been accepted at Journal of Cyber Security 🎉🎉. 
- *2024.12.15*: &nbsp;One Paper has been accepted at NAACL 2025 🎉🎉. 
- *2024.12.01*: &nbsp;One Paper has been accepted at COLING 2025 🎉🎉. 
- *2024.08.10*: &nbsp;One Paper has been published at ACL 2024 🎉🎉. 

<span class='anchor' id='-publications'></span>

# 📝 Publications 

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

<span class='anchor' id='-honors-and-awards'></span>

# 🎖 Honors and Awards
- *2024.12* The Shanghai Jiao Tong
University First-Class Cybersecurity Scholarship.
- *2023.10* The Shanghai Jiao Tong University Excellent Student Award.
- *2022.06* Excellent Bachelor's Thesis of Wuhan University.
- *2022.05* Outstanding Graduates of Wuhan University.
- *2021.08* The
Second Place Winner Award of the 14th National College Student Information Security Contest
(CISCN2021).
- *2021* The Meritorious Winner in the Mathematical Contest in Modeling (MCM).


<span class='anchor' id='-educations'></span>

# 📖 Educations
- *2022.09 - (now)*, Shanghai Jiao Tong University, Ph.D. - SCHOOL OF CYBER SCIENCE AND ENGINEERING.
- *2018.09 - 2022.06*, Wuhan University, Bachelor of Engineering - SCHOOL OF CYBER SCIENCE AND ENGINEERING.

<span class='anchor' id='-academic-service'></span>

# 🎓 Academic Service
- Conference Reviewer: ACL ARR 2024, NAACL ARR 2025, IJCNN 2025, ACL ARR 2025.