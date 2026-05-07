---
created_at: '2026-05-07T05:16:40Z'
source_papers:
- '[[arxiv-260504229-capabilities-of-auto-encoders-and-principal-component-analys]]'
title: Challenges in Long-term Forecasting
---

**Background:** Phase-field simulation of complex physical phenomena involves computationally expensive evolution of microstructural images over many time steps. Dimensionality reduction of these image sequences into latent spaces is a critical step to enable efficient time-series prediction using neural networks.

**Question / Future Work:** While auto-encoders and PCA successfully reduce the dimensionality of microstructural images, current models show limitations in long-term sequence prediction as errors accumulate. It remains an open challenge to optimize the combination of non-linear dimensionality reduction and time-series models, such as exploring advanced architectures like Transformers, to achieve higher fidelity forecasting over longer time intervals.

**Why It Matters:** The bottleneck of long-term predictive accuracy in surrogate models prevents their full adoption as replacements for computationally intensive high-fidelity physical simulations, particularly for applications like microstructure evolution and crack propagation.

**Evidence:** In order to achieve better Forecasting, more combinations of dimensionality reduction techniques and time series predictions should be explored. Deep transformer models for time series predictions could be explored and could be faster than RNNs and have the capability to successfully extract correlations among the elements in a long sequence.