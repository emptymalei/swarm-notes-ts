---
# CSL-compatible fields
title: "The Newsworthiness of Brazilian Distress: A Peak Analysis on Time Series of International Media Attention to Disasters in Brazil"
author:
  - literal: "Brielen Madureira"
  - literal: "Andreas Niekler"
  - literal: "Marc Keuschnigg"
  - literal: "Mariana Madruga de Brito"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04552"

# Custom fields
paper_id: "2605.04552"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "peak-driven-region-segmentation-pdrs"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:15:41Z"
created_at: "2026-05-07T05:15:41Z"
---

# The Newsworthiness of Brazilian Distress: A Peak Analysis on Time Series of International Media Attention to Disasters in Brazil

**Authors**: Brielen Madureira, Andreas Niekler, Marc Keuschnigg, Mariana Madruga de Brito
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04552](https://arxiv.org/abs/2605.04552)

## Summary

This paper investigates the drivers of international media attention toward localized disaster events in Brazil using a curated dataset of 2,000 news articles from German newspapers spanning 2000 to 2024. By employing time series segmentation to detect attention peaks, the authors systematically align media coverage with global and national disaster databases. This study addresses the lack of representative, country-specific datasets for analyzing the dynamics of international disaster reporting.

## Key Contributions

- Introduces a specialized news dataset of international media coverage of Brazilian natural disasters (fires and landslides) in German newspapers from 2000 to 2024.
- Demonstrates a time series segmentation framework that quantifies the temporal alignment between media attention peaks and recorded disaster events.
- Provides a systematic framework for assessing the drivers of international newsworthiness for local crises.

## Open Questions & Future Work

- [[disaster-media-alignment-bottlenecks]]

## Key Concepts

- [[peak-driven-region-segmentation-pdrs]]: A technique for segmenting time series to identify and align peaks in media coverage with real-world disaster events.

## Archivist Review

The paper's method of segmenting time series to correlate news attention with external events is a recognized pattern in event-driven analysis, so it was approved. The identified open question regarding media-disaster alignment is a substantial bottleneck in the field of event detection and news analytics. A dataset proposal was rejected due to its limited scope and size.

### Approved Concepts
- Peak-driven region segmentation (PDRS): The paper utilizes this approach to align international media coverage with specific disaster occurrences, bridging the gap between social science event analysis and time series methodology.

### Approved Open Questions
- Media-Disaster Database Alignment Challenges: Addressing this misalignment is critical for validating the use of global news as a proxy for disaster impact and for understanding the selective nature of media attention, which in turn influences humanitarian aid and policy.

### Rejected Candidates
- [dataset] Brazilian Disaster News Dataset (2000-2024) (`brazilian-disaster-news-dataset-2000-2024`) - low_impact: The dataset size (2k articles) is small and highly specialized, functioning more as a research corpus than a general-purpose benchmark for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2605.04552)
- [PDF](https://arxiv.org/pdf/2605.04552)

