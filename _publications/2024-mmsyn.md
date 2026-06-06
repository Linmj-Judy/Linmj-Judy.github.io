---
title: "MMSyn: A New Multimodal Deep Learning Framework for Enhanced Prediction of Synergistic Drug Combinations"
collection: publications
permalink: /publication/2024-mmsyn
excerpt: 'Multimodal framework integrating drug molecular features and cancer cell line characteristics for synergistic combination prediction in cancer therapy.'
date: 2024-04-27
venue: 'Journal of Chemical Information and Modeling (SCI Q1, IF = 6)'
paperurl: 'https://pubs.acs.org/doi/full/10.1021/acs.jcim.4c00165'
citation: 'Yu Pang#, Yihao Chen#, Mujie Lin, Yanhong Zhang, Jiquan Zhang, Ling Wang. &quot;MMSyn.&quot; <i>J. Chem. Inf. Model.</i>, 2024.'
---

## Links

- **Paper**: [JCIM](https://pubs.acs.org/doi/full/10.1021/acs.jcim.4c00165)
- **Code**: [GitHub](https://github.com/idrugLab/MMSyn)

## Abstract

Combination therapy is a promising strategy for the successful treatment of cancer. The large number of possible combinations, however, mean that it is laborious and expensive to screen for synergistic drug combinations in vitro. Nevertheless, because of the availability of high-throughput screening data and advances in computational techniques, deep learning (DL) can be a useful tool for the prediction of synergistic drug combinations. In this study, we proposed a multimodal DL framework, MMSyn, for the prediction of synergistic drug combinations. First, features embedded in the drug molecules were extracted: structure, fingerprint, and string encoding. Then, gene expression data, DNA copy number, and pathway activity were used to describe cancer cell lines. Finally, these processed features were integrated using an attention mechanism and an interaction module and then input into a multilayer perceptron to predict drug synergy. Experimental results showed that our method outperformed five state-of-the-art DL methods and three traditional machine learning models for drug combination prediction. We verified that MMSyn achieved superior performance in stratified cross-validation settings using both the drug combination and cell line data. Moreover, we performed a set of ablation experiments to illustrate the effectiveness of each component and the efficacy of our model. In addition, our visual representation and case studies further confirmed the effectiveness of our model. All results showed that MMSyn can be used as a powerful tool for the prediction of synergistic drug combinations.

## Contribution

Third author. Benchmarking, cross-validation, interpretability, and ablation experiments.
