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

I am currently a PhD Candidate at the College of Computer Science and Artificial Intelligence, Fudan University w/ Prof. [Xingjun Ma](https://xingjunm.github.io/). 

Previously, I began my graduate studies at Fudan University in 2023 as a Master’s student and was fast-tracked/recommended for the doctoral program in 2025. Prior to this, I earned my Bachelor’s degree from Fudan University in 2023. In addition to my academic studies, I have been a Research Intern at
StepFun since June 2024, focusing on vector graphics generation. I am honored to work closely with [Wei Cheng](https://wchengad.github.io/) (StepFun), [Sijin Chen](https://ch3cook-fdu.github.io/)  (HKU MMLab), and Dr. [Gang Yu](https://www.skicyyu.org/) (StepFun).

My research interest includes vector graphics generation and generative models.


# 🔥 News
- *2026.02*: &nbsp;🎉🎉  We release [OmniLottie](https://openvglab.github.io/OmniLottie/), the first Lottie Generation model. Now accepted to <span style="color: #e74c3c;">**CVPR 2026**</span>!
  [![GitHub stars](https://img.shields.io/github/stars/OpenVGLab/OmniLottie?style=social)](https://github.com/OpenVGLab/OmniLottie)
- *2025.09*: &nbsp;🎉🎉 We release [OmniSVG](https://omnisvg.github.io/) a family of VLMs that generate SVGs. Now accepted to <span style="color: #e74c3c;">**NeurIPS 2025**</span>! 
  [![GitHub stars](https://img.shields.io/github/stars/OmniSVG/OmniSVG?style=social)](https://github.com/OmniSVG/OmniSVG)
- *2025.07*: &nbsp;🎉🎉 [Scene123](https://ojs.aaai.org/index.php/AAAI/article/view/28481) was accepted by <span style="color: #e74c3c;">**ACMMM 2025**</span>.  
- *2023.12*: &nbsp;🎉🎉 [Pm-inr](https://ojs.aaai.org/index.php/AAAI/article/view/28481) was accepted by <span style="color: #e74c3c;">**AAAI 2024**</span>. 

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge" style="background-color: #5261ff;">CVPR 2026</div>
      <img src='images/OmniLottie.gif' alt="OmniLottie" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[**OmniLottie: Generating Vector Animations via Parameterized Lottie Tokens**](https://openvglab.github.io/OmniLottie/)

**Yiying Yang**, Wei Cheng, Sijin Chen, Honghao Fu, Xianfang Zeng, Yujun Cai, Gang Yu, Xingjun Ma

[![Project](https://img.shields.io/badge/Project-Page-lightgrey)](https://openvglab.github.io/OmniLottie/) [![Paper](https://img.shields.io/badge/arXiv-2603.02138-b31b1b.svg)](https://arxiv.org/abs/2603.02138) [![GitHub stars](https://img.shields.io/github/stars/OpenVGLab/OmniLottie?style=social)](https://github.com/OpenVGLab/OmniLottie) [![Huggingface](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Demo-blue)](https://huggingface.co/OmniLottie) 
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge" style="background-color: #2ecc71;">NeurIPS 2025</div>
      <img src='images/OmniSVG.gif' alt="OmniSVG" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[**OmniSVG: A Unified Scalable Vector Graphics Generation Model**](https://omnisvg.github.io/)

**Yiying Yang**\*, Wei Cheng\*, Sijin Chen, Xianfang Zeng, Jiaxu Zhang, Liao Wang, Gang Yu, Xingjun Ma, Yu-Gang Jiang

[![Project](https://img.shields.io/badge/Project-Page-lightgrey)](https://omnisvg.github.io/) [![Paper](https://img.shields.io/badge/arXiv-2504.06263-b31b1b.svg)](https://arxiv.org/pdf/2504.06263) [![GitHub stars](https://img.shields.io/github/stars/OmniSVG/OmniSVG?style=social)](https://github.com/OmniSVG/OmniSVG) [![Huggingface](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Demo-blue)](https://huggingface.co/OmniSVG)
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge" style="background-color: #9b59b6;">ACM MM 2025</div>
      <img src='images/scene123.png' alt="Scene123" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[**Scene123: One Prompt to 3D Scene Generation via Video-Assisted and Consistency-Enhanced MAE**](https://arxiv.org/abs/2408.05477)

**Yiying Yang**\*, Fukun Yin\*, Jiayuan Fan, Xin Chen, Wanzhang Li, Gang Yu

[![Paper](https://img.shields.io/badge/arXiv-2408.05477-b31b1b.svg)](https://arxiv.org/abs/2408.05477)

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge" style="background-color: #34495e;">AAAI 2024</div>
      <img src='images/pminr.png' alt="Pm-inr" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[**Pm-inr: Prior-rich multi-modal implicit large-scale scene neural representation**](https://ojs.aaai.org/index.php/AAAI/article/view/28481)

**Yiying Yang**, Fukun Yin, Wen Liu, Jiayuan Fan, Xin Chen, Gang Yu, Tao Chen

[![Paper](https://img.shields.io/badge/Paper-AAAI-blue)](https://ojs.aaai.org/index.php/AAAI/article/view/28481)

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge" style="background-color: #34495e;">Arxiv Preprint</div>
      <img src='images/vqnerf.png' alt="Pm-inr" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[**Vq-nerf: Vector quantization enhances implicit neural representations**](https://arxiv.org/abs/2310.14487)

**Yiying Yang**, Wen Liu, Fukun Yin, Xin Chen, Gang Yu, Jiayuan Fan, Tao Chen

[![Paper](https://img.shields.io/badge/arXiv-2408.05477-b31b1b.svg)](https://arxiv.org/abs/2310.14487)

</div>
</div>

# 🎖 Honors and Awards
- *2024.10* Panasonic Scholarship, Fudan University. 
- *2023.06* Outstanding Graduates, Fudan University.
- *2022.10* First Class Scholarship, Fudan University.
- *2021,2022* Third Prize, 5th China Post-Graduate Artificial Intelligence Contest (Leader). 

# 📖 Educations
- *2025.09 - 2028.06(now)*, Ph.D. in Computer Science and Technology, Fudan University. 
- *2023.09 - 2025.06*, Master in Computer Science and Technology, Fudan University. 
- *2019.09 - 2023.06*, Bachelor in Electrical Engineering and Automation, Fudan University. 


# 💻 Internships
- *2024.06 - now*, [StepFun](https://www.stepfun.com/company), China.
