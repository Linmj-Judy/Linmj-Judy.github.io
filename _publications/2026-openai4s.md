---
title: "OpenAI4S: Code as Action, Science as Sessions"
collection: publications
permalink: /publication/2026-openai4s
excerpt: 'An open-source scientific research agent built around persistent computational state and provenance: scientific actions are complete code cells executed in persistent Python and R kernels, with an append-only Action Ledger, versioned artifacts, and workspace checkpoints enabling inspectable, resumable, and reproducible long-running studies.'
date: 2026-09-14
venue: 'arXiv preprint (arXiv:2609.15096)'
paperurl: 'https://arxiv.org/abs/2609.15096'
citation: 'Gongbo Zhang*, Hao Li*, Yu Wang, Mujie Lin, Liuzhenghao Lv, Yicheng Mao, Yimi Wang, Jun Zhu, Minhan Tang, Zhengxiang Jiang, Yusong Wang, Jiayu Yao, Kunpeng Ning, Dawei Pang, Yonghong Tian, OpenAI4S Community, Yuyang Liu, Li Yuan. &quot;OpenAI4S: Code as Action, Science as Sessions.&quot; <i>arXiv preprint</i> arXiv:2609.15096, 2026.'
---

## Links

- **Paper**: [arXiv:2609.15096](https://arxiv.org/abs/2609.15096)
- **Code**: [GitHub](https://github.com/PKU-YuanGroup/OpenAI4S)

## Abstract

AI co-scientists could accelerate computational research, but over a long-running study the workflow also has to stay inspectable, resumable and reproducible, which requires persistent computational state and provenance. Here we present OpenAI4S, an open-source scientific research agent built around the principle of *Code as Action, Science as Sessions*. OpenAI4S combines a persistent computing runtime with research-session management: orchestration is handled through structured tool calls, while scientific actions are represented as complete code cells executed in persistent Python and R kernels. An append-only Action Ledger, per-cell execution records, versioned artifacts, environment records, and workspace checkpoints preserve how results were produced and support session recovery, branching, and extension. Configurable sandboxing, permission controls, and code and trajectory screening provide complementary safeguards. We evaluate OpenAI4S on 36 research scenarios spanning retrosynthesis, molecular dynamics, protein binder design, protein mutation, catalyst screening, and mineral spectroscopy, measuring scientific task accuracy, workflow completeness, and reproducibility of the resulting repositories. OpenAI4S achieves an overall score of 7.83, compared with 5.7–6.4 for a general-purpose coding harness evaluated with three frontier models, with the largest gains on long-horizon and computation-intensive workflows. These results suggest that integrating persistent execution with session-level provenance can improve the reliability of AI-assisted scientific workflows. Environment specification and full rerunnability remain weak for every evaluated system, ours included, so reproducibility is still an open problem for scientific agents.

## Contribution

Contributing author (4th author). <!-- TODO: describe specific contribution -->

<small><sup>*</sup>These authors contributed equally to this work. <sup>&dagger;</sup>Members of the OpenAI4S Community are listed at the end of the paper. <sup>&ddagger;</sup>Corresponding author.</small>
