---
title: "PhiFold: Towards Dynamic Protein Design with Physics-Structured Covariance Modeling"
collection: publications
permalink: /publication/2026-phifold
excerpt: 'A framework for jointly generating protein backbones and their second-order dynamics. Decomposes residue-displacement covariance into local flexibility, low-rank collective motion, and residue-wise collective participation, assembled into a positive-definite covariance with exact marginal consistency.'
date: 2026-09-26
venue: 'arXiv preprint (arXiv:2609.32309)'
paperurl: 'https://arxiv.org/abs/2609.32309'
citation: 'Yutian Liu#, Mujie Lin#, Lanqian Zhang#, Meng Fan, Chang Liu&dagger;, Zhiwei Nie&dagger;, Siwei Ma&dagger;. &quot;PhiFold: Towards Dynamic Protein Design with Physics-Structured Covariance Modeling.&quot; <i>arXiv preprint</i> arXiv:2609.32309, 2026.'
---

## Links

- **Paper**: [arXiv:2609.32309](https://arxiv.org/abs/2609.32309)
- **Code**: TBD — *add GitHub repository URL*

## Abstract

Protein design is moving beyond structural correctness toward function-aware design, yet existing generative models typically treat dynamics as a downstream property estimated through simulation or prediction after structure generation. Using MD trajectories as a generative target is also undesirable because stochastic, path-dependent trajectories over-specify the underlying equilibrium ensemble. We introduce PhiFold, a framework for jointly generating protein backbones and their second-order dynamics, represented by residue-displacement covariance. Rather than predicting the quadratically sized full covariance, PhiFold decomposes dynamics into three interpretable components: local flexibility, a low-rank collective-motion representation, and residue-wise collective participation. These components are assembled into a positive-definite covariance matrix with exact marginal consistency, yielding a compact and physically constrained representation of equilibrium dynamics. Across generated proteins, PhiFold improves recovery of local fluctuations and long-range residue coupling while remaining competitive on dominant collective-motion subspaces. It further enables bidirectional control of residue flexibility while preserving backbone designability. By unifying structure generation with an explicit representation of equilibrium dynamics, PhiFold lays a foundation for designing proteins not only by how they look, but also by how they move.

## Contribution

Co-first author (equal contribution). <!-- TODO: describe specific contribution -->

<small><sup>#</sup>These authors contributed equally. <sup>&dagger;</sup>Corresponding author.</small>
