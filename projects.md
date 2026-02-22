---
title: Projects
---

## DRSuite — Diffusion–Relaxation MRI Software
Open-source toolkit for multidimensional MRI that supports phantom generation, spectral estimation (NNLS/ADMM/LADMM), visualization, and CRLB-based acquisition analysis. It also includes reproducible benchmarking workflows to compare estimators and speed collaborator adoption.  
**Link:** https://drsuite.org

## Linearized ADMM for Spatial–Spectral Mapping (USC)
Developed and benchmarked a linearized ADMM solver for recovering spatial–spectral maps from indirect, noisy measurements. The approach combines ARMA-inspired signal modeling with structural regularization (finite-difference priors), yielding reported 3–50× speedups and 2–15× memory efficiency over prior baselines.

## Low-Rank Regularized Spectral Estimation (USC)
Designed structured non-convex low-rank estimators for resolving closely spaced spectral components in highly ill-posed multidimensional MR settings, with improved component separability on real datasets.

## Multimodal Survival Analysis for Leukemia Risk (QRT Challenge ’26)
Built an end-to-end survival modeling pipeline for adult myeloid leukemia prognosis using multi-center clinical and somatic mutation data. Feature engineering included cytogenetics tokenization and variant-allele-frequency summaries. Trained censoring-aware Cox and XGBoost-Cox models with 5-fold CV and tuned against IPCW C-index at \(\tau = 7\) years.

## Axon Radii Estimation from Clinical dMRI
Built a predictive estimator for high-b diffusion signals from low-b clinical acquisitions by combining sparse spherical ridgelet angular modeling and bi-exponential radial decay, solved via ADMM. Validated with stress tests on synthetic and in-vivo datasets with strong prediction accuracy and consistent axon radii estimates.

## Neural Coding of Two-Tone Harmonic Complexes
Analyzed cortical encoding of harmonic complexes in mouse auditory cortex by modeling tuning to fundamental frequency and quantifying enhancement/suppression versus matched pure tones, including population-level statistical analyses for sex-specific signatures.
