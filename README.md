# Knowledge Mechanisms Across the Lifecycle of Large Language Models

> A lifecycle-based survey of how large language models acquire, represent, utilize, evolve, transfer, and evaluate knowledge.

[中文说明](README_CN.md) | [Project Homepage](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/) | [Download Paper](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/downloads/knowledge-mechanisms-across-llm-lifecycle.pdf)

## Overview

Knowledge is fundamental to the capabilities of large language models, yet research on how models learn, store, use, and revise knowledge remains distributed across multiple communities and evaluation traditions.

This survey organizes that research around a single lifecycle. It follows knowledge from training into internal representations and inference-time behavior, then through editing, unlearning, cross-boundary transfer, and evaluation. The lifecycle view exposes dependencies that are difficult to see when each topic is studied in isolation and helps connect behavioral observations with mechanistic explanations.

The accompanying taxonomy covers six lifecycle stages.

## Authors

**Core Contributors:** Hao Xiang (Leading Contributor), Xiusheng Huang, Shangqing Tu, Jiasheng Zheng, Jiakuan Xie, Chenhui Hu, JiaXiang Liu, Qiao Liang

**Instructors:** Boxi Cao, Pengfei Cao, Lei Hou, Hongyu Lin, Jian Luan, Yaojie Lu, Jun Zhao, Xianpei Han, Juanzi Li, Kang Liu, Bin Wang, Le Sun

## Knowledge Lifecycle

![The knowledge lifecycle of large language models](docs/assets/knowledge-lifecycle.png)

The first five stages form a progression: what a model acquires constrains what it can represent; representation shapes utilization; evolution changes existing knowledge; and transfer moves knowledge across models, modalities, and languages. Evaluation runs alongside the entire process.

## Lifecycle Taxonomy

| Stage | Core question | Main topics |
| --- | --- | --- |
| **Knowledge Acquisition / 知识获取** | How is knowledge learned? | Training methods, training data, model architecture and scale |
| **Knowledge Representation / 知识表征** | How is knowledge stored and organized? | Parametric memory, activation spaces, model circuits |
| **Knowledge Utilization / 知识利用** | How is knowledge used during inference? | Recall, augmentation, knowledge conflict |
| **Knowledge Evolution / 知识演化** | How is knowledge changed after training? | Editing, unlearning, side effects |
| **Knowledge Transfer / 知识迁移** | How does knowledge cross boundaries? | Cross-model, cross-modal, cross-lingual transfer |
| **Knowledge Evaluation / 知识评测** | How should model knowledge be measured? | Factuality, compositionality, currency, calibration |

## Resources

| Resource | Link |
| --- | --- |
| Project homepage | [xiangh8.github.io/Awesome-Knowledge-Mechanisms](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/) |
| Survey manuscript | [Download the current PDF](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/downloads/knowledge-mechanisms-across-llm-lifecycle.pdf) |
| Canonical record | [OSF DOI: 10.17605/OSF.IO/C8HXB](https://doi.org/10.17605/OSF.IO/C8HXB) |

## Citation

```bibtex
@misc{xiang2026knowledgemechanisms,
  title = {Knowledge Mechanisms Across the Lifecycle of Large Language Models},
  author = {Hao Xiang and Xiusheng Huang and Shangqing Tu and Jiasheng Zheng and Jiakuan Xie and Chenhui Hu and JiaXiang Liu and Qiao Liang and Boxi Cao and Pengfei Cao and Lei Hou and Hongyu Lin and Jian Luan and Yaojie Lu and Jun Zhao and Xianpei Han and Juanzi Li and Kang Liu and Bin Wang and Le Sun},
  year = {2026},
  month = {July},
  publisher = {OSF},
  doi = {10.17605/OSF.IO/C8HXB},
  url = {https://doi.org/10.17605/OSF.IO/C8HXB}
}
```

## Repository Structure

```text
.
├── README.md                         # Project overview
├── README_CN.md                      # 中文项目说明
├── CITATION.cff                      # Citation metadata
└── docs/                             # GitHub Pages homepage
    ├── index.html
    ├── styles.css
    ├── assets/
    └── downloads/
```

The homepage is a dependency-free static site published from `xh:/docs`. Maintenance notes and local preview instructions are available in [`docs/README.md`](docs/README.md).

## Status

The survey and taxonomy are active drafts. The manuscript and terminology may change as the project develops.
