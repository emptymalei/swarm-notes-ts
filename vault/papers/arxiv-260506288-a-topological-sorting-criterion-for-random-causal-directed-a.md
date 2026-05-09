---
# CSL-compatible fields
title: "A Topological Sorting Criterion for Random Causal Directed Acyclic Graphs"
author:
  - literal: "Alexander G. Reisach"
  - literal: "Antoine Chambaz"
  - literal: "Gilles Blanchard"
  - literal: "Sebastian Weichwald"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06288"

# Custom fields
paper_id: "2605.06288"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:11:02Z"
created_at: "2026-05-09T05:11:02Z"
---

# A Topological Sorting Criterion for Random Causal Directed Acyclic Graphs

**Authors**: Alexander G. Reisach, Antoine Chambaz, Gilles Blanchard, Sebastian Weichwald
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06288](https://arxiv.org/abs/2605.06288)

## Summary

This paper investigates the structural properties of common random DAG generation schemes used to benchmark causal discovery algorithms. The authors prove that the set of reachable nodes (relatives) in these graphs grows monotonically along the causal order, a feature that can be exploited to recover the causal ordering itself. They demonstrate that many existing benchmarks may be inadvertently simplified by this property, and argue that time-series DAGs offer a more robust alternative for future causal discovery research.

## Key Contributions

- Demonstrates that the number of reachable nodes (relatives) in standard random DAGs increases monotonically along the causal order.
- Proposes a causal order recovery method based on sorting nodes by their estimated number of relatives.
- Identifies that strict monotonicity of relatives implies a singular Markov equivalence class, suggesting potential biases in common causal discovery evaluations.
- Proposes sampling time-series DAGs as an alternative to existing random DAG models to avoid structural artifacts.

## Links

- [Abstract](https://arxiv.org/abs/2605.06288)
- [PDF](https://arxiv.org/pdf/2605.06288)

