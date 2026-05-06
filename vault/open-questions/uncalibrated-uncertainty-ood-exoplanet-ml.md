---
created_at: '2026-05-06T05:12:03Z'
source_papers:
- '[[arxiv-260503719-a-public-dataset-of-ariel-simulated-observations-for-develop]]'
title: Calibrated Uncertainty for OOD Spectroscopy
---

**Background:** Machine learning models applied to exoplanetary atmospheric retrieval often lack robust mechanisms to flag or accurately quantify uncertainty when encountering out-of-distribution (OOD) data.

**Question / Future Work:** Future work must develop methods that provide reliable epistemic uncertainty estimates (e.g., higher uncertainty on unseen or novel atmospheric scenarios) rather than just reflecting noise patterns learned from simulated training sets.

**Why It Matters:** In survey-scale missions like Ariel, overconfident predictions on OOD data can lead to erroneous scientific conclusions, making epistemic uncertainty quantification a critical bottleneck.

**Evidence:** Ideally, the model should produce larger error bars for unseen examples, reflecting increased uncertainty. Instead, it applies learned uncertainty patterns to novel cases, adversely affecting the Gaussian Log Likelihood based score.