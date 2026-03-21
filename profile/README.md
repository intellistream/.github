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

SAGE (Streaming-Augmented Generative Execution) 是一个高性能、模块化的 AI 推理框架生态系统，通过数据流抽象实现透明、可扩展的 LLM 驱动系统。

*SAGE is a high-performance, modular AI inference framework ecosystem that enables transparent, scalable LLM-powered systems through dataflow abstractions.*

[SAGE](https://github.com/intellistream/SAGE) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/SAGE?style=flat&logo=github)](https://github.com/intellistream/SAGE/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage.svg)](https://pypi.org/project/isage/)

- **Benchmarks**: 详见下方 [🔬 研究评测仓库](#-研究评测仓库--research-benchmark-repos) | *See [🔬 Research Benchmark Repos](#-研究评测仓库--research-benchmark-repos) below*
### 🏗️ SAGE 分层架构（L1→L5）| SAGE Layered Architecture

```text
L1  sage-common
 ↓
L2  sage-platform   sageFlownet
 ↓
L3  sage-kernel     sage-libs
 ↓
L4  sage-middleware
 ↓
L5  sage-cli        sage-dev-tools   sage-studio
```

#### L1 — 基础层 | Foundation

#### ⚙️ [sage-common](https://github.com/intellistream/sage-common)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-common?style=flat&logo=github)](https://github.com/intellistream/sage-common/stargazers)
[![PyPI](https://img.shields.io/pypi/v/isage-common.svg)](https://pypi.org/project/isage-common/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)

提供配置、日志、协议、通用组件等底座能力，是整个 SAGE 生态的依赖起点。

*Provides foundational config, logging, protocol, and shared components used by all upper layers.*

#### L2 — 平台层 | Platform

<table>
<tr>
<td width="50%">

#### ⚙️ [sage-platform](https://github.com/intellistream/sage-platform)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-platform?style=flat&logo=github)](https://github.com/intellistream/sage-platform/stargazers)
[![PyPI](https://img.shields.io/pypi/v/isage-platform.svg)](https://pypi.org/project/isage-platform/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)

队列、存储、服务抽象与运行基础设施接口层。

*Queue/storage/service abstractions as platform interfaces for runtime infrastructure.*

</td>
<td width="50%">

#### 🔗 [sageFlownet](https://github.com/intellistream/sageFlownet)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageFlownet?style=flat&logo=github)](https://github.com/intellistream/sageFlownet/stargazers)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)

分布式通信与执行底座，作为上层运行时的重要平台能力。

*Distributed communication/runtime substrate serving as a platform capability for upper layers.*

</td>
</tr>
</table>

#### L3 — 运行时与算法层 | Runtime & Algorithm

<table>
<tr>
<td width="50%">

#### ⚙️ [sage-kernel](https://github.com/intellistream/sage-kernel)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-kernel?style=flat&logo=github)](https://github.com/intellistream/sage-kernel/stargazers)
[![PyPI](https://img.shields.io/pypi/v/isage-kernel.svg)](https://pypi.org/project/isage-kernel/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)

流式运行时、调度器、Flow DSL、容错与 RPC。

*Streaming runtime, scheduler, Flow DSL, fault tolerance, and RPC.*

</td>
<td width="50%">

#### ⚙️ [sage-libs](https://github.com/intellistream/sage-libs)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-libs?style=flat&logo=github)](https://github.com/intellistream/sage-libs/stargazers)
[![PyPI](https://img.shields.io/pypi/v/isage-libs.svg)](https://pypi.org/project/isage-libs/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)

算法接口与实现集合（Agentic / RAG / Eval / Intent）。

*Algorithm interfaces and implementations (Agentic / RAG / Eval / Intent).* 

</td>
</tr>
</table>

##### L3 子仓库（按功能）| L3 Satellite Repos (By Function)

- **Agentic / ToolUse**: 
  - [sage-agentic](https://github.com/intellistream/sage-agentic) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-agentic?style=flat&logo=github)](https://github.com/intellistream/sage-agentic/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-agentic.svg)](https://pypi.org/project/isage-agentic/), 
  - [sage-agentic-tooluse](https://github.com/intellistream/sage-agentic-tooluse) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-agentic-tooluse?style=flat&logo=github)](https://github.com/intellistream/sage-agentic-tooluse/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-agentic.svg)](https://pypi.org/project/isage-agentic-tooluse/), 
  - [sage-agentic-tooluse-sias](https://github.com/intellistream/sage-agentic-tooluse-sias) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-agentic-tooluse-sias?style=flat&logo=github)](https://github.com/intellistream/sage-agentic-tooluse-sias/stargazers)[![PyPI](https://img.shields.io/pypi/v/isage-agentic.svg)](https://pypi.org/project/isage-agentic-tooluse-sias/), 

- **RAG / Refiner / Data**: 
  - [sage-rag](https://github.com/intellistream/sage-rag) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-rag?style=flat&logo=github)](https://github.com/intellistream/sage-rag/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-rag.svg)](https://pypi.org/project/isage-rag/), 
  - [sageRefiner](https://github.com/intellistream/sageRefiner) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageRefiner?style=flat&logo=github)](https://github.com/intellistream/sageRefiner/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-refiner.svg)](https://pypi.org/project/isage-refiner/), 
  - [sageData](https://github.com/intellistream/sageData) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageData?style=flat&logo=github)](https://github.com/intellistream/sageData/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-data.svg)](https://pypi.org/project/isage-data/)
- **Eval / Intent / Safety**: 
  - [sage-eval](https://github.com/intellistream/sage-eval) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-eval?style=flat&logo=github)](https://github.com/intellistream/sage-eval/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-eval.svg)](https://pypi.org/project/isage-eval/), 
  - [sage-intent](https://github.com/intellistream/sage-intent) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-intent?style=flat&logo=github)](https://github.com/intellistream/sage-intent/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-intent.svg)](https://pypi.org/project/isage-intent/), 
  - [sage-safety](https://github.com/intellistream/sage-safety) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-safety?style=flat&logo=github)](https://github.com/intellistream/sage-safety/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-safety.svg)](https://pypi.org/project/isage-safety/), 
  - [sage-privacy](https://github.com/intellistream/sage-privacy) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-privacy?style=flat&logo=github)](https://github.com/intellistream/sage-privacy/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-privacy.svg)](https://pypi.org/project/isage-privacy/)

#### L4 — 中间件层 | Middleware

#### ⚙️ [sage-middleware](https://github.com/intellistream/sage-middleware)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-middleware?style=flat&logo=github)](https://github.com/intellistream/sage-middleware/stargazers)
[![PyPI](https://img.shields.io/pypi/v/isage-middleware.svg)](https://pypi.org/project/isage-middleware/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)

运行时服务组件层：向量数据库、记忆后端、联网算子等。

*Runtime-bound service layer: vector DB, memory backends, and networked operators.*

##### L4 子仓库（按功能）| L4 Satellite Repos (By Function)

- **Vector DB / ANNS**: 
  - [sageVDB](https://github.com/intellistream/sageVDB) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageVDB?style=flat&logo=github)](https://github.com/intellistream/sageVDB/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-vdb.svg)](https://pypi.org/project/isage-vdb/) [![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/), 
  - [sage-anns](https://github.com/intellistream/sage-anns) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-anns?style=flat&logo=github)](https://github.com/intellistream/sage-anns/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-anns.svg)](https://pypi.org/project/isage-anns/), 
  - [CANDOR-Bench](https://github.com/intellistream/CANDOR-Bench) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/CANDOR-Bench?style=flat&logo=github)](https://github.com/intellistream/CANDOR-Bench/stargazers)
- **Stream / TSDB / Memory**:
  - [sageFlow](https://github.com/intellistream/sageFlow) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageFlow?style=flat&logo=github)](https://github.com/intellistream/sageFlow/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-flow.svg)](https://pypi.org/project/isage-flow/), 
  - [sageTSDB](https://github.com/intellistream/sageTSDB) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageTSDB?style=flat&logo=github)](https://github.com/intellistream/sageTSDB/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-tsdb.svg)](https://pypi.org/project/isage-tsdb/), 
  - [neuromem](https://github.com/intellistream/neuromem) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/neuromem?style=flat&logo=github)](https://github.com/intellistream/neuromem/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-neuromem.svg)](https://pypi.org/project/isage-neuromem/)

#### L5 — 应用与工具层 | Applications & Tooling

<table>
<tr>
<td width="50%">

#### ⚙️ [sage-cli](https://github.com/intellistream/sage-cli)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-cli?style=flat&logo=github)](https://github.com/intellistream/sage-cli/stargazers)
[![PyPI](https://img.shields.io/pypi/v/isage-cli.svg)](https://pypi.org/project/isage-cli/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)

统一命令行入口，连接平台能力与应用场景。

*Unified CLI entrypoint connecting platform capabilities and app scenarios.*

</td>
<td width="50%">

#### 🔧 [sage-dev-tools](https://github.com/intellistream/sage-dev-tools)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-dev-tools?style=flat&logo=github)](https://github.com/intellistream/sage-dev-tools/stargazers)
[![PyPI](https://img.shields.io/pypi/v/isage-dev-tools.svg)](https://pypi.org/project/isage-dev-tools/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)

SAGE 开发工具链（质量检查、测试、维护、报告）。

*SAGE developer tooling for quality, testing, maintenance, and reports.*

</td>
</tr>
</table>

##### L5 子仓库（按功能）| L5 Satellite Repos (By Function)

- **应用体验与入口**: 
  - [sage-studio](https://github.com/intellistream/sage-studio) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-studio?style=flat&logo=github)](https://github.com/intellistream/sage-studio/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-studio.svg)](https://pypi.org/project/isage-studio/), 
  -  [sage-edge](https://github.com/intellistream/sage-edge) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-edge?style=flat&logo=github)](https://github.com/intellistream/sage-edge/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-edge.svg)](https://pypi.org/project/isage-edge/)
- **开发与发布工具**: 
  - [sage-pypi-publisher](https://github.com/intellistream/sage-pypi-publisher) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-pypi-publisher?style=flat&logo=github)](https://github.com/intellistream/sage-pypi-publisher/stargazers) [![PyPI](https://img.shields.io/pypi/v/isage-pypi-publisher.svg)](https://pypi.org/project/isage-pypi-publisher/), 
  - [sage-github-manager](https://github.com/intellistream/sage-github-manager) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-github-manager?style=flat&logo=github)](https://github.com/intellistream/sage-github-manager/stargazers), 
  - [sage-team-info](https://github.com/intellistream/sage-team-info) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-team-info?style=flat&logo=github)](https://github.com/intellistream/sage-team-info/stargazers)
- **文档与学习资源**: 
  - [sage-docs](https://github.com/intellistream/sage-docs) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-docs?style=flat&logo=github)](https://github.com/intellistream/sage-docs/stargazers), 
  - [sage-examples](https://github.com/intellistream/sage-examples) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-examples?style=flat&logo=github)](https://github.com/intellistream/sage-examples/stargazers), 
  - [sage-tutorials](https://github.com/intellistream/sage-tutorials) [![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-tutorials?style=flat&logo=github)](https://github.com/intellistream/sage-tutorials/stargazers)

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
