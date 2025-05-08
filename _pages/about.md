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

I am currently serving as an Algorithm Expert at DAMO Academy, Alibaba Group, based in Hangzhou, where I have had the privilege of receiving guidance from [Prof. Qixing Huang](https://www.cs.utexas.edu/~huangqx/) and [Prof. Tan Ping](https://ece.hkust.edu.hk/pingtan).

I earned my Bachelor's degree (2010–2015) from Chongqing Medical University and completed my Ph.D. (2015–2020) at Fudan University, specifically at the Shanghai Key Lab of Medical Image Computing and Computer-Assisted Intervention, where i was supervised by [Prof. Zhijian Song](https://miccai.fudan.edu.cn/34225/list.htm/) and co-supervised by [Prof. Chenxi Zhang](https://miccai.fudan.edu.cn/6a/e6/c34227a420582/page.htm) and [Prof. Manning Wang](https://miccai.fudan.edu.cn/6a/e4/c34227a420580/page.htm).

My research passions lie in the domains of Computer Vision, 3D Vision, and Medical Image Processing. I have contributed more than 10+ publications to prestigious international AI conferences and journals, including CVPR, SIGGRAPH, NeurIPS, ECCV, ICRA, and TIP.

# 🔥 News

- *2025.02*: &nbsp;🎉 One paper accepted to IEEE Conference on Computer Vision and Pattern Recognition (CVPR 2025). 
- *2025.01*: &nbsp;🎉 Two paper accepted to International Conference on Learning Representations (ICLR 2025). 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH 2025</div><img src='images/paper/lam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LAM: Large Avatar Model for One-shot Animatable Gaussian Head](https://arxiv.org/pdf/2502.17796)

Yisheng He, Xiaodong Gu, Xiaodan Ye, Chao Xu, Zhengyi Zhao, **Yuan Dong<sup>#</sup>**, Weihao Yuan<sup>#</sup>, Zilong Dong, Liefeng Bo

[**Project**](https://aigc3d.github.io/projects/LAM/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/aigc3d/LAM/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A large avatar model for generating the animatable Gaussian head avatar from one image, allowing animation and rendering without additional network.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 (Spotlight)</div><img src='images/paper/atlas_gaussion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Atlas Gaussians Diffusion for 3D Generation](https://openreview.net/pdf?id=H2Gxil855b)

Haitao Yang<sup>*</sup>, **Yuan Dong<sup>*</sup>**, Hanwen Jiang, Dejia Xu, Georgios Pavlakos, Qixing Huang

[**Code**](https://github.com/yanghtr/AtlasGaussians/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A new 3D representation that can efficiently decode a sufficiently large and theoretically infinite number of 3D Gaussians for high-quality 3D generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3DV 2025</div><img src='images/paper/ctrlroom.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ctrl-Room: Controllable Text-to-3D Room Meshes Generation with Layout Constraints](https://arxiv.org/pdf/2310.03602)

Chuan Fang<sup>*</sup>, **Yuan Dong<sup>*</sup>**, Kunming Luo, Xiaotao Hu, Rakesh Shrestha, Ping Tan

[**Project**](https://fangchuan.github.io/ctrl-room.github.io//) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A two-stage method for 3D room generation from pure text input, which separates the geometric layout generation and appearance generation.
</div>
</div>

[//]: # (GPLD3D)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 (Oral)</div><img src='images/paper/gpld3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GPLD3D: Latent Diffusion of 3D Shape Generative Models by Enforcing Geometric and Physical Priors](https://openaccess.thecvf.com/content/CVPR2024/papers/Dong_GPLD3D_Latent_Diffusion_of_3D_Shape_Generative_Models_by_Enforcing_CVPR_2024_paper.pdf)

**Yuan Dong<sup>*</sup>**, Qi Zuo<sup>*</sup>, Xiaodong Gu, Weihao Yuan, Zhengyi Zhao, Zilong Dong, Liefeng Bo, Qixing Huang

[**Project**](https://aigc3d.github.io/GPLD3D/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A novel latent diffusion shape-generative model regularized by a quality checker that outputs a score of a latent code. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/paper/panocontextformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PanoContext-Former: Panoramic Total Scene Understanding with a Transformer](https://openaccess.thecvf.com/content/CVPR2024/papers/Dong_PanoContext-Former_Panoramic_Total_Scene_Understanding_with_a_Transformer_CVPR_2024_paper.pdf)

**Yuan Dong<sup>*</sup>**, Chuan Fang<sup>*</sup>, Liefeng Bo, Zilong Dong, Ping Tan

[**Project**](https://fangchuan.github.io/PanoContext-Former/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Dataset**](https://github.com/fdyuandong/ReplicaPano-Dataset/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

-  A new fully 3D method for total scene understanding from a single RGB panorama in an end-to-end fashion, which will better preserve the intrinsic structure of the indoor scene.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/paper/sparse3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[High-Fidelity 3D Textured Shapes Generation by Sparse Encoding and Adversarial Decoding](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01495.pdf)

Qi Zuo<sup>*</sup>, Xiaodong Gu<sup>*</sup>, **Yuan Dong<sup>*</sup>**, Zhengyi Zhao, Weihao Yuan, Lingteng Qiu, Liefeng Bo, Zilong Dong

[**Project**](https://aigc3d.github.io/Sparse3D/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A novel sparse encoding and dense decoding paradigm that can achieve both high-fidelity single-class generation. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCARS 2019</div><img src='images/paper/surface_reg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Regional-surface-basedregistration for image-guided neurosurgery: Effects of scan modes onregistration accuracy](https://link.springer.com/article/10.1007/s11548-019-01990-6/)

**Yuan Dong**, Chenxi Zhang , Dafeng Ji, Manning Wang, Zhijian Song
- A new framework for selecting an appropriate scan resolution and scan mode in image-guided neurosurgery. 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2018</div><img src='images/paper/global_roation_search.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[2D-3D Point Set Registration Based on Global Rotation Search](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8579206)

Yinlong Liu<sup>*</sup>, **Yuan Dong<sup>*</sup>**; Zhijian Song; Manning Wang

[**Code**](https://github.com/fdyuandong/2D-3D-Point-Set-Registration-Based-on-Global-Rotation-Search/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- New bounds for a global rotation search in 2D-3D registration. 

</div>
</div>

More Publications:
- [AniGS: Animatable Gaussian Avatar from a Single Image with Inconsistent Gaussian Reconstruction](https://arxiv.org/pdf/2412.02684/),  Lingteng Qiu, Shenhao Zhu, Qi Zuo, Xiaodong Gu, **Yuan Dong**, Junfei Zhang, Chao Xu, Zhe Li, Weihao Yuan, Liefeng Bo, Guanying Chen, Zilong Dong, **CVPR 2025**
- [LaMP: Language-Motion Pretraining for Motion Generation, Retrieval, and Captioning](https://arxiv.org/abs/2410.07093/),  Zhe Li, Weihao Yuan, Yisheng HE, Lingteng Qiu, Shenhao Zhu, Xiaodong Gu, Weichao Shen, **Yuan Dong**, Zilong Dong, Laurence Tianruo Yang, **ICLR 2025**
- [MoGenTS: Motion Generation based on Spatial-Temporal Joint Modeling](https://aigc3d.github.io/mogents/),  Weihao Yuan, Yisheng He, Weichao Shen, **Yuan Dong**, Xiaodong Gu, Zilong Dong, Liefeng Bo, **NeurIPS 2024**
- [An Optimization Framework to Enforce Multi-View Consistency for Texturing 3D Meshes Using Pre-Trained Text-to-Image Models](https://arxiv.org/pdf/2403.15559v1/),  Zhengyi Zhao, Chen Song, Xiaodong Gu, **Yuan Dong**, Qi Zuo, Weihao Yuan, Zilong Dong, Liefeng Bo, and Qixing Huang, **ECCV 2024**
- [Videomv: Consistent multi-view generation based on large video generative model](https://arxiv.org/pdf/2403.12010), Qi Zuo, Xiaodong Gu, Lingteng Qiu, **Yuan Dong**, Zhengyi Zhao, Weihao Yuan, Rui Peng, Siyu Zhu, Zilong Dong, Liefeng Bo, Qixing Huang, **2024**
- [PanoViT: Vision Transformer for Room Layout Estimation from a Single Panoramic Image](https://www.alphaxiv.org/abs/2212.12156), Weichao Shen, **Yuan Dong**, Zonghao Chen, Zhengyi Zhao, Yang Gao, Zhu Liu, **2022**

# 📦 Datasets

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ReplicPano</div><img src='images/dataset/replicapano.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PanoContext-Former: Panoramic Total Scene Understanding with a Transformer](https://github.com/fdyuandong/ReplicaPano-Dataset)

**Yuan Dong<sup>*</sup>**, Chuan Fang<sup>*</sup>, Liefeng Bo, Zilong Dong, Ping Tan

[**Download**](https://github.com/fdyuandong/ReplicaPano-Dataset/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- ReplicaPano is a new panoramic dataset that offers various ground truths, including photo-realistic panorama, depth maps, real-world 3D room layouts and 3D oriented object bounding boxes, and object meshes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GObjaverse</div><img src='images/dataset/gobjaverse.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[G-buffer Objaverse: High-Quality Rendering Dataset of Objaverse](https://aigc3d.github.io/gobjaverse/)

Chao Xu, **Yuan Dong**, Qi Zuo, Junfei Zhang, Xiaodan Ye, Wenbo Geng, Yuxiang Zhang, Xiaodong Gu, Lingteng Qiu, Zhengyi Zhao, Qing Ran, Jiayi Jiang, Zilong Dong, Liefeng Bo

[**Project**](https://aigc3d.github.io/gobjaverse//) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Download**](https://github.com/modelscope/richdreamer/tree/main/dataset/gobjaverse/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- High-Quality Rendering Dataset of Objaverse.
</div>
</div>


# 🎖 Honors and Awards
- *2024.05*, GPLD3D is selectd as one of 90 Oral presentations (3.3% accepted paper) by CVPR2024 
- *2019.09*, National Scholarship (Top 1%)


# 📖 Educations
- *2015.06 - 2020.09*, PhD, [MICCAI](https://miccai.fudan.edu.cn/), Fudan Univeristy, Shanghai.
- *2010.09 - 2015.06*, Undergraduate, Chongqing Medical University, Chongqing.


[//]: # (# 💬 Invited Talks)

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

[//]: # ()
[//]: # (# 💻 Internships)

[//]: # (- *2019.05 - 2020.02*, [Lorem]&#40;https://github.com/&#41;, China.)