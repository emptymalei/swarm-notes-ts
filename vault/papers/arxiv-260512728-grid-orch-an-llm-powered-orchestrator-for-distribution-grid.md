---
# CSL-compatible fields
title: "Grid-Orch: An LLM-Powered Orchestrator for Distribution Grid Simulation and Analytics"
author:
  - literal: "Boming Liu"
  - literal: "Jin Dong"
  - literal: "Jamie Lian"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12728"

# Custom fields
paper_id: "2605.12728"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "model-context-protocol-for-power-systems"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:25:56Z"
created_at: "2026-05-14T05:25:56Z"
---

# Grid-Orch: An LLM-Powered Orchestrator for Distribution Grid Simulation and Analytics

**Authors**: Boming Liu, Jin Dong, Jamie Lian
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12728](https://arxiv.org/abs/2605.12728)

## Summary

Grid-Orch addresses the power engineering talent shortage by providing an LLM-powered orchestration layer that translates natural language into complex simulation commands via the Model Context Protocol. By integrating 36 specialized tools for OpenDSS, the platform automates sophisticated tasks like DER interconnection screening and quasi-static time series (QSTS) simulation. It supports both cloud and air-gapped local LLM deployments, ensuring accessibility and security in utility environments while maintaining numerical parity with traditional scripting.

## Key Contributions

- Introduces Grid-Orch, a framework using the Model Context Protocol to bridge LLMs with power system simulation tools like OpenDSS.
- Provides a library of 36 domain-specific engineering tools for power flow, voltage analysis, and QSTS simulation accessible via natural language.
- Enables multi-step engineering workflows—such as DER interconnection screening—to be completed in under two minutes, reducing task duration from hours to minutes.

## Key Concepts

- [[model-context-protocol-for-power-systems]]: A standardized interface enabling LLM-based orchestration of power system simulation tools and workflows.

## Archivist Review

The paper presents an LLM-based orchestration framework for domain-specific simulation. The core contribution is the application of the Model Context Protocol (MCP) to bridge general-purpose LLMs with technical simulation engines. I have approved the concept for the protocol's integration in this domain but rejected the simulation software as a dataset.

### Approved Concepts
- Model Context Protocol (MCP) for Power Systems: It establishes a standardized interface for connecting LLMs to specialized simulation environments, specifically OpenDSS for power grids.

### Rejected Candidates
- [dataset] OpenDSS (`opendss`) - other: OpenDSS is a standard power system simulation software engine, not a specific research dataset.

## Links

- [Abstract](https://arxiv.org/abs/2605.12728)
- [PDF](https://arxiv.org/pdf/2605.12728)

