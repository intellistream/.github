# IntelliStream Research Group

[![Total Stars](https://img.shields.io/github/stars/intellistream?style=flat&logo=github&label=Total%20Stars)](https://github.com/intellistream)

<div align="center">

[![Website](https://img.shields.io/badge/Website-intellistream.github.io-blue?style=flat&logo=github)](https://intellistream.github.io)
[![GitHub Organization](https://img.shields.io/badge/GitHub-intellistream-181717?style=flat&logo=github)](https://github.com/intellistream)

**专注于流处理、AI系统与智能数据库的研究与开发**

*Focused on Stream Processing, AI Systems, and Intelligent Databases*

</div>

---

## 🌟 SAGE 项目生态系统 | SAGE Project Ecosystem

SAGE (Streaming-Augmented Generative Execution) 是 IntelliStream 面向 AI 数据处理与推理流水线的主框架。
当前核心代码已经重新收敛到一个主仓库中，围绕统一的 L1→L5 分层架构组织开发、测试与发布。

*SAGE is IntelliStream's primary framework for AI data processing and inference pipelines, organized as a single main repository with a unified L1→L5 layered architecture.*

[SAGE](https://github.com/intellistream/SAGE) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/SAGE?style=flat&logo=github)](https://github.com/intellistream/SAGE/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage.svg)](https://pypi.org/project/isage/)

- **Monorepo packages**: `sage`, `sage-common`, `sage-platform`, `sage-kernel`, `sage-libs`, `sage-middleware`, `sage-cli`, `sage-tools`
- **In-tree benchmarking**: benchmark configs, experiment scripts, and evaluation assets now live alongside the main repo
- **Public docs**: maintained in [SAGE-Pub](https://github.com/intellistream/SAGE-Pub)

### 🏗️ SAGE 分层架构（L1→L5）| SAGE Layered Architecture

```text
L1  sage-common
 ↓
L2  sage-platform
 ↓
L3  sage-kernel     sage-libs
 ↓
L4  sage-middleware
 ↓
L5  sage-cli        sage-tools
```

### 核心主仓库 | Core Monorepo

| 层级 / Layer | 组件 / Components | 作用 / Role |
|---|---|---|
| L1 | `sage-common` | 配置、日志、协议、公共工具 |
| L2 | `sage-platform` | 队列、存储、服务与运行基础设施抽象 |
| L3 | `sage-kernel`, `sage-libs` | 流式运行时、调度、算法与数据处理能力 |
| L4 | `sage-middleware` | 向量库、记忆系统、网络算子与运行时绑定组件 |
| L5 | `sage-cli`, `sage-tools` | CLI、开发工作流、质量检查与维护工具 |

附加内容：

- `benchmark/`：主仓库内维护的评测配置、实验脚本和结果资产
- `packages/sage/`：聚合安装入口与统一发布包

### 配套仓库 | Companion Repositories

这些仓库仍然独立维护，但围绕主 SAGE 仓库协同工作：

| 仓库 / Repo | 用途 / Purpose |
|---|---|
| [SAGE-Pub](https://github.com/intellistream/SAGE-Pub) | 公共文档、网站与发布文档源 |
| [wheelwright](https://github.com/intellistream/wheelwright) | 通用 Python 包发布工具 |
| [sage-studio](https://github.com/intellistream/sage-studio) | 可视化工作流与交互式体验入口 |
| [sage-edge](https://github.com/intellistream/sage-edge) | 边缘部署与聚合网关 |

> 说明：公共 profile 仅保留对外可见且仍建议独立使用的配套仓库；内部团队仓库不在此处展示。

---

## 🧠 vLLM-HUST 生态 | vLLM-HUST Ecosystem

vLLM-HUST 是 IntelliStream 后续重点推进的 LLM 推理研发主线，基于 vLLM 进行增强与工程化扩展。

*vLLM-HUST is IntelliStream's primary LLM inference development line, built on top of vLLM with engineering-focused extensions.*

- [vllm-hust](https://github.com/intellistream/vllm-hust) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/vllm-hust?style=flat&logo=github)](https://github.com/intellistream/vllm-hust/stargazers)
- [vllm-hust-workstation](https://github.com/intellistream/vllm-hust-workstation) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/vllm-hust-workstation?style=flat&logo=github)](https://github.com/intellistream/vllm-hust-workstation/stargazers)
- [vllm-hust-website](https://github.com/intellistream/vllm-hust-website) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/vllm-hust-website?style=flat&logo=github)](https://github.com/intellistream/vllm-hust-website/stargazers)

```text
vllm-hust (core)
  ├─ vllm-hust-workstation (product/runtime workspace)
  └─ vllm-hust-website (public site and docs portal)
```

---

## � 研究评测仓库 | Research Benchmark Repos

每个评测仓库独立维护，专注于评估对应子系统的性能与正确性。

*Each benchmark repo is independently maintained and focuses on evaluating the corresponding subsystem.*

| 仓库 / Repo | 评测对象 / Evaluates | 说明 / Description |
|---|---|---|
| [sage-agentic-tooluse-benchmark](https://github.com/intellistream/sage-agentic-tooluse-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sage-agentic-tooluse-benchmark?style=flat&logo=github)](https://github.com/intellistream/sage-agentic-tooluse-benchmark/stargazers) | sage-agentic-tooluse | Agent 工具调用选择算法评测 |
| [sage-rag-benchmark](https://github.com/intellistream/sage-rag-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sage-rag-benchmark?style=flat&logo=github)](https://github.com/intellistream/sage-rag-benchmark/stargazers) | sage-rag | RAG 检索与重排管道评测 |
| [sage-refiner-benchmark](https://github.com/intellistream/sage-refiner-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sage-refiner-benchmark?style=flat&logo=github)](https://github.com/intellistream/sage-refiner-benchmark/stargazers) | sageRefiner | 上下文压缩与精炼算法评测 |
| [sage-memory-benchmark](https://github.com/intellistream/sage-memory-benchmark) [![Stars](https://img.shields.io/github/stars/intellistream/sage-memory-benchmark?style=flat&logo=github)](https://github.com/intellistream/sage-memory-benchmark/stargazers) | neuromem | 记忆管理与检索性能评测 |
| [SAGE-DB-Bench](https://github.com/intellistream/SAGE-DB-Bench) [![Stars](https://img.shields.io/github/stars/intellistream/SAGE-DB-Bench?style=flat&logo=github)](https://github.com/intellistream/SAGE-DB-Bench/stargazers) | sage-anns / sageVDB | 流式 ANN 向量数据库评测 |
| [LibAMM](https://github.com/intellistream/LibAMM) [![Stars](https://img.shields.io/github/stars/intellistream/LibAMM?style=flat&logo=github)](https://github.com/intellistream/LibAMM/stargazers) | sage-amms | 近似矩阵乘法算法评测 |

---

## �🚀 其他研究项目 | Other Research Projects

### 流处理系统 | Stream Processing Systems

- **[MorphStream](https://github.com/intellistream/MorphStream)** ⭐ 141 - [ICDE'20, SIGMOD'23, TKDE'24] 可扩展的事务性流处理引擎 | Scalable transactional stream processing engine
- **[AllianceDB](https://github.com/intellistream/AllianceDB)** ⭐ 16 - [SIGMOD'21] 并行数据库系统 | Parallel database system

### 基准测试与工具 | Benchmarks & Tools

- **[Sesame](https://github.com/intellistream/Sesame)** ⭐ 26 - [SIGMOD'23] 数据流聚类实证研究 | Data stream clustering empirical study
- **[PDSC](https://github.com/intellistream/PDSC)** - 并行数据流聚类基准 | Parallel data stream clustering benchmark

### 机器学习与AI | Machine Learning & AI

- **[SentiStream](https://github.com/intellistream/SentiStream)** ⭐ 7 - [EMENLP'23] 情感分析流处理 | Sentiment analysis stream processing
- **[StreamLearning](https://github.com/intellistream/StreamLearning)** - 流式学习框架 | Stream learning framework

### 资源与文档 | Resources & Documentation

- **[StreamProcessing_ReadingList](https://github.com/intellistream/StreamProcessing_ReadingList)** ⭐ 69 - 流处理文献阅读列表 | Stream processing reading list
- **[Awesome-Online-Continual-Learning](https://github.com/intellistream/Awesome-Online-Continual-Learning)** - 在线持续学习资源 | Online continual learning resources

---

## 📖 快速开始 | Quick Start

### 安装 SAGE | Install SAGE

```bash
# PyPI 安装 | Install from PyPI
pip install isage

# 开发安装 | Development installation
git clone https://github.com/intellistream/SAGE.git
cd SAGE
./quickstart.sh --dev --yes
```

### 简单示例 | Simple Example

```python
from sage.kernel.api.local_environment import LocalEnvironment
from sage.libs.io.source import FileSource
from sage.middleware.operators.rag import DenseRetriever, QAPromptor, OpenAIGenerator
from sage.libs.io.sink import TerminalSink

# 创建执行环境 | Create execution environment
env = LocalEnvironment("rag_pipeline")

# 构建声明式管道 | Build declarative pipeline
(
    env.from_source(FileSource, {"file_path": "questions.txt"})
    .map(DenseRetriever, {"model": "sentence-transformers/all-MiniLM-L6-v2"})
    .map(QAPromptor, {"template": "Answer based on: {context}\nQ: {query}\nA:"})
    .map(OpenAIGenerator, {"model": "gpt-3.5-turbo"})
    .sink(TerminalSink)
)

# 执行管道 | Execute pipeline
env.submit()
```

详细文档请访问：[SAGE Documentation](https://intellistream.github.io/sage-docs/)

*For detailed documentation, visit: [SAGE Documentation](https://intellistream.github.io/sage-docs/)*

---

## 🤝 参与贡献 | Contributing

我们欢迎各种形式的贡献！请查看各个仓库的 CONTRIBUTING.md 文件了解详情。

*We welcome contributions of all kinds! Please check the CONTRIBUTING.md file in each repository for details.*

---

## 📞 联系我们 | Contact Us

- 💬 **Email**: [shuhao_zhang at hust.edu.cn](shuao_zhang@hust.edu.cn)
- 🌐 **Website**: [intellistream.github.io](https://intellistream.github.io)

---

## 📄 许可证 | License

各项目许可证详见各仓库的 LICENSE 文件。大多数项目采用 MIT 或 Apache 2.0 许可证。

*License details can be found in each repository's LICENSE file. Most projects use MIT or Apache 2.0 licenses.*

---

<div align="center">

**⭐ 如果我们的项目对您有帮助，请给我们一个 Star！**

***If our projects help you, please give us a Star!***

</div>
