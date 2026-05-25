---
title: "DeepCancerMap: A versatile deep learning platform for target- and cell-based anticancer drug discovery"
collection: publications
permalink: /publication/2023-deepcancermap
excerpt: 'Large-scale anticancer dataset (25.63M records) and 832 FP-GNN models with web platform for virtual screening and similarity search. AUC up to 0.91 on benchmark test sets with time-split external validation.'
date: 2023-01-01
venue: 'European Journal of Medicinal Chemistry (SCI Q1 TOP, IF = 7.1)'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0223523423003677'
citation: 'Jingxing Wu#, Yi Xiao#, Mujie Lin#, Hanxuan Cai, Duancheng Zhao, Yirui Li, Hailin Luo, Chuanqi Tang, Ling Wang. &quot;DeepCancerMap.&quot; <i>Eur. J. Med. Chem.</i>, 2023.'
---

## Links

- **Paper**: [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0223523423003677)
- **Code**: TBD — *add GitHub repository URL*

## Abstract

<!-- TODO: paste official abstract here -->

Discovering new anticancer drugs has been widely concerned and remains an open challenge. Target- and phenotypic-based experimental screening represent two mainstream anticancer drug discovery methods, which suffer from time-consuming, labor-intensive, and high experimental costs. In this study, we collected 485,900 compounds involving in 3,919,974 bioactivity records against 426 anticancer targets and 346 cancer cell lines from academic literature, as well as 60 tumor cell lines from NCI-60 panel. A total of 832 classification models (426 target- and 406 cell-based predictive models) were then constructed to predict the inhibitory activity of compounds against targets and tumor cell lines using FP-GNN deep learning method. Compared to the classical machine learning and deep learning methods, the FP-GNN models achieve considerable overall predictive performance, with the highest AUC values of 0.91, 0.88, 0.91 for the test sets of targets, academia-sourced and NCI-60 cancer cell lines, respectively. A user-friendly webserver called DeepCancerMap and its local version were developed based on these high-quality models, enabling users to perform anticancer drug discovery-related tasks including large-scale virtual screening, profiling prediction of anticancer agents, target fishing, and drug repositioning. We anticipate this platform to accelerate the discovery of anticancer drugs in the field. DeepCancerMap is freely available at https://deepcancermap.idruglab.cn.

## Contribution

Co-first author. Target-based dataset curation, deep learning modeling, interpretability analysis, and case studies.
