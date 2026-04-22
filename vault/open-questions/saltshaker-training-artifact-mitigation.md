---
created_at: '2026-04-22T05:02:37Z'
source_papers:
- '[[arxiv-260419746-calibration-induced-systematics-in-salt3-training-and-their]]'
title: SALTshaker training artifact mitigation
---

**Background:** Spectral energy distribution models for Type Ia supernovae, such as SALT3, are typically trained using a combination of photometric and spectroscopic observations to standardize distance measurements. Current training pipelines for these models often rely on limited subsets of spectral data, which can introduce artifacts and biases in the resulting light-curve templates.

**Question / Future Work:** The use of only near-infrared prism spectra during the training of the SALT3 model leads to subtle artifacts in the templates, such as reduced color dispersion and increased rejection of high-signal-to-noise, low-redshift events. Research is needed to determine the origin of these artifacts and to establish whether a combination of both optical and near-infrared spectra is required for optimal model training in future surveys.

**Why It Matters:** Establishing optimal training datasets is critical for the accuracy of next-generation SN Ia cosmological analyses, as these models are fundamental for standardizing supernovae across wide redshift ranges.

**Evidence:** Although the SALT3.NIREXT model used in the OpenUniverse24 simulation extends to 25,000 Å, enabling coverage into the near-infrared (NIR), we found subtle SALTShaker artifacts training with only prism spectra... Future work is needed to understand these SALTshaker artifacts, and if both optical and NIR spectra are needed for optimal training results.