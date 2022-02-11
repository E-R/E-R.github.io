---
layout: page
title: Software
permalink: /software/
nav_order: 5
---

### Software

- **Keris** - “kernel of integrated single cells”, a framework for identifying systematic variation at the single-cell level by leveraging low-resolution population-level data. By inferring cell-type-specific moments and their variation across conditions using large tissue-level bulk data representing a population, Keris allows us to generate testable hypotheses at the single-cell level that would otherwise require collecting single-cell data from a large number of donors.
\[[GitHub](https://github.com/YosefLab/Keris)\] \[[paper](https://www.biorxiv.org/content/10.1101/2022.01.27.478115v1.abstract)\]

- **TCA** - Tensor Composition Analysis (TCA) allows the deconvolution of two-dimensional data (observations by features) coming from a mixture of heterogeneous sources into a three-dimensional tensor of signals (observations by features by sources). In the context of genomics, TCA can deconvolve tissue-level bulk data (individuals by features) into a tensor of cell-type-specific levels for each individual (individuals by features by cell types) and it allows one to detect cell-type-specific statistical relations (associations) with an outcome of interest.
\[[GitHub](https://github.com/cozygene/TCA)\] \[[paper](https://www.nature.com/articles/s41467-019-11052-9)\]

<!--
- **TCAx** - A distribution-free generalization of Tensor Composition Analysis (TCA). Considering the observation that the gene expression is often different yet coordinated between different cell types, TCAx models and accounts for covariances across cell types.
TCAx provides a transformative capacity to conduct more powerful large-scale cell-type level studies in multiple organisms, tissues, and under different conditions, for which bulk data have already been collected.
\[[GitHub](link)\] \[[paper](link)\]
-->

- **BayesCCE** - Bayesian Cell Count Estimation, a reference-free, semi-supervised method for estimating cell-type proportions from DNA methylation data collected from heterogeneous sources by leveraging an easily obtainable prior knowledge on the cell-type composition distribution of the studied tissue.
\[[GitHub](https://github.com/cozygene/BayesCCE)\] \[[paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1513-2)\]

- **GLINT** - A user-friendly command-line toolset for fast analysis of genome-wide DNA methylation data. GLINT, which does not require any programming proficiency, allows an easy execution of Epigenome-Wide Association Study (EWAS) analysis pipeline under different statistical models while accounting for known confounders in methylation data.
\[[GitHub](https://github.com/cozygene/glint)\] \[[paper](https://academic.oup.com/bioinformatics/article/33/12/1870/2976715)\]

- **EPISTRUCTURE** - A reference-based algorithm for the inference of ancestry information from methylation data, without the need for genetic data.
EPISTRUCTURE is based on an observation that ancestry is mirrored in genome-wide DNA methylation data and that it can be further isolated more effectively by leveraging the correlation structure of methylation CpGs with cis-located SNPs.
EPISTRUCTURE is available via GLINT (See above).
\[[paper](https://epigeneticsandchromatin.biomedcentral.com/articles/10.1186/s13072-016-0108-y)\]

- **ReFACTor** - Reference-Free Adjustment for Cell-Type composition, a sparse principal component analysis (PCA) under a column-sparse model. In the context of DNA methylation analysis, ReFACTor allows one to capture and correct for cell-type heterogeneity in an unsupervised manner.
\[[GitHub](https://github.com/cozygene/refactor)\] \[[paper](https://www.nature.com/articles/nmeth.3809)\]
