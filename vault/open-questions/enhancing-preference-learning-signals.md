---
created_at: '2026-04-28T05:15:45Z'
source_papers:
- '[[arxiv-260423988-hindsight-preference-optimization-for-financial-time-series]]'
title: Improving Preference Learning Signals
---

**Background:** In preference optimization frameworks for time series advisory, current approaches often rely on rankings from LLM judges, which may provide insufficient signal for effective model convergence.

**Question / Future Work:** The current training approach relies on simple pairwise rankings derived from LLM judges, which serves as a relatively weak learning signal for Direct Preference Optimization (DPO). Future research should explore incorporating richer, more descriptive feedback from judges—such as natural language rationales—as a source of supervision to improve the efficiency, stability, and interpretability of the learning process.

**Why It Matters:** The learning signal quality is a primary bottleneck for DPO; enhancing this signal can lead to more stable and faster training, as well as better interpretability of why certain model responses are preferred.

**Evidence:** Additionally, the current approach uses only the judge’s rankings, which provides a weak learning signal for DPO—leading to slow and unstable convergence. Incorporating judge rationales as natural-language reward signals and disentangling which advisory dimensions—scenario calibration, reasoning quality, or risk estimation—drive improvement are promising directions.