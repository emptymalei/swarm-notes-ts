---
created_at: '2026-04-09T04:55:36Z'
source_papers:
- '[[arxiv-260406602-umi-a-gpu-accelerated-asymmetric-robust-estimator-for-photom]]'
title: Asymmetric Estimator False-Positive Risks
---

**Background:** Asymmetric estimators used in time-series detrending can introduce constant flux offsets or periodic artifacts that may influence downstream anomaly or event detection.

**Question / Future Work:** Investigate the impact of biased robust estimators on the false-positive rates of periodic signal detection algorithms such as BLS and TLS, specifically verifying whether induced offsets translate into algorithmic artifacts.

**Why It Matters:** Quantifying the unintended bias-to-false-positive trade-off is critical for robust automated pipeline design.

**Evidence:** A systematic verification using matched-filter detection on detrended light curves without injected transits would confirm this reasoning and is planned for future work.