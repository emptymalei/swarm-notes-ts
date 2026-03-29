---
created_at: '2026-03-29T20:17:44Z'
source_papers:
- '[[openalex-2603.25687-on-neural-scaling-laws-for-weather-emulation-through-continu]]'
title: Scaling with Transformer Resolution
---

**Background:** The experimental analysis was conducted using a fixed spatial resolution of the input data, specifically $0.25^{\circ}$ ERA5 patches. This limits the systematic study of scaling across another critical dimension of scientific data complexity.

**Question / Future Work:** A systematic exploration of neural scaling laws where the internal Transformer resolution (sequence length, influenced by patch size) is treated as an explicit scaling dimension, in addition to model size, data size, and compute, is needed. This involves varying the patch size across experiments to see how computational efficiency and performance bounds change.

**Why It Matters:** Resolving the relationship between model resolution (patch size) and scaling laws is essential for determining compute-optimal resource allocation when data resolution is a variable input.

**Evidence:** Our patch size is fixed for the scaling tests, but the internal Transformer resolution (sequence length) represents another dimension for systematic scaling studies.