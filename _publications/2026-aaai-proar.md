---
title: "ProAR: Probabilistic Autoregressive Modeling for Molecular Dynamics"
collection: publications
permalink: /publication/2026-aaai-proar
excerpt: 'Probabilistic autoregressive framework for long-horizon MD generation with multivariate Gaussian timesteps, dual-network architecture, and anti-drifting sampling. Achieves 7.5% RMSE reduction and 25.8% improvement in dynamic pattern accuracy.'
date: 2026-01-01
venue: 'AAAI Conference on Artificial Intelligence (AAAI 2026)'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/36974'
citation: 'Kaiwen Cheng, Yutian Liu, Zhiwei Nie, Mujie Lin, Yanzhen Hou, Yiheng Tao, Chang Liu, Jie Chen, Youdong Mao, Yonghong Tian. &quot;ProAR: Probabilistic Autoregressive Modeling for Molecular Dynamics.&quot; <i>AAAI</i>, 2026.'
---

## Links

- **Paper**: [arXiv](https://ojs.aaai.org/index.php/AAAI/article/view/36974) <!-- TODO: update with AAAI/official link if different -->
- **Code**: TBD — *add GitHub repository URL*

## Abstract

<!-- TODO: paste official abstract here -->

Understanding the structural dynamics of biomolecules is crucial for uncovering biological functions. As molecular dynamics (MD) simulation data becomes more available, deep generative models have been developed to synthesize realistic MD trajectories. However, existing methods produce fixed-length trajectories by jointly denoising high-dimensional spatiotemporal representations, which conflicts with MD’s frame-by-frame integration process and fails to capture time-dependent conformational diversity. Inspired by MD's sequential nature, we introduce a new probabilistic autoregressive (ProAR) framework for trajectory generation. ProAR uses a dual-network system that models each frame as a multivariate Gaussian distribution and employs an anti-drifting sampling strategy to reduce cumulative errors. This approach captures conformational uncertainty and time-coupled structural changes while allowing flexible generation of trajectories of arbitrary length. Experiments on ATLAS, a large-scale protein MD dataset, demonstrate that for long trajectory generation, our model achieves a 7.5% reduction in reconstruction RMSE and an average 25.8% improvement in conformation change accuracy compared to previous state-of-the-art methods. For conformation sampling task, it performs comparably to specialized time-independent models, providing a flexible and dependable alternative to standard MD simulations.

## Contribution

Fourth author. Modeling design, large-scale data pipeline, training stabilization, and long-horizon evaluation.
