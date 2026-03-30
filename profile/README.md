# IntelliStream Research Group

[![Total Stars](https://img.shields.io/github/stars/intellistream?style=flat&logo=github&label=Total%20Stars)](https://github.com/intellistream)

<div align="center">

[![Website](https://img.shields.io/badge/Website-lab.sage.org.ai-blue?style=flat&logo=github)](https://lab.sage.org.ai)
[![GitHub Organization](https://img.shields.io/badge/GitHub-intellistream-181717?style=flat&logo=github)](https://github.com/intellistream)

**面向流处理、推理系统与智能数据基础设施的开源研究团队**

*Open-source research group for stream processing, inference systems, and intelligent data infrastructure.*

</div>

---

## Official Entry Points | 官方入口

为减少入口分散，当前对外统一为三类入口：

- [sage.org.ai](https://sage.org.ai/): SAGE 产品首页与文档主入口
- [lab.sage.org.ai](https://lab.sage.org.ai): IntelliStream 组织/实验室门户
- [github.com/intellistream](https://github.com/intellistream): 团队 GitHub Profile，与代码、Issue、发布和仓库入口

建议使用方式：

- 想了解或使用 SAGE：先看 `sage.org.ai`
- 想了解团队与项目全景：看 `lab.sage.org.ai`
- 想找源码、仓库和贡献入口：看 GitHub Profile

---

## SAGE First | SAGE 主线

[SAGE](https://github.com/intellistream/SAGE) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/SAGE?style=flat&logo=github)](https://github.com/intellistream/SAGE/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage.svg)](https://pypi.org/project/isage/)

SAGE (Streaming-Augmented Generative Execution) 是 IntelliStream 当前的核心框架，定位为 **stream-first inference service system**。

*SAGE is IntelliStream's core framework and is currently focused as a stream-first inference service system.*

当前核心产品面（in-tree）集中在：

- `sage.foundation`
- `sage.stream`
- `sage.runtime`
- `sage.serving`
- `sage.cli`

分层结构（L1 -> L4）：

```text
L1: sage.foundation
L2: sage.stream + sage.runtime
L3: sage.cli
L4: optional apps/research repos (docs, studio, benchmarks)
```

治理约定（公开协作关键信息）：

- 默认工作分支为 `main`
- `main-dev` 已不再作为持续集成工作分支
- 主仓开发入口为 `quickstart.sh` 与 `sage-dev`

---

## Repository Map | 仓库地图

### Core

- [SAGE](https://github.com/intellistream/SAGE): 核心框架与运行时主仓
- [SAGE-Docs](https://github.com/intellistream/SAGE-Docs): 公共文档站点与文档源
- [sage-tutorials](https://github.com/intellistream/sage-tutorials): 教程与示例代码

### Benchmarks

- [sage-agentic-tooluse-benchmark](https://github.com/intellistream/sage-agentic-tooluse-benchmark): Agent 工具调用评测
- [sage-rag-benchmark](https://github.com/intellistream/sage-rag-benchmark): RAG 管道评测
- [sage-refiner-benchmark](https://github.com/intellistream/sage-refiner-benchmark): Refiner 评测
- [SAGE-DB-Bench](https://github.com/intellistream/SAGE-DB-Bench): 向量检索/数据库评测
- [LibAMM](https://github.com/intellistream/LibAMM): 近似矩阵乘法评测

### Selected Research Systems

- [MorphStream](https://github.com/intellistream/MorphStream)
- [AllianceDB](https://github.com/intellistream/AllianceDB)
- [Sesame](https://github.com/intellistream/Sesame)
- [PDSC](https://github.com/intellistream/PDSC)

> Public profile keeps the map concise. Internal/private coordination repositories are not listed here.

---

## Quick Start | 快速开始

```bash
# Install from PyPI
pip install isage

# Developer setup
git clone https://github.com/intellistream/SAGE.git
cd SAGE
git checkout main
./quickstart.sh --dev --yes
```

常用验证命令：

```bash
sage verify
sage status
sage chat --ask "Hello, SAGE!"
```

文档入口：

- [SAGE-Docs repository](https://github.com/intellistream/SAGE-Docs)
- [SAGE Documentation site](https://sage.org.ai/)

---

## Contributing | 参与贡献

欢迎 issue、PR、文档修订与基准复现。

*We welcome issues, PRs, doc improvements, and reproducible benchmark contributions.*

请优先阅读目标仓库中的：

- `CONTRIBUTING.md`
- `DEVELOPER.md`（若存在）

---

## Contact | 联系方式

- Email: [shuhao_zhang at hust.edu.cn](mailto:shuhao_zhang@hust.edu.cn)
- Website: [intellistream.github.io](https://intellistream.github.io)

---

<div align="center">

**If our work helps your research or products, a star is always appreciated.**

</div>
