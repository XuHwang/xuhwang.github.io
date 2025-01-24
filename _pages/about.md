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

I am currently a 4th-year Ph.D. student under the advisory of Prof.[Defu Lian](https://faculty.ustc.edu.cn/liandefu) in School of Computer Science and Technology, [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/). I got my B.S. degree from University of Science and Technology of China (USTC) in 2021. 

My research interest includes large language models, data mining, information retrieval, especially on recommender system. Recently my major research direction is on the LLM-driven autonomous agents. I have published several papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=fXFMb-gAAAAJ'> <strong><span id='total_cit'>300+</span></strong> google scholar citations </a> <a href='https://scholar.google.com/citations?user=fXFMb-gAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2025.01*: &nbsp;🎉🎉 Our work HyperGate for multi-domain multi-task recommendation is accepted by [WWW 2025](https://www2025.thewebconf.org/), accept rate 22.42%. 
- *2025.01*: &nbsp;🎉🎉 Our work [ToolACE](https://openreview.net/forum?id=8EB8k6DdCU) for enhancing tool-using ability of LLM is accepted by [ICLR 2025](https://iclr.cc/Conferences/2025). 
- *2024.09*: &nbsp;🎉🎉 Our framework and model ToolACE for enhancing tool-using ability of LLM is released in [arXiv](https://arxiv.org/abs/2409.00920). 
- *2024.05*: &nbsp;🎉🎉 Our work for weak exploration to strong exploitation for LLM agents is released in [arXiv](https://arxiv.org/abs/2404.07456). 
- *2024.04*: &nbsp;🎉🎉 Our method for weak exploration to strong exploitation for LLM agents is released in [arXiv](https://arxiv.org/abs/2404.07456). 
- *2024.03*: &nbsp;🎉🎉 Our demo paper for the toolkit **RecAI** for bridging LLM and Recommendation Systems is accepted by [WWW 2024](https://www2024.thewebconf.org/). The project is released in [Github](https://github.com/microsoft/RecAI). 
- *2024.02*: &nbsp;🎉🎉 Our survey for the planning ability of LLM agents is released in [arXiv](https://arxiv.org/abs/2402.02716). 
- *2024.01*: &nbsp;🎉🎉 Our work for the data-centric multi-objective recommendation *[MoRec](https://arxiv.org/abs/2310.13260)* is accepted by [WWW 2024](https://www2024.thewebconf.org/), accept rate 20.2%. 
<!-- - *2023.10*: &nbsp;🎉🎉 Our work for the data-centric multi-objective recommendation *[MoRec](https://arxiv.org/abs/2310.13260)* is released in [arXiv](https://arxiv.org/abs/2310.13260).  -->
<!-- - *2023.08*: &nbsp;🎉🎉 Our work for the LLM-augmented interactive recommendation agent *[InteRecAgent](https://arxiv.org/abs/2308.16505)* is released in [arXiv](https://arxiv.org/abs/2308.16505).  -->
<!-- - *2023.04*: &nbsp;🎉🎉 Our paper for the modularized recommender system library *[RecStudio](http://recstudio.org.cn/)* is accepted by SIGIR 2023.  -->
<!-- - *2023.01*: &nbsp;🎉🎉 Our work for jointly optimization in multi-stage recommendation *CoRR* is accepted by The Web Conference 2023.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2025</div><img src='images/hypergate.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

HyperGate: Hierarchical Perceptive Gating Network for Multi-domain Multi-task Recommendation

**Xu Huang\***, Xiaolong Chen\*, Yichao Wang, Weiwen Liu, Yang Yang, Xingmei Wang, Defu Lian and Ruiming Tang

**Project**
- A hierarchical gating network for multi-domain and multi-task recommendation.
- We propose a contrastive domain and task representation augumentation module to extract domain and task embeddings, and a hierarchical gating network to construct a domain- and
task-perceptive parameter-sharing network from the bottom up.
- The paper will be public soon.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2025</div><img src='images/toolace.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ToolACE: Winning the Points of LLM Function Calling](https://openreview.net/forum?id=8EB8k6DdCU)

Weiwen Liu\*, **Xu Huang\***, Xingshan Zeng\*, Xinlong Hao, Shuai Yu, Dexun Li, Shuai Wang, Weinan Gan, et al.

[**Project**](https://huggingface.co/Team-ACE/ToolACE-8B) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:YOwf2qJgpHMC'></span></strong>
- A data synthetic framework tailored for enhancing tool-using ability of LLMs.
- [Model](https://huggingface.co/Team-ACE/ToolACE-8B); [Dataset](https://huggingface.co/datasets/Team-ACE/ToolACE)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/wese.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WESE: Weak Exploration to Strong Exploitation for LLM Agents](https://arxiv.org/abs/2404.07456)

**Xu Huang**, Weiwen Liu, Xiaolong Chen, Xingmei Wang, Defu Lian, Yasheng Wang, Ruiming Tang, Enhong Chen

[**Project**](https://scholar.google.com/citations?view_op=view_citation&citation_for_view=fXFMb-gAAAAJ:eQOLeE2rZwMC) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:eQOLeE2rZwMC'></span></strong>
- A novel prompt-based method for LLM agents, leveraging weaker agent for exploration and stronger agent for exploitation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/survey-planning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Understanding the planning of LLM agents: A survey](https://arxiv.org/abs/2402.02716)

**Xu Huang**, Weiwen Liu, Xiaolong Chen, Xingmei Wang, Hao Wang, Defu Lian, Yasheng Wang, Ruiming Tang, Enhong Chen

[**Project**](https://scholar.google.com/citations?view_op=view_citation&citation_for_view=fXFMb-gAAAAJ:W7OEmFMy1HYC) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:W7OEmFMy1HYC'></span></strong>
- A survey about the planning ability of LLM agents.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2024</div><img src='images/morec.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Data-Centric Multi-Objective Learning Framework for Responsible Recommendation Systems](https://arxiv.org/abs/2310.13260)

**Xu Huang**, Jianxun Lian, Hao Wang, Defu Lian, Xing Xie

[**Project**](https://scholar.google.com/citations?view_op=view_citation&citation_for_view=fXFMb-gAAAAJ:zYLM7Y9cAGgC) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:zYLM7Y9cAGgC'></span></strong>
- A data-centric framework for multi-objective learning in recommendation systems.
- [Code](https://github.com/microsoft/UniRec/tree/main/unirec/facility/morec)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/interecagent.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations](https://arxiv.org/abs/2308.16505)

**Xu Huang**, Jianxun Lian, Yuxuan Lei, Jing Yao, Defu Lian, Xing Xie

[**Project**](https://scholar.google.com/citations?view_op=view_citation&user=fXFMb-gAAAAJ&citation_for_view=fXFMb-gAAAAJ:IjCSPb-OGe4C) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:IjCSPb-OGe4C'></span></strong>
- A framework to build an interactive recommendation agent with LLM
- [Code](https://aka.ms/recagent)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2023</div><img src='images/recstudio.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RecStudio: Towards a Highly-Modularized Recommender System](http://recstudio.org.cn)

Defu Lian(mentor), **Xu Huang**, Xiaolong Chen, Jin Chen, Xingmei Wang, Yankai Wang, Haoran Jin, Rui Fan, Zheng Liu, Le Wu, Enhong Chen

[**Project**](https://scholar.google.com/citations?view_op=view_citation&user=fXFMb-gAAAAJ&citation_for_view=fXFMb-gAAAAJ:qjMakFHDy7sC) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:qjMakFHDy7sC'></span></strong>
- A modularized recommender system library *RecStudio* was developped and released to public
- [Project homepage](http://recstudio.org.cn)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2023</div><img src='images/corr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cooperative Retriever and Ranker in Deep Recommenders](https://dl.acm.org/doi/abs/10.1145/3543507.3583422)

**Xu Huang**, Defu Lian, Jin Chen, Zheng Liu, Xing Xie, Enhong Chen

[**Project**](https://scholar.google.com/citations?view_op=view_citation&user=fXFMb-gAAAAJ&citation_for_view=fXFMb-gAAAAJ:u5HHmVD_uO8C) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:u5HHmVD_uO8C'></span></strong>
- An adaptive hard negative sampler was introduced to enhance the ranker
- An sampling based KL divergence was proposed to enhance the retriever
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD2024</div><img src='images/recexplainer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RecExplainer: Aligning Large Language Models for Explaining Recommendation Models](https://arxiv.org/abs/2311.10947)

Yuxuan Lei, Jianxun Lian, Jing Yao, **Xu Huang**, Defu Lian, Xing Xie

[**Project**](https://github.com/microsoft/RecAI/blob/main/RecExplainer/README.md) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:Tyk-4Ss8FVUC'></span></strong>
- A novel approach to leverage LLMs as surrogate models for explaining black-box recommender models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML2024</div><img src='images/RG2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning-Efficient Yet Generalizable Collaborative Filtering for Item Recommendation](https://openreview.net/pdf?id=D5IRvFF1lN)

Yuanhao Pu, Xiaolong Chen, **Xu Huang**, Jin Chen, Defu Lian, Enhong Chen

[**Project**](https://github.com/yuanhao53/RG2) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:Zph67rFs4hoC'></span></strong>
- This work proposes a new square loss RG2 for recommendation based on the approximation of the softmax loss with Taylor expansion.
- We have studied the theoretical properties of the proposed loss in terms of generalization and consistency. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW2024</div><img src='images/recai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RecAI: Leveraging Large Language Models for Next-GenerationRecommender Systems](https://arxiv.org/abs/2403.06465)

Jianxun Lian, Yuxuan Lei, **Xu Huang**, Jing Yao, Wei Xu, Xing Xie

[**Project**](https://github.com/microsoft/RecAI) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:YsMSGLbcyi4C'></span></strong>
- A practical toolkit designed to augmentor even revolutionize recommender systems with the advanced capabilities of Large Language Models.
- Demo Paper
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWWJ</div><img src='images/llm4rec.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When large language models meet personalization: Perspectives of challenges and opportunities](https://link.springer.com/article/10.1007/s11280-024-01276-1)

Jin Chen, Zheng Liu, **Xu Huang**, Chenwang Wu, Qi Liu, Gangwei Jiang, Yuanhao Pu, Yuxuan Lei, Xiaolong Chen, Xingmei Wang, Defu Lian, Enhong Chen

[**Project**](https://scholar.google.com/citations?view_op=view_citation&user=fXFMb-gAAAAJ&citation_for_view=fXFMb-gAAAAJ:UeHWp8X0CEIC) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:UeHWp8X0CEIC'></span></strong>
- A survey to summarize the combination of large language models and personlization systems
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2022</div><img src='images/fastvae.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fast variational autoencoder with inverted multi-index for collaborative filtering](https://dl.acm.org/doi/abs/10.1145/3485447.3512068)

Jin Chen, Defu Lian, Binbin Jin, **Xu Huang**, Kai Zhang, Enhong Chen

[**Project**](https://scholar.google.com/citations?view_op=view_citation&user=fXFMb-gAAAAJ&citation_for_view=fXFMb-gAAAAJ:u-x6o8ySG0sC) <strong><span class='show_paper_citations' data='fXFMb-gAAAAJ:u-x6o8ySG0sC'></span></strong>
- An adaptive negative sampler was proposed to training VAE efficiently
</div>
</div>

# ⚙️ Projects

- [ToolACE](https://huggingface.co/Team-ACE): Large Language Models tailored for functional-calling (or tool-using) tasks.
- [RecAI](https://github.com/microsoft/RecAI): A project aims to bridge this gap by investigating various strategies to integrate LLMs into recommender systems.
- [RecFM](https://github.com/USTCLLM/RecFM): A project aims to build foundation models for recommendation systems.
- [RecStudio](http://recstudio.org.cn): A modularized and unified library for recommendation system based on PyTorch.
- [UniRec]( https://github.com/microsoft/UniRec): An easy-to-use, lightweight, and scalable implementation of recommender systems.


# 🎖 Honors and Awards
- Stars of Tomorrow Award, Microsoft Research Asia, *2023.10*
- National Scholarship, *2023.10*
- USTC Academic Scholarship, *2021.09*, *2022.09*, *2023.09*, *2024.09*
- USTC Excellent Student Prize, *2017.09*, *2018.09*, *2019.09*
- National Encouragement Scholarship, *2018.09*
- Shizhang Bei Talent class Scholarship, *2017.09*

# 📖 Educations
- *2021.09 - 2026.06 (expected)*, [School of Computer Science and Technology](http://cs.ustc.edu.cn/), [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/), Ph.D. student.
- *2017.08 - 2021.06*, [School of Computer Science and Technology](http://cs.ustc.edu.cn/), [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/), Bachelor.

# 💻 Internships
- *2023.11 - Now*, [Huawei Noah's Ark Lab](http://dev3.noahlab.com.hk/), Shenzhen, China.
  - Intern in Recommendation and Search Group lead by Ruiming Tang
  - Dive into: Multi-domain and Multi-task Recommendation, LLM Agents
  - Mentor: [Weiwen Liu](https://wwliu555.github.io/)
- *2022.10 - 2023.10*, [Microsoft Research Asia](https://www.msra.cn/), Beijing, China.
  - Intern in [Social Computing Group](https://www.microsoft.com/en-us/research/group/social-computing-beijing/) lead by [Xing Xie](https://www.microsoft.com/en-us/research/people/xingx/)
  - Dive into: Responsible Recommendation, Recommendation Agent
  - Mentor: [Jianxun Lian](https://www.microsoft.com/en-us/research/people/jialia/)


# ⏳ Professional Services

##### Program Committee Members
- Reviewer, [IEEE TKDE](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=69)
- Reviewer, [WWW 2024, WWW 2025](https://thewebconf.org/)
- PC member, [TrustKDD2023 (workshop)](https://ustcml.github.io/TrustKDD/)
- PC member, [AAAI 2024, 2025](https://aaai.org/conference/aaai/)
- PC member, [KDD 2025](https://kdd.org/conferences)
- Sub-Reviewer, [CIKM 2023](https://uobevents.eventsair.com/cikm2023/)



# 📃 Curriculum Vitae

I am a 2026 graduate seeking employment opportunities. Please do not hesitate to contact me via email if you have any suitable positions available. Contact me: [xuhuangcs@mail.ustc.edu.cn](mailto:xuhuangcs@mail.ustc.edu.cn).

<!-- <object data="images/CV.pdf" type="application/pdf" width="48%" height="64%">
  <p>It appears you don't have a PDF plugin for this browser. No worries, you can<a href="images/cv.pdf"> click here to download the PDF file.</a></p>
</object> -->


# 📈 Pageviews

<div style="width: 25%">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=aLTLPi6PPrI1G1FwRYJ7ISibafGELDLQqzFUoVKfe34&cl=ffffff&w=a"></script>
<div>
