---
created_at: '2026-04-10T15:27:01Z'
source_papers:
- '[[arxiv-260408400-zero-shot-multivariate-time-series-forecasting-using-tabular]]'
title: Probabilistic Forecasting Calibration Drivers
---

**Background:** Tabular foundation models can be applied to time series forecasting by reformulating the task as a scalar regression problem, with performance evaluated using both point and probabilistic metrics. The mechanisms influencing the quality of probabilistic forecasts in this reformulated setting are not fully understood.

**Question / Future Work:** There is a need to identify the specific factors—such as model calibration, training objective, or data transformation strategies—that contribute to discrepancies in probabilistic forecast accuracy when applying zero-shot tabular models to multivariate time series. Understanding these drivers is essential to closing the performance gap in uncertainty estimation.

**Why It Matters:** Reliable uncertainty quantification is critical for decision-making in real-world forecasting applications, making the gap in probabilistic accuracy a key barrier to practical deployment.

**Evidence:** We further evaluate probabilistic forecast accuracy via the Weighted Quantile Loss (WQL). While our standardization strategies prove beneficial (Appendix E), our approach demonstrates a performance deficit compared to TabPFN-TS (Table 1). Future work is required to isolate the drivers of this behavior and investigate potential mitigation strategies.