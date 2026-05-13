---
created_at: '2026-05-13T05:26:03Z'
source_papers:
- '[[arxiv-260511287-beyond-similarity-temporal-operator-attention-for-time-serie]]'
title: Transformer Operator Approximation Limits
---

**Background:** Deep, multi-head Transformer stacks utilize multiple layers and heads to combine learned sequence-space operators. Characterizing the theoretical approximation efficiency and sample-complexity trade-offs of these complex stacks relative to explicit operator-based attention remains unresolved.

**Question / Future Work:** While Transformers may implicitly re-combine signed operators via subsequent layers and MLPs, the specific expressive and computational costs of this 're-combination' strategy compared to an explicitly parameterized signed operator remain uncharacterized. Future work is required to rigorously quantify the approximation power and sample complexity tradeoffs between these architectural paradigms.

**Why It Matters:** This informs the debate on whether specialized attention primitives are strictly necessary for time-series modeling or if sufficient architectural depth can emulate the same inductive biases.

**Evidence:** Finally, our formal impossibility results apply specifically to the single-layer, single-head softmax primitive; characterizing the approximation efficiency and sample-complexity tradeoffs of deep, multi-head Transformer stacks relative to TOA remains an important open problem.