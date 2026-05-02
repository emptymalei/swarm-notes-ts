---
created_at: '2026-05-02T05:08:35Z'
source_papers:
- '[[arxiv-260427443-abc-any-subset-autoregression-via-non-markovian-diffusion-br]]'
title: Hybrid ODE-SDE sampling schemes
---

**Background:** Generative models for continuous-time processes typically struggle to bridge the gap between noise-based sampling and physically plausible, time-adjacent state coherence.

**Question / Future Work:** It remains an open question how to design hybrid ODE-SDE sampling schemes that balance generation speed, computational efficiency, and structural fidelity for long-horizon continuous-time processes, particularly when incorporating coarse-to-fine or multiscale generation strategies.

**Why It Matters:** Efficient and structurally coherent sampling is essential for scaling continuous-time generative models to high-resolution spatiotemporal tasks.

**Evidence:** Future work should investigate alternative sampling schemes, such as hybrid ODE-SDE sampling schemes. Another example is coarse-to-fine generation by causally generating every K frames at low sampling rate before infilling the K-1 frames in between.