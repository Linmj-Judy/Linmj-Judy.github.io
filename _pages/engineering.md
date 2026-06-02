---
permalink: /engineering/
title: "Research Engineering"
author_profile: true
redirect_from:
  - /engineering.html
---

My research experience covers the full engineering lifecycle of deep learning systems, from scientific data construction and model development to distributed training, inference, evaluation, and reproducible experimentation. I have independently implemented end-to-end research systems for protein dynamics generation, LLM evaluation, scientific foundation models, molecular representation learning, and AI-driven drug discovery.

Technical stack
------

* **Programming:** Python, Bash, LaTeX
* **Deep learning:** PyTorch, PyTorch Lightning, Hugging Face ecosystem, LoRA / PEFT-style fine-tuning, mixed-precision training
* **Generative modeling:** diffusion models, autoregressive generation, spectral representations, frequency-domain modeling, trajectory generation
* **Efficient Large-model systems:** DDP, multi-GPU workflows, Ray Tune, FlashAttention, Megatron, DeepSpeed, practical exposure to tensor/sequence parallelism, model sharding, inference acceleration
* **Scientific AI:** molecular graphs, molecular fingerprints, protein structures, molecular dynamics trajectories, ESM embeddings, BiHiTo features, OpenFold-style geometric modules, etc.
* **Data engineering:** dataloaders, multiprocessing, caching, large-scale preprocessing, benchmark construction, statistical evaluation
* **Research infrastructure:** Linux, Git, Docker, Slurm, WandB, CI/CD-style workflows, reproducible experiment pipelines

End-to-end scientific ML systems
------

* **Independently implemented [the full BioDynaSpec codebase](https://github.com/Linmj-Judy/BioDynaSpec)**, covering molecular dynamics data preparation, spectral preprocessing, geometric diffusion modeling, custom distributed/memory optimizations, training, inference, evaluation, visualization, and reproducibility documentation.
* Built complete workflows for dataset preprocessing, dataloader construction, model training, checkpointing, validation, inference, metric computation, and result analysis.
* Developed training and fine-tuning pipelines for diffusion models, autoregressive generative models, graph neural networks, molecular language models, and scientific multimodal models.
* Designed evaluation pipelines for both academic benchmarks and industrial LLM evaluation, supporting automated model comparison, error analysis, and iterative model improvement.

Scientific data engineering and trajectory preprocessing
------

* Built molecular dynamics trajectory preprocessing pipelines, including ATLAS data download, frame extraction, structural coordinate processing, Kabsch alignment, windowed Fourier decomposition (rFFT/iFFT), frequency-wise normalization, train/validation/test split construction, and reconstruction sanity checks.
* Implemented representation caching pipelines for protein sequence and structure features, including ESM embeddings, BiHiTo representations, and protein structure-derived features.
* Developed dataloaders and batch collation logic for molecular graphs, molecular fingerprints, protein structures, MD trajectories, scientific documents, and multimodal scientific data.
* Experienced in large-scale data cleaning, deduplication, normalization, caching, multiprocessing, padding/masking strategies, and GPU-friendly tensor formatting.

Model training, optimization, and distributed computing
------

* Experienced with PyTorch and PyTorch Lightning model implementation, including custom modules, loss functions, attention blocks, diffusion denoising networks, graph neural networks, and multimodal encoders.
* Built configurable training systems with YAML-based configs, checkpoint/resume logic, WandB logging, learning-rate scheduling, gradient clipping, validation hooks, and reproducibility control.
* Optimized memory-intensive scientific generation models using bf16 mixed precision, activation checkpointing, FlashAttention, chunked denoising, memory-aware batching, and dataloader/GPU memory debugging.
* Familiar with distributed training and inference workflows, including DDP, Ray Tune-based hyperparameter search, multi-GPU launch scripts, Megatron/DeepSpeed-style parallelism, and practical exposure to tensor and sequence parallelism, model sharding, and efficient attention implementations.

Generative model engineering
------

* Implemented frequency-domain autoregressive diffusion models with complex-valued spectral inputs, low-to-high frequency generation, diffusion denoising losses, structural attention bias (IRFC), and long-horizon rollout reconstruction.
* Integrated protein representation and structure-modeling components, including ESM embeddings, BiHiTo structural representations, OpenFold-style geometric modules, and Protenix-related utilities.
* Built inference systems for spectral-to-coordinate reconstruction, multi-window trajectory generation, Kabsch-aligned evaluation, sample diversity analysis, and trajectory/PDB export.
* Implemented scientific evaluation metrics for long-horizon molecular dynamics generation, including aligned coordinate errors (RMSE/MAE), long-horizon rollout metrics (R50/R100/R250), distributional distances (W2), PCA/tICA-based analyses, RMSF/PWD/RG, spectral consistency, diversity, and physical validity checks.
* Familiar with inference-time optimization for generative models, including caching, representation reuse, training-free acceleration, and test-time compute allocation.

Experiment orchestration
------

* Built configurable experiment orchestration with YAML-based configs, checkpoint/resume logic, WandB logging, Ray Tune hyperparameter search (ASHAScheduler), and reproducible shell entrypoints for data generation, training, inference, and analysis.

LLM and benchmark infrastructure
------

* Built evaluation and analysis pipelines for LLM reasoning, scientific question answering, literature understanding, code generation, and agentic task solving.
* Built large-scale automated evaluation pipelines for code-centric benchmarks such as LiveCodeBench and BigCodeBench, aligning results with public leaderboards for model iteration.
* Improved correctness and consistency of evaluation metrics such as pass@k, and implemented robust error handling for empty outputs, timeouts, invalid-language generations, and sandbox execution failures.
* Debugged multi-language execution environments, including testcase entrypoints, file-handle issues, concurrent temporary-file conflicts, compilation scripts, dependency management, and long-running cluster evaluation jobs.

Software engineering and research code quality
------

* Emphasize modular and maintainable research code, with clear separation of data processing, model architecture, training logic, inference scripts, evaluation modules, configuration files, and utility functions.
* Able to convert exploratory research code into reusable pipelines for larger-scale experiments, team collaboration, and reproducible research releases.
* Experienced with Linux, Git-based collaborative development, Bash scripting, Docker, Slurm, CI/CD-style workflows, experiment versioning, debugging, and reproducibility documentation.

[← Back to About](/)
