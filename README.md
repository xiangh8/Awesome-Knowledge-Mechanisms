# Knowledge Mechanisms Across the Lifecycle of Large Language Models

> A lifecycle-based survey of how large language models acquire, represent, utilize, evolve, transfer, and evaluate knowledge.

[Project Homepage](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/) | [Download Paper](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/downloads/knowledge-mechanisms-across-llm-lifecycle.pdf)

## Overview

Knowledge is fundamental to the capabilities of large language models, yet research on how models learn, store, use, and revise knowledge remains distributed across multiple communities and evaluation traditions.

This survey organizes that research around a single lifecycle. It follows knowledge from training into internal representations and inference-time behavior, then through editing, unlearning, cross-boundary transfer, and evaluation. The lifecycle view exposes dependencies that are difficult to see when each topic is studied in isolation and helps connect behavioral observations with mechanistic explanations.

The accompanying collection covers six lifecycle stages and preserves a curated snapshot of 577 papers from 2024-2026.

## Knowledge Lifecycle

![The knowledge lifecycle of large language models](docs/assets/knowledge-lifecycle.png)

The first five stages form a progression: what a model acquires constrains what it can represent; representation shapes utilization; evolution changes existing knowledge; and transfer moves knowledge across models, modalities, and languages. Evaluation runs alongside the entire process.

## Lifecycle Taxonomy

| Stage | Core question | Main topics | Papers |
| --- | --- | --- | ---: |
| **Knowledge Acquisition / 知识获取** | How is knowledge learned? | Training methods, training data, model architecture and scale | 100 |
| **Knowledge Representation / 知识表征** | How is knowledge stored and organized? | Parametric memory, activation spaces, model circuits | 100 |
| **Knowledge Utilization / 知识利用** | How is knowledge used during inference? | Recall, augmentation, knowledge conflict | 100 |
| **Knowledge Evolution / 知识演化** | How is knowledge changed after training? | Editing, unlearning, side effects | 77 |
| **Knowledge Transfer / 知识迁移** | How does knowledge cross boundaries? | Cross-model, cross-modal, cross-lingual transfer | 100 |
| **Knowledge Evaluation / 知识评测** | How should model knowledge be measured? | Factuality, compositionality, currency, calibration | 100 |

## Resources

| Resource | Link |
| --- | --- |
| Project homepage | [xiangh8.github.io/Awesome-Knowledge-Mechanisms](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/) |
| Survey manuscript | [Download the current PDF](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/downloads/knowledge-mechanisms-across-llm-lifecycle.pdf) |

## Repository Structure

```text
.
├── README.md                         # Project overview
└── docs/                             # GitHub Pages homepage
    ├── index.html
    ├── styles.css
    ├── assets/
    └── downloads/
```

The homepage is a dependency-free static site published from `xh:/docs`. Maintenance notes and local preview instructions are available in [`docs/README.md`](docs/README.md).

## Status

The survey and taxonomy are active drafts. The manuscript, counts, terminology, and public citation information may change as the project develops.
