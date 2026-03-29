---
created_at: '2026-03-29T20:17:44Z'
source_papers:
- '[[openalex-2603.25687-on-neural-scaling-laws-for-weather-emulation-through-continu]]'
title: Probabilistic Scaling Law Investigation
---

**Background:** The inherent chaotic nature of weather systems means that probabilistic forecasts, which quantify uncertainty, are often more informative than deterministic forecasts.

**Question / Future Work:** Investigating the scaling behavior of models trained with objectives designed for probabilistic estimation, such as diffusion objectives or CRPS-based ensemble training, is required, as these methods may exhibit different scaling characteristics than the currently studied deterministic MSE-based training. This involves training or fine-tuning models with these probabilistic loss functions and observing how model size, data, and compute interact under scaling laws.

**Why It Matters:** Understanding probabilistic scaling is crucial for generating reliable, uncertainty-aware forecasts in chaotic systems like weather, which is a key aspect of operational forecasting.

**Evidence:** The main limitation of this paper is its focus on deterministic training of the weather model. Given the inherently chaotic nature of weather, probabilistic estimates are often more informative for forecasting at future time points, with metrics such as continuous ranked probability scores (CRPS) and spread-skill ratios (SSR) providing better diagnostics for a model’s predictive capability. Addressing this would involve training (or cooling down) models using diffusion objectives [Price et al., 2023, Alexe et al., 2024] or CRPS-based ensemble training [Alexe et al., 2024, Bonev et al., 2025], and this may exhibit different scaling behaviors—this is left for future work.