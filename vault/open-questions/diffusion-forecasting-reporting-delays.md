---
created_at: '2026-04-29T05:12:42Z'
source_papers:
- '[[arxiv-260424913-generative-diffusion-models-for-spatiotemporal-influenza-for]]'
title: Diffusion Reporting Delay Handling
---

**Background:** Denoising diffusion models in time-series forecasting often assume static or complete historical observations, whereas real-world surveillance data are subject to continuous reporting delays and retrospective revisions.

**Question / Future Work:** Future research is required to incorporate latent mechanisms for reporting delays and backfill correction directly into the diffusion sampling or training process to maintain reliability in real-time epidemiological settings.

**Why It Matters:** Inaccurate handling of data revisions leads to biased projections in public health, making this a critical reliability bottleneck for real-time model deployment.

**Evidence:** Influpaint also does not yet handle reporting delays or backfill correction, which may affect real-time applications in which data are revised over time.