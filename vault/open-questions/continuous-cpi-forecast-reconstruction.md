---
created_at: '2026-04-23T05:06:54Z'
source_papers:
- '[[arxiv-260420421-unlocking-the-forecasting-economy-a-suite-of-datasets-for-th]]'
title: Continuous CPI Forecast Reconstruction
---

**Background:** The process of converting fragmented categorical market probability beliefs into a continuous point estimate of future macroeconomic indicators, such as the Consumer Price Index (CPI), involves complex distributional assumptions and data reconciliation challenges.

**Question / Future Work:** Current methods for reconstructing continuous CPI expectations from discrete market contracts often rely on restrictive parametric assumptions, such as Gaussianity of the belief distribution. Future research is needed to develop more robust, model-independent methods for point-forecast reconstruction that do not rely on specific parametric assumptions about the underlying belief distribution.

**Why It Matters:** This is technically critical because the choice of distribution (e.g., Gaussian) directly influences the resulting point forecast, potentially introducing bias if the actual market-implied belief is skewed, multi-modal, or has fat tails, which is common in macroeconomic expectations.

**Evidence:** The main challenge is that raw Polymarket prices only encode the probability of individual bucket events rather than a direct numerical forecast. ... we assume that the market-implied monthly CPI distribution at time t follows a unimodal Gaussian distribution ... The implied CPI at time t is then represented by the fitted mean.