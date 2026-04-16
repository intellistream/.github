# IntelliStream Research Group

[![Total Stars](https://img.shields.io/github/stars/intellistream?style=flat&logo=github&label=Total%20Stars)](https://github.com/intellistream)

<div align="center">

[![Website](https://img.shields.io/badge/Website-sage.org.ai-blue?style=flat&logo=googlechrome)](https://sage.org.ai)
[![Lab](https://img.shields.io/badge/Lab-lab.sage.org.ai-0aa8a7?style=flat&logo=googlechrome)](https://lab.sage.org.ai)
[![GitHub Organization](https://img.shields.io/badge/GitHub-intellistream-181717?style=flat&logo=github)](https://github.com/intellistream)

**面向流处理、推理系统与智能数据基础设施的开源研究团队**

*Open-source research group for stream processing, inference systems, and intelligent data infrastructure.*

</div>

---

## Official Entry Points | 官方入口

当前对外统一为三个稳定入口：

- [sage.org.ai](https://sage.org.ai/): SAGE 产品与公开文档主入口
- [lab.sage.org.ai](https://lab.sage.org.ai/): IntelliStream 团队与研究门户
- [github.com/intellistream](https://github.com/intellistream): 源码、Issue、发布与仓库导航入口

使用建议：

- 想了解或使用 SAGE：从 `sage.org.ai` 开始
- 想看团队与研究全景：进入 `lab.sage.org.ai`
- 想找代码、仓库、贡献入口：查看 GitHub Profile

---

## SAGE First | SAGE 主线

[SAGE](https://github.com/intellistream/SAGE) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/SAGE?style=flat&logo=github)](https://github.com/intellistream/SAGE/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage.svg)](https://pypi.org/project/isage/)

SAGE (Streaming-Augmented Generative Execution) 是 IntelliStream 当前的核心框架，定位为 **stream-first inference service system**。

*SAGE is IntelliStream's core framework and current product center, focused on a stream-first inference service system.*

当前主线以主仓的 in-tree 核心能力为中心：

- `sage.foundation`
- `sage.stream`
- `sage.runtime`
- `sage.serving`
- `sage.cli`

围绕主仓的公开生态仓库分别承担不同角色：

- 文档发布：`SAGE-Docs`
- 分层学习路径：`sage-tutorials`
- 可运行应用示例：`sage-examples`
- 评测与复现：benchmark 系列仓库

公开协作约定：

- 默认工作分支为 `main`
- `main-dev` 不再作为持续集成工作分支
- 主仓开发入口为 `quickstart.sh` 与 `sage-dev`

---

## Repository Guide | 仓库导航

### Core Platform

- [SAGE](https://github.com/intellistream/SAGE): 核心框架、运行时、CLI 与服务主仓
- [SAGE-Docs](https://github.com/intellistream/SAGE-Docs): 对外文档站点与文档源

### Learning and Examples

- [sage-tutorials](https://github.com/intellistream/sage-tutorials): 按层组织的教程、最小示例与学习路径
- [sage-examples](https://github.com/intellistream/sage-examples): 端到端应用示例、演示脚本与可安装应用入口

### Benchmarks

- [sage-agentic-tooluse-benchmark](https://github.com/intellistream/sage-agentic-tooluse-benchmark): Agent 工具调用评测
- [sage-rag-benchmark](https://github.com/intellistream/sage-rag-benchmark): RAG 管道评测
- [sage-refiner-benchmark](https://github.com/intellistream/sage-refiner-benchmark): Refiner 评测
- [SAGE-DB-Bench](https://github.com/intellistream/SAGE-DB-Bench): 向量检索与数据库评测
- [LibAMM](https://github.com/intellistream/LibAMM): 近似矩阵乘法评测

### Selected Research Systems

- [MorphStream](https://github.com/intellistream/MorphStream): 流处理研究系统
- [AllianceDB](https://github.com/intellistream/AllianceDB): 数据管理研究系统
- [Sesame](https://github.com/intellistream/Sesame): 智能数据系统研究项目
- [PDSC](https://github.com/intellistream/PDSC): 相关研究系统与原型

> Public profile keeps the map concise. Internal or private coordination repositories are not listed here.

---

## Where To Start | 从哪里开始

- 想直接使用 SAGE：访问 [sage.org.ai](https://sage.org.ai/)
- 想开发或扩展核心能力：进入 [SAGE](https://github.com/intellistream/SAGE)
- 想按层学习框架概念：进入 [sage-tutorials](https://github.com/intellistream/sage-tutorials)
- 想看完整应用和运行脚本：进入 [sage-examples](https://github.com/intellistream/sage-examples)
- 想做评测、复现或系统比较：查看 benchmark 系列仓库

---

## Quick Start | 快速开始

```bash
# Install from PyPI
python -m pip install isage

# Developer setup
git clone https://github.com/intellistream/SAGE.git
cd SAGE
git checkout main
./quickstart.sh --dev --yes

# Basic verification
sage verify
sage status
```

文档与学习入口：

- Documentation site: [sage.org.ai](https://sage.org.ai/)
- Docs repository: [SAGE-Docs](https://github.com/intellistream/SAGE-Docs)
- Layered tutorials: [sage-tutorials](https://github.com/intellistream/sage-tutorials)
- Runnable examples: [sage-examples](https://github.com/intellistream/sage-examples)

---

## Contributing | 参与贡献

欢迎提交 Issue、PR、文档修订和可复现实验结果。

*We welcome issues, pull requests, doc improvements, and reproducible benchmark contributions.*

提交前建议优先阅读目标仓库中的：

- `CONTRIBUTING.md`
- `DEVELOPER.md`（若存在）

---

## Contact | 联系方式

- Email: [shuhao_zhang at hust.edu.cn](mailto:shuhao_zhang@hust.edu.cn)
- Website: [lab.sage.org.ai](https://lab.sage.org.ai/)

---

<div align="center">

**If our work helps your research or products, a star is always appreciated.**

</div>
