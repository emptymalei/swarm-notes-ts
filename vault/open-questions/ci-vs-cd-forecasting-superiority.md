---
created_at: '2026-04-10T15:27:01Z'
modified_at: '2026-04-12T05:02:41Z'
source_papers:
- '[[arxiv-260408400-zero-shot-multivariate-time-series-forecasting-using-tabular]]'
title: CI vs CD Forecasting Superiority
---

**Background:** Multivariate time series forecasting can be performed either through channel-independent (CI) univariate decomposition or channel-dependent (CD) modeling of joint distributions. It remains unclear under what conditions each approach outperforms the other.

**Question / Future Work:** Characterizing the dataset and problem attributes that necessitate or favor channel-dependent versus channel-independent forecasting strategies is an open research challenge. Establishing these criteria would provide essential guidance for model selection and architecture design in diverse forecasting domains.

**Why It Matters:** This is a fundamental methodological question in time series forecasting that informs whether models should explicitly account for inter-variable correlations or rely on simpler, more robust univariate assumptions.

**Evidence:** While we find the empirical performance of our method to be mostly positive, we observe the channel-independent to work better under some datasets. Determining precisely when a CI or CD method is superior remains an open question in the field.