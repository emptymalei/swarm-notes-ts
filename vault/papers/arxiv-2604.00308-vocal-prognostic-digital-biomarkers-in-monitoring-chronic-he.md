---
# CSL-compatible fields
title: "Vocal Prognostic Digital Biomarkers in Monitoring Chronic Heart Failure: A Longitudinal Observational Study"
author:
  - literal: "Fan Wu"
  - literal: "Matthias P. Nägele"
  - literal: "Daryush D. Mehta, Elgar Fleisch, Frank Ruschitzka, Andreas J. Flammer, Filipe Barata"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2604.00308"

# Custom fields
paper_id: "2604.00308"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series"
  - "forecasting"
  - "healthcare-ai"
  - "longitudinal-study"
  - "explainable-ml"
  - "digital-biomarker"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:39:08Z"
created_at: "2026-04-02T05:39:08Z"
---

# Vocal Prognostic Digital Biomarkers in Monitoring Chronic Heart Failure: A Longitudinal Observational Study

**Authors**: Fan Wu, Matthias P. Nägele, Daryush D. Mehta, Elgar Fleisch, Frank Ruschitzka, Andreas J. Flammer, Filipe Barata
**Date**: 2026-03-31
**Paper ID**: [arxiv:2604.00308](https://arxiv.org/abs/2604.00308)

## Summary

This study investigates the use of longitudinal voice recordings as a non-invasive digital biomarker to predict health deterioration in patients with chronic heart failure. By analyzing 21,863 daily recordings, the authors demonstrate that vocal acoustic features, particularly from vowels and speech patterns, provide superior predictive accuracy for health status compared to traditional methods like daily weight tracking. The findings suggest that time-series analysis of vocal markers within 7-day windows can serve as an effective tool for early, proactive clinical intervention.

## Key Contributions

- Identified vocal prognostic biomarkers for chronic heart failure, including vowel energy shifts and speech rate metrics, outperforming standard weight/blood pressure monitoring.
- Demonstrated that time-series aggregation of vocal features over 7-day windows improves predictive sensitivity (0.826) and specificity (0.782) compared to standard-of-care measures.
- Validated the utility of longitudinal, non-invasive voice monitoring for early detection of health deterioration in heart failure patients using a 2-month observational cohort.

## Open Questions & Future Work

- [[standardization-of-at-home-voice-recording-protocols]]

## Archivist Review

The paper presents domain-specific findings in digital health rather than general-purpose forecasting or ML architecture innovations. I have approved one open question regarding the standardization of home-based monitoring, as this is a fundamental bottleneck for the reliability of vocal biomarkers that applies beyond this specific patient cohort.

### Approved Open Questions
- Standardizing home-based voice recording protocols: Reliability in home-based digital biomarkers is currently hampered by significant noise and variability introduced by the uncontrolled recording environment, which could lead to false positives or missed clinical deterioration events.

### Rejected Candidates
- [concept] Vocal prognostic biomarkers (`vocal-prognostic-biomarkers`) - paper_local: Specific biomarkers for heart failure are domain-specific medical findings rather than generalizable forecasting mechanisms or architectures.

## Links

- [Abstract](https://arxiv.org/abs/2604.00308)
- [PDF](https://arxiv.org/pdf/2604.00308)

