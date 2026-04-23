---
# CSL-compatible fields
title: "A Multi-Plant Machine Learning Framework for Emission Prediction, Forecasting, and Control in Cement Manufacturing"
author:
  - literal: "Sheikh Junaid Fayaz"
  - literal: "Nestor D. Montiel-Bohorquez"
  - literal: "Wilson Ricardo Leal da Silva"
  - literal: "Shashank Bishnoi"
  - literal: "Matteo Romano"
  - literal: "Manuele Gatti"
  - literal: "N. M. Anoop Krishnan"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19903"

# Custom fields
paper_id: "2604.19903"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "industrial-applications"
  - "emission-control"
architectures:
  []
datasets:
  []
concept_slugs:
  - "process-memory-aware-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:08:24Z"
created_at: "2026-04-23T05:08:24Z"
---

# A Multi-Plant Machine Learning Framework for Emission Prediction, Forecasting, and Control in Cement Manufacturing

**Authors**: Sheikh Junaid Fayaz, Nestor D. Montiel-Bohorquez, Wilson Ricardo Leal da Silva, Shashank Bishnoi, Matteo Romano, Manuele Gatti, N. M. Anoop Krishnan
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19903](https://arxiv.org/abs/2604.19903)

## Summary

This paper presents a robust data-driven framework for emission prediction, forecasting, and control in cement manufacturing, using operational data from four global plants. By integrating short-term process history, the authors significantly enhance NOx prediction accuracy, revealing a unique process memory in NOx formation not found in other emissions. The resulting model enables nine-minute proactive emission forecasting, facilitating effective source control that reduces ammonia consumption and costs. The framework offers a generalizable, low-cost pathway for decarbonization in hard-to-abate industries like steel and glass.

## Key Contributions

- Develops a data-driven framework for NOx emission control in cement manufacturing that achieves a 34-64% reduction in NOx emissions while maintaining product quality.
- Demonstrates that incorporating short-term process history triples prediction accuracy for NOx, revealing distinct process memory characteristics compared to CO and CO2.
- Provides a forecasting model capable of predicting NOx overshoots nine minutes in advance, enabling proactive operational adjustments without hardware modifications.

## Open Questions & Future Work

- [[causal-attribution-in-industrial-process-control]]

## Key Concepts

- [[process-memory-aware-forecasting]]: Leveraging short-term process history to capture specific temporal dependencies in industrial emission formation processes.

## Archivist Review

I have approved 'Process Memory-Aware Forecasting' as it captures a specific temporal inductive bias relevant to process control, and 'Causal Attribution in Control' as it identifies a critical bottleneck in the transition from ML-based forecasting to trusted industrial control. I rejected the open question on reliability as it describes general multi-step forecasting limitations already well-represented in the literature.

### Approved Concepts
- Process Memory-Aware Forecasting: Highlights the critical role of temporal dependencies in industrial emission control, which are often overlooked in static modeling approaches.

### Approved Open Questions
- Causal Attribution in Control: Moving from statistical correlation to causal understanding is essential for designing truly robust, interpretable control systems.

### Rejected Candidates
- [open_question] Emission Forecast Reliability Inconsistency (`emission-forecast-reliability-and-instability`) - not_novel: The problem described is a standard forecasting challenge (multi-step horizon degradation) rather than a novel, deep scientific bottleneck specific enough to this domain to merit a standalone vault note.

## Links

- [Abstract](https://arxiv.org/abs/2604.19903)
- [PDF](https://arxiv.org/pdf/2604.19903)

