---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Agronomic Characterization and Time-Series UAV Phenotyping to Support Field Pea Breeding in Iowa"
description: "This paper evaluates the performance of field pea varieties in the U.S. Midwest using a combination of traditional agronomic characterization and time-series UAV-based phenotyping. By extracting temporal canopy features and vegetation indices from drone imagery, the authors identify that UAV-derived canopy area serves as a highly reliable selection trait (H2 = 0.87) with a significant correlation to final seed yield (r = 0.63). The results suggest that integrating time-series remote sensing into breeding workflows can significantly accelerate the development of locally adapted, high-yielding crop varieties."
resource: "https://arxiv.org/abs/2610.19154"
tags:
  - "time-series-analysis"
  - "feature-extraction"
  - "multivariate-analysis"
  - "spatio-temporal-analysis"
  - "precision-livestock-farming"
  - "forecasting"
timestamp: "2026-10-18T00:48:28Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Yanben Shen"
  - literal: "Joscif Raigne"
  - literal: "Asheesh Singh"
  - literal: "Arti Singh"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.19154"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "uav-high-throughput-phenotyping"
    description: "The use of unmanned aerial vehicles to capture multi-temporal imagery for the automated, non-destructive extraction and analysis of plant traits across large-scale breeding trials."
datasets:
  []
open_questions:
  - name: "cross-environment-phenotype-generalization"
    description: "How can time-series features extracted from UAV imagery be made robust enough to generalize across diverse climatic zones and soil types without requiring site-specific ground-truth calibration for every new environment?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:48:28Z"
created_at: "2026-10-18T00:48:28Z"
---

# Agronomic Characterization and Time-Series UAV Phenotyping to Support Field Pea Breeding in Iowa

**Authors**: Yanben Shen, Joscif Raigne, Asheesh Singh, Arti Singh
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.19154](https://arxiv.org/abs/2610.19154)

## Summary

This paper evaluates the performance of field pea varieties in the U.S. Midwest using a combination of traditional agronomic characterization and time-series UAV-based phenotyping. By extracting temporal canopy features and vegetation indices from drone imagery, the authors identify that UAV-derived canopy area serves as a highly reliable selection trait (H2 = 0.87) with a significant correlation to final seed yield (r = 0.63). The results suggest that integrating time-series remote sensing into breeding workflows can significantly accelerate the development of locally adapted, high-yielding crop varieties.

## Key Contributions

- Demonstrated that UAV-derived time-series canopy area is a superior predictor of field pea yield (r = 0.63) compared to vegetation indices and manual measurements.
- Established high selection reliability (H2 = 0.87) for UAV-derived traits, suggesting their efficacy for phenotypic selection in Midwest breeding programs.
- Characterized the phenology and yield potential of 17 accessions and 7 elite Canadian field pea varieties specifically for the Iowa climate across six site-years.

## Limitations

The study is geographically limited to Iowa, and the correlation between canopy area and yield may vary under different environmental stresses or in different crop species.

## Open Questions & Future Work

- [[cross-environment-phenotype-generalization]]

## Key Concepts

- [[uav-high-throughput-phenotyping]]: The use of unmanned aerial vehicles to capture multi-temporal imagery for the automated, non-destructive extraction and analysis of plant traits across large-scale breeding trials.

## Archivist Review

The approved items reflect the paper's primary contribution: applying time-series UAV imagery to accelerate crop breeding. I approved 'UAV High-Throughput Phenotyping' as a central, recurring concept in digital agriculture. I also approved an open question regarding 'Cross-Environment Phenotype Generalization', as the paper acknowledges its geographical limitations, identifying a significant bottleneck in the field of agricultural time-series analysis. No datasets were approved as the paper describes a specific study rather than a named, reusable benchmark.

### Approved Concepts
- UAV High-Throughput Phenotyping: UAV-HTP allows for the non-destructive, large-scale, and temporal monitoring of crop development, which is becoming a standard in modern digital breeding and precision agriculture.

### Approved Open Questions
- Cross-Environment Phenotype Generalization: The lack of model generalizability across site-years and locations is a major technical hurdle for the commercial deployment of automated phenotypic selection tools in global breeding programs.

### Rejected Candidates
- [concept] Canopy Area Selection Reliability (`canopy-area-selection-reliability`) - paper_local: This candidate refers to a specific statistical finding (heritability) of a single trait in this study rather than a novel or reusable ML mechanism.
- [open_question] Multi-modal UAV Sensor Fusion (`multi-sensor-fusion-agronomy`) - generic: Multi-sensor fusion is a standard, broad area of research in remote sensing; the question posed is generic and lacks a specific technical angle unique to the findings of this paper.
- [open_question] Cross-Environment Feature Generalization (`ag-model-generalization`) - duplicate_existing: Consolidated into the approved 'cross-environment-phenotype-generalization' question which better captures the domain-specific nuances.

## Links

- [Abstract](https://arxiv.org/abs/2610.19154)
- [PDF](https://arxiv.org/pdf/2610.19154)

