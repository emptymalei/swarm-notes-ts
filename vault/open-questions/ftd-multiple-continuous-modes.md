---
created_at: '2026-03-29T20:17:52Z'
source_papers:
- '[[openalex-2603.25530-adaptive-subspace-modeling-with-functional-tucker-decomposit]]'
title: Expand FTD to multiple continuous modes
---

**Background:** The functional Tucker decomposition (FTD) formulation is currently restricted to only one continuous mode due to computational considerations in solving for the core tensor.

**Question / Future Work:** Extend the functional Tucker decomposition (FTD) to support multiple continuous modes, which would be beneficial for analyzing complex data like multi-channel electrocardiogram (ECG) or electroencephalogram (EEG) data.

**Why It Matters:** Expanding to multiple continuous modes would significantly broaden the applicability of the FTD method to other domains characterized by multiple smoothly varying measurements, such as multi-sensor medical signal analysis.

**Evidence:** For instance, the current formulation is restricted to one continuous mode because of computational considerations regarding the solution for the core tensor. Even though this setup already covers many real-world applications, an expansion to an FTD with multiple continuous modes could be interesting for medical challenges such as the analysis of electrocardiogram (ECG) or electroencephalogram (EEG) data with multiple channels.