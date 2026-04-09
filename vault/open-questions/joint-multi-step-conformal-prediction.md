---
created_at: '2026-04-09T04:52:35Z'
source_papers:
- '[[arxiv-260407325-conformal-prediction-with-time-series-data-via-sequential-co]]'
title: Joint Multi-Step Conformal Prediction
---

**Background:** Conformal prediction for time-series data typically focuses on constructing marginal or conditional prediction intervals. The ability to generate and validate joint prediction regions over multiple future time steps remains an open challenge.

**Question / Future Work:** While current methods provide asymptotic guarantees for one-step-ahead prediction sets, extending these guarantees to joint prediction sets over multiple future steps (H-steps ahead) is non-trivial. Developing frameworks that maintain rigorous coverage guarantees while managing the dependencies inherent in sequential updates for multi-step joint regions is identified as a critical future research direction.

**Why It Matters:** Moving from one-step to multi-step joint prediction is essential for tasks requiring path-wise uncertainty quantification, which is necessary for many sequential decision-making processes.

**Evidence:** A second area for future research is the development of joint H-step ahead prediction regions. While Section A in the supplementary materials introduces an extension of the SCDR method that provides an asymptotic guarantee on the individual prediction sets, we believe certain problems benefit from a coverage guarantee on the joint prediction sets over H steps. Although our framework can accommodate multivariate responses, visualizing and updating these sets as data are sequentially observed remains a non-trivial challenge.