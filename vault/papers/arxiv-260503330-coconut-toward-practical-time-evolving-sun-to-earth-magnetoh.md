---
# CSL-compatible fields
title: "COCONUT: Toward practical time-evolving Sun-to-Earth magnetohydrodynamic modeling"
author:
  - literal: "Haopeng Wang"
  - literal: "Stefaan Poedts"
  - literal: "Andrea Lani"
  - literal: "Rayan Dhib"
  - literal: "Luis Linan"
  - literal: "Tinatin Baratashvili"
  - literal: "Fan Zhang"
  - literal: "Quentin Noraz,"
  - literal: "Hyun-Jin Jeong"
  - literal: "Nicolas Wijsen"
  - literal: "Martina Condoluci"
  - literal: "Lingyu Dong"
  - literal: "Junyan Liu"
  - literal: "Rui Zhuo"
  - literal: "Mahdi Najafi-Ziyazi"
  - literal: "Ketevan Arabuli"
  - literal: "Myrthe Flossie"
  - literal: "Jasmina M. Magdalenić Zhukov"
  - literal: "Brigitte Schmieder"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03330"

# Custom fields
paper_id: "2605.03330"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "coconut-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:12:46Z"
created_at: "2026-05-06T05:12:46Z"
---

# COCONUT: Toward practical time-evolving Sun-to-Earth magnetohydrodynamic modeling

**Authors**: Haopeng Wang, Stefaan Poedts, Andrea Lani, Rayan Dhib, Luis Linan, Tinatin Baratashvili, Fan Zhang, Quentin Noraz,, Hyun-Jin Jeong, Nicolas Wijsen, Martina Condoluci, Lingyu Dong, Junyan Liu, Rui Zhuo, Mahdi Najafi-Ziyazi, Ketevan Arabuli, Myrthe Flossie, Jasmina M. Magdalenić Zhukov, Brigitte Schmieder
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03330](https://arxiv.org/abs/2605.03330)

## Summary

COCONUT is an implicit, time-evolving magnetohydrodynamic (MHD) model designed to simplify the traditional Sun-to-Earth modeling pipeline by unifying coronal and inner-heliosphere simulation stages. Unlike conventional steady-state models that rely on static magnetograms, COCONUT accounts for dynamic magnetic field evolution, leading to more accurate plasma parameter predictions at L1 and L5 points. The framework is shown to be computationally efficient enough for practical space weather applications, while successfully forecasting Earth-bound solar wind conditions approximately four days in advance using L5 observations.

## Key Contributions

- Introduces the COCONUT model, an implicit time-evolving MHD solver that extends from the solar surface to 1 AU in a single unified pipeline.
- Demonstrates that time-evolving implicit MHD modeling improves plasma parameter estimation accuracy by capturing magnetic field evolution neglected by steady-state approaches.
- Validates the reliability of using L5 observations for solar wind forecasting at Earth with a four-day lead time.

## Key Concepts

- [[coconut-model]]: An implicit time-evolving magnetohydrodynamic model that simulates the solar corona and inner heliosphere out to 1 AU in a single unified framework.

## Archivist Review

The paper proposes the COCONUT model as a paradigm shift from multi-stage coupled models to a unified, time-evolving implicit MHD approach for Sun-to-Earth space weather forecasting. This unification is a significant structural contribution to physical simulation pipelines in time-series forecasting. No additional open questions or datasets were deemed sufficiently novel or central to the global literature to warrant standalone vault entries.

### Approved Concepts
- COCONUT Model: Represents a novel approach for unified Sun-to-Earth MHD modeling that replaces traditional multi-stage coupling pipelines.

### Rejected Candidates
- [concept] COCONUT (`coconut-model`) - duplicate_existing: Duplicate existing concept in same vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.03330)
- [PDF](https://arxiv.org/pdf/2605.03330)

