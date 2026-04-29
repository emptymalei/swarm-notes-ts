---
created_at: '2026-04-29T05:13:08Z'
source_papers:
- '[[arxiv-260424646-reduced-order-data-assimilation-for-thermospheric-density-us]]'
title: Ensemble-based latent space assimilation
---

**Background:** Data assimilation of thermospheric density is currently performed using extended Kalman filters (EKF) operating on a latent state space. While the EKF provides a computational efficiency advantage, it may inadequately represent the full probability distribution of forecast uncertainty in highly nonlinear regimes.

**Question / Future Work:** There is a need to extend the latent-space assimilation framework from an EKF to ensemble-based or higher-order methods, such as the Ensemble Kalman Filter (EnKF) or the Unscented Kalman Filter (UKF). These approaches would provide more accurate representations of forecast uncertainty and better handle the nonlinear transformations between latent states and observed physical density.

**Why It Matters:** Moving beyond the EKF linear-first-order approximation is essential to better capture non-Gaussian and nonlinear uncertainties inherent in upper atmospheric dynamics.

**Evidence:** An ensemble Kalman filter (EnKF) or unscented Kalman filter (UKF) formulation in the same latent space would provide a more faithful representation of forecast uncertainty and would naturally handle the nonlinear relationship between the latent state and physical density in full-space reconstruction.