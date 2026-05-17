---
created_at: '2026-05-17T05:25:19Z'
source_papers:
- '[[arxiv-260514285-forcingdas-unified-and-robust-data-assimilation-via-diffusio]]'
title: Causal-Only Smoothing Limitations
---

**Background:** In data assimilation, causal temporal attention mechanisms allow past frames to directly influence future frames, but prevent future observations from directly affecting past states during the forward pass. This asymmetry forces future observations to influence past estimates only through indirect backward gradients during the inference-time guidance phase.

**Question / Future Work:** The extent to which causal-only smoothing—where future observations reach past states strictly through backward gradients—limits the performance of unified data assimilation compared to bidirectional forward-pass models remains to be determined. Understanding how to mitigate this asymmetry while maintaining the ability to switch between filtering and smoothing regimes is a significant open challenge.

**Why It Matters:** This is explicitly listed as a key limitation of the proposed ForcingDAS framework, directly impacting its potential performance in batch reanalysis tasks.