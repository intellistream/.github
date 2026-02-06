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
[![PyPI](https://img.shields.io/pypi/v/isage.svg)](https://pypi.org/project/isage/)

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

#### � [sage-benchmark](https://github.com/intellistream/sage-benchmark)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-benchmark.svg)](https://pypi.org/project/isage-benchmark/)

**SAGE 系统基准测试 | SAGE System Benchmarks**

SAGE 框架的端到端基准测试套件，评估系统整体性能。

*End-to-end benchmark suite for SAGE framework evaluating system-level performance.*

**测试维度 | Test Dimensions:**
- 🔄 控制面调度 | Control Plane Scheduling  
- 🧪 端到端流水线 | E2E Pipeline
- 📈 隔离性与扩展性 | Isolation & Scalability

</td>
</tr>
<tr>
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
<td width="50%">
</td>
</tr>
</table>

### 🔧 数据库与系统组件 | Database & System Components

#### 💾 向量数据库 & ANNS | Vector Database & ANNS

<table>
<tr>
<td width="50%">

#### 🔍 [sageVDB](https://github.com/intellistream/sageVDB)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)
[![PyPI](https://img.shields.io/pypi/v/isage-vdb.svg)](https://pypi.org/project/isage-vdb/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageVDB?style=flat&logo=github)](https://github.com/intellistream/sageVDB/stargazers)

**向量数据库核心 | Vector Database Core**

高性能向量数据库 C++ 核心库，支持可插拔 ANNS 架构和多模态特性。

*High-performance C++20 vector database library with pluggable ANNS architecture and multimodal support.*

</td>
<td width="50%">

#### 🔍 [sage-anns](https://github.com/intellistream/sage-anns)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-anns.svg)](https://pypi.org/project/isage-anns/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-anns?style=flat&logo=github)](https://github.com/intellistream/sage-anns/stargazers)

**ANNS 算法库 | ANNS Algorithm Library**

提供统一 Python 接口的近似最近邻搜索算法集合，被 sageVDB 调用。

*ANNS algorithms with unified Python interface, used by sageVDB.*

</td>
</tr>
<tr>
<td width="50%">

#### 📊 [CANDOR-Bench](https://github.com/intellistream/CANDOR-Bench)
[![C++](https://img.shields.io/badge/C%2B%2B-latest-blue.svg)](https://isocpp.org/)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)

**ANNS 基准测试 | ANNS Benchmark [SIGMOD'26]**

全面的 ANNS 算法基准测试套件，评估 sage-anns 和 sageVDB 性能。

*Comprehensive ANNS benchmark suite evaluating sage-anns and sageVDB performance.*

</td>
<td width="50%">
</td>
</tr>
</table>

#### 🌊 流处理引擎 | Stream Processing

<table>
<tr>
<td width="50%">

#### [sageFlow](https://github.com/intellistream/sageFlow)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)
[![PyPI](https://img.shields.io/pypi/v/isage-flow.svg)](https://pypi.org/project/isage-flow/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sageFlow?style=flat&logo=github)](https://github.com/intellistream/sageFlow/stargazers)

**向量流处理引擎 | Vector Stream Processing Engine**

向量原生流处理引擎，专为实时 LLM 生成任务维护和物化语义状态快照而设计。

*Vector-native stream processing engine for real-time LLM generation tasks.*

</td>
<td width="50%">
</td>
</tr>
</table>

#### 🔗 分布式运行时 | Distributed Runtime

<table>
<tr>
<td width="50%">

#### [sageFlownet](https://github.com/intellistream/sageFlownet)
[![C++](https://img.shields.io/badge/C%2B%2B-blue.svg)](https://isocpp.org/)

**分布式通信框架 | Distributed Communication Framework**

类似 Ray 的分布式运行时基础组件，提供高性能通信堆栈。

*Ray-like distributed runtime infrastructure providing high-performance communication stack.*

</td>
<td width="50%">
</td>
</tr>
</table>

#### ⏱️ 时序数据库 | Time Series Database

<table>
<tr>
<td width="50%">

#### [sageTSDB](https://github.com/intellistream/sageTSDB)
[![C++](https://img.shields.io/badge/C%2B%2B-latest-blue.svg)](https://isocpp.org/)
[![PyPI](https://img.shields.io/pypi/v/isage-tsdb.svg)](https://pypi.org/project/isage-tsdb/)

**时序数据库 | Time Series Database**

SAGE 生态系统的时序数据库组件，用于处理时间序列数据。

*Time series database component for handling temporal data streams.*

</td>
<td width="50%">
</td>
</tr>
</table>

#### 📊 数据集 | Datasets

<table>
<tr>
<td width="50%">

#### [sageData](https://github.com/intellistream/sageData)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-data.svg)](https://pypi.org/project/isage-data/)

**基准数据集 | Benchmark Datasets**

SAGE 基准测试的共享数据集和资源库。

*Shared test datasets and resources for SAGE benchmarks.*

</td>
<td width="50%">
</td>
</tr>
</table>

#### 🤏 上下文压缩 | Context Compression

<table>
<tr>
<td width="50%">

#### [sageRefiner](https://github.com/intellistream/sageRefiner)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-refiner.svg)](https://pypi.org/project/isage-refiner/)

**上下文压缩 | Context Compression**

SAGE 生态系统的上下文压缩组件，用于优化 RAG 应用的输入长度。

*Context compression component for optimizing input length in RAG applications.*

</td>
<td width="50%">

#### 📊 [sage-refiner-benchmark](https://github.com/intellistream/sage-refiner-benchmark)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-refiner-benchmark.svg)](https://pypi.org/project/isage-refiner-benchmark/)

**Refiner 基准测试 | Refiner Benchmarks**

评估各种上下文压缩算法在 RAG 应用中的性能。

*Benchmark suite for context compression algorithms in RAG applications.*

</td>
</tr>
</table>

### 🤖 AI 与智能体组件 | AI & Agent Components

#### 🧠 LLM 推理引擎 | LLM Inference Engine

<table>
<tr>
<td width="50%">

#### [sageLLM](https://github.com/intellistream/sagellm)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isagellm.svg)](https://pypi.org/project/isagellm/)
[![Website](https://img.shields.io/badge/Website-sagellm-blue?style=flat&logo=github)](https://intellistream.github.io/sagellm-website/)

**LLM 推理引擎 | LLM Inference Engine**

面向华为昇腾与 NVIDIA 的模块化 LLM 推理引擎，默认 CPU 优先，提供统一的 Python/HTTP 接口。
*(See dedicated section below for sub-modules)*

*Modular LLM inference engine for domestic computing power, CPU-first with unified APIs.*

</td>
<td width="50%">

#### 📊 [sagellm-benchmark](https://github.com/intellistream/sagellm-benchmark)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isagellm-benchmark.svg)](https://pypi.org/project/isagellm-benchmark/)

**E2E 验证 | E2E Validation**

sageLLM 推理引擎的端到端验证套件，年度验证与演示运行器。

*End-to-end validation suite for sageLLM with yearly validations.*

</td>
</tr>
<tr>
<td width="50%">

#### 📊 [sagellm-control-plane-benchmark](https://github.com/intellistream/sagellm-control-plane-benchmark)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isagellm-control-plane-benchmark.svg)](https://pypi.org/project/isagellm-control-plane-benchmark/)

**Control Plane 评测 | Control Plane Benchmark**

专门评测 sageLLM Control Plane 模块的调度策略、吞吐量、延迟等性能指标。

*Dedicated benchmark for sageLLM Control Plane module.*

</td>
<td width="50%">
</td>
</tr>
</table>

#### 🕵️ 智能体 | Agents

<table>
<tr>
<td width="50%">

#### [sage-agentic](https://github.com/intellistream/sage-agentic)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-agentic.svg)](https://pypi.org/project/isage-agentic/)

**智能体框架 | Agentic Framework**

智能体工具选择、规划、工作流与多智能体协作框架。

*Tool selection, planning, workflows, and agent coordination framework.*

</td>
<td width="50%">

#### 📊 [sage-agent-benchmark](https://github.com/intellistream/sage-agent-benchmark)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-agent-benchmark.svg)](https://pypi.org/project/isage-agent-benchmark/)

**智能体评测 | Agent Benchmark**

配置驱动的智能体能力评估框架（工具选择、规划、时序检测）。

*Configuration-driven agent evaluation framework.*

</td>
</tr>
</table>

#### 🧩 记忆体 | Memory Systems

<table>
<tr>
<td width="50%">

#### [neuromem](https://github.com/intellistream/neuromem)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-neuromem.svg)](https://pypi.org/project/isage-neuromem/)

**记忆管理引擎 | Memory Management Engine**

SAGE 项目的记忆体组件，RAG 应用的独立内存管理引擎。

*Standalone memory management engine for RAG applications.*

</td>
<td width="50%">

#### 📊 [sage-memory-benchmark](https://github.com/intellistream/sage-memory-benchmark)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-memory-benchmark.svg)](https://pypi.org/project/isage-memory-benchmark/)

**记忆系统评测 | Memory System Benchmark**

NeuroMem 记忆系统性能评估。

*Performance evaluation for NeuroMem memory systems.*

</td>
</tr>
</table>

#### 📚 RAG 框架 | RAG Framework

<table>
<tr>
<td width="50%">

#### [sage-rag](https://github.com/intellistream/sage-rag)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-rag.svg)](https://pypi.org/project/isage-rag/)

**RAG 框架 | RAG Framework**

RAG 流水线的文档加载、分块与检索框架。

*Document loaders, chunkers, and retrievers for RAG pipelines.*

</td>
<td width="50%">

#### 📊 [sage-rag-benchmark](https://github.com/intellistream/sage-rag-benchmark)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-rag-benchmark.svg)](https://pypi.org/project/isage-rag-benchmark/)

**RAG 评测 | RAG Benchmark**

RAG 流水线端到端性能评估框架。

*End-to-end performance evaluation for RAG pipelines.*

</td>
</tr>
</table>

#### 🛠️ 其他工具 | Other AI Tools

<table>
<tr>
<td width="50%">

#### 🎯 [sage-intent](https://github.com/intellistream/sage-intent)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-intent.svg)](https://pypi.org/project/isage-intent/)

**意图识别 | Intent Recognition**

基于关键词和大模型的对话 AI 意图分类工具。

*Keyword and LLM-based intent classification for conversational AI.*

</td>
<td width="50%">

#### 🔧 [sage-finetune](https://github.com/intellistream/sage-finetune)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-finetune.svg)](https://pypi.org/project/isage-finetune/)

**轻量微调工具 | Lightweight Fine-tuning**

SAGE 生态系统的 LLM 轻量级微调工具箱。

*Lightweight LLM fine-tuning toolkit for SAGE ecosystem.*

</td>
</tr>
<tr>
<td width="50%">

#### 🔒 [sage-safety](https://github.com/intellistream/sage-safety)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-safety.svg)](https://pypi.org/project/isage-safety/)

**安全框架 | Safety Framework**

AI 系统的安全护栏与检测器。

*Safety guardrails and detectors for AI systems.*

</td>
<td width="50%">

#### 🔒 [sage-privacy](https://github.com/intellistream/sage-privacy)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-privacy.svg)](https://pypi.org/project/isage-privacy/)

**隐私保护 | Privacy Protection**

机器学习遗忘与差分隐私工具。

*Machine unlearning and differential privacy tools.*

</td>
</tr>
<tr>
<td width="50%">

#### 📖 [sage-examples](https://github.com/intellistream/sage-examples)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)

**示例代码库 | Examples Repository**

SAGE 框架的示例代码和使用案例集合。

*Collection of example code and use cases for SAGE framework.*

</td>
<td width="50%">

#### 🧪 [sage-eval](https://github.com/intellistream/sage-eval)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-eval.svg)](https://pypi.org/project/isage-eval/)

**评估工具库 | Evaluation Toolkit**

L3 纯算法库，提供评估指标（F1/ROUGE/BLEU）、性能分析器与 LLM 评审工具。

*L3 algorithm library providing metrics, profilers, and LLM judges.*

</td>
</tr>
</table>
### 🧮 算法库 | Algorithm Libraries

<table>
<tr>
<td width="50%">

#### ⚡ [Concurrent-HNSW](https://github.com/intellistream/Concurrent-HNSW)
[![C++](https://img.shields.io/badge/C%2B%2B-latest-blue.svg)](https://isocpp.org/)

**并发 HNSW 库 | Concurrent HNSW Library**

支持并发操作的 HNSW 实现，提供快速并发的近似最近邻搜索。

*Header-only C++/Python library for fast and concurrent approximate nearest neighbor search.*

**状态 | Status:** 🚧 开发中 | In Development

</td>
<td width="50%">

#### 🔍 [sage-anns](https://github.com/intellistream/sage-anns)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-anns?style=flat&logo=github)](https://github.com/intellistream/sage-anns/stargazers)

**近似最近邻搜索算法库 | ANNS Algorithm Library**

提供统一 Python 接口的近似最近邻搜索算法集合，支持多种 ANNS 算法。

*SAGE ANNS: Approximate Nearest Neighbor Search algorithms with unified Python interface.*

</td>
</tr>
<tr>
<td width="50%">

#### ✖️ [sage-amms](https://github.com/intellistream/sage-amms)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)

**近似矩阵乘法算法 | AMM Algorithms**

近似矩阵乘法算法的 C++ 实现集合。

*Approximate Matrix Multiplication algorithms with C++ implementations.*

</td>
<td width="50%">

#### 📊 [LibAMM](https://github.com/intellistream/LibAMM)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg)](https://isocpp.org/)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/LibAMM?style=flat&logo=github)](https://github.com/intellistream/LibAMM/stargazers)

**AMM 基准测试 | AMM Benchmark Library [NIPS'24]**

聚合主流 AMM 算法的高性能基准测试库，支持标准化评估和高效实验管理。

*High-performance benchmark library for AMM algorithms with CUDA acceleration and PAPI profiling.*

</td>
</tr>
<tr>
<td width="50%">

#### 🎯 [sage-agentic-sias](https://github.com/intellistream/sage-agentic-sias)

**SIAS 算法实现 | SIAS Algorithm (sage-agentic submodule)**

sage-agentic 的子仓库，实现样本重要性感知选择算法用于持续学习和核心集。

*Submodule of sage-agentic implementing Sample-Importance-Aware Selection for continual learning and coreset algorithms.*

</td>
<td width="50%">
</td>
</tr>
</table>

### 🧠 sageLLM 模块架构 | sageLLM Modular Architecture

*The modular ecosystem behind the **sageLLM** inference engine.*

<table>
<tr>
<td width="50%">

#### 🔒 [sagellm-protocol](https://github.com/intellistream/sagellm-protocol)

**基础协议 | Protocol & Foundations**

定义推理引擎的 Schema、Error Codes 和基础类型 (Task0.1)。

*Protocol definitions and types for sageLLM inference engine.*

</td>
<td width="50%">

#### 🔒 [sagellm-core](https://github.com/intellistream/sagellm-core)

**引擎核心 | Engine Core**

推理引擎的核心运行时与执行逻辑 (Task0)。

*Core engine and runtime for sageLLM inference.*

</td>
</tr>
<tr>
<td width="50%">

#### 🔒 [sagellm-backend](https://github.com/intellistream/sagellm-backend)

**计算后端 | Compute Backend**

面向国产硬件（华为昇腾 / CPU）的计算抽象层 (Task0)。

*Backend provider abstraction for domestic hardware.*

</td>
<td width="50%">

#### 🔒 [sagellm-comm](https://github.com/intellistream/sagellm-comm)

**通信层 | Communication Layer**

分布式推理的通信硬件抽象层与拓扑管理 (Task1)。

*Communication layer for distributed inference.*

</td>
</tr>
<tr>
<td width="50%">

#### 🔒 [sagellm-kv-cache](https://github.com/intellistream/sagellm-kv-cache)

**KV 缓存 | KV Cache Management**

KV 缓存池、前缀缓存与驱逐策略管理 (Task2)。

*KV cache management with prefix caching and eviction.*

</td>
<td width="50%">

#### 🔒 [sagellm-control-plane](https://github.com/intellistream/sagellm-control-plane)

**控制面 | Control Plane**

请求路由、调度器 IR 与生命周期管理。

*Request routing, scheduling, and lifecycle management.*

</td>
</tr>
<tr>
<td width="50%">

#### 🔒 [sagellm-gateway](https://github.com/intellistream/sagellm-gateway)

**API 网关 | API Gateway**

OpenAI 兼容的 REST API 网关。

*OpenAI-compatible REST API gateway.*

</td>
<td width="50%">

#### 🔒 [sagellm-compression](https://github.com/intellistream/sagellm-compression)

**模型压缩 | Model Compression**

量化、稀疏化与投机解码加速技术 (Task3)。

*Model compression and acceleration techniques.*

</td>
<td width="50%">

#### 🔒 [sagellm-docs](https://github.com/intellistream/sagellm-docs)

**文档 | Documentation**

内部任务书、规范与研究文档。

*Internal task books, specifications, and research docs.*

</td>
</tr>
</table>

### �️ 工具与基础设施 | Tools & Infrastructure

<table>
<tr>
<td width="50%">

#### 📦 [sage-pypi-publisher](https://github.com/intellistream/sage-pypi-publisher)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/isage-pypi-publisher.svg)](https://pypi.org/project/isage-pypi-publisher/)

**PyPI 发布工具 | PyPI Publisher Toolkit**

Python monorepos 的字节码编译与 PyPI 发布工具。

*Bytecode compiler and PyPI publisher toolkit for Python monorepos.*

</td>
<td width="50%">

#### 🌐 [sage-edge](https://github.com/intellistream/sage-edge)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-edge?style=flat&logo=github)](https://github.com/intellistream/sage-edge/stargazers)
[![PyPI](https://img.shields.io/pypi/v/isage-edge.svg)](https://pypi.org/project/isage-edge/)

**SAGE 网关聚合器 | SAGE Gateway Aggregator**

轻量级 FastAPI 网关聚合器，为 SAGE 提供统一的 API 入口。

*Lightweight FastAPI aggregator for SAGE Gateway.*

</td>
</tr>
<tr>
<td width="50%">

#### 🐙 [sage-github-manager](https://github.com/intellistream/sage-github-manager)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![GitHub Stars](https://img.shields.io/github/stars/intellistream/sage-github-manager?style=flat&logo=github)](https://github.com/intellistream/sage-github-manager/stargazers)

**GitHub 问题管理工具 | GitHub Issues Manager**

SAGE 项目的 GitHub Issues 管理工具，具有 AI 增强功能。

*A comprehensive GitHub Issues management tool for SAGE project with AI-powered features.*

</td>
<td width="50%">

#### 🎨 [sage-studio](https://github.com/intellistream/sage-studio)
[![PyPI](https://img.shields.io/pypi/v/isage-studio.svg)](https://pypi.org/project/isage-studio/)

**可视化工作流 | Visual Workflow**

SAGE AI 流水线的可视化构建器与 LLM Playground。

*Visual workflow builder and LLM playground for SAGE AI pipelines.*

</td>
</tr>
<tr>
<td width="50%">

#### 🔒 [sage-team-info](https://github.com/intellistream/sage-team-info)

**团队信息 | Team Info**

SAGE 项目人员分配和敏感信息。

*Internal team allocation and sensitive information.*

</td>
<td width="50%">
</td>
</tr>
</table>

### �🗄️ 历史仓库 | Historical Repositories

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
# 开发安装 | Development installation (recommended)
git clone https://github.com/intellistream/SAGE.git
cd SAGE
./quickstart.sh --dev --yes

# PyPI 安装核心包 | Install core packages from PyPI
pip install isage-common isage-libs isage-kernel

# 完整功能安装 | Full feature installation
pip install isage-common isage-platform isage-kernel isage-libs isage-middleware
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
