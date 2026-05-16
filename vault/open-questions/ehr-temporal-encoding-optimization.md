---
created_at: '2026-05-16T05:13:42Z'
source_papers:
- '[[arxiv-260514227-dt-transformer-a-foundation-model-for-disease-trajectory-pre]]'
title: Optimizing temporal representation for EHRs
---

**Background:** The design of longitudinal electronic health record (EHR) models typically involves encoding patient histories as temporal sequences. Existing time-encoding strategies may not optimally handle the irregular, dense, and potentially censored nature of real-world clinical data.

**Question / Future Work:** Research is required to develop and validate more explicit interval-aware temporal encoding methods tailored to real-world EHR data, as standard embeddings often fail to capture the nuances of clinical encounters and variable longitudinal observation windows.

**Why It Matters:** Effective time representation is critical for foundation models to accurately predict disease trajectories over varying time horizons in fragmented real-world clinical systems.

**Evidence:** The time encoding with age embeddings and no-event paddings may be suboptimal for real-world EHR data, where events are more tightly spaced and long-term observability and censoring are more pronounced.