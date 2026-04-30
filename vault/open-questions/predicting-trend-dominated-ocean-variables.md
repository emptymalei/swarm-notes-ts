---
created_at: '2026-04-30T05:15:43Z'
source_papers:
- '[[arxiv-260425559-representing-the-surface-ocean-in-ecmwfs-data-driven-forecas]]'
title: Predicting Trend-Dominated Ocean Variables
---

**Background:** Data-driven forecasting models often struggle to maintain physical consistency and accurate long-term trends for variables that exhibit slow, monotonic shifts over time.

**Question / Future Work:** There is a need to determine effective methods for training machine learning models to represent and predict slowly varying, trend-dominated ocean variables, such as sea surface height, which currently show systematic negative biases due to the model's tendency to predict climatological averages over the training period rather than absolute values. Investigating whether training on detrended anomalies or adopting alternative loss functions can mitigate these biases remains an open challenge.

**Why It Matters:** Correctly representing ocean state variables is critical for climate forecasting and oceanography. Understanding how to handle long-term climate trends in data-driven models is a key bottleneck for the field.