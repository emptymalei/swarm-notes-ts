---
created_at: '2026-04-29T05:10:41Z'
source_papers:
- '[[arxiv-260425890-observation-guided-neural-surrogate-learning-for-scientific]]'
title: Validating Spatial Accuracy of Surrogates
---

**Background:** Scientific simulation emulation for flood-inundation mapping often relies on high-fidelity hydrodynamic models to generate training targets for surrogate models, which may inherit simulation-specific biases.

**Question / Future Work:** It remains unresolved how to independently validate the spatial accuracy of flood-inundation surrogates across an entire domain when most spatial pixels lack direct ground-truth observations and are supervised by simulation outputs. Developing methods to ingest independent observational sources like satellite SAR or high-water marks is essential for moving beyond simulation-consistency metrics.

**Why It Matters:** This is critical to distinguishing between a model that faithfully reproduces a simulator's potentially biased physics versus one that accurately models the real world.