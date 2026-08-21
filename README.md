<div align="center">

# Knowledge Mechanisms Across the Lifecycle of Large Language Models

<p>
  <a href="https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/"><img src="https://img.shields.io/badge/Project%20Page-xiangh8.github.io-2F80ED?style=for-the-badge&logo=githubpages&logoColor=white" alt="Project Page"></a>
  <a href="https://xiangh8.github.io/Awesome-Knowledge-Mechanisms/downloads/knowledge-mechanisms-across-llm-lifecycle.pdf"><img src="https://img.shields.io/badge/Paper-PDF-B31B1B?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Paper PDF"></a>
  <a href="https://doi.org/10.17605/OSF.IO/C8HXB"><img src="https://img.shields.io/badge/OSF-10.17605%2FOSF.IO%2FC8HXB-2CB9B0?style=for-the-badge&logo=osf&logoColor=white" alt="OSF DOI"></a>
  <a href="README_CN.md"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-README-555555?style=for-the-badge" alt="中文说明"></a>
</p>

</div>

Knowledge is fundamental to the capabilities of large language models, but research on how models acquire, represent, use, and revise knowledge remains scattered across communities with different concepts, methods, and evaluation standards.

This survey organizes that research around a single lifecycle. It treats knowledge as an object under continuous change and connects behavioral observations with the internal mechanisms that produce them.

<p align="center">
  <img src="docs/assets/knowledge-lifecycle.png" alt="The knowledge lifecycle of large language models" width="88%">
</p>

## ✨ Highlights

- **A unified lifecycle:** Knowledge acquisition, representation, utilization, evolution, transfer, and evaluation are studied as six interconnected stages.
- **A mechanism-centered view:** The survey connects observable behavior with parametric storage, activation-space representations, retrieval, editing, unlearning, and transfer.
- **Dependencies across stages:** It examines how decisions and interventions at one stage constrain or alter the stages that follow.
- **Findings and open problems:** Each stage concludes with its main findings and the questions that remain unresolved.

## 🧭 Survey Scope

- **Knowledge Acquisition:** How training methods, data, architecture, and scale determine what knowledge enters a model.
- **Knowledge Representation:** How knowledge is encoded and organized in model parameters and activation spaces.
- **Knowledge Utilization:** How models recall internal knowledge, augment it with external sources, and resolve conflicts.
- **Knowledge Evolution:** How editing and unlearning change model knowledge and produce side effects.
- **Knowledge Transfer:** How knowledge moves across models, modalities, and languages.
- **Knowledge Evaluation:** How parametric and contextual knowledge are assessed across the lifecycle.

Explore the [complete taxonomy](docs/assets/taxonomy-overview.png) or open the [vector PDF](docs/assets/knowledge-taxonomy.pdf).

## 👥 Authors

**Core Contributors:** Hao Xiang (Leading Contributor), Xiusheng Huang, Shangqing Tu, Jiasheng Zheng, Jiakuan Xie, Chenhui Hu, JiaXiang Liu, Qiao Liang

**Instructors:** Boxi Cao, Pengfei Cao, Lei Hou, Hongyu Lin, Jian Luan, Yaojie Lu, Jun Zhao, Xianpei Han, Juanzi Li, Kang Liu, Bin Wang, Le Sun

## 📁 Repository Layout

```text
.
|-- README.md                 # English project overview
|-- README_CN.md              # Chinese project overview
|-- CITATION.cff              # Citation metadata
`-- docs/                     # GitHub Pages source
    |-- index.html
    |-- styles.css
    |-- assets/
    `-- downloads/
```

The homepage is published from `xh:/docs`. Maintenance and local preview instructions are available in [`docs/README.md`](docs/README.md).

## 📚 Citation

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
