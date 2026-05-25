---
title: "MalariaFlow: A Comprehensive Deep Learning Platform for Multistage Phenotypic Antimalarial Drug Discovery"
collection: publications
permalink: /publication/2024-malariaflow
excerpt: 'Considering the limitation of previous antimalarial activity prediction models in neglecting the multi-stage/multi-phenotype activity of Plasmodium, this study constructs a comprehensive data benchmark covering the three major life cycles of Plasmodium falciparum and activity test data from ten common mutant strains. Building upon this foundation, we propose an adaptive neural network, FP-GNN, which integrates molecular fingerprints and molecular graphs, effectively leveraging the advantages of chemical prior knowledge and graph representation learning. Compared to mainstream algorithms, FP-GNN achieves a 9.5% and 7.4% improvement in AUC and BA metrics, respectively, significantly enhancing the accuracy and robustness of Plasmodium activity prediction.'
date: 2024-05-19
venue: 'European Journal of Medicinal Chemistry (SCI Q1 TOP, IF = 7.1)'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0223523424006573'
citation: 'Mujie Lin, Junxi Cai, Yuancheng Wei, Xinru Peng, Qianhui Luo, Biaoshun Li, Yihao Chen, Ling Wang. &quot;MalariaFlow: A Comprehensive Deep Learning Platform for Multistage Phenotypic Antimalarial Drug Discovery.&quot; <i>Eur. J. Med. Chem.</i>, 2024.'
---

## Links

- **Paper**: [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0223523424006573)
- **Code**: TBD — *add GitHub repository URL*

## Abstract

<!-- TODO: paste official abstract here -->

Malaria remains a significant global health challenge due to the growing drug resistance of Plasmodium parasites and the failure to block transmission within human host. While machine learning (ML) and deep learning (DL) methods have shown promise in accelerating antimalarial drug discovery, the performance of deep learning models based on molecular graph and other co-representation approaches warrants further exploration. Current research has overlooked mutant strains of the malaria parasite with varying degrees of sensitivity or resistance, and has not covered the prediction of inhibitory activities across the three major life cycle stages (liver, asexual blood, and gametocyte) within the human host, which is crucial for both treatment and transmission blocking. In this study, we manually curated a benchmark antimalarial activity dataset comprising 407,404 unique compounds and 410,654 bioactivity data points across ten Plasmodium phenotypes and three stages. The performance was systematically compared among two fingerprint-based ML models (RF::Morgan and XGBoost:Morgan), four graph-based DL models (GCN, GAT, MPNN, and Attentive FP), and three co-representations DL models (FP-GNN, HiGNN, and FG-BERT), which reveal that: 1) The FP-GNN model achieved the best predictive performance, outperforming the other methods in distinguishing active and inactive compounds across balanced, more positive, and more negative datasets, with an overall AUROC of 0.900; 2) Fingerprint-based ML models outperformed graph-based DL models on large datasets (>1000 compounds), but the three co-representations DL models were able to incorporate domain-specific chemical knowledge to bridge this gap, achieving better predictive performance. These findings provide valuable guidance for selecting appropriate ML and DL methods for antimalarial activity prediction tasks. The interpretability analysis of the FP-GNN model revealed its ability to accurately capture the key structural features responsible for the liver- and blood-stage activities of the known antimalarial drug atovaquone. Finally, we developed a web server, MalariaFlow, incorporating these high-quality models for antimalarial activity prediction, virtual screening, and similarity search, successfully predicting novel triple-stage antimalarial hits validated through experimental testing, demonstrating its effectiveness and value in discovering potential multistage antimalarial drug candidates.

## Contribution

First author. Literature review, research design, data mining/cleaning, modeling, analysis, visualization, and manuscript writing.
