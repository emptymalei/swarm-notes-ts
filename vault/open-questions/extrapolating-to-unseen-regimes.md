---
created_at: '2026-04-25T04:55:18Z'
source_papers:
- '[[arxiv-260421101-a-hybridizable-neural-time-integrator-for-stable-autoregress]]'
title: Extrapolation to Unseen Regimes
---

**Background:** When forecasting complex chaotic systems over long time horizons, the accuracy of autoregressive models is inherently limited by the expressive capability of the underlying architecture. While structural scaffolds improve stability, they remain constrained by the transformer's latent encoding capacity.

**Question / Future Work:** It remains an open challenge to extend stable autoregressive architectures to effectively extrapolate into regimes with unseen physics or energy states, such as when mass accumulates in a fusion component or when physical systems undergo transitions not represented in the training data. Developing methodologies to move beyond autoregressive forecasting, potentially by explicitly learning the underlying partial differential equations (PDEs), is necessary for robust long-term generalization.

**Why It Matters:** This defines the fundamental limit of the current architecture and identifies the transition from autoregressive surrogate modeling to explicit PDE learning as the next necessary step for broader scientific application.

**Evidence:** For MITL, the energy of the system increases as mass accumulates in the gap, eventually leading to states not seen in training. To extrapolate into unseen regimes, one would need to identify a physics-based model for field evolution beyond autoregressive forecasting (e.g. by learning a PDE).