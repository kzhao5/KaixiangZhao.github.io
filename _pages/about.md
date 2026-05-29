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

I am a Ph.D. student in Computer Science at Brigham Young University (BYU), where I work with <a href="https://science.byu.edu/directory/porter-jenkins">Prof. Porter Jenkins</a>. I received my M.S. in Computer Science and Engineering from the University of Notre Dame, and my B.Eng. in Computer Science from Beijing Jiaotong University.

My research is in AI/ML, with a focus on Large Language Models (LLMs), Vision-Language and Multimodal Large Language Models (VLMs/MLLMs), computer vision, and trustworthy AI. I am particularly interested in post-training and reasoning distillation, test-time scaling, multimodal hallucination mitigation, and image forensics. I work day-to-day with PyTorch, Hugging Face Transformers, vLLM, DeepSpeed, and PEFT/LoRA, building reproducible distributed training and evaluation pipelines.

I am actively seeking research internships in LLMs, VLMs, multimodal reasoning, generative AI, and AI safety. I am always happy to connect and discuss related ideas.


# 🔥 News
- *2026.02*: &nbsp;🎉 *FRAME* was accepted to the **CVPR 2026 SAFE Workshop**.
- *2026.01*: &nbsp;🎉 *ICPO* was accepted to **ICLR 2026**.


# 📝 Publications 

(\* denotes equal contribution)

## Image Forensics & Multimodal AI Safety

- **FRAME: Forensic Routing and Adaptive Multi-path Evidence Fusion for Image Manipulation Detection**  
  **Kaixiang Zhao**, Tianrun Yu, Aoxu Zhang, Junhao Su, Porter Jenkins, Amanda Hughes  
  *CVPR 2026 SAFE Workshop*

- **TIGER: Traceable Inference with Graph-based Evidence Routing for Multimodal Generation**  
  **Kaixiang Zhao**, et al.  
  *EMNLP 2026 (under review)*

## LLM Reasoning, Distillation & Test-Time Optimization

- **LARK: Learnability-Grounded Trajectory Selection for Efficient Reasoning Distillation**  
  Tianrun Yu, **Kaixiang Zhao**, et al.  
  *NeurIPS 2026 (under review)*

- **Provable and Practical In-Context Policy Optimization for Self-Improvement**  
  Tianrun Yu, Yuxiao Yang, Zhaoyang Wang, **Kaixiang Zhao**, Porter Jenkins, Xuchao Zhang, Chetan Bansal, Huaxiu Yao, Weitong Zhang  
  *ICLR 2026*  
  [PDF](https://arxiv.org/pdf/2603.01335)

## Trustworthy AI & Model Security

- **A Survey on Model Extraction Attacks and Defenses for Large Language Models**  
  **Kaixiang Zhao**, Lincan Li, Kaize Ding, Neil Zhenqiang Gong, Yue Zhao, Yushun Dong  
  *KDD 2025 Tutorial*


# 📖 Educations
- *2025.08 - 2028.05 (Expected)*, Ph.D. in Computer Science, Brigham Young University, Provo, USA
- *2023.08 - 2025.08*, M.S. in Computer Science and Engineering, University of Notre Dame, USA
- *2020.09 - 2024.06*, B.Eng. in Computer Science, Beijing Jiaotong University, Beijing, China


# 🛠 Skills
- **Programming & Systems**: Python, C/C++, Bash, SQL, Git, Linux, CUDA, Docker, Slurm, LaTeX
- **ML/DL Frameworks**: PyTorch, Hugging Face Transformers, JAX, TensorFlow, vLLM, DeepSpeed, Accelerate, PEFT/LoRA, FlashAttention, NumPy, Pandas, scikit-learn
- **LLMs & Post-Training**: supervised fine-tuning, instruction tuning, reasoning distillation, chain-of-thought reasoning, test-time scaling, policy/preference optimization, model evaluation
- **VLMs, Vision & Multimodal AI**: Vision-Language Models, Multimodal LLMs, computer vision, generative AI, image/audio-text modeling, image forensics, cross-modal consistency, hallucination mitigation
- **Research Engineering**: distributed training, multi-GPU inference, model serving, retrieval-augmented generation, embeddings & vector search, reproducible evaluation pipelines, benchmark design, ablation studies
