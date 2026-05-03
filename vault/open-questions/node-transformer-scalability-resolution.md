---
created_at: '2026-05-03T05:15:33Z'
source_papers:
- '[[arxiv-260427313-pinn-cast-exploring-the-role-of-continuous-depth-node-in-tra]]'
title: Scalability of NODE-Transformers at High Resolution
---

**Background:** Weather forecasting models are increasingly exploring the integration of Neural Ordinary Differential Equations (NODEs) into transformer-based architectures to model continuous-time dynamics. However, these models have primarily been evaluated at relatively coarse spatial resolutions.

**Question / Future Work:** It remains an open question whether the performance gains observed by integrating continuous-depth NODE dynamics into transformer encoders for weather forecasting persist when scaling to higher spatial resolutions. Systematic investigation is required to determine if these architectures maintain their efficacy and computational feasibility as the grid resolution increases.

**Why It Matters:** Understanding scalability is critical for the practical adoption of data-driven forecasting models, as operational systems require high-resolution predictions. If the continuous-depth advantages vanish at scale, it would fundamentally limit the utility of this architectural approach.

**Evidence:** We evaluate at 5.625 ∘ resolution to enable controlled comparison under limited compute, whether the observed gains persist at higher resolutions remains an open question for future work and is addressed in section 5.