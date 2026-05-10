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
  - "topological-sorting-via-node-relatives"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:19:10Z"
created_at: "2026-05-10T05:19:10Z"
---

# A Topological Sorting Criterion for Random Causal Directed Acyclic Graphs

**Authors**: Alexander G. Reisach, Antoine Chambaz, Gilles Blanchard, Sebastian Weichwald
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06288](https://arxiv.org/abs/2605.06288)

## Summary

This paper investigates structural patterns in random causal DAGs, specifically focusing on the relationship between node order and reachability. The authors demonstrate that the number of reachable nodes (termed 'relatives') increases monotonically along the causal order, providing an unintended, simple heuristic for causal order recovery. They show that this pattern is prevalent in many synthetic datasets used in the literature, which may lead to overly optimistic performance results for causal discovery algorithms. Consequently, the authors propose sampling time-series DAGs as a more rigorous approach for evaluating causal discovery methods.

## Key Contributions

- Identified that the number of reachable nodes (relatives) in random causal DAGs increases monotonically along the causal order.
- Proposed a causal order recovery algorithm based on sorting nodes by their estimated count of relatives.
- Demonstrated that this simple sorting strategy serves as an effective proxy for causal order in many existing synthetic causal discovery evaluation settings.
- Identified potential biases in current causal discovery evaluation methodologies and proposed time-series DAGs as a more robust alternative.

## Open Questions & Future Work

- [[synthetic-dag-evaluation-bias]]

## Key Concepts

- [[topological-sorting-via-node-relatives]]: A causal order recovery heuristic that sorts nodes by the number of reachable nodes (relatives) in a DAG.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 1 concept(s), 1 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- Topological sorting via node relatives: Reveals an unintended, prevalent structural property in synthetic causal discovery benchmarks that simplifies causal order recovery.

### Approved Open Questions
- Synthetic DAG evaluation bias: Existing synthetic benchmarks may overestimate algorithmic performance by allowing simple heuristics to recover causal order, necessitating more rigorous synthetic data generation methods.

### Rejected Candidates
- [concept] Causal discovery evaluation methodologies (`causal-discovery-evaluation-methodologies`) - generic: This is a general research area rather than a specific mechanism or concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.06288)
- [PDF](https://arxiv.org/pdf/2605.06288)

