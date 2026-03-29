---
created_at: '2026-03-29T20:18:53Z'
source_papers:
- '[[openalex-2603.25446-implementation-of-a-near-realtime-recording-and-reporting-sy]]'
title: Expand burst class training set
---

**Background:** Deep learning models for solar radio burst detection are typically trained on synthetic data generated using first-principles physical models to capture various event morphologies and noise conditions.

**Question / Future Work:** Future work should involve expanding the detector's training set beyond Type III and Type IIIb bursts to include Type II bursts, which are key signatures of CME-driven shocks, as well as other burst classes (e.g., Type V) and complex background scenarios like noise storms. This expansion will allow for retraining and fine-tuning the detector to better represent real burst morphology across a broader event spectrum and enable a direct comparison between performance when trained on observed versus synthetic data.

**Why It Matters:** Type II bursts are crucial indicators of CME-driven shocks directly relevant to space weather forecasting, making their inclusion a necessary step for a complete operational system.

**Evidence:** Future work will expand the detector beyond the current type III/type IIIb training set. In particular, type II bursts—key signatures of CME-driven shocks—and other burst classes (e.g., type V) are not yet represented in the training data, so the present system should be viewed as optimized for type III-related electron-beam activity. We are building a larger multi-type labeled dataset (including type II, additional burst classes, and noise-storm/background scenarios). Once this labeling effort is completed, we will retrain/fine-tune the detector using these well-observed events to better reflect real burst morphology and to enable a direct comparison between observed- and synthetic-training performance.