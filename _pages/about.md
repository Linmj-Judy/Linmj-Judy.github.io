---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year **M.Phil. student in Computer Science** at [Peking University](https://www.pku.edu.cn/) (2025–2028). My research sits at the intersection of **AI for Science (AI4S)**, **computational biology**, and **generative deep learning**—with a long-term goal of building intelligent systems that understand and generate biomolecular behavior at scale.

Research narrative
======

My work follows a single thread: **from biology-grounded drug discovery, to science foundation models, to generative modeling of biomolecular dynamics and efficient deep learning systems.**

**Phase I — Biology-grounded AI for drug discovery (2021–2025, SCUT)**  
With a B.S. in Biotechnology (rank 1/56) and a CS minor, I spent four years in Prof. Ling Wang's lab building end-to-end AI platforms for medicinal chemistry: molecular representation learning ([FG-BERT](https://academic.oup.com/bib/article/24/6/bbad398/7337693)), large-scale anticancer virtual screening ([DeepCancerMap](https://www.sciencedirect.com/science/article/abs/pii/S0223523423003677)), and multistage antimalarial phenotypic prediction ([MalariaFlow](https://www.sciencedirect.com/science/article/abs/pii/S0223523424006573)). This phase taught me how to turn biological problems into reproducible data benchmarks, models, and deployable tools.

**Phase II — Science LLMs and industry-scale AI4S (2023–2025)**  
At [DP Technology](https://www.dp.tech/), [Westlake University](https://www.westlake.edu.cn/), and [KAUST CoE GenAI](https://cemse.kaust.edu.sa/genai), I moved from task-specific predictors to **foundation models for science**—contributing to [Uni-SMART](https://arxiv.org/abs/2403.10301) ([arXiv preprint](https://arxiv.org/abs/2403.10301); [Hugging Face Paper of the Day](https://huggingface.co/papers/2403.10301)) and [SciAssess](https://aclanthology.org/2025.findings-naacl.125/) for multimodal scientific literature understanding, and peptide structure alignment.

At **[MiniMax](https://www.minimax.io/)** (Foundation Language Model Team, Feb–Aug 2025), I contributed to **[MiniMax-M1](https://arxiv.org/abs/2506.13585)**—the world's first open-weight, large-scale hybrid-attention reasoning model (456B MoE, 1M-token context, Lightning Attention). I built the automated evaluation framework and reasoning benchmarks for coding and agentic tasks that supported large-scale pre-training and post-training iteration. The release reached [3.2k+ GitHub stars](https://github.com/MiniMax-AI/MiniMax-M1), [#1 on Hugging Face Daily Papers](https://huggingface.co/collections/MiniMaxAI/minimax-m1), and [media coverage](https://mp.weixin.qq.com/s/DpIz2fPKqfRThrTdZzG2ww).

**Phase III — Generative AI for biomolecular systems (2025–present, PKU)**  
My current focus shifts to **generative modeling of complex biomolecular processes**: long-horizon protein dynamics ([BioDynaSpec](https://icml.cc/virtual/2026/poster/63769), ICML 2026) and probabilistic autoregressive MD ([ProAR](https://ojs.aaai.org/index.php/AAAI/article/view/36974), AAAI 2026). I am interested in how spectral, geometric, and probabilistic structure can make generative models both **accurate over long horizons** and **efficient at deployment scale**.

Current research interests
======

* **AI-driven drug discovery (AIDD)** — molecular representation, property prediction, and virtual screening
* **Generative modeling for molecular & protein dynamics** — spatio-spectral, autoregressive, and diffusion-based approaches
* **LLM for Science** — scientific literature understanding, evaluation, and multimodal reasoning
* **Efficient deep learning** — scalable training, inference acceleration, and reproducible evaluation pipelines

Research Engineering
======

I build end-to-end research systems for scientific deep learning and foundation-model evaluation. I **independently implemented the full [BioDynaSpec](https://icml.cc/virtual/2026/poster/63769) codebase** ([GitHub](https://github.com/Linmj-Judy/BioDynaSpec))—MD-to-spectrum pipelines, AlphaFold3/OpenFold-style geometric diffusion modeling, custom sequence-parallel autograd ops, fine-grained activation checkpointing for memory-constrained training, PyTorch Lightning/DDP infrastructure, trajectory reconstruction, and scientific evaluation metrics. At MiniMax, I built industrial LLM evaluation infrastructure for coding and agentic tasks, sandboxed execution, and large-scale cluster workflows.

**[Full engineering profile →](/engineering/)**

Selected highlights
======

Academic & research highlights
------

* **BioDynaSpec** (ICML 2026, first author): spatio-spectral generative framework for long-horizon protein dynamics; >60% error reduction vs. SOTA on ATLAS  
* **MalariaFlow** & **DeepCancerMap** (EJMC, first/co-first author): published platforms for antimalarial and anticancer drug discovery  
* **Uni-SMART** (arXiv 2024): multimodal science literature model; [Hugging Face Paper of the Day](https://huggingface.co/papers/2403.10301)  
* **Google Scholar**: H-index 9, 411+ citations ([profile](https://scholar.google.com/citations?user=OXT8aDAAAAAJ&hl=zh-CN))

Industry highlight — MiniMax-M1
------

**[MiniMax-M1](https://arxiv.org/abs/2506.13585)** · Foundation Model Team **contributor** (MiniMax, 2025)

Open-weight hybrid-attention reasoning model scaling test-time compute with Lightning Attention. I designed and shipped the **automated evaluation framework** and **reasoning benchmarks** used across pre-training and post-training to shorten model iteration cycles and guide hybrid attention (Lightning + sliding window) optimization.

| | |
|---|---|
| **Paper** | [arXiv:2506.13585](https://arxiv.org/abs/2506.13585) |
| **Code** | [GitHub — 3.2k+ stars](https://github.com/MiniMax-AI/MiniMax-M1) |
| **Models** | [Hugging Face Collection](https://huggingface.co/collections/MiniMaxAI/minimax-m1) · [#1 Paper of the Day](https://huggingface.co/papers/2506.13585) |
| **Product** | [Try on MiniMax](https://www.minimax.io/) |
| **Press** | [WeChat coverage](https://mp.weixin.qq.com/s/DpIz2fPKqfRThrTdZzG2ww) |

Academic service
======

* **Journal reviewer**: *Scientific Reports*, *Bioinformatics*, *Molecular Diversity* (2025)  
* **Conference reviewer**: ACM MM 2026, NeurIPS 2026  

For a full publication list and CV, see [Publications](/publications/) and [CV](/cv/).  
A PDF résumé is available in the repository as `resume.tex`.

Contact
======

Feel free to reach me at [linmujiegz@163.com](mailto:linmujiegz@163.com) or [mjlin25@stu.pku.edu.cn](mailto:mjlin25@stu.pku.edu.cn).
