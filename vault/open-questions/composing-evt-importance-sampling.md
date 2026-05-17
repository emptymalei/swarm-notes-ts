---
created_at: '2026-05-17T05:22:27Z'
source_papers:
- '[[arxiv-260515134-training-ml-models-with-predictable-failures]]'
title: Composing EVT and IS
---

**Background:** Rare-event estimation for machine learning safety is currently split between extrapolation-based approaches and importance sampling methods.

**Question / Future Work:** The integration of extreme value theory (EVT)-based tail extrapolation with the distributional tilting of importance sampling remains an open challenge for managing rare, high-cost failures.

**Why It Matters:** Combining these two complementary paradigms could provide more robust safety guarantees by leveraging the strengths of both extrapolation and rare-event simulation.

**Evidence:** tail extrapolation may compose with importance sampling, the other main approach to rare-event estimation; we leave that combination to future work.