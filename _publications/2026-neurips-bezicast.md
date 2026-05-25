---
title: "Tikhonov-Stabilized Bezier Representation Forecasting for Training-free Diffusion Acceleration"
collection: publications
permalink: /publication/2026-neurips-bezicast
excerpt: 'BeziCast accelerates diffusion inference via Tikhonov-stabilized low-order Bézier trajectory forecasting of denoiser representations, with convex-hull guardrails for stable extrapolation. Up to 4.79× speedup on FLUX.1 and 4.11× on HunyuanVideo with strong quality preservation.'
date: 2026-01-01
venue: 'Neural Information Processing Systems (NeurIPS 2026)'
paperurl: 'https://openreview.net/forum?id=6cYL3DrquA'
citation: 'Lei Zhu#, Mujie Lin#, Ruochong Zheng, Guangyi Wang, Hao Li, Peng Jin, Chang Liu, Jie Chen. &quot;Tikhonov-Stabilized Bezier Representation Forecasting for Training-free Diffusion Acceleration.&quot; <i>NeurIPS</i>, 2026.'
---

## Links

- **Paper**: [OpenReview](https://openreview.net/forum?id=6cYL3DrquA)
- **Code**: TBD — *add GitHub repository URL*

## Abstract

Diffusion models, particularly Diffusion Transformers, achieve strong image and video generation quality but remain expensive at inference time due to repeated denoiser evaluations. Feature caching offers a deployment-friendly acceleration strategy by reusing or predicting intermediate representations without retraining the generator or modifying the sampler. However, existing cache-then-forecast methods often rely on Taylor-style finite-difference extrapolation, which can become unstable over longer cache intervals, and typically predict local module outputs whose errors may accumulate through subsequent denoiser blocks. We propose $\textbf{BeziCast}$, a training-free diffusion acceleration framework that forecasts output-proximal denoising representations using low-order B'ezier trajectories. BeziCast estimates B'ezier control points via Tikhonov-stabilized fitting, providing a smooth, capacity-controlled temporal parameterization that avoids explicit high-order derivative estimation and decouples trajectory capacity from cache-query density. To moderate aggressive extrapolation, we further derive equivalent forecasting weights and introduce a convex-hull-inspired guardrail that detects high-risk predictions and softly pulls them toward a conservative simplex-projected estimate. Extensive evaluations across advanced image and video diffusion models demonstrate the effectiveness of BeziCast. In particular, BeziCast accelerates FLUX.1 by up to $4.79\times$ and HunyuanVideo by up to $4.11\times$, while preserving substantially better generation quality than competing acceleration baselines.

## Contribution

Co-first author. Research ideation, method design, implementation, experiments, and manuscript writing.
