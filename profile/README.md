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

### 📦 核心仓库 | Core Repositories

<table>
<tr>
<td width="50%">

#### 🎯 [SAGE](https://github.com/intellistream/SAGE)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/SAGE?style=flat&logo=github)](https://github.com/intellistream/SAGE/stargazers)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)

**主框架 | Main Framework**

声明式、可组合的流式增强生成执行框架，用于通过数据流抽象构建透明的 LLM 驱动系统。

*A declarative, composable framework for building transparent LLM-powered systems through dataflow abstractions.*

**特性 | Features:**
- ⚡ 生产就绪的企业级应用
- 🔧 直观的声明式 API
- 🚀 高吞吐量流式工作负载优化
- 👁️ 内置可观测性和调试工具

</td>
<td width="50%">

#### 📚 [SAGE-Pub](https://github.com/intellistream/SAGE-Pub)
[![Documentation](https://img.shields.io/badge/docs-online-brightgreen)](https://intellistream.github.io/SAGE-Pub/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/SAGE-Pub?style=flat&logo=github)](https://github.com/intellistream/SAGE-Pub/stargazers)

**文档中心 | Documentation Hub**

SAGE 系统的官方对外文档仓库，包含快速开始、架构图、API 文档等。

*Official public documentation repository for the SAGE system, including quick start guides, architecture diagrams, and API documentation.*

**内容 | Contents:**
- 📘 快速开始指南
- 🏗️ 架构与核心模块说明
- 📊 Dashboard 使用指南
- 🔗 API 文档

</td>
</tr>
</table>

### 🔧 数据库组件 | Database Components

<table>
<tr>
<td width="50%">

#### 💾 [sageDB](https://github.com/intellistream/sageDB)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageDB?style=flat&logo=github)](https://github.com/intellistream/sageDB/stargazers)

**向量数据库核心 | Vector Database Core**

高性能向量数据库 C++ 核心库，支持可插拔 ANNS 架构和多模态特性。

*High-performance C++20 vector database library with pluggable ANNS architecture and multimodal support.*

**核心能力 | Core Capabilities:**
- 🔍 精确与近似搜索
- 📏 多种距离度量 (L2, Inner Product, Cosine)
- 🏷️ 元数据管理与过滤
- 🔌 可插拔 ANNS 算法
- 🎨 多模态融合支持

</td>
<td width="50%">

#### 🌊 [sageFlow](https://github.com/intellistream/sageFlow)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageFlow?style=flat&logo=github)](https://github.com/intellistream/sageFlow/stargazers)

**向量流处理引擎 | Vector Stream Processing Engine**

向量原生流处理引擎，专为实时 LLM 生成任务维护和物化语义状态快照而设计。

*Vector-native stream processing engine designed to maintain and materialize semantic state snapshots for real-time LLM generation tasks.*

**特性 | Features:**
- 🎯 向量原生处理
- 📝 声明式 API
- ⚡ 增量低延迟更新
- 🪟 有状态窗口操作

</td>
</tr>
<tr>
<td width="50%">

#### ⏱️ [sageTSDB](https://github.com/intellistream/sageTSDB)
[![C++](https://img.shields.io/badge/C%2B%2B-latest-blue.svg)](https://isocpp.org/)

**时序数据库 | Time Series Database**

SAGE 生态系统的时序数据库组件，用于处理时间序列数据。

*Time series database component of the SAGE ecosystem for handling temporal data streams.*

</td>
<td width="50%">

#### 🧪 [SAGE-DB-Bench](https://github.com/intellistream/SAGE-DB-Bench)
[![C++](https://img.shields.io/badge/C%2B%2B-latest-blue.svg)](https://isocpp.org/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/SAGE-DB-Bench?style=flat&logo=github)](https://github.com/intellistream/SAGE-DB-Bench/stargazers)

**数据库基准测试 | Database Benchmark**

SAGE 数据库组件的性能基准测试套件。

*Performance benchmark suite for SAGE database components.*

</td>
</tr>
</table>

### 🤖 AI 组件 | AI Components

<table>
<tr>
<td width="50%">

#### 🧠 [sageLLM](https://github.com/intellistream/sageLLM)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)

**LLM 集成模块 | LLM Integration Module**

SAGE 生态系统的大语言模型集成组件，提供统一的 LLM 接口。

*Large Language Model integration component for the SAGE ecosystem, providing unified LLM interfaces.*

</td>
<td width="50%">

#### 📖 [sage-examples](https://github.com/intellistream/sage-examples)

**示例代码库 | Examples Repository**

SAGE 框架的示例代码和使用案例集合。

*Collection of example code and use cases for the SAGE framework.*

</td>
</tr>
<tr>
<td width="50%">

#### 🧩 [neuromem](https://github.com/intellistream/neuromem)

**记忆管理引擎 | Memory Management Engine**

SAGE 项目的记忆体组件，RAG 应用的独立内存管理引擎。

*Memory component of the SAGE project, a standalone memory management engine for RAG applications.*

</td>
<td width="50%">

#### 📊 [sageData](https://github.com/intellistream/sageData)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)

**基准数据集 | Benchmark Datasets**

SAGE 基准测试的共享数据集和资源库。

*Shared test datasets and resources for SAGE benchmarks.*

</td>
</tr>
</table>

### 🧮 算法库 | Algorithm Libraries

<table>
<tr>
<td width="50%">

#### 🔢 [LibAMM](https://github.com/intellistream/LibAMM)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/LibAMM?style=flat&logo=github)](https://github.com/intellistream/LibAMM/stargazers)

**近似矩阵乘法库 | Approximate Matrix Multiplication Library**

聚合了主流 AMM 算法的高性能库，支持标准化评估和高效实验管理，兼容 LibTorch (C++)。

*Aggregates prevalent AMM algorithms for standardized evaluations and efficient experiment management, compatible with LibTorch (C++).*

**特性 | Features:**
- 🚀 高性能 C++ 实现
- 🐍 Python 绑定 (PyAMM)
- 🔥 可选 CUDA 加速支持
- 📊 PAPI 性能分析工具

</td>
<td width="50%">

#### ⚡ [Concurrent-HNSW](https://github.com/intellistream/Concurrent-HNSW)
[![C++](https://img.shields.io/badge/C%2B%2B-latest-blue.svg)](https://isocpp.org/)

**并发 HNSW 库 | Concurrent HNSW Library**

支持并发操作的 HNSW 实现，提供快速并发的近似最近邻搜索。

*Header-only C++/Python library for fast and concurrent approximate nearest neighbor search.*

**状态 | Status:** 🚧 开发中 | In Development

</td>
<td width="50%">

### 🗄️ 历史仓库 | Historical Repositories

- **[sage-db_outdated](https://github.com/intellistream/sage-db_outdated)** - SAGE 数据库的早期版本（已过时）| Early version of SAGE database (outdated)

---

## 🚀 其他研究项目 | Other Research Projects

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
# 标准安装 | Standard installation (recommended)
pip install isage[standard]

# 核心安装 | Core installation only
pip install isage[core]
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

详细文档请访问：[SAGE Documentation](https://intellistream.github.io/SAGE-Pub/)

*For detailed documentation, visit: [SAGE Documentation](https://intellistream.github.io/SAGE-Pub/)*

---

## 🤝 参与贡献 | Contributing

我们欢迎各种形式的贡献！请查看各个仓库的 CONTRIBUTING.md 文件了解详情。

*We welcome contributions of all kinds! Please check the CONTRIBUTING.md file in each repository for details.*

---

## 📞 联系我们 | Contact Us

- 💬 **WeChat/微信群**: [加入微信群](https://github.com/intellistream/SAGE/blob/main/docs/COMMUNITY.md)
- 💬 **QQ群**: [IntelliStream课题组讨论QQ群](https://qm.qq.com/q/bcnuyQVcvm)
- 💬 **Slack**: [Join our Slack](https://join.slack.com/t/intellistream/shared_invite/zt-2qayp8bs7-v4F71ge0RkO_rn34hBDWQg)
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
