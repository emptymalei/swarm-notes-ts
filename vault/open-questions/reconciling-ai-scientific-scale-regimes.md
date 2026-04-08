---
created_at: '2026-04-08T04:55:16Z'
source_papers:
- '[[arxiv-260406000-regimes-of-scale-in-ai-meteorology]]'
title: Reconciling AI and Scientific Scaling
---

**Background:** Scientific domains often utilize physics-based models and established data pipelines, whereas modern machine learning methods are designed around platform-centric data-driven scaling. Integrating these disparate systems often leads to friction, as AI/ML models may struggle to maintain physical consistency and operate within existing institutional data assimilation workflows.

**Question / Future Work:** There is a need to develop methods for reconciling the differing epistemic and architectural expectations between 'data-driven' scaling and 'domain-specific' (e.g., physics-based) scaling, particularly regarding model generalizability, physical consistency, and integration into existing operational workflows. Research is required to bridge the gap between optimizing for domain-agnostic benchmarks and adhering to the institutional norms of high-stakes scientific fields.

**Why It Matters:** This fundamental conflict is a major bottleneck for the reliable deployment of AI-based scientific models in high-stakes operational environments where physical rigor is as essential as statistical performance.

**Evidence:** As these models are put in the place of more ”traditional” physics-based meteorological models, they are assumed to scale like those models do... [Operational forecasters] variously said, ”I can’t use this. There’s no physical consistency.” The AI/ML researcher replied, ”You tell me the metrics you’re interested in, and I’ll optimize for those metrics.”