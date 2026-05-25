---
title: "FG-BERT: a generalized and self-supervised functional group-based molecular representation learning framework for properties prediction"
collection: publications
permalink: /publication/2023-fg-bert
excerpt: 'Functional-group-based molecular language model with self-supervised pre-training for transfer learning on 44 molecular property benchmarks, outperforming state-of-the-art methods.'
date: 2023-01-01
venue: 'Briefings in Bioinformatics (SCI Q1, IF = 7.7)'
paperurl: 'https://academic.oup.com/bib/article/24/6/bbad398/7337693'
citation: 'Biaoshun Li, Mujie Lin, Tiegen Chen, Ling Wang. &quot;FG-BERT.&quot; <i>Brief. Bioinform.</i>, 2023.'
---

## Links

- **Paper**: [Briefings in Bioinformatics](https://academic.oup.com/bib/article/24/6/bbad398/7337693)
- **Code**: [Github](https://github.com/idrugLab/FG-BERT)

## Abstract

<!-- TODO: paste official abstract here -->

Artificial intelligence-based molecular property prediction plays a key role in molecular design such as bioactive molecules and functional materials. In this study, we propose a self-supervised pretraining deep learning (DL) framework, called functional group bidirectional encoder representations from transformers (FG-BERT), pertained based on ~1.45 million unlabeled drug-like molecules, to learn meaningful representation of molecules from function groups. The pretrained FG-BERT framework can be fine-tuned to predict molecular properties. Compared to state-of-the-art (SOTA) machine learning and DL methods, we demonstrate the high performance of FG-BERT in evaluating molecular properties in tasks involving physical chemistry, biophysics and physiology across 44 benchmark datasets. In addition, FG-BERT utilizes attention mechanisms to focus on FG features that are critical to the target properties, thereby providing excellent interpretability for downstream training tasks. Collectively, FG-BERT does not require any artificially crafted features as input and has excellent interpretability, providing an out-of-the-box framework for developing SOTA models for a variety of molecule (especially for drug) discovery tasks.

## Contribution

Second author. Downstream fine-tuning design, distributed training, and 1–2× fine-tuning speedup via pipeline optimization.
