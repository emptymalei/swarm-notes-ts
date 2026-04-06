---
created_at: '2026-04-06T05:03:26Z'
source_papers:
- '[[arxiv-260402711-foundation-models-defining-a-new-era-in-sensor-based-human-a]]'
title: 'Representation Limits: Temporal Hierarchy'
---

**Background:** Human activities exhibit hierarchical temporal structures ranging from short-term micro-events to long-term daily routines, yet current sensor-based representations struggle to capture these multi-scale abstractions effectively. Aligning these representations with high-level semantic concepts is difficult due to the lack of clear grounding between raw signals and language.

**Question / Future Work:** There is a lack of principled methods to capture the hierarchical temporal structure of human activities, from instantaneous gestures to long-term routines, in a form that remains stable across varied users and devices. Further research is required to develop pretraining objectives that explicitly model this temporal hierarchy and to identify robust methods for aligning sensor embeddings with semantic/linguistic concepts without overfitting to specific prompts or captioning styles.

**Why It Matters:** Robust activity understanding requires the model to comprehend the temporal context of human behavior. Without effective hierarchical and semantic abstraction, models remain limited to short-window classification and cannot reason about intent or complex behavioral patterns.