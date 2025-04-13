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

I graduated with a bachelor's degree from [the Department of Physics at Zhejiang University](http://physics.zju.edu.cn) and is now a Phd student undert the mentorship of [Wenhai Wang](https://person.zju.edu.cn/wangweihai) and [Xuhong Zhang](https://person.zju.edu.cn/zhangxuhong) at ZheJiang University.  

My research interests include Large Language Models (LLMs), Code Intelligence, Code Generation, etc.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 🚀 News
- 🔥🔥 **[2025-03-25]** [**Ling-Coder-Lite**](https://arxiv.org/abs/2503.17793) is released by Codefuse and Ling Team, Ant Group.
- 🔥🔥 **[2025-03-16]** [**Awesome-Code-Benchmark**](https://github.com/tongye98/Awesome-Code-Benchmark) A thorough review of code domain benchmarks for LLM research has been released.


# 📝 Conference Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- [Every Sample Matters: Leveraging Mixture-of-Experts and High-Quality Data for Efficient and Accurate Code LLM](https://arxiv.org/abs/2503.17793), **Codefuse, Ling Team**: Wenting Cai, Yuchen Cao, Chaoyu Chen, Chen Chen, Siba Chen, Qing Cui, Peng Di, Junpeng Fang, Zi Gong, Ting Guo, Zhengyu He, Yang Huang, Cong Li, Jianguo Li, Zheng Li, Shijie Lian, BingChang Liu, Songshan Luo, Shuo Mao, Min Shen, Jian Wu, Jiaolong Yang, Wenjie Yang, **Tong Ye**, Hang Yu, Wei Zhang, Zhenduo Zhang, Hailin Zhao, Xunjin Zheng, Jun Zhou. **Techinical Report, Ant Group**  *<u>(Authors are listed in the alphabet order based on their last name.)</u>*

- [ModiGen: A Large Language Model-Based Workflow for Multi-Task  Modelica Code Generation](https://arxiv.org/abs/2503.18460), Jiahui Xiang, **Tong Ye**, Peiyu Liu, Yinan Zhang, Wenhai Wang, **ICSE 2025 under review**

- [Towards Automated SOC Alert Validation: Leveraging LLMs for False Positives Identification](), Weigang Huang, Peiyu Liu, Kangjie Lu, **Tong Ye**, Lirong Fu, Wenhai Wang, **ICSE 2025 under review**

- [LLM4EFFI: Leveraging Large Language Models to Enhance Code Efficiency and Correctness](https://arxiv.org/abs/2502.18489), **Tong Ye**, Weigang Huang, Xuhong Zhang, Tengfei Ma, Peiyu Liu, Jianwei Yin, Wenhai Wang, **ACL 2025 under reivew**

- [A Problem-Oriented Perspective and Anchor Verification for Code Optimization](https://arxiv.org/abs/2406.11935), **Tong Ye**, Tengfei Ma, Xuhong Zhang, Hang Yu, Jianwei Yin, Wenhai Wang, **ACL 2025 under reivew**

- [Uncovering LLM-Generated Code: A Zero-Shot Synthetic Code Detector via Code Rewriting](https://doi.org/10.1609/aaai.v39i1.32082), **Tong Ye**, Yangkai Du, Tengfei Ma, Lingfei Wu, Xuhong Zhang, Shouling Ji, Wenhai Wang, **AAAI 2025** **Oral**

- [Tram: A Token-level Retrieval-augmented Mechanism for Source Code Summarization](https://aclanthology.org/2024.findings-naacl.186/), **Tong Ye**, Lingfei Wu, Tengfei Ma, Xuhong Zhang, Yangkai Du, Peiyu Liu, Shouling Ji, Wenhai Wang, **NAACL 2024**

- [CP-BCS: Binary Code Summarization Guided by Control Flow Graph and Pseudo Code](https://aclanthology.org/2023.emnlp-main.911/), **Tong Ye**, Lingfei Wu, Tengfei Ma, Xuhong Zhang, Yangkai Du, Peiyu Liu, Shouling Ji, Wenhai Wang, **EMNLP 2023**



# 📝 Journal Publications 
- [LuaTaint: A Static Analysis System for Web Configuration Interface Vulnerability of Internet of Things Device](https://ieeexplore.ieee.org/document/10742550), Jiahui Xiang, Lirong Fu, **Tong Ye**, Peiyu Liu, Huan Le, Liming Zhu, Wenhai Wang, **IEEE Internet of Things Journal, 2024**

- [State-of-the-Art Survey of Open-source Software Supply Chain Security](https://www.jos.org.cn/jos/article/abstract/lh049), Shouling Ji, Qinying Wang, Anying Chen, Binbin Zhao, **Tong Ye**, Xuhong Zhang, Jingzheng Wu, Yun Li, Jianwei Yin, Yanjun Wu, **Journal of Software, 2022**


# 📖 Educations
- *2020.09 - now*, CyberSecurity, Zhejiang University, China. 
- *2016.09 - 2020.06*, Physics, Zhejiang University, China. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.06 - now*, Ant-Star, LLM Algorithm Research Intern, [Ant Group](https://www.antgroup.com), China.
- *2021.07 - 2021.09*, Digital Twin, [UWNTEK](https://www.uwntek.com), China.

# 🎖 Honors and Awards
- *2020.06* Outstanding Graduates of Zhejiang Province (Top 3%). 
- *2019.09* Zhejiang Provincial Government Scholarship. 