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


<!-- <div class="container">
        <img src="../cola_image/04-Hey.svg" alt="Hey, this is Laka!" class="foreground" />
</div> -->


<p align="center">
    <!-- <a href="https://github.com/Laka-3DV"> -->
      <!-- <img width="90%" alt="Hey, this is Laka!" src="../cola_image/04-Hey.svg" style="margin-top: -0px;" /> -->
      <img width="90%" alt="Hey, this is Laka!" src="../cola_image/07-Hey.png" style="margin-top: -0px;" />
    <!-- </a> -->
</p>

<!-- 
<p align="center">
    <a href="https://github.com/Laka-3DV">
        <img width="90%" alt="Hey, this is Laka!" src="../cola_image/06-Hey-dynamic.gif" style="margin-top: -0px;" />
    </a>
</p>
 -->


### 🧑‍💻 About Me

- **Master’s Student**, Wuhan University (Advisor: [Jiayuan Li](https://ljy-rs.github.io/web/))  
- **Research**: Point Cloud Registration, Robust Estimation, Keypoint Matching
<!-- SLAM, 3D reconstruction, -->
<!-- pose estimation -->
- **Contact**: [shaochengyan@whu.edu.cn](mailto:shaochengyan@whu.edu.cn)  
<!-- - **Open to collaboration** -->

> Excited for collaboration opportunities — reach out if you have questions or want to explore!

### 🔥 News

- *2025.06*:  🎉🎉 Our paper TurboReg is accepted by **<a href="https://iccv.thecvf.com/" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">ICCV 2025</a>**!
- *2025.02*:  🎉🎉 Our paper HeMoRa (zh: 赫默拉) is accepted by **<a href="https://cvpr.thecvf.com/Conferences/2025" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">CVPR 2025</a>**!
- *2024.11*:  🎉🎉 One paper is accepted by **<span style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">RA-L 2024</span>**!
- *2024.09*:  🎉🎉 One paper is accepted by <span style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">TGRS 2024</span>!
- *2024.07*:  🎉🎉 One paper is accepted by **<a href="https://eccv2024.ecva.net/" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">ECCV 2024</a>**!
- *2024.07*:  🎉🎉 My homepage is created!


<!-- ### 📚 Publications  -->
### 🖋️ First-Author Publications

<!-- TurboReg -->
<!-- Image -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div>
<img src='../paper_images/0004-turboreg.png' alt="TurboReg" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- Information -->
<a style="text-decoration: none; color: inherit;"><span style="background: linear-gradient(90deg, #ff7f50, #87cefa, #da70d6); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">TurboReg:</span></a>
TurboClique for Robust and Efficient Point Cloud Registration [[PDF](https://arxiv.org/pdf/2507.01439)] [[CODE](https://github.com/Laka-3DV/TurboReg)] [[BIB](https://arxiv.org/bibtex/2507.01439)]

**Shaocheng Yan**,
<a href="https://orcid.org/0000-0003-2504-9890" style="text-decoration: none; color: inherit;"><span>Pengcheng Shi</span></a>,
<a href="https://ericzzj1989.github.io/" style="text-decoration: none; color: inherit;"><span>Zhenjun Zhao</span></a>,
<a href="https://ericzzj1989.github.io/" style="text-decoration: none; color: inherit;"><span>Kaixin Wang</span></a>,
<a href="https://ericzzj1989.github.io/" style="text-decoration: none; color: inherit;"><span>Kuang Cao</span></a>,
<a href="https://ericzzj1989.github.io/" style="text-decoration: none; color: inherit;"><span>Ji Wu</span></a>,
<a href="https://ljy-rs.github.io/web/" style="text-decoration: none; color: inherit;"><span>Jiayuan Li</span></a>

**TL;DR:** A highly efficient and robust estimator for point cloud registration (PCR), supporting both CPU and GPU platforms.

<a href="https://iccv.thecvf.com/" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">
[ICCV 2025]
</a>International Conference on Computer Vision

</div></div>


<!-- HeMoRa -->
<!-- Image -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div>
<img src='../paper_images/0003-hemora.png' alt="HeMoRa" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


<!-- Information -->
<a style="text-decoration: none; color: inherit;"><span style="background: linear-gradient(90deg, #ff7f50, #87cefa, #da70d6); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">HeMoRa:</span></a>
Unsupervised Heuristic Consensus Sampling for Robust Point Cloud Registration  [[PDF]()] [[CODE](https://github.com/Laka-3DV/HeMoRa)] [[BIB](https://scholar.googleusercontent.com/scholar.bib?q=info:tjG9h2tNY34J:scholar.google.com/&output=citation&scisdr=ChZh9TUgAQPWeildyYkFYPqPEfhkkme8QVI:AAZF9b8AAAAAaGX_r1LJKSPvAWG5S6a6WVKMKv4&scisig=AAZF9b8AAAAAaGX_r6PIthz9uZJK1uTcii3gobM&scisf=4&ct=citation&cd=-1&hl=en)]


**Shaocheng Yan**,
<a href="https://yimingwangmingle.github.io/bio/" style="text-decoration: none; color: inherit;"><span>Yiming Wang</span></a>,
<a href="https://kaiyanzhaophoenix.github.io/bio/" style="text-decoration: none; color: inherit;"><span>Kaiyan Zhao</span></a>,
<a href="https://orcid.org/0000-0003-2504-9890" style="text-decoration: none; color: inherit;"><span>Pengcheng Shi</span></a>,
<a href="https://ericzzj1989.github.io/" style="text-decoration: none; color: inherit;"><span>Zhenjun Zhao</span></a>,
<a href="https://skyearth.org/zhangyj/" style="text-decoration: none; color: inherit;"><span>Yongjun Zhang</span></a>,
<a href="https://ljy-rs.github.io/web/" style="text-decoration: none; color: inherit;"><span>Jiayuan Li</span></a>

**TL;DR:** Learning a sampling probability distribution for matches in robust estimation, no supervision and reinforcement-inspired


<!-- <span style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">[CVPR 2025]</span> 
Computer Vision and Pattern Recognition -->

<a href="https://cvpr.thecvf.com/Conferences/2025" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">
[CVPR 2025]
</a>Computer Vision and Pattern Recognition


<!-- <div style="margin: 10px;">
        <span style="background-color: #e0e0e0; padding: 5px 10px; margin: 5px; border-radius: 5px; display: inline-block;">#point cloud registration</span>
        <span style="background-color: #e0e0e0; padding: 5px 10px; margin: 5px; border-radius: 5px; display: inline-block;">#keypoint matching</span>
        <span style="background-color: #e0e0e0; padding: 5px 10px; margin: 5px; border-radius: 5px; display: inline-block;">#semantic slam</span>
</div> -->


</div></div>

<!-- ML-SemReg -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='../paper_images/0001-ml_semreg.png' alt="ML-SemReg" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a style="text-decoration: none; color: inherit;"><span style="background: linear-gradient(90deg, #ff7f50, #87cefa, #da70d6); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">ML-SemReg:</span></a>
Boosting Point Cloud Registration with Multi-level Semantic Consistency [[PDF](https://arxiv.org/pdf/2407.09862)] [[CODE](https://github.com/Laka-3DV/ML-SemReg)] [[BIB](https://scholar.googleusercontent.com/scholar.bib?q=info:PcPA4MCDeisJ:scholar.google.com/&output=citation&scisdr=ChZh9TUgAQPWeildij_UWKX_IU6zTjBC1rk:AAZF9b8AAAAAaGX_7OQYEXyfMddul_FEzrkWTtY&scisig=AAZF9b8AAAAAaGX_7NAzXL36juNT2nrsHq9JKZQ&scisf=4&ct=citation&cd=-1&hl=en)]


**Shaocheng Yan**, 
<a href="https://orcid.org/0000-0003-2504-9890" style="text-decoration: none; color: inherit;"><span>Pengcheng Shi</span></a>,
<a href="https://ljy-rs.github.io/web/" style="text-decoration: none; color: inherit;"><span>Jiayuan Li</span></a>

**TL;DR:** Boosting 3D keypoint match recall using semantic labels, no learning needed and SLAM-ready

<!-- <span style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">[ECCV 2024]</span> European Conference on Computer Vision -->


<a href="https://eccv2024.ecva.net/" style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">
[ECCV 2024]
</a> European Conference on Computer Vision


</div></div>


### 🧩 Co-Authored Publications


<!-- TCF -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2024</div><img src='../paper_images/0002-ransac.png' alt="RANSAC Back to SOTA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

RANSAC Back to SOTA: A Two-stage Consensus Filtering for Real-time 3D Registration [[PDF](https://arxiv.org/abs/2410.15682)] [[Code](https://github.com/ShiPC-AI/TCF)]

Pengcheng Shi, **Shaocheng Yan**, Yilin Xiao, Xinyi Liu, Yongjun Zhang, Jiayuan Li

<span style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">[RA-L 2024]</span> IEEE Robotics and Automation Letters

</div></div>

<!-- PCSFormer -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2024</div><img src='../paper_images/0000-pcsformer.png' alt="PCSformer" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Proxy and Cross-Stripes Integration Transformer for Remote Sensing Image Dehazing [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10677537)] [[Code](https://github.com/SmileShaun/PCSformer)] [[Hazy-LoveDA Dataset](https://huggingface.co/datasets/SmileShaun/Hazy-LoveDA)] [[Hazy-DIOR Dataset](https://huggingface.co/datasets/SmileShaun/Hazy-DIOR)]

Xiaozhe Zhang, Fengying Xie, Haidong Ding, **Shaocheng Yan**, Zhenwei Shi

<span style="background: linear-gradient(90deg, #007bff, #00cc99, #9933ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">[TGRS 2024]</span>
IEEE Transactions on Geoscience and Remote Sensing

</div></div>


 
### 🏆 Honors and Awards

- *2025.04*, **<span style="background: linear-gradient(90deg, #00ffff, #ff00ff, #0033ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">Outstanding Graduate</span>**, Class of 2025  
- *2024.11*, **<span style="background: linear-gradient(90deg, #00ffff, #ff00ff, #0033ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">National Second Prize</span>**, China Graduate Mathematical Modeling Contest
- *2022.08*, **<span style="background: linear-gradient(90deg, #00ffff, #ff00ff, #0033ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">National First Prize (Champion)</span>**, China University Robotics Innovation Competition  
- *2020.12*, **<span style="background: linear-gradient(90deg, #00ffff, #ff00ff, #0033ff); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; font-weight: bold;">First Prize</span>**, 11th National College Student Mathematics Competition (Non-Math Major Category)


### 🎓 Educations
- *2023.09 - Present*, M.S. in Geomatics Engineering, School of Remote Sensing and Information Engineering, Wuhan University
- *2019.09 - 2023.06*, B.S. in Artificial Intelligence, School of Electronic and Information Engineering, Southwest Jiaotong University