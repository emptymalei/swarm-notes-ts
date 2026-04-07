---
# CSL-compatible fields
title: "TimeSeek: Temporal Reliability of Agentic Forecasters"
author:
  - literal: "Hamza Mostafa"
  - literal: "Om Shastri"
  - literal: "Dennis Lee"
issued:
  date-parts:
    - [2026, 4, 5]
url: "https://arxiv.org/abs/2604.04220"

# Custom fields
paper_id: "2604.04220"
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
processed_at: "2026-04-07T04:54:05Z"
created_at: "2026-04-07T04:54:05Z"
---

# TimeSeek: Temporal Reliability of Agentic Forecasters

**Authors**: Hamza Mostafa, Om Shastri, Dennis Lee
**Date**: 2026-04-05
**Paper ID**: [arxiv:2604.04220](https://arxiv.org/abs/2604.04220)

## Summary

TimeSeek is a new benchmark designed to assess the temporal reliability of agentic LLM forecasters by analyzing their performance at multiple checkpoints throughout the lifecycle of real-world binary prediction markets. The study evaluates 10 frontier models across 15,000 forecasts, highlighting significant performance variability depending on the market phase and consensus levels. The findings challenge the assumption of uniform tool-use benefits, demonstrating that web search can often degrade performance depending on the temporal context.

## Key Contributions

- Introduces TimeSeek, a benchmark evaluating agentic LLM performance across the lifecycle of 150 regulated binary prediction markets.
- Demonstrates that LLM forecasting competitive performance declines significantly near market resolution and on strong-consensus markets.
- Reveals that while web search improves average Brier Skill Scores, it negatively impacts performance in 12% of model-checkpoint scenarios, necessitating selective retrieval policies.

## Open Questions & Future Work

- [[optimal-agentic-tool-use-policies]]
- [[market-model-hybrid-forecasting]]

## Archivist Review

The paper introduces a focused empirical study on the temporal dynamics of LLM forecasters in binary markets. I approved two open questions that capture the core research bottlenecks identified: the need for selective tool-use policies and the integration of AI models with prediction markets. I rejected the benchmark itself as it is highly specific to the binary market domain and not a general-purpose dataset for the broader vault.

### Approved Open Questions
- Optimal Agentic Tool-Use Policies: This addresses the critical challenge of ensuring tool-use reliably improves agentic reasoning rather than introducing noise, which is essential for high-stakes decision-making environments.
- Market-Model Hybrid Forecasting Systems: Integrating AI reasoning with established information aggregation mechanisms is a key frontier for creating reliable, decision-support systems.

### Rejected Candidates
- [dataset] TimeSeek Benchmark (`timeseek-benchmark`) - low_impact: This is a specialized evaluation benchmark derived from proprietary/regulated market data, lacking broad reusability as a dataset note for general forecasting research.

## Links

- [Abstract](https://arxiv.org/abs/2604.04220)
- [PDF](https://arxiv.org/pdf/2604.04220)

