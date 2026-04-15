---
# CSL-compatible fields
title: "GCA Framework: A Gulf-Grounded Dataset and Agentic Pipeline for Climate Decision Support"
author:
  - literal: "Muhammad Umer Sheikh"
  - literal: "Khawar Shehzad"
  - literal: "Salman Khan"
  - literal: "Fahad Shahbaz Khan"
  - literal: "Muhammad Haris Khan"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12306"

# Custom fields
paper_id: "2604.12306"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "gca-ds"
concept_slugs:
  []
dataset_slugs:
  - "gca-ds"
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:04:20Z"
created_at: "2026-04-15T05:04:20Z"
---

# GCA Framework: A Gulf-Grounded Dataset and Agentic Pipeline for Climate Decision Support

**Authors**: Muhammad Umer Sheikh, Khawar Shehzad, Salman Khan, Fahad Shahbaz Khan, Muhammad Haris Khan
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12306](https://arxiv.org/abs/2604.12306)

## Summary

The GCA framework addresses the lack of regional climate expertise in general-purpose LLMs by introducing a specialized multimodal dataset (GCA-DS) and a tool-augmented agent (GCA) for the Gulf region. GCA-DS consolidates governmental policies, scientific literature, and remote-sensing data to provide a robust grounding for climate analysis. The GCA agent utilizes this foundation through a modular pipeline that performs geospatial processing and generates interpretable visualizations, offering a reliable decision-support system for climate adaptation.

## Key Contributions

- Introduces GCA-DS, a specialized multimodal dataset comprising ~200k QA pairs covering Gulf-specific climate policies, academic literature, and event-driven environmental reports.
- Presents the Gulf Climate Agent (GCA), a modular, tool-augmented agent pipeline that integrates geospatial processing with historical climate signals to deliver actionable policy guidance.
- Demonstrates that domain-specific fine-tuning and tool orchestration significantly outperform general-purpose LLMs in grounding and reliability for regional climate decision support.

## Open Questions & Future Work

- [[uncertainty-aware-climate-agentic-reasoning]]

## Archivist Review

The GCA framework itself and the specific agent instance were rejected as they are domain-specific applications rather than reusable methodological contributions. The multimodal dataset GCA-DS was approved due to its specialized nature and size. The open question regarding uncertainty-aware agentic reasoning was approved as a substantial unresolved bottleneck for tool-augmented decision systems.

### Approved Open Questions
- Uncertainty-Aware Climate Agentic Reasoning: As climate decision support systems move toward real-world application, the ability to manage cascading tool errors and quantify uncertainty is critical for stakeholder trust and safety.

### Rejected Candidates
- [concept] GCA Framework (`gca-framework`) - paper_local: The framework is a specific application instance rather than a reusable methodological concept or architectural pattern.
- [concept] Gulf Climate Agent (GCA) (`gulf-climate-agent-gca`) - paper_local: This is a specific implementation of a tool-augmented agent for a particular geographic region.

## Datasets

- [[gca-ds]]

## Links

- [Abstract](https://arxiv.org/abs/2604.12306)
- [PDF](https://arxiv.org/pdf/2604.12306)

