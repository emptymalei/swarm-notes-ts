---
# CSL-compatible fields
title: "Order-based Rehearsal Learning"
author:
  - literal: "Yu-Xuan Tao"
  - literal: "Tian-Zuo Wang"
  - literal: "Zhi-Hua Zhou"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04955"

# Custom fields
paper_id: "2605.04955"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "order-based-rehearsal-learning"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-07T05:14:27Z"
created_at: "2026-05-07T05:14:27Z"
---

# Order-based Rehearsal Learning

**Authors**: Yu-Xuan Tao, Tian-Zuo Wang, Zhi-Hua Zhou
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04955](https://arxiv.org/abs/2605.04955)

## Summary

This paper addresses the Avoiding Undesired Future (AUF) problem by shifting focus from learning computationally expensive and error-prone causal graphs to learning simpler causal orders. The authors introduce an information-theoretic approach to infer these orders directly from observational data without restricting structural functional forms. An order-based sampler is then employed to optimize post-decision outcomes, effectively reducing the AUF problem to a differentiable optimization task. Empirical results demonstrate superior performance against graph-based alternatives and consistency with oracle-level accuracy.

## Key Contributions

- Introduces the first order-based rehearsal learning method for the Avoiding Undesired Future (AUF) problem.
- Develops an information-theoretic method for learning causal orders that is robust to structural function forms and noise types.
- Demonstrates that order-based decision-making matches or exceeds performance of oracle baselines using true causal graphs in AUF tasks.

## Open Questions & Future Work

- [[sufficiency-of-order-vs-graph-for-auf]]

## Key Concepts

- [[order-based-rehearsal-learning]]: A decision-making framework for avoiding undesired events that utilizes causal ordering instead of full graph structures to simplify learning from observational data.

## Archivist Review

The paper introduces a significant methodological shift by substituting complex causal graphs with causal orders for intervention optimization. I have approved the overarching framework as a concept and the question of its theoretical sufficiency as an open research problem, adhering to the scarcity and relevance guidelines.

### Approved Concepts
- Order-based Rehearsal Learning: Represents a paradigm shift from graph-based to order-based causal reasoning for avoiding undesired future events, reducing estimation complexity.

### Approved Open Questions
- Order vs Graph Sufficiency: Establishing the theoretical boundaries of order-based structures is essential for understanding the trade-off between structural simplicity and decision-making performance in complex causal systems.

## Links

- [Abstract](https://arxiv.org/abs/2605.04955)
- [PDF](https://arxiv.org/pdf/2605.04955)

