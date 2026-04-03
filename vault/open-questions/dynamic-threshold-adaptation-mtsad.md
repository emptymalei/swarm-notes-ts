---
created_at: '2026-04-03T05:19:40Z'
source_papers:
- '[[arxiv-2604.01845-candi-curated-test-time-adaptation-for-multivariate-time-ser]]'
title: Dynamic Threshold Adaptation in MTSAD
---

**Background:** Test-time adaptation (TTA) frameworks for multivariate time-series anomaly detection (MTSAD) aim to update models to address distribution shifts, but these methods often prioritize parameter optimization over the dynamic adjustment of detection thresholds.

**Question / Future Work:** Investigating whether and how to adapt anomaly detection thresholds at inference time alongside model parameters is a critical area for future research. While parameter adaptation helps maintain latent representations, dynamic thresholding could provide an additional, highly responsive mechanism to mitigate false positives under evolving distributions.

**Why It Matters:** Thresholding is the final step in anomaly detection, and static thresholds become unreliable under non-stationary conditions, making dynamic adaptation a potential key to better performance.