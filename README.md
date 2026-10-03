# RMLS-Tunnel17

This repository is reserved for the public data release accompanying the manuscript:

**Fine-grained Semantic Segmentation of RMLS Shield Tunnel Point Clouds for Automated Structural Health Assessment: Joint-MinkUNet with Cylindrical Geometry Adaptation and Element Distribution-aware Learning**

## Data availability

**If the manuscript is accepted for publication, a representative 100-meter annotated subset of RMLS-Tunnel17 will be publicly released through this repository**, together with data preprocessing scripts and semantic label definitions. The public subset is not available at this stage.

The full raw dataset cannot be publicly released due to safety and operational management constraints of in-service metro tunnel infrastructure. For academic research, access to the full dataset may be requested from the authors, subject to approval by the data owner.

## Overview

RMLS-Tunnel17 is a benchmark for fine-grained semantic segmentation of shield tunnel point clouds acquired by Railborne Mobile Laser Scanning (RMLS) on Guangzhou Metro Line 8.

The dataset defines **17 semantic categories**, including circumferential joints, longitudinal joints, bolt holes, and grouting holes. In the manuscript's experiments, **14 categories** are used for training and quantitative evaluation; noise is ignored, while telephone and emergency exit signage are excluded because of their very low sample counts.

## Code

For the corresponding model and code release announcement, see [Joint-MinkUNet](https://github.com/ZelasYou/Joint-MinkUNet).
