---
# CSL-compatible fields
title: "Quasi-Periodic Microstructures in Pulsar Emission: Automated Detection and Archival Survey"
author:
  - literal: "Amarnath"
  - literal: "Yogesh Maan"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19883"

# Custom fields
paper_id: "2604.19883"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "astrophysics"
  - "automation"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:08:33Z"
created_at: "2026-04-23T05:08:33Z"
---

# Quasi-Periodic Microstructures in Pulsar Emission: Automated Detection and Archival Survey

**Authors**: Amarnath, Yogesh Maan
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19883](https://arxiv.org/abs/2604.19883)

## Summary

This paper introduces the Quasi-periodic MIcrostructure Search Tool (QMIST), an automated framework for identifying quasi-periodic signal variations in radio pulsar intensity time series. By moving away from manual inspection, the authors demonstrate the tool's effectiveness across multiple telescope datasets, including observations from GMRT, GBT, and Parkes. The survey successfully identifies new microstructures in three pulsars and clarifies the periodicity for a fourth, supporting the existence of a linear correlation between microstructure periods and pulsar rotation periods.

## Key Contributions

- Developed QMIST, an automated Python-based tool for detecting quasi-periodic microstructures in radio pulsar time-series data.
- Performed a multi-epoch survey of 27 pulsars, successfully recovering known microstructures and discovering new ones in pulsars B1451-68, B1706-16, and B1845-19.
- Confirmed a near-linear relationship between microstructure periodicity and the pulsar rotation period using a systematic survey approach.

## Open Questions & Future Work

- [[pulsar-microstructure-origin-mechanism]]
- [[automated-microstructure-vetting-ml]]

## Archivist Review

The paper provides a specialized tool for astrophysical signal analysis. I have approved two open questions that capture the broader scientific and methodological challenges (understanding the underlying physical emission mechanism and the use of ML for automated vetting). The specific software tool itself (QMIST) was rejected as it is a project-specific implementation rather than a general-purpose methodological concept.

### Approved Open Questions
- Physical Origin of Microstructures: Resolving the physical mechanism of pulsar microstructures is fundamental to understanding the radio emission process in neutron stars.
- Machine Learning for Microstructure Vetting: Automation is critical for efficiently processing the rapidly growing volume of pulsar survey data and identifying rare or subtle emission features.

### Rejected Candidates
- [concept] Quasi-periodic MIcrostructure Search Tool (QMIST) (`qmist-pulsar-tool`) - paper_local: The tool is a paper-specific implementation and software application rather than a reusable methodological concept for the general ML/time-series community.

## Links

- [Abstract](https://arxiv.org/abs/2604.19883)
- [PDF](https://arxiv.org/pdf/2604.19883)

