---
created_at: '2026-05-13T05:22:59Z'
source_papers:
- '[[arxiv-260512391-trajectory-agnostic-asteroid-detection-in-tess-with-deep-lea]]'
title: Mitigating Training Label Noise
---

**Background:** Machine learning-based asteroid detection often relies on training labels derived from existing catalogs which are incomplete and contain positional uncertainties.

**Question / Future Work:** The presence of significant label noise and incompleteness in astronomical survey data causes models to be counter-trained, where unidentified objects are incorrectly labeled as background. Semi-supervised or iterative labeling schemes that can refine training sets as a model improves are needed to mitigate this bias.

**Why It Matters:** Label incompleteness is a foundational problem for supervised learning in astronomy and time-domain surveys, directly affecting the scalability and accuracy of future detection pipelines.

**Evidence:** The effect of both the fundamental incompleteness and inaccuracy of the data is that we are “counter-training” a non-trivial fraction of the data.