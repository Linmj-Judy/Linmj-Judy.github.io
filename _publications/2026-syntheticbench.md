---
title: "Structure Prediction of Peptides Containing Non-Canonical Amino Acids: A Comprehensive Benchmark of Full-Atom Prediction Algorithms"
collection: publications
permalink: /publication/2026-syntheticbench
excerpt: 'A benchmark study evaluating leading all-atom structure prediction models on canonical and modified peptide–protein complexes, providing practical guidance for protocol selection across diverse peptide design scenarios.'
date: 2026-06-04
venue: 'Genomics, Proteomics & Bioinformatics (SCI Q1 TOP, IF = 13.9)'
paperurl: ''

citation: 'Yu Wang, Yifan Deng, Fuming Zeng, Mujie Lin, Tao Guo, Bin Cong, Shiwei Sun, Xin Gao. "Structure Prediction of Peptides Containing Non-Canonical Amino Acids: A Comprehensive Benchmark of Full-Atom Prediction Algorithms." <i>Genomics, Proteomics & Bioinformatics</i>, accepted, 2026.'

---

## Links

- **Paper**: TBD — *add paper URL*
- **Code**: TBD — *add GitHub repository URL*

## Abstract

<!-- TODO: paste official abstract here -->

Peptides are emerging as a highly promising class of therapeutic agents, but those composed solely of canonical amino acids often suffer from poor stability, rapid degradation, and low bioavailability. To address these limitations, peptides are frequently engineered with non-canonical amino acids or complex topologies such as cyclic or bicyclic structures, which improve their pharmacological properties. Most existing protein structure prediction algorithms fail to accommodate non-canonical amino acids or specialized linkers. Recent advances in all-atom structure prediction algorithms, exemplified by AlphaFold 3, overcome this by supporting flexible inputs, including post-translational modifications and covalent linkers. To evaluate current algorithms on structurally diverse peptides, we curated a benchmark dataset covering both canonical and modified peptides. We systematically assessed AlphaFold 2, AlphaFold 3, HelixFold 3, ProteniX, Chai-1, and Boltz2. Our results indicate that current methods exhibit broadly comparable performance in peptide binding site prediction, with differences largely depending on input modality rather than model architecture. Models such as AlphaFold 3 and ProteniX demonstrate relatively stable performance across diverse settings, while sequence-based and PTM-based inputs consistently enable more reliable predictions. Finally, we propose a practical strategy for selecting appropriate prediction protocols under different scenarios, facilitating the identification of more reliable peptide–protein complex structures.

## Contribution

Forth author. Provided task definition, evaluation protocols, and baseline analysis.
