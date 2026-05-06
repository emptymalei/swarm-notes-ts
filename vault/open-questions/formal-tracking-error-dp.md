---
created_at: '2026-05-06T05:13:28Z'
source_papers:
- '[[arxiv-260502886-cityos-privacy-architecture-for-urban-sensing]]'
title: Formalizing Tracking-DP Error Bounds
---

**Background:** Computer vision systems used for differentially private aggregation typically rely on empirical tracking models that lack formal error bounds. This creates an unresolved gap in incorporating tracking uncertainty into rigorous differential privacy guarantees.

**Question / Future Work:** Future work is needed to develop tracking models whose error bounds can be formally incorporated into differential privacy guarantees, specifically by folding tracking failure probabilities into the error analysis of approximate differential privacy mechanisms.

**Why It Matters:** This is critical for transitioning DP applications in computer vision from empirical, heuristic-based sensitivity bounds to theoretically sound, verifiable privacy guarantees.

**Evidence:** More importantly, the design surfaces a new problem at the intersection of computer vision and DP, namely, developing tracking models whose error bounds can be formally incorporated into privacy guarantees (e.g., folded into the failure probability of approximate DP). We leave this to future work.