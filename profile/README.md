# IntelliStream Research Group

[![Total Stars](https://img.shields.io/github/stars/intellistream?style=flat&logo=github&label=Total%20Stars)](https://github.com/intellistream)

[![Website](https://img.shields.io/badge/Website-intellistream.github.io-blue?style=flat&logo=github)](https://intellistream.github.io)
[![GitHub Organization](https://img.shields.io/badge/GitHub-intellistream-181717?style=flat&logo=github)](https://github.com/intellistream)
[![SAGE](https://img.shields.io/badge/SAGE-isage-7c3aed?style=flat&logo=python)](https://pypi.org/project/isage/)
[![sageLLM](https://img.shields.io/badge/sageLLM-isagellm-0ea5e9?style=flat&logo=pypi)](https://pypi.org/project/isagellm/)

## 专注于流处理、AI 系统与智能数据库的研究与工程化

*Focused on stream processing, AI systems, and intelligent databases.*

---

## 🌟 SAGE 生态系统 | SAGE Ecosystem

SAGE（Streaming-Augmented Generative Execution）是一个**以数据流、运行时与服务接口为核心**的 AI 系统生态。

*SAGE is a stream-first AI systems ecosystem centered on dataflow, runtime, and serving surfaces.*

### 核心特征 | Core characteristics

- **统一主入口**：从 [SAGE](https://github.com/intellistream/SAGE) 开始，安装包为 [isage](https://pypi.org/project/isage/)
- **核心能力集中提供**：`sage.foundation`、`sage.stream`、`sage.runtime`、`sage.serving`、`sage.cli`
- **边缘与服务一体化**：`sage.edge` 作为核心服务表面的一部分
- **分布式执行可选启用**：采用 **Flutty-first** 路线，`FluttyEnvironment` 提供扩展执行能力
- **推理引擎独立协同**：[`sagellm`](https://github.com/intellistream/sagellm) / [`isagellm`](https://pypi.org/project/isagellm/) 作为独立引擎生态与 SAGE 协同工作
- **外围仓库清晰分层**：文档、教程、示例、评测位于核心系统之上

### 当前推荐的产品表面 | Preferred product surface

```python
from sage.foundation import SagePorts, SageUserPaths
from sage.stream import DataStream
from sage.runtime import LocalEnvironment, FluttyEnvironment, JobManager
from sage.serving import build_sagellm_gateway_command, probe_gateway
```

### 当前架构拓扑 | Current topology

```text
L4  Satellite repos / apps / benchmarks
    sage-docs · sage-examples · sage-tutorials · sage-benchmark · optional adapters
 ↓
L3  Interfaces owned in-tree
    sage.cli · sage.serving · sage.edge
 ↓
L2  Execution core owned in-tree
    sage.runtime · sage.stream
 ↓
L1  Foundation owned in-tree
    sage.foundation
```

> `intellistream/SAGE` 是 SAGE 生态的默认主入口，统一承载核心 API、运行时与服务表面。

---

## 🚀 从哪里开始 | Start Here

### 核心仓库 | Core repos

| Repo | 角色 | Description |
| --- | --- | --- |
| [SAGE](https://github.com/intellistream/SAGE) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/SAGE?style=flat&logo=github)](https://github.com/intellistream/SAGE/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage.svg)](https://pypi.org/project/isage/) | 统一核心仓 | 主产品面：`sage.foundation` / `sage.stream` / `sage.runtime` / `sage.serving` / `sage.cli` |
| [sage-docs](https://github.com/intellistream/sage-docs) | 文档站 | 用户文档、架构说明、API 入口、站点发布 |
| [sage-examples](https://github.com/intellistream/sage-examples) | 示例仓 | 最小可运行样例、应用入口、实践片段 |
| [sage-tutorials](https://github.com/intellistream/sage-tutorials) | 教程仓 | 分层教学材料与学习路径 |
| [sage-benchmark](https://github.com/intellistream/sage-benchmark) | 评测仓 | 面向 SAGE 子系统和端到端场景的评测 |

### 工作区仓库 | Workspace repos

| Repo | 当前定位 |
| --- | --- |
| [sage-common](https://github.com/intellistream/sage-common) | 基础能力与共享契约相关仓库 |
| [sage-kernel](https://github.com/intellistream/sage-kernel) | 运行时与执行相关仓库 |
| [sage-cli](https://github.com/intellistream/sage-cli) | 命令行与开发入口相关仓库 |
| [sage-studio](https://github.com/intellistream/sage-studio) | 上层应用与交互式实验空间 |

---

## 🧱 SAGE 现在强调什么 | What SAGE now emphasizes

- **Stream-first**：数据流是产品中心，不是附属层
- **Runtime-owned execution**：本地执行、调度、作业管理、服务生命周期统一进入主仓
- **Serving as a contract**：服务接入、健康检查、OpenAI-compatible gateway 集成边界清晰
- **Local-first, scale-out optional**：默认本地可用，分布式执行按需启用
- **Sharper boundaries**：RAG、memory、tool-use、benchmark 等能力优先作为可选适配层存在

---

## 🧠 sageLLM：独立但协同的推理引擎生态 | sageLLM: Independent but tightly integrated

[`sagellm`](https://github.com/intellistream/sagellm) 是与 SAGE 协同演进的独立推理引擎生态。

*sageLLM is an independent inference engine ecosystem that integrates with SAGE through stable boundaries rather than being absorbed into the SAGE core.*

```text
L1  sagellm-protocol
 ↓
L2  sagellm-core · sagellm-backend · sagellm-comm · sagellm-kv-cache · sagellm-compression
 ↓
L3  sagellm-control-plane
 ↓
L4  sagellm-gateway
 ↓
L5  sagellm · sagellm-benchmark · sagellm-docs · sagellm-dev-tools
```

### 关键仓库 | Key repos

- [sagellm](https://github.com/intellistream/sagellm) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sagellm?style=flat&logo=github)](https://github.com/intellistream/sagellm/stargazers) [![PyPI](https://img.shields.io/pypi/v/isagellm.svg)](https://pypi.org/project/isagellm/)
- [sagellm-protocol](https://github.com/intellistream/sagellm-protocol)
- [sagellm-control-plane](https://github.com/intellistream/sagellm-control-plane)
- [sagellm-gateway](https://github.com/intellistream/sagellm-gateway)

---

## 🧩 能力生态仓库 | Capability repos

这些仓库提供算法能力、数据能力或工具能力，通常通过独立包与 SAGE 核心协同。

*These repos provide algorithmic, data, or tooling capabilities that integrate with the SAGE core as independent packages or adapters.*

- **算法能力 | Algorithm capabilities**:
  [sage-agentic](https://github.com/intellistream/sage-agentic),
  [sage-agentic-tooluse](https://github.com/intellistream/sage-agentic-tooluse),
  [sage-agentic-tooluse-sias](https://github.com/intellistream/sage-agentic-tooluse-sias),
  [sage-rag](https://github.com/intellistream/sage-rag),
  [sageRefiner](https://github.com/intellistream/sageRefiner),
  [sage-eval](https://github.com/intellistream/sage-eval),
  [sage-intent](https://github.com/intellistream/sage-intent),
  [sage-safety](https://github.com/intellistream/sage-safety),
  [sage-privacy](https://github.com/intellistream/sage-privacy)
- **运行时 / 数据能力 | Runtime and data capabilities**:
  [sageVDB](https://github.com/intellistream/sageVDB),
  [sage-anns](https://github.com/intellistream/sage-anns),
  [sageFlow](https://github.com/intellistream/sageFlow),
  [sageTSDB](https://github.com/intellistream/sageTSDB),
  [neuromem](https://github.com/intellistream/neuromem),
  [sageData](https://github.com/intellistream/sageData)
- **文档与开发工具 | Docs and tooling**:
  [sage-pypi-publisher](https://github.com/intellistream/sage-pypi-publisher),
  [sage-github-manager](https://github.com/intellistream/sage-github-manager),
  [sage-team-info](https://github.com/intellistream/sage-team-info)

---

## 🔬 研究评测仓库 | Research benchmark repos

| Repo | Evaluates | Description |
| --- | --- | --- |
| [sage-agentic-tooluse-benchmark](https://github.com/intellistream/sage-agentic-tooluse-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sage-agentic-tooluse-benchmark?style=flat&logo=github)](https://github.com/intellistream/sage-agentic-tooluse-benchmark/stargazers) | `sage-agentic-tooluse` | Agent 工具调用选择算法评测 |
| [sage-rag-benchmark](https://github.com/intellistream/sage-rag-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sage-rag-benchmark?style=flat&logo=github)](https://github.com/intellistream/sage-rag-benchmark/stargazers) | `sage-rag` | RAG 检索与重排评测 |
| [sage-refiner-benchmark](https://github.com/intellistream/sage-refiner-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sage-refiner-benchmark?style=flat&logo=github)](https://github.com/intellistream/sage-refiner-benchmark/stargazers) | `sageRefiner` | 上下文压缩与精炼算法评测 |
| [sage-memory-benchmark](https://github.com/intellistream/sage-memory-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sage-memory-benchmark?style=flat&logo=github)](https://github.com/intellistream/sage-memory-benchmark/stargazers) | `neuromem` | 记忆管理与检索性能评测 |
| [sagellm-control-plane-benchmark](https://github.com/intellistream/sagellm-control-plane-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sagellm-control-plane-benchmark?style=flat&logo=github)](https://github.com/intellistream/sagellm-control-plane-benchmark/stargazers) | `sagellm-control-plane` | LLM 调度控制面算法评测 |
| [sagellm-benchmark](https://github.com/intellistream/sagellm-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sagellm-benchmark?style=flat&logo=github)](https://github.com/intellistream/sagellm-benchmark/stargazers) | `sagellm` | 端到端 LLM 推理系统评测 |
| [SAGE-DB-Bench](https://github.com/intellistream/SAGE-DB-Bench) [![Stars](https://img.shields.io/github/stars/intellistream/SAGE-DB-Bench?style=flat&logo=github)](https://github.com/intellistream/SAGE-DB-Bench/stargazers) | `sage-anns` / `sageVDB` | 流式 ANN 向量数据库评测 |
| [LibAMM](https://github.com/intellistream/LibAMM) [![Stars](https://img.shields.io/github/stars/intellistream/LibAMM?style=flat&logo=github)](https://github.com/intellistream/LibAMM/stargazers) | `sage-amms` | 近似矩阵乘法算法评测 |

---

## 🚀 快速开始 | Quick start

### 安装统一核心 | Install the unified core

```bash
pip install isage

# 或开发安装 | or dev install
git clone https://github.com/intellistream/SAGE.git
cd SAGE
git checkout main-dev
./quickstart.sh --dev --yes
```

### 先跑通核心命令 | First commands to try

```bash
sage verify
sage status
sage runtime nodes
sage serve gateway --probe --json
sage chat --ask "Hello, SAGE!"
```

### 继续探索 | Continue exploring

- 文档 | Docs: [intellistream.github.io/sage-docs](https://intellistream.github.io/sage-docs/)
- 示例 | Examples: [sage-examples](https://github.com/intellistream/sage-examples)
- 教程 | Tutorials: [sage-tutorials](https://github.com/intellistream/sage-tutorials)
- 评测 | Benchmarks: [sage-benchmark](https://github.com/intellistream/sage-benchmark)

---

## 🧪 其他研究项目 | Other research projects

### 流处理系统 | Stream processing systems

- **[MorphStream](https://github.com/intellistream/MorphStream)** — scalable transactional stream processing engine
- **[AllianceDB](https://github.com/intellistream/AllianceDB)** — parallel database system

### 基准测试与工具 | Benchmarks and tools

- **[Sesame](https://github.com/intellistream/Sesame)** — empirical study on data stream clustering
- **[PDSC](https://github.com/intellistream/PDSC)** — parallel data stream clustering benchmark

### 机器学习与 AI | Machine learning and AI

- **[SentiStream](https://github.com/intellistream/SentiStream)** — sentiment analysis stream processing
- **[StreamLearning](https://github.com/intellistream/StreamLearning)** — stream learning framework

### 资源与文档 | Resources and reading

- **[StreamProcessing_ReadingList](https://github.com/intellistream/StreamProcessing_ReadingList)** — reading list for stream processing
- **[Awesome-Online-Continual-Learning](https://github.com/intellistream/Awesome-Online-Continual-Learning)** — online continual learning resources

---

## 🤝 参与贡献 | Contributing

欢迎通过代码、文档、评测、Issue 和讨论参与贡献。各仓库的贡献方式可能不同，请优先阅读对应仓库的 `CONTRIBUTING.md`。

*Contributions are welcome across code, docs, benchmarks, issues, and discussions. Please read each repository's `CONTRIBUTING.md` for repo-specific guidance.*

---

## 📞 联系方式 | Contact

- 📧 **Email**: [shuhao_zhang@hust.edu.cn](mailto:shuhao_zhang@hust.edu.cn)
- 🌐 **Website**: [intellistream.github.io](https://intellistream.github.io)

---

## 📄 许可证 | License

各项目的许可证以对应仓库为准；大多数项目采用 MIT 或 Apache 2.0。

*License terms are defined per repository; most projects use MIT or Apache 2.0.*

---

**⭐ 如果这些项目对你有帮助，欢迎 Star 与关注。**

***If these projects are useful, consider starring the repos and following the organization.***
