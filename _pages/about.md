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

LIU Yijiang (刘一茳) is the Head of the Algorithm Team at the ISCL Lab (Nanjing University), and an Associate Professor at Nanjing University of Information Science and Technology. He received his Ph.D. from the School of Electronic Science and Engineering, Nanjing University. His research focuses on on-device large models, model compression and acceleration, and software-hardware co-optimization. He has published multiple papers in CCF-A international top-tier journals and conferences. His corresponding-author paper, LiftQuant: Continuous Bit-Width Control for Pareto-Optimal LLM Deployment, was selected as an ICML 2026 Spotlight. His first-author paper (AAAI'25 Pruning-Aware Tuning) has been applied to Samsung's on-device applications for smartphones and TVs. Additionally, his collaborative work with UC Berkeley (ICCV'23 Q-Diffusion) has been featured in MIT OpenCourse and adopted by NVIDIA's TensorRT team for deployment.

刘一茳，南京大学ISCL算法团队负责人，南京信息工程大学校聘副教授，主要研究方向为端侧大模型的压缩、加速以及软硬件协同优化设计。其博士毕业于南京大学电子科学与工程学院，在CCF-A类国际顶级期刊和会议上发表10余篇论文。
其通讯作者论文（ICML'26 LiftQuant获得“焦点关注”荣誉）提出一种连续位宽量化技术，其第一作者论文（AAAI'25 Pruning-Aware Tuning）已应用于三星手机和电视业务，与加州大学伯克利分校的合作成果（ICCV'23 Q-Diffusion）已被MIT公开课程收录，并被NVIDIA的TensorRT团队采用部署。

🔥🔥🔥 We are recruiting Master and Ph.D students! Please visit our Lab page for more details! [南京大学智能感知与通信实验室](https://iscl.nju.edu.cn/d9/65/c58186a645477/page.htm)

# 🔥 News
- *2026.04*: &nbsp;🎉🎉 **ICML 2026 SpotLight!!:** LiftQuant, Continuous Bit-Width Control for Pareto-Optimal LLM Deployment. 
- *2025.04*: &nbsp;🎉🎉 **IJCAI 2025:** [FBQuant](https://arxiv.org/abs/2501.16385), a novel quantization method for LLMs. 
- *2024.12*: &nbsp;🎉🎉 **AAAI 2025:** [PAT](https://www.arxiv.org/abs/2408.14721), an efficient pruning technology for LLMs.
- *2024.02*: &nbsp;🎉🎉 **CVPR 2024:** [Cloud-Device Collaborative](https://arxiv.org/abs/2312.16279).
- *2024.02*: &nbsp;🎉🎉 **CVPR 2024:** [PromptCoT](https://openaccess.thecvf.com/content/CVPR2024/html/Yao_PromptCoT_Align_Prompt_Distribution_via_Adapted_Chain-of-Thought_CVPR_2024_paper.html), a novel technology for enhancing T2I quality.
- *2024.04*: &nbsp;🎉🎉 Q-Diffusion is featured in the newest [TensorRT post](https://developer.nvidia.com/blog/tensorrt-accelerates-stable-diffusion-nearly-2x-faster-with-8-bit-post-training-quantization) and [MIT opencourses](https://www.youtube.com/watch?v=nFE1euQ_Wtw).
- *2023.08*: &nbsp;🎉🎉 **Project:** [LLaMA-Accessory](https://github.com/Alpha-VLLM/LLaMA2-Accessory), an Open-source Toolkit for LLM Development.
- *2023.08*: &nbsp;🎉🎉 **ICCV 2023:** [Q-Diffusion](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Q-Diffusion_Quantizing_Diffusion_Models_ICCV_2023_paper.html), a low-bit quantization technology for diffusion models.
- *2023.03*: &nbsp;🎉🎉 **CVPR 2023:** [NoisyQuant](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_NoisyQuant_Noisy_Bias-Enhanced_Post-Training_Activation_Quantization_for_Vision_Transformers_CVPR_2023_paper.html), a novel quantization mothod for Vision Transformers.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026 SpotLight</div><img src='paper_images/LiftQuant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ICML 2026 SpotLight** LiftQuant: Continuous Bit-Width LLM via Dimensional Lifting and Projection

Liulu He, Xuan Ang Liu, Taolue Feng, Ting Lu, Chunsheng Gan, ZHIYV PENG, Yuan Du, Huanrui Yang, **Yijiang Liu**, Li Du

- LLM quantization. 

**GitHub**: Soon
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src='paper_images/fbquant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**IJCAI 2025** [FBQuant: FeedBack Quantization for Large Language Models](https://arxiv.org/abs/2501.16385)

**Yijiang Liu**, Hengyu Fang, Liulu He, Rongyu Zhang, Yichuan Bai, Yuan Du, Li Du

- LLM quantization. 
- Sub-branch approach.

[**GitHub**](https://github.com/kriskrisliu/FeedBackQuant) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='paper_images/pat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AAAI 2025** [PAT: Pruning-Aware Tuning for Large Language Models](https://arxiv.org/pdf/2408.14721)

**Yijiang Liu**, Huanrui Yang, Youxin Chen, Rongyu Zhang, Miao Wang, Yuan Du, Li Du

- LLM structural pruning.
- Adaptation to downstream tasks.

[**GitHub**](https://github.com/kriskrisliu/PAT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<!-- begin -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='paper_images/promptcot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CVPR 2024** [PromptCoT: Align Prompt Distribution via Adapted Chain-of-Thought](https://openaccess.thecvf.com/content/CVPR2024/html/Yao_PromptCoT_Align_Prompt_Distribution_via_Adapted_Chain-of-Thought_CVPR_2024_paper.html)

**Yijiang Liu\***, Junyi Yao\*, Zhen Dong, Mingfei Guo, Helan Hu, Kurt Keutzer, Li Du, Daquan Zhou, Shanghang Zhang 

- Enhance prompt quality by LLMs.
- Enhance T2I generation quality by better prompts.

[**GitHub**](https://github.com/SanGibb/PromptCoT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>
<!-- end -->

<!-- begin -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='paper_images/cloud-device.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CVPR 2024** [Cloud-Device Collaborative Learning for Multimodal Large Language Models](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Cloud-Device_Collaborative_Learning_for_Multimodal_Large_Language_Models_CVPR_2024_paper.html)

Guanqun Wang, Jiaming Liu, Chenxuan Li, Yuan Zhang, Junpeng Ma, Xinyu Wei, Kevin Zhang, Maurice Chong, Renrui Zhang, **Yijiang Liu**, Shanghang Zhang 

- Improves compressed MLLMs on devices using cloud-based models.
- Efficient data transmission, knowledge distillation, and adaptive weight compression.

[**GitHub**](https://github.com/KongoCat/Cloud-Device-Collaborative-Learning-for-Multimodal-Large-Language-Models) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>
<!-- end -->

<!-- begin -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='paper_images/q-diffusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ICCV 2023** [Q-diffusion: Quantizing diffusion models](http://openaccess.thecvf.com/content/ICCV2023/html/Li_Q-Diffusion_Quantizing_Diffusion_Models_ICCV_2023_paper.html)

Xiuyu Li, **Yijiang Liu**, Long Lian, Huanrui Yang, Zhen Dong, Daniel Kang, Shanghang Zhang, Kurt Keutzer


- PTQ method for diffusion models.
- Timestep-aware calibration and shortcut split methods.

[**GitHub**](https://github.com/Xiuyu-Li/q-diffusion) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Website**](https://xiuyuli.com/qdiffusion/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>
<!-- end -->

<!-- begin -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='paper_images/noisyquant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CVPR 2023** [NoisyQuant: Noisy Bias-Enhanced Post-Training Activation Quantization for Vision Transformers](http://openaccess.thecvf.com/content/CVPR2023/html/Liu_NoisyQuant_Noisy_Bias-Enhanced_Post-Training_Activation_Quantization_for_Vision_Transformers_CVPR_2023_paper.html)

**Yijiang Liu**, Huanrui Yang, Zhen Dong, Kurt Keutzer, Li Du, Shanghang Zhang

- Using additive uniform noisy bias to actively reduce quantization error.
- Improving 6-bit quantization performance with minimal overhead.

[**GitHub**](https://github.com/kriskrisliu/NoisyQuant) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>
<!-- end -->

<!-- begin -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2022</div><img src='paper_images/limb-pose.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TIP 2022** [Limb Pose Aware Networks for Monocular 3D Pose Estimation](https://ieeexplore.ieee.org/abstract/document/9663053/)

Lele Wu, Zhenbo Yu, **Yijiang Liu**, Qingshan Liu

- Monocular 3D pose estimation.
- Kinematic constraints and a trajectory-aware approach to reduce estimation errors.

<!-- [**GitHub**](https://github.com/kriskrisliu/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>
<!-- end -->

# 🎖 Services
- Reviewer for CVPR, AAAI, ICML, ACMMM, ICCV, NeurIPS, IJCAI, ICLR.

# 📖 Educations
- *2022.09 - now*, Nanjing University, Ph.D
- *2008.09 - 2012.06*, University of Edinburgh, M.S
- *2008.09 - 2012.06*, Xidian University, B.S

# 💬 Invited Talks
- *2025.04*, invited by Momenta at the 2025 Shanghai International Automobile Industry Exhibition. 


# 💻 Visitings
- *2022.09 - 2024.12*, Peking University.
