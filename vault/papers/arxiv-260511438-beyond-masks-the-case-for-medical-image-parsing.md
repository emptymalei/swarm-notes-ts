---
# CSL-compatible fields
title: "Beyond Masks: The Case for Medical Image Parsing"
author:
  - literal: "Siddharth Gupta"
  - literal: "Alan L. Yuille"
  - literal: "Zongwei Zhou"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11438"

# Custom fields
paper_id: "2605.11438"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "medical-image-parsing"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-13T05:25:37Z"
created_at: "2026-05-13T05:25:37Z"
---

# Beyond Masks: The Case for Medical Image Parsing

**Authors**: Siddharth Gupta, Alan L. Yuille, Zongwei Zhou
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11438](https://arxiv.org/abs/2605.11438)

## Summary

This paper argues that medical imaging research should pivot from voxel-level segmentation to a more comprehensive 'medical image parsing' framework. Instead of simply generating masks, models should output structured, mutually consistent representations containing entities, their attributes, and clinical relationships. The authors provide a rigorous framework for evaluating these parses based on decision, reconstruction, and prediction capabilities, and show that existing state-of-the-art systems largely fail to meet these requirements.

## Key Contributions

- Proposes medical image parsing as a new paradigm to replace conventional per-voxel mask-based segmentation in clinical diagnostics.
- Defines the parsing framework through three core criteria: decision (entity identification), reconstruction (content-rich representation), and prediction (forecasting patient state).
- Audits eleven representative medical imaging systems, demonstrating that while entity identification is mature, current models lack the necessary capabilities for attribute, relationship, and closure representation.

## Open Questions & Future Work

- [[joint-medical-image-parsing-algorithms]]

## Key Concepts

- [[medical-image-parsing]]: A clinical imaging paradigm where models output structured, mutually consistent entities, attributes, and relationships rather than simple masks.

## Archivist Review

The paper makes a compelling case for a shift in diagnostic imaging from per-voxel masks to structured parsing. I have approved the 'medical image parsing' concept as it defines the central methodology, and the open question regarding joint algorithmic frameworks as it captures the primary technical roadblock identified by the authors. Other candidates were not submitted, so no rejections were necessary.

### Approved Concepts
- Medical Image Parsing: It represents a shift from low-level voxel prediction to higher-level structured semantic understanding in clinical diagnostics.

### Approved Open Questions
- Joint Medical Image Parsing Algorithms: Establishing a joint objective is critical for shifting clinical AI from mere measurement (segmentation) to clinical reasoning.

## Links

- [Abstract](https://arxiv.org/abs/2605.11438)
- [PDF](https://arxiv.org/pdf/2605.11438)

