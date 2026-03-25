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

Hi! I'm Chunxiao Li. I received my M.Sc. in Statistics from Beijing Normal University, supervised by Prof. Chuanlong Xie. Since June 2025, I have been a research intern at [Shanghai Artificial Intelligence Laboratory](https://www.shlab.org.cn) (上海人工智能实验室). I will join the joint PhD program between Fudan University and Shanghai Artificial Intelligence Laboratory in September 2026.

My research interests broadly include AI Safety and vision-language models (VLMs).


# 🔥 News
- *2026.09*: I will enroll in the joint PhD program between **Fudan University** and **Shanghai Artificial Intelligence Laboratory**.
- *2025.06*: I joined **Shanghai Artificial Intelligence Laboratory** as a research intern.
- *2026.02*: 🎉 Our paper **"TreeTeaming: Autonomous Red-Teaming of Vision-Language Models via Hierarchical Strategy Exploration"** has been accepted by **CVPR 2026**! (First author)
- *2025.06*: 🎉 Our paper **"Towards Annotation-Free Evaluation: KPA-Score for Human Keypoint Detection"** has been accepted by **ICCV 2025**! (Co-First author)
- *2025.06*: 🎉 Our paper **"Bridging the Gap Between Ideal and Real-world Evaluation: Benchmarking
AI-Generated Image Detection in Challenging Scenarios"** has been accepted by **ICCV 2025**! (First author)
- *2025.3*: 🎉 Our paper **Noise Diffusion for Enhancing Semantic Faithfulness in Text-to-Image Synthesis** has been accepted by **CVPR 2025**! (Second author)
- *2024.11*: 🎉 Our paper **An Efficient Framework for Enhancing Discriminative Models via Diffusion Techniques** has been accepted by **AAAI 2025**! (Co-first author)
- *2024.11*: 🎉 Our paper **Prediction of iliac limb occlusion after endovascular aneurysm repair for abdominal aortic aneurysm by anatomical and near-wall hemodynamic characteristics combining numerical simulation and in vitro experiment** has been accepted by **Computer Methods and Programs in Biomedicine, IF=4.9. JCRQ1**! (Co-first author)
  
# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICCV 2025</div>
      <img src='images/kpa_score.png' alt="KPAScore" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Towards Annotation-Free Evaluation: KPAScore for Human Keypoint Detection**](#)

Xiaoxiao Wang\*, **Chunxiao Li**\*, Peng Sun, Boming Miao, Yunjian Zhang, Yao Zhu

- We propose *KPA-Score*, a new annotation-free evaluation metric for keypoint detection based on vision-language models (VLMs). Our method simulates human judgment through binary response probability and correlates strongly with mAP, achieving 0.71 correlation without using ground-truth annotations.
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICCV 2025</div>
      <img src='images/bench.png' alt="Fake Image Detection Benchmark" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Bridging the Gap Between Ideal and Real-world Evaluation: Benchmarking AI-Generated Image Detection in Challenging Scenarios**](#)

**Chunxiao Li**\*, Xiaoxiao Wang\*, Meiling Li, Boming Miao, Peng Sun, Yunjian Zhang, Xiangyang Ji, Yao Zhu

- We introduce a new benchmark for AI-generated image detection that incorporates real-world distortions such as social media compression and re-digitization. Extensive experiments reveal performance gaps in existing detectors and VLMs. We also propose a robustness-aware in-context few-shot prompting method for improved detection accuracy.
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2025</div>
      <img src='images/cvpr.png' alt="Noise Diffusion" width="90%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Noise Diffusion for Enhancing Semantic Faithfulness in Text-to-Image Synthesis**](https://arxiv.org/abs/2411.16503)

Boming Miao, **Chunxiao Li**, Xiaoxiao Wang, Andi Zhang, Rui Sun, Zizhe Wang, Yao Zhu

- We propose a simple yet effective method to optimize the latent noise of diffusion models using VLM-guided question-answering, aiming to improve semantic faithfulness of generated images. Our method is model-agnostic, training-free, and improves both VQA and CLIP-based alignment scores.
</div>
</div>
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AAAI 2025</div>
      <img src='images/aaai.png' alt="Diffusion Framework for Classification" width="90%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**An Efficient Framework for Enhancing Discriminative Models via Diffusion Techniques**]([#](https://ojs.aaai.org/index.php/AAAI/article/view/32493))

**Chunxiao Li**\*, Xiaoxiao Wang\*, Boming Miao, Chuanlong Xie, Zizhe Wang, Yao Zhu

- Inspired by brain-like reasoning, we design a plug-and-play diffusion-enhanced framework for classification tasks. Low-confidence samples are reprocessed via conditional denoising paths, leading to consistent improvements across ImageNet-1K, CIFAR-10/100, and multiple robustness benchmarks.
</div>
</div>

# 🎖 Honors and Awards
- *2021.09* 🏆 Second Prize (National), China Undergraduate Mathematical Contest in Modeling (CUMCM)

- *2022.12* 🥉 Third Prize (National), China Undergraduate Statistical Modeling Competition

- *2021.12* 🥉 Third Prize (National), China Undergraduate Statistical Modeling Competition

# 📖 Educations
- *2023.09 – 2025.06*, 🎓 M.Sc. in Statistics, Beijing Normal University (graduated).
- *2019.09 – 2023.06*, 🎓 B.Sc. in Information and Computing Science, University of Science and Technology Beijing.

# 🌱 Interests
I enjoy sports like **Muay Thai**, **strength training**, **Kick-Boxing**, and more. I pursue a robust physique and a free spirit.


