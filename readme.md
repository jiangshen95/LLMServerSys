## 项目描述

本项目主要关注大模型推理并行策略的优化和实现，同时希望集成现有的大模型推理优化技术构建高效的推理系统。

本项目关注的并行推理策略主要分为两部分：

- 异构硬件环境下最优的流水线并行划分。
- 探索利用（零冗余）数据并行提升系统吞吐量的可能性。

本项目关注的其他推理优化策略：

- Batching 技术
- 投机解码
- KV 缓存的管理和压缩
- 底层的计算和通信优化

## 工作计划

- :O: 深入研究和理解现有大模型推理框架，如 FasterTransformer、vLLM 和 HuggingFace TGI 等，确定系统开发基础。
- :O: 实际部署现有推理系统，进行性能测试。
- :O: 开发或寻找一系列大模型推理系统的性能探索工具。
- :O: 在已有系统基础上，修改并行推理引擎部分，集成不同并行推理策略，并可以方便切换。
- :O: 细化大模型推理并行方案设计，以及系统设计。
- :O: 分别开发流水线并行部分策略和数据并行部分策略。
- :O: 集成其他推理优化策略。
- :O: 框架/系统重构优化。