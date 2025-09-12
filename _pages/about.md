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

I'm currently a third year Ph.D student advised by [Prof. Ming](https://ic.seu.edu.cn/2022/0411/c2210a404378/page.htm) of [EECS-Ling Lab](https://github.com/ECAS-Ling) from [School of Integrated Circuits](https://ic.seu.edu.cn/), [Southeast University](https://www.seu.edu.cn/).

I received my B.S. and M.S. degrees from Central China Normal University (CCNU) and Nanjing University of Posts and Telecommunications (NJUPT), separately.

My research <a href='https://scholar.google.com/citations?user=mf6xshEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> interest includes domain specific accelerator, efficient machine learning and parallel computing. 

I was an research intern at Microsoft Research Asia (MSRA), AI for Science group from 2022 to 2023, during which I obtained the *Stars of Tomorrow Internship Program* Award.



# 🔥 News
- *2025.09*: &nbsp;🎉🎉 **Diff-DiT** has been selected as the <span style="color: red; font-weight: bold;"> Best Paper Award Candidate </span> in ICCAD'25!
- *2025.07*: &nbsp;🎉🎉 **Diff-DiT: Temporal Differential Accelerator for Low-bit Diffusion Transformers on FPGA** has been accepted in *The 2025 International Conference on Computer-Aided Design (ICCAD'25)*.
- *2025.05*: &nbsp;🎉🎉 [Diff-Acc: An Efficient FPGA Accelerator for Unconditional Diffusion Models](https://dl.acm.org/doi/abs/10.1145/3728470) has been accepted in *ACM Transactions on Embedded Computing Systems*.
- *2025.05*: &nbsp;🎉🎉 Two papers accepted in *GLVLSI'25*.

# 📝 Publications 

<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TECS 2025</div><img src='images/diffuser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Diff-Acc: An Efficient FPGA Accelerator for Unconditional Diffusion Models](https://ieeexplore.ieee.org/abstract/document/10884806)

**Shidi Tang**, Ruiqi Chen, Rui Liu, Yuxuan Lv, Pengwei Zheng, He Li, Ming Ling<br>
**ACM Transactions on Embedded Computing Systems** (Early Access).

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:WF5omc3nYNoC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:eQOLeE2rZwMC'></span></strong>
- This work presents Diff-Acc, an efficient FPGA accelerator for unconditional UNet-based diffusion models with noval step-wise quantization method and group-wise parallelism. Compared with both server-based (Tesla V100 and Intel Xeon) and edge-based (Raspberry Pi 4 and Jetson Nano) platforms, Diff-Acc implemented on the Zynq UltraScale+ XCZU9EG FPGA demonstrates an up-to 12.5 × energy efficiency. Particularly versus edge-based platforms, Diff-Acc achieves up to 10.26 × and 1.97 × performance improvements over CPU and GPU, respectively.
</div>
</div>


<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCBB 2024</div><img src='images/EEVS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EEVS: Redeploying Discarded Smartphones for Economic and Ecological Drug Molecules Virtual Screening](https://ieeexplore.ieee.org/abstract/document/10884806)

Ming Ling, Chuanzhao Zhang, **Shidi Tang**, Ruiqi Chen, Yanxiang Zhu<br>
**IEEE Transactions on Sustainable Computing**.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:eQOLeE2rZwMC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:eQOLeE2rZwMC'></span></strong>
- This work presents EEVS, aimed at redeploying discarded smartphones for economic and ecological drug molecules virtual screening.
</div>
</div>


<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCBB 2024</div><img src='images/Vina-GPU 2.1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vina-GPU 2.1: towards further optimizing docking speed and precision of AutoDock Vina and its derivatives](https://ieeexplore.ieee.org/abstract/document/10693356)

**Shidi Tang**, Ji Ding, Xiangyu Zhu, Zheng Wang, Haitao Zhao, Jiansheng Wu<br>
**IEEE/ACM Transactions on Computational Biology and Bioinformatics**.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:UeHWp8X0CEIC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:UeHWp8X0CEIC'></span></strong>
- This work presents [Vina-GPU 2.1 ![](https://img.shields.io/github/stars/DeltaGroupNJUPT/Vina-GPU-2.1?style=social)](https://github.com/DeltaGroupNJUPT/Vina-GPU-2.1), aimed at enhancing the docking speed and precision of AutoDock Vina and its derivatives through the integration of novel algorithms to facil-itate improved docking and virtual screening outcomes.
</div>
</div>


<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PACRIM 2024</div><img src='images/PACRIM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Modeling equivariant neural networks for hardware acceleration, a case study on the molecular docking tool DiffDock](https://ieeexplore.ieee.org/abstract/document/10690224)

**Shidi Tang**, Xingxing Zhou, Ming Ling.<br>
**PACRIM'2024**.

[**Project**](https://ieeexplore.ieee.org/abstract/document/10690224) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:Y0pCki6q_DkC'></span></strong>
- This work proposes first SystemC model for equivariant neural networks, specifically targeting Diffdock, with the aim of accelerating its performance using customized hardware such as the FPGA..
</div>
</div>

<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NMI 2024</div><img src='images/DiG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Predicting equilibrium distributions for molecular systems with deep learning](https://ieeexplore.ieee.org/abstract/document/10500753)

Shuxin Zheng, Jiyan He, Chang Liu, Yu Shi, Ziheng Lu, Weitao Feng, Fusong Ju, Jiaxi Wang, Jianwei Zhu, Yaosen Min, He Zhang, **Shidi Tang**, Hongxia Hao, Peiran Jin, Chi Chen, Frank Noé, Haiguang Liu, Tie-Yan Liu.<br>
**Nature Machine Intelligence** (2024): 1-10.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:Y0pCki6q_DkC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:Y0pCki6q_DkC'></span></strong>
- This work proposes Distributional Graphormer (DiG) in an attempt to predict the equilibrium distribution of molecular systems.
</div>
</div>


<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TBCAS 2024</div><img src='images/Vina-FPGA-Cluster.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vina-FPGA-Cluster: Multi-FPGA Based Molecular Docking Tool with High-Accuracy and Multi-Level Parallelism](https://ieeexplore.ieee.org/abstract/document/10500753)

Ming Ling, Zhihao Feng, Ruiqi Chen, Yi Shao, **Shidi Tang**, Yanxiang Zhu<br>
**IEEE Transactions on Biomedical Circuits and Systems (TBCAS)** (2024).

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:zYLM7Y9cAGgC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:zYLM7Y9cAGgC'></span></strong>
- This work presents Vina-FPGA-cluster, a multi-FPGA-based molecular docking tool enabling high-accuracy and multi-level parallel Vina acceleration.
</div>
</div>


<!-- ######################################################################### -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCIM 2023</div><img src='images/Vina-GPU2.0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vina-GPU 2.0: further accelerating AutoDock Vina and its derivatives with graphics processing units](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.2c01504)

Ji Ding, **Shidi Tang**, Zheming Mei, Lingyue Wang, Qinqin Huang, Haifeng Hu, Ming Ling, Jiansheng Wu<br>
**Journal of Chemical Information and Modeling (JCIM)** 63 (7), 1982-1998

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:9yKSN-GCB0IC) <strong><span class='show_paper_citations' data='mf6xshEAAAAJ:9yKSN-GCB0IC'></span></strong>
- This work presents [Vina-GPU 2.0 ![](https://img.shields.io/github/stars/DeltaGroupNJUPT/Vina-GPU-2.0?style=social)](https://github.com/DeltaGroupNJUPT/Vina-GPU-2.0) to further accelerate AutoDock Vina and its derivatives with graphics processing units.
</div>
</div>


<!-- ######################################################################### -->

- ``TCBB 2023`` [Effectiveness Analysis of Multiple Initial States Simulated Annealing Algorithm, A Case Study on the Molecular Docking Tool AutoDock Vina](https://ieeexplore.ieee.org/abstract/document/10500753)

Xingxing Zhou, Ming Ling, Qingde Lin, **Shidi Tang**, Jiansheng Wu, Haifeng Hu<br>
**IEEE/ACM Transactions on Computational Biology and Bioinformatics (TCBB)**, 2023 

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:d1gkVwhDpl0C)<strong><span class='show_paper_citations' data='mf6xshEAAAAJ:d1gkVwhDpl0C'></span></strong>
- This work presents a probabilistic model for the effectiveness of multiple initial states parallel SA (MISPSA) that is adapted in Vina-GPU.


<!-- ######################################################################### -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Moleculars 2022</div><img src='images/Vina-GPU.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accelerate autodock vina with GPUs](https://www.mdpi.com/1420-3049/27/9/3041#)

**Shidi Tang**, Ruiqi Chen, Mengru Lin, Qingde Lin, Yanxiang Zhu, Ji Ding, Haifeng Hu, Ming Ling, Jiansheng Wu<br>
**Molecules**, 2022, 27(9): 3041

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:u-x6o8ySG0sC)<strong><span class='show_paper_citations' data='mf6xshEAAAAJ:u-x6o8ySG0sC'></span></strong>
- This work presents a parallel algorithm called [Vina-GPU ![](https://img.shields.io/github/stars/DeltaGroupNJUPT/Vina-GPU?style=social)](https://github.com/DeltaGroupNJUPT/Vina-GPU) and the OpenCL implementation on GPUs.
</div>
</div>

<!-- ######################################################################### -->
[A fast approximate check polytope projection algorithm for ADMM decoding of LDPC codes](https://ieeexplore.ieee.org/abstract/document/10500753)

Qiaoqiao Xia, Yan Lin, **Shidi Tang**, Qinglin Zhang<br>
**IEEE Communications Letters**, 2019, 23(9): 1520-1523.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=mf6xshEAAAAJ&citation_for_view=mf6xshEAAAAJ:u5HHmVD_uO8C)<strong><span class='show_paper_citations' data='mf6xshEAAAAJ:u5HHmVD_uO8C'></span></strong>
- This work presents a fast projection algorithm for ADMM decoding of LDPC codes

# 💼 Service
- Reviewer of *The Journal of Supercomputing*

# 🎖 Honors and Awards
- *2023.8*  *Stars of Tomorrow Internship Program* Award at Microsoft Research Asia.

# 📖 Educations
- ### B.S. in Communication Engineering, 2016-2019
  > Central China Normal University (CCNU), Wuhan, China

- ### M.S. in Biomedical Engineering, 2020-2023
  > Nanjing University of Posts and Telecommunications (NJUPT), Nanjing, China

- ### Ph.D student, 2023-present
  > Southeast University, Nanjing, China

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- ### Research Intern, 2022-2023
  > Microsoft Research Asia (MSRA), AI for Science group, Beijing, China