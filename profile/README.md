# Holtwood Forks

上游源码研读室。这里没有原创项目；除组织配置仓 `.github` 外，所有仓库都是 fork。

维护者：[holtwood](https://github.com/holtwood)

## 这里放什么

读大型代码库时，光看不够：需要加注释、改一行看行为、跑最小复现。这些改动放在原创仓库里会和上游历史分叉，所以统一放在这里；改坏了直接重 fork。

Fork 保留完整提交历史，随时可以和 upstream 对比。这里的 fork 不构成原创贡献，也不进入作品集计数。

**注意**：其中若干仓库带本地补丁分支（例如 `vllm`、`sglang`、`mini-sglang`、`Termius-Pro-zh_CN` 都领先上游若干提交）。补丁的存在不改变"不算原创、不计入作品集"的结论；补丁的晋升条件见下。

## 我的原创工作在哪里

- [holtwood-systems](https://github.com/holtwood-systems)：AI Infra / HPC 系统实现与性能证据
- [holtwood-arena](https://github.com/holtwood-arena)：比赛、benchmark 与赛后复盘
- [holtwood-projects](https://github.com/holtwood-projects)：早期应用与工具项目（归档维护）
- [open-genomics](https://github.com/open-genomics)：生信旧主线（归档维护）

个人入口：[github.com/holtwood](https://github.com/holtwood) · 项目总览：[imshane.site/projects](https://imshane.site/projects)

## LLM 推理与服务

| 仓库 | 上游 |
|------|------|
| [vllm](https://github.com/holtwood-forks/vllm) | vllm-project/vllm |
| [sglang](https://github.com/holtwood-forks/sglang) | sgl-project/sglang |
| [mini-sglang](https://github.com/holtwood-forks/mini-sglang) | sgl-project/mini-sglang |
| [nano-vllm](https://github.com/holtwood-forks/nano-vllm) | GeeeekExplorer/nano-vllm |
| [LightLLM](https://github.com/holtwood-forks/LightLLM) | ModelTC/LightLLM |
| [TensorRT-LLM](https://github.com/holtwood-forks/TensorRT-LLM) | NVIDIA/TensorRT-LLM |
| [LLM-Workshop](https://github.com/holtwood-forks/LLM-Workshop) | tylerelyt/LLM-Workshop |

## 注意力与算子

| 仓库 | 上游 |
|------|------|
| [flash-attention](https://github.com/holtwood-forks/flash-attention) | Dao-AILab/flash-attention |
| [flashinfer](https://github.com/holtwood-forks/flashinfer) | flashinfer-ai/flashinfer |
| [Triton-Puzzles](https://github.com/holtwood-forks/Triton-Puzzles) | gpu-mode/Triton-Puzzles |
| [extension-cpp](https://github.com/holtwood-forks/extension-cpp) | pytorch/extension-cpp |

## 编译器与运行时

| 仓库 | 上游 |
|------|------|
| [triton](https://github.com/holtwood-forks/triton) | triton-lang/triton |
| [tvm](https://github.com/holtwood-forks/tvm) | apache/tvm |
| [ompi](https://github.com/holtwood-forks/ompi) | open-mpi/ompi |

## CUDA 基础与课程

| 仓库 | 上游 |
|------|------|
| [cuda-samples](https://github.com/holtwood-forks/cuda-samples) | NVIDIA/cuda-samples |
| [cuda-course](https://github.com/holtwood-forks/cuda-course) | Infatoshi/cuda-course |
| [SGEMM_CUDA](https://github.com/holtwood-forks/SGEMM_CUDA) | siboehm/SGEMM_CUDA |
| [lectures](https://github.com/holtwood-forks/lectures) | gpu-mode/lectures |
| [dataflowr-notebooks](https://github.com/holtwood-forks/dataflowr-notebooks) | dataflowr/notebooks |
| [minGPT](https://github.com/holtwood-forks/minGPT) | karpathy/minGPT |
| [tutorials](https://github.com/holtwood-forks/tutorials) | triton-inference-server/tutorials |

## 自用与汉化 fork

不用于研读，只为自己跑得舒服；与上面两组学习向副本分开看。

| 仓库 | 上游 | 说明 |
|------|------|------|
| [Termius-Pro-zh_CN](https://github.com/holtwood-forks/Termius-Pro-zh_CN) | ArcSurge/Termius-Pro-zh_CN | Termius 汉化中文包 |
| [DLX](https://github.com/holtwood-forks/DLX) | OwO-Network/DLX | 自建翻译 API 服务 |
| [axonhub](https://github.com/holtwood-forks/axonhub) | looplj/axonhub | 开源 AI Gateway（多模型统一接入） |
| [massCode](https://github.com/holtwood-forks/massCode) | massCodeIO/massCode | 开发者工作区（片段/笔记/HTTP 请求） |
| [Clay](https://github.com/holtwood-forks/Clay) | chaun-yi7/Clay | Typora 主题（仿 Claude 配色） |
| [gpt6-astra-one-shot-games](https://github.com/holtwood-forks/gpt6-astra-one-shot-games) | Ayi1337/gpt6-astra-one-shot-games | GPT-6 Astra One Shot 小游戏合集 |
| [fruit-ninja-dojo](https://github.com/holtwood-forks/fruit-ninja-dojo) | yongqixue99-hue/fruit-ninja-dojo | 原生 Canvas 水果忍者小游戏 |
| [patch-devin](https://github.com/holtwood-forks/patch-devin) | a0yark/patch-devin | Devin CLI 系统提示词补丁工具 |
| [web_search_devin](https://github.com/holtwood-forks/web_search_devin) | mimimaster/windsurf-search-mcp | Devin 服务端 Web 搜索 MCP 服务器 |
| [JadeAI](https://github.com/holtwood-forks/JadeAI) | LingyiChen-AI/JadeAI | AI 简历/求职工作台（自 holtwood-projects 归位，fork 归属修正） |

## 补丁的晋升条件

补丁默认留在这里。同时满足以下三条时，才提升到 [holtwood-systems](https://github.com/holtwood-systems)：

1. 代码已脱离上游仓库的构建体系，能在仓内独立构建与运行；
2. 有一条能在普通硬件上复现的验证路径（不依赖评靶机或特定集群）；
3. 不涉及上游许可禁止再分发的内容。

提升时在新仓库注明来源与改动范围，并在这里保留指向新仓库的说明；**不删除**原 fork。

## 约定

- 不改写上游历史：不 rebase、不 squash
- 实验改动只放在自己的分支，不推 upstream
- 版权与许可归原作者，各仓库保留原 LICENSE
- 衍生作品（汉化、移植、二次修改）在仓库 README 顶部标注上游与改动范围

---

维护者：[holtwood](https://github.com/holtwood) · 原创系统：[holtwood-systems](https://github.com/holtwood-systems) · 比赛：[holtwood-arena](https://github.com/holtwood-arena)
