---
title: "BioDynaSpec: Harmonic-Guided Spatio-Spectral Autoregressive Diffusion for Protein Dynamics Generation"
collection: publications
permalink: /publication/2026-icml-biodynaspec
excerpt: 'A spatio-spectral generative framework for long-horizon protein molecular dynamics. Introduces IWFD frequency decomposition, hybrid autoregressive-diffusion generation, and IRFC structural priors. Reduces long-horizon trajectory error by over 60% on ATLAS vs. state-of-the-art methods.'
date: 2026-01-01
venue: 'International Conference on Machine Learning (ICML 2026)'
paperurl: 'https://icml.cc/virtual/2026/poster/63769'
citation: 'Mujie Lin, Yutian Liu, Yudi Guo, Yanzhen Hou, Yiheng Tao, Ruochong Zheng, Kaiwen Cheng, Xin Shan, Youdong Mao, Jie Chen. &quot;BioDynaSpec: Harmonic-Guided Spatio-Spectral Autoregressive Diffusion for Protein Dynamics Generation.&quot; <i>ICML</i>, 2026.'
---

## Links

- **Paper**: [ICML 2026](https://icml.cc/virtual/2026/poster/63769)
- **Code**: [GitHub](https://github.com/Linmj-Judy/BioDynaSpec)

## Abstract

Generating long-horizon molecular dynamics (MD) is difficult due to error accumulation in time-domain autoregressive models, which causes drift, and fixed step-size constraints on temporal resolution. We propose **BioDynaSpec**, which reformulates protein dynamics as spatio-spectral generation: **Independent Windowed Fourier Decomposition (IWFD)** decomposes trajectories into window-wise spectral representations, and a generator combines low-to-high frequency autoregression with diffusion denoising to reconstruct continuous motion. This formulation is motivated by **a local near-equilibrium view of protein dynamics**: after per-window alignment, fluctuations around an anchor conformation are better characterized in spectral space, where local mode structure is more explicit than in frame-wise coordinates. To improve cross-residue and cross-frequency consistency, we introduce **Inter-Residue Frequency Coupling (IRFC)**, a learnable Gaussian distance bias in attention that injects a resonance-inspired structural prior. On ATLAS, BioDynaSpec improves 250-frame trajectory generation with $R_{250}=1.509$ Å, where $R_s$ denotes the mean per-frame C$\alpha$-RMSE over the first $s$ frames after alignment, reducing error by 60.4\% versus MDGEN and 57.2\% versus ProAR, while achieving the best PCA-2D displacement-profile correlation and stepwise distribution matching. For equilibrium conformational sampling, it achieves Root Mean $W_2=1.31$, MD PCA $W_2=0.90$, and Joint PCA $W_2=1.19$, improving over the next best method by 50.03\%, 35.25\%, and 47.58\%, respectively. It also improves near-equilibrium local-dynamics and covariance consistency, achieving PCA-PSD-LogCorr $=0.817$ and CFRE $=0.989$, corresponding to a 21.9\% gain and a 36.7\% reduction over the next best method, respectively. The source code is available at https://github.com/Linmj-Judy/BioDynaSpec.

## Contribution

First author. Led end-to-end: problem formulation, method design (IWFD, hybrid AR-diffusion, IRFC), training pipeline, experiments, and manuscript writing.
