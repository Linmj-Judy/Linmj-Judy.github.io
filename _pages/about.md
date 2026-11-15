---
permalink: /
title: "Mujie Lin"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home-page" markdown="1">

Hi there! I am **Mujie Lin (林慕婕)**, an M.S. student in Computer Science at the [School of Electronic and Computer Engineering](https://www.ece.pku.edu.cn/), [Peking University](https://www.pku.edu.cn/), supervised by [Prof. Jie Chen](https://www.ece.pku.edu.cn/info/1046/2492.htm) at the [AIMIA Lab](https://aimia-pku.github.io/), with co-supervision from [Prof. Youdong Mao](https://www.aais.pku.edu.cn/info/1424/2799.htm). Before that, I received my B.S. in Biotechnology, with a minor in Computer Science, from the [South China University of Technology](https://www.scut.edu.cn/).

My research focuses on AI for Science, spanning scientific reasoning and agents, biomolecular dynamics and design, and generative modeling. I am particularly interested in building reliable scientific AI systems that combine foundation model reasoning, physically grounded generation, and verifiable scientific computation.

<!-- My research spans two complementary directions: **large language models and scientific agents**, focusing on post-training, evaluation, and scientific reasoning; and **scientific foundation and generative models**, with applications in biomolecular dynamics, protein and molecular design, and AI-driven drug discovery.

I am particularly interested in bridging **foundation model reasoning and biomolecular modeling** to advance reliable, verifiable, and AI-driven scientific discovery. -->


<iframe
  src="{{ '/research-interests.html' | relative_url }}"
  title="Research Interests"
  style="width:100%;height:800px;border:0;"
  loading="lazy">
</iframe>


<!-- ## Research Interest

* **Generative modeling for biomolecular dynamics:** spatio-spectral, autoregressive, and diffusion-based models for long-horizon protein and molecular dynamics generation.
* **AI-driven drug discovery:** molecular representation learning, property and phenotype prediction, virtual screening, and benchmark/platform development for medicinal chemistry.
* **Scientific foundation models:** multimodal and language models for scientific literature understanding, molecular knowledge reasoning, and AI4S evaluation.
* **Efficient scientific ML systems:** scalable training, inference acceleration, automated evaluation, and reproducible pipelines for research deployment.
 -->

<!-- ## Research Interests

* **Large Language Models and Scientific Agents**
  * **Foundation model evaluation and post-training** LLM evaluation, capability-driven data synthesis, supervised fine-tuning, reinforcement learning, and evaluation-driven model improvement.
  * **Scientific reasoning and agentic intelligence:** Scientific knowledge reasoning, tool-augmented problem solving, scientific agent post-training, and verifiable research workflows.

* **Scientific Foundation and Generative Models**
  * **Biomolecular dynamics:** Spatiotemporal and spatio-spectral generative modeling, autoregressive and diffusion-based molecular dynamics generation, and conformational ensemble modeling.
  * **Protein and molecular design:** Structure-conditioned generation, sequence–structure co-design, protein–ligand modeling, and dynamics-guided biomolecular design.
  * **AI-driven drug discovery:** Molecular representation learning, property and phenotype prediction, and virtual screening for medicinal chemistry. -->

## News

* **2026.10:** **[BeziCast](/publication/2026-bezicast)** (co-first author work) accepted to NeurIPS 2026 as a poster — training-free diffusion acceleration via Tikhonov-stabilized Bézier representation forecasting.
* **2026.09:** **[PhiFold](/publication/2026-phifold)** (co-first author work) released on arXiv — dynamic protein design via physics-structured covariance modeling.
* **2026.09:** **[OpenAI4S](/publication/2026-openai4s)** released on arXiv — an open-source scientific research agent with persistent execution and session-level provenance ([code](https://github.com/PKU-YuanGroup/OpenAI4S)).
* **2026.06:** **[SyntheticBench](/publication/2026-syntheticbench)** (work done during internship at Syneron Bio & KAUST Center of Excellence on Generative AI) accepted to *Genomics, Proteomics & Bioinformatics* (SCI, JCR Q1 TOP, IF = 13.9).
* **2026.05:** Co-authored **[The MiniMax-M2 Series: Mini Activations Unleashing Max Real-World Intelligence](/publication/2026-minimax-m2)**, an arXiv technical report on sparse Mixture-of-Experts models and agent-native reinforcement learning.
* **2026.05:** **[BioDynaSpec](/publication/2026-icml-biodynaspec)** (first-author work) accepted to ICML 2026.
* **2025.11:** **[ProAR](/publication/2026-aaai-proar)** accepted to AAAI 2026.
* **2025.06:** Contributed to **[MiniMax-M1](https://arxiv.org/abs/2506.13585)** in the MiniMax Foundation Language Model Team.
* **2025.05:** **[ADCNet](/publication/2025-adcnet)** published in *Briefings in Bioinformatics* (SCI, JCR Q1, IF = 8.7).
* **2025.02:** Joined the **MiniMax Foundation Language Model Team** as a research intern.
* **2025.01:** **[SciAssess](https://aclanthology.org/2025.findings-naacl.125/)** (work done during internship at [DP Technology](https://www.dp.tech/)) accepted to NAACL 2025 Findings.
* **2024.05:** **[MalariaFlow](/publication/2024-malariaflow)** (first-author work) published in *European Journal of Medicinal Chemistry* (SCI, JCR Q1, IF = 6.4).
* **2023.11:** **[FG-BERT](/publication/2023-fg-bert)** (second-author work) published in *Briefings in Bioinformatics* (SCI, JCR Q1, IF = 8.7).

## Selected Publications and Preprints

<div class="home-publication" markdown="1">
<div class="home-pub-venue">NeurIPS 2026</div>
<div class="home-pub-body" markdown="1">
**[Tikhonov-Stabilized Bézier Representation Forecasting for Training-free Diffusion Acceleration](/publication/2026-bezicast)**

Lei Zhu#, **Mujie Lin**#, Ruochong Zheng, Guangyi Wang, Hao Li, Peng Jin, Chang Liu†, Jie Chen†

[[Publication page](/publication/2026-bezicast)]

Training-free diffusion acceleration by forecasting output-proximal denoising representations along low-order Bézier trajectories, with Tikhonov-stabilized control-point fitting. Up to 4.79× speedup on FLUX.1 and 4.11× on HunyuanVideo.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">arXiv 2026</div>
<div class="home-pub-body" markdown="1">
**[PhiFold: Towards Dynamic Protein Design with Physics-Structured Covariance Modeling](/publication/2026-phifold)**

Yutian Liu#, **Mujie Lin**#, Lanqian Zhang#, Meng Fan, Chang Liu†, Zhiwei Nie†, Siwei Ma†

[[Paper](https://arxiv.org/abs/2609.32309)]

Joint generation of protein backbones and their second-order dynamics via a compact, physically constrained covariance representation.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">arXiv 2026</div>
<div class="home-pub-body" markdown="1">
**[OpenAI4S: Code as Action, Science as Sessions](/publication/2026-openai4s)**

Gongbo Zhang*, Hao Li*, Yu Wang, **Mujie Lin**, Liuzhenghao Lv, Yicheng Mao, Yimi Wang, Jun Zhu, Minhan Tang, Zhengxiang Jiang, Yusong Wang, Jiayu Yao, Kunpeng Ning, Dawei Pang, Yonghong Tian, OpenAI4S Community, Yuyang Liu, Li Yuan

[[Paper](https://arxiv.org/abs/2609.15096)] [[Code](https://github.com/PKU-YuanGroup/OpenAI4S)]

Open-source scientific research agent with a persistent runtime, append-only Action Ledger, and workspace checkpoints for inspectable, resumable, and reproducible long-horizon studies.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">ICML 2026</div>
<div class="home-pub-body" markdown="1">
**[BioDynaSpec: Harmonic-Guided Spatio-Spectral Autoregressive Diffusion for Protein Dynamics Generation](/publication/2026-icml-biodynaspec)**

**Mujie Lin**, Yutian Liu, Yudi Guo, Yanzhen Hou, Yiheng Tao, Ruochong Zheng, Kaiwen Cheng, Xin Shan, Youdong Mao, Jie Chen

[[Paper](https://icml.cc/virtual/2026/poster/63769)] [[Code](https://github.com/Linmj-Judy/BioDynaSpec)]

Spatio-spectral generative modeling for long-horizon protein dynamics, reducing trajectory error by over 60% on ATLAS.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">AAAI 2026</div>
<div class="home-pub-body" markdown="1">
**[ProAR: Probabilistic Autoregressive Modeling for Molecular Dynamics](/publication/2026-aaai-proar)**

Kaiwen Cheng, Yutian Liu, Zhiwei Nie, **Mujie Lin**, Yanzhen Hou, Yiheng Tao, Chang Liu, Jie Chen, Youdong Mao, Yonghong Tian

[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/36974)]

Probabilistic autoregressive generation of molecular dynamics trajectories with anti-drifting sampling for long-horizon stability.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">arXiv 2026</div>
<div class="home-pub-body" markdown="1">
**[The MiniMax-M2 Series: Mini Activations Unleashing Max Real-World Intelligence](/publication/2026-minimax-m2)**

Aili Chen, Aonian Li, ..., **Mujie Lin**, ..., et al.

[[Paper](https://arxiv.org/abs/2605.26494)] [[Models](https://huggingface.co/MiniMaxAI/MiniMax-M2)]

Technical report on sparse Mixture-of-Experts models, agent-native reinforcement learning, and real-world agentic intelligence.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">arXiv 2025</div>
<div class="home-pub-body" markdown="1">
**[MiniMax-M1: Scaling Test-Time Compute Efficiently with Lightning Attention](https://arxiv.org/abs/2506.13585)**

Aili Chen, Aonian Li, ..., **Mujie Lin**, ..., et al.

[[Paper](https://arxiv.org/abs/2506.13585)] [[Code](https://github.com/MiniMax-AI/MiniMax-M1)] [[Models](https://huggingface.co/collections/MiniMaxAI/minimax-m1)]

Open-weight hybrid-attention reasoning model. I built automated evaluation infrastructure and reasoning benchmarks for large-scale model iteration.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">BIB 2025</div>
<div class="home-pub-body" markdown="1">
**[ADCNet: a unified framework for predicting the activity of antibody-drug conjugates](/publication/2025-adcnet)**

Liye Chen#, Biaoshun Li#, Yihao Chen#, **Mujie Lin**, Shipeng Zhang, Chenxin Li, Yu Pang, Ling Wang

[[Paper](https://academic.oup.com/bib/article/26/3/bbaf228/8151285)] [[Code](https://github.com/idrugLab/ADCNet)] [[Webserver](https://ADCNet.idruglab.cn)]

A unified deep learning framework for antibody-drug conjugate activity prediction, integrating antigen, antibody, linker, payload, and DAR representations.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">EJMC 2024</div>
<div class="home-pub-body" markdown="1">
**[MalariaFlow: A Comprehensive Deep Learning Platform for Multistage Phenotypic Antimalarial Drug Discovery](/publication/2024-malariaflow)**

**Mujie Lin**, Junxi Cai, Yuancheng Wei, Xinru Peng, Qianhui Luo, Biaoshun Li, Yihao Chen, Ling Wang

[[Paper](https://www.sciencedirect.com/science/article/pii/S0223523424006573)][[Webserver](https://malariaflow.idruglab.cn)]

A curated antimalarial activity prediction platform for multistage phenotypic drug discovery.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">arXiv 2024</div>
<div class="home-pub-body" markdown="1">
**[Uni-SMART: Universal Science Multimodal Analysis and Research Transformer](/publication/2024-uni-smart)**

Hengxing Cai, Xiaochen Cai, Shuwen Yang, Jiankun Wang, Lin Yao, ..., **Mujie Lin**, ..., Guolin Ke

[[Project](https://uni-smart.dp.tech/)] [[Paper](https://arxiv.org/abs/2403.10301)] [[Code](https://github.com/dptech-corp/Uni-SMART)]

Multimodal scientific literature understanding for molecules, tables, and charts; featured as Hugging Face Paper of the Day.
</div>
</div>

<div class="home-publication" markdown="1">
<div class="home-pub-venue">BIB 2023</div>
<div class="home-pub-body" markdown="1">
**[FG-BERT: a generalized and self-supervised functional group-based molecular representation learning framework for properties prediction](/publication/2023-fg-bert)**

Biaoshun Li, **Mujie Lin**, Tiegen Chen, Ling Wang

[[Paper](https://academic.oup.com/bib/article/24/6/bbad398/7337693)] [[Code](https://github.com/idrugLab/FG-BERT)]

Functional-group-based molecular representation learning for transferable molecular property prediction, pertained based on ~1.45 million unlabeled drug-like molecules.
</div>
</div>

## Educations

* **2025.09 - now**, M.S. student in Computer Science and Technology, Peking University
* **2021.09 - 2025.06**, B.S. in Biotechnology, Minor in Computer Science, South China University of Technology

## Internships

* **2025.02 - 2025.08**, LLM Algorithm Intern, Foundation Language Model Team, MiniMax
* **2024.12 - 2025.03**, Machine Learning Research Intern, Syneron Bio & KAUST Center of Excellence on Generative AI
* **2024.07 - 2024.08**, Visiting Student, AI Computational Biology Lab, Westlake University
* **2023.07 - 2024.03**, AI4S Innovative Algorithm Researcher Intern, DP Technology

## Honors and Awards

* **2026:** Peking University Merit Student<br>
  Ranked 10th out of 115 students (top 8.7%) in the first academic year of the M.S. program.
* **2024:** **National College Student Innovation Training Program, Outstanding Completion | Project Leader**<br>
  Project: [*Application of a Multitask Deep Learning Algorithm for PI3K/AKT/mTOR (PAM) Pathway Inhibitor Activity Prediction and Development of a Cloud Computing Platform*](https://www.gjcxcy.cn/ZPZS/GGCG/Detail?XaBaZWAVWb1xqQ0hBBvLREBkPM1Mjfn2p9Hm4q8aStIhy7vmV7p010RBMUOz2o07) (Project No. 202310561121).<br>
  Selected as a Reform Achievement Showcase Project at the National College Students' Innovation Annual Conference, one of only four projects selected university-wide.
* **2023:** **National Grand Prize, 18th "Challenge Cup" China College Students' Extracurricular Academic Science and Technology Contest | Team Leader**<br>
  Historic achievement: First Grand Prize since 2011 and only the 3rd in university history (out of 1,000+ competing universities).<br>
  Project: [*"Jingcheng Smart Medicine, AI Empowerment" — Deep Learning-Driven Drug Design and Discovery: Methods and Applications*](https://mp.weixin.qq.com/s/dfnudr_sg4otRnXWMi9Xhw)
* **2022–2023:** Chinese National Scholarship


## Academic Service

* **Journal reviewer:** *Scientific Reports*, *Bioinformatics*, *Molecular Diversity*
* **Conference reviewer:** ACM MM 2026, NeurIPS 2026, AAAI 2026

</div>
