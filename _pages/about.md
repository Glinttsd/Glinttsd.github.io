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

I'm currently a first year Ph.D student advised by [Prof. Ming](https://ic.seu.edu.cn/2022/0411/c2210a404378/page.htm) of [EECS-Ling Lab](https://github.com/ECAS-Ling) from [School of Integrated Circuits](https://ic.seu.edu.cn/), [Southeast University](https://www.seu.edu.cn/).

I received my B.S. and M.S. degrees from Central China Normal University (CCNU) and Nanjing University of Posts and Telecommunications (NJUPT), separately.

My research <a href='https://scholar.google.com/citations?user=mf6xshEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> interest includes domain specific accelerator, efficient machine learning and parallel computing. 

I was an research intern at Microsoft Research Asia (MSRA), AI for Science group from 2022 to 2023, during which I obtained the *Stars of Tomorrow Internship Program* Award.



# 🔥 News
- *2024.05*: &nbsp;🎉🎉 [DiG](https://www.nature.com/articles/s42256-024-00837-3) has been accepted (as a co-author) in *Nature Machine Intelligence*. Much appreciated to MSRA AI4Science.
- *2024.04*: &nbsp;🎉🎉 [Vina-FPGA-Cluster](https://ieeexplore.ieee.org/abstract/document/10500753) has been accepted (as a co-author) in *IEEE Transactions on Biomedical Circuits and Systems*

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Vina-GPU</div><img src='images/Vina-GPU.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accelerate autodock vina with GPUs](https://www.mdpi.com/1420-3049/27/9/3041#)

**Shidi Tang**, Ruiqi Chen, Mengru Lin, Qingde Lin, Yanxiang Zhu, Ji Ding, Haifeng Hu, Ming Ling, Jiansheng Wu

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:u-x6o8ySG0sC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:u-x6o8ySG0sC'></span></strong>
- This work presents a parallel algorithm called Vina-GPU and the OpenCL implementation on GPUs.
</div>
</div>

<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Vina-GPU 2.0</div><img src='images/Vina-GPU2.0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vina-GPU 2.0: further accelerating AutoDock Vina and its derivatives with graphics processing units](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.2c01504)

Ji Ding, **Shidi Tang**, Zheming Mei, Lingyue Wang, Qinqin Huang, Haifeng Hu, Ming Ling, Jiansheng Wu

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:9yKSN-GCB0IC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:9yKSN-GCB0IC'></span></strong>
- This work presents Vina-GPU 2.0 to further accelerate AutoDock Vina and its derivatives with graphics processing units.
</div>
</div>

<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Vina-FPGA-Cluster</div><img src='images/Vina-FPGA-Cluster.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vina-FPGA-Cluster: Multi-FPGA Based Molecular Docking Tool with High-Accuracy and Multi-Level Parallelism](https://ieeexplore.ieee.org/abstract/document/10500753)

Ming Ling, Zhihao Feng, Ruiqi Chen, Yi Shao, **Shidi Tang**, Yanxiang Zhu

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:zYLM7Y9cAGgC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:zYLM7Y9cAGgC'></span></strong>
- This work presents Vina-GPU 2.0 to further accelerate AutoDock Vina and its derivatives with graphics processing units.
</div>
</div>

<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Effectiveness Analysis</div><img src='images/Vina-FPGA-Cluster.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Effectiveness Analysis of Multiple Initial States Simulated Annealing Algorithm, A Case Study on the Molecular Docking Tool AutoDock Vina](https://ieeexplore.ieee.org/abstract/document/10500753)

Xingxing Zhou, Ming Ling, Qingde Lin, **Shidi Tang**, Jiansheng Wu, Haifeng Hu

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:d1gkVwhDpl0C'></span></strong>
- This work presents Vina-GPU 2.0 to further accelerate AutoDock Vina and its derivatives with graphics processing units.
</div>
</div>

<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DiG</div><img src='images/DiG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Predicting equilibrium distributions for molecular systems with deep learning](https://ieeexplore.ieee.org/abstract/document/10500753)

Shuxin Zheng, Jiyan He, Chang Liu, Yu Shi, Ziheng Lu, Weitao Feng, Fusong Ju, Jiaxi Wang, Jianwei Zhu, Yaosen Min, He Zhang, **Shidi Tang**, Hongxia Hao, Peiran Jin, Chi Chen, Frank Noé, Haiguang Liu, Tie-Yan Liu

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:Y0pCki6q_DkC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:Y0pCki6q_DkC'></span></strong>
- This work presents Vina-GPU 2.0 to further accelerate AutoDock Vina and its derivatives with graphics processing units.
</div>
</div>


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