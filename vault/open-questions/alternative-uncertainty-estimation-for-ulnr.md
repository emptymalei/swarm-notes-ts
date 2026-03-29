---
created_at: '2026-03-29T20:19:00Z'
source_papers:
- '[[openalex-2603.25670-uncertainty-guided-label-rebalancing-for-cps-safety-monitori]]'
title: Investigate alternative uncertainty estimators
---

**Background:** The proposed U-Balance framework utilizes a GatedMLP-based uncertainty predictor to guide label rebalancing (uLNR) by relabeling uncertain safe windows as unsafe.

**Question / Future Work:** Explore alternative techniques for estimating behavioral uncertainty, such as Monte Carlo Dropout (MC Dropout) and Deep Ensembles, to determine how the accuracy and nature of the uncertainty estimates influence the overall effectiveness of the label rebalancing procedure (uLNR) for safety prediction.

**Why It Matters:** The effectiveness of the core concept (uncertainty-guided rebalancing) depends on the quality of the uncertainty signal; exploring more robust uncertainty estimators can lead to theoretically stronger guarantees.

**Evidence:** We also plan to investigate alternative uncertainty estimation techniques, such as MC Dropout and Deep Ensembles, to better understand how the accuracy of the uncertainty estimates influences the effectiveness of rebalancing.