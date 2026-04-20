---
created_at: '2026-04-20T05:09:02Z'
source_papers:
- '[[arxiv-260416182-synthetic-data-in-cryptocurrencies-using-generative-models]]'
title: Reproducing volatility in GANs
---

**Background:** Generative Adversarial Networks (GANs) are frequently applied to financial time series, yet they often struggle to accurately replicate high-volatility events and heavy-tailed distributions.

**Question / Future Work:** The generator in current GAN architectures often exhibits a smoothing effect, which leads to the attenuation of volatility peaks in synthetic financial data. Investigating techniques to improve the reproduction of extreme events and heavy-tailed distributions in non-stationary financial time series remains an open research challenge.

**Why It Matters:** Smoothing of volatility peaks renders synthetic data less useful for stress testing and risk management, where capturing extreme tail risk is crucial.

**Evidence:** In the case of ETH, the model is able to adequately capture the general direction of price movement; however, a systematic attenuation is noted in volatility peaks, with the generated series showing amplitudes lower than those observed in the real data. This behavior is consistent with results reported in the literature on GANs applied to financial series, in which the generator tends to smooth extreme events due to the difficulty in reproducing abrupt shocks and distributions with heavy tails.