---
created_at: '2026-05-03T05:15:22Z'
source_papers:
- '[[arxiv-260427443-abc-any-subset-autoregression-via-non-markovian-diffusion-br]]'
title: Time-Adaptive Volatility in SDEs
---

**Background:** Standard continuous-time generative models often treat all temporal transitions as having uniform volatility, ignoring the relationship between physical time intervals and the required state perturbation magnitude.

**Question / Future Work:** Investigate the integration of physically-informed, time-adaptive volatility schedules into continuous-time generative SDEs, ensuring that noise injection explicitly scales with the physical time gap between conditioning states.

**Why It Matters:** Decoupling the generation process from fixed noise schedules is essential for achieving physically plausible dynamics in long-horizon forecasting and video synthesis.

**Evidence:** Regardless of what physical times they interpolate, the SDE always starts at auxiliary (non-physical) time 0 and ends at auxiliary time 1, with the same exact volatility (aka noise) schedule.