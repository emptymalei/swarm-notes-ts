---
created_at: '2026-05-09T05:12:18Z'
source_papers:
- '[[arxiv-260505771-beyond-long-tail-pois-transition-centered-generalization-for]]'
title: Transition-aware LLM mobility prediction
---

**Background:** Human mobility prediction models often treat POI visit sequences as the primary data unit, but predictive failures frequently stem from the absence of specific source-to-destination transitions in training data, regardless of POI popularity.

**Question / Future Work:** It remains an open challenge to unify transition-level compositional generalization techniques with Large Language Model (LLM)-based mobility predictors, which typically rely on different input formats and architectural priors. Future work needs to integrate explicit transition-level signals into LLM-based architectures to combine their semantic generative power with robust mobility-specific generalization.

**Why It Matters:** LLM-based mobility prediction is an emerging paradigm, but currently struggles with transition-level sparsity that simple neural models are beginning to address; merging these approaches is critical for achieving both scalability and accuracy.

**Evidence:** Future work can inject transition signals into LLM-based models, grounding world knowledge in mobility transitions for more interpretable predictions.