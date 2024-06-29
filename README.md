# Tau-analysis
This repository contains code for the whole-brain-scale analysis of pTau depositions, utilizing datasets imaged through tissue clearing and light-sheet microscopy.

## Overview
The primary objective of this code is to facilitate the identification and analysis of pTau protein deposition patterns across the entire brain. Our methods integrate several advanced computational techniques and visualization tools to achieve this goal.

## Basic Workflow
The basic procedure for analyzing whole-brain tau depositions consists of the following steps:

### 1. Expert Review: Initially, raw data undergo a thorough review by experts to exclude any non-specifically stained anatomical regions.
2. Voxel Scale Normalization: Data are normalized to a resolution of 8.3x8.3x8.3 µm to ensure uniformity across different datasets.
3. Tau Deposition ROI Extraction: Regions of interest (ROIs) for tau deposition are identified using a Gaussian-mean difference method. This is implemented in the **Tau extraction.ipynb** notebook.
4. CUBIC-Cloud Registration: Following ROI extraction, data are registered to a mouse brain atlas using CUBIC-Cloud, a software tool designed for whole-brain visualization and analysis. The guidelines were detailed in Mano T et al., CellRepMethods, 2021 ([DOI](https://doi.org/10.1016/j.crmeth.2021.100038)https://doi.org/10.1016/j.crmeth.2021.100038).

## Advanced Analysis
Further analysis is conducted through the following advanced procedures:

1. Tau Gradient Consensus Analysis: Detailed workflow for consensus analysis on tau gradients, structured in **Tau gradient consensus analysis.ipynb**.
2. Whole Brain Data Visualization: Comprehensive tools and methods for visualizing the whole brain data, structured in **Tau gradient consensus analysis.ipynb**.

## System Requirements
This code has been tested on a CentOS Linux release 7.9.2009 (Core) PC within a Python 3.6.8 virtualenv environment.

## Citation
If you utilize this code in your research, please cite our paper:
### A Novel Tauopathy Model Mimicking Molecular and Spatial Aspects of Human Tau Pathology
Authors: Rin Yanai, Tomoki T. Mitani, Etsuo A. Susaki, Takeharu Minamihisamatsu, Masafumi Shimojo, Yuri Saito, Hiroshi Mizuma, Nobuhiro Nitta, Daita Kaneda, Yoshio Hashizume, Gen Matsumoto, Kentaro Tanemura, Ming-Rong Zhang, Makoto Higuchi, Hiroki R. Ueda, Naruhiko Sahara.
Journal: Brain Communications, 2024 (Accepted)
DOI: under preparation




T
