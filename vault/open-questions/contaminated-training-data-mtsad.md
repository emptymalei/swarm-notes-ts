---
created_at: '2026-04-03T05:19:40Z'
source_papers:
- '[[arxiv-2604.01845-candi-curated-test-time-adaptation-for-multivariate-time-ser]]'
title: Contaminated Training Data in MTSAD
---

**Background:** Unsupervised multivariate time-series anomaly detection (MTSAD) models typically assume that training data is entirely free of anomalies, a premise that is often violated in practical, real-world deployment scenarios where training data may contain noise or contamination.

**Question / Future Work:** Developing robust mechanisms to detect and handle contaminated or noisy training data in the context of unsupervised MTSAD remains an open challenge. Current adaptation frameworks generally rely on the assumption of purely normal training data, limiting their effectiveness when this assumption does not hold.

**Why It Matters:** This is a fundamental limitation for applying unsupervised methods to real-world industrial or medical time-series data, where labels are often scarce and data quality is inconsistent.