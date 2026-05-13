---
title: "Latent Chain-of-Thought"
slug: "latent-chain-of-thought"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-260511262-latent-chain-of-thought-improves-structured-data-transformer]]"
processed_at: "2026-05-13T05:26:28Z"
created_at: "2026-05-13T05:26:28Z"
---

# Latent Chain-of-Thought

> *Auto-generated stub. Edit this file to add more details.*

A recurrent mechanism for transformers that compresses hidden states into feedback tokens for multiple rounds of iterative latent computation before generating a final prediction.


## Why It Matters

Introduces a general mechanism for scaling test-time compute in transformers via iterative feedback loops, moving beyond simple static depth.

## Evidence

> We propose a recurrent scheme in which a structured-data transformer... compresses its query-position hidden states into feedback tokens that are appended to the input and processed again, allowing multiple rounds of latent computation before prediction.

## Related Papers

- [[arxiv-260511262-latent-chain-of-thought-improves-structured-data-transformer]]
