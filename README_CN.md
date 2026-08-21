# 大语言模型全生命周期中的知识机制

> 一项从生命周期视角系统梳理大语言模型如何获取、表征、利用、演化、迁移和评测知识的综述工作。

[English](README.md) | [项目主页](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/) | [下载论文](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/downloads/knowledge-mechanisms-across-llm-lifecycle.pdf)

## 项目简介

知识是大语言模型能力的基础，但关于模型如何学习、存储、使用和修正知识的研究仍然分散在训练、可解释性、检索增强、知识编辑、知识遗忘、迁移和评测等不同研究方向中。

本综述以同一个知识对象在模型中的连续变化为主线，将相关研究组织为一个完整生命周期：知识首先通过训练进入模型，随后形成内部表征并参与推理，再通过编辑或遗忘发生变化，并在模型、模态和语言之间迁移；评测则贯穿整个过程。生命周期视角能够揭示各阶段之间容易被单独研究所掩盖的依赖关系，并将外部行为观察与内部机制解释联系起来。

当前分类体系包含六个生命周期阶段。

## 作者

**核心贡献者：** Hao Xiang（Leading Contributor）、Xiusheng Huang、Shangqing Tu、Jiasheng Zheng、Jiakuan Xie、Chenhui Hu、JiaXiang Liu、Qiao Liang

**指导者：** Boxi Cao、Pengfei Cao、Lei Hou、Hongyu Lin、Jian Luan、Yaojie Lu、Jun Zhao、Xianpei Han、Juanzi Li、Kang Liu、Bin Wang、Le Sun

## 知识生命周期

![大语言模型知识生命周期](docs/assets/knowledge-lifecycle.png)

前五个阶段构成连续过程：模型获取到的知识约束其可形成的表征，知识表征决定知识如何被利用，知识演化修改模型中已有的知识，知识迁移则让知识跨越模型、模态和语言边界。知识评测贯穿并检验整个生命周期。

## 生命周期分类

| 阶段 | 核心问题 | 主要内容 |
| --- | --- | --- |
| **知识获取（Knowledge Acquisition）** | 模型如何学习知识？ | 训练方法、训练数据、模型架构与规模 |
| **知识表征（Knowledge Representation）** | 知识如何在模型中存储和组织？ | 参数记忆、激活空间、模型回路 |
| **知识利用（Knowledge Utilization）** | 模型如何在推理中使用知识？ | 知识召回、知识增强、知识冲突 |
| **知识演化（Knowledge Evolution）** | 训练后的知识如何发生变化？ | 知识编辑、知识遗忘及其副作用 |
| **知识迁移（Knowledge Transfer）** | 知识如何跨越不同边界？ | 跨模型、跨模态、跨语言迁移 |
| **知识评测（Knowledge Evaluation）** | 应当如何衡量模型中的知识？ | 事实性、组合性、时效性、校准性 |

## 项目资源

| 资源 | 链接 |
| --- | --- |
| 项目主页 | [xiangh8.github.io/Awesome-Knowledge-Mechanisms](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/) |
| 综述论文 | [下载当前 PDF](https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/downloads/knowledge-mechanisms-across-llm-lifecycle.pdf) |
| 规范记录 | [OSF DOI: 10.17605/OSF.IO/C8HXB](https://doi.org/10.17605/OSF.IO/C8HXB) |

## 引用

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

## 仓库结构

```text
.
├── README.md                         # 英文项目说明
├── README_CN.md                      # 中文项目说明
├── CITATION.cff                      # 引用元数据
└── docs/                             # GitHub Pages 项目主页
    ├── index.html
    ├── styles.css
    ├── assets/
    └── downloads/
```

项目主页是一个无外部依赖的静态站点，从 `xh:/docs` 发布。站点维护方法和本地预览命令见 [`docs/README.md`](docs/README.md)。

## 项目状态

当前综述和分类体系仍处于持续完善阶段，论文内容和术语可能随着项目推进而更新。
