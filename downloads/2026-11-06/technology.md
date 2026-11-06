# 2026-11-06 科技

报道时段：11月05日 12:00 — 11月06日 12:00

## 人工智能

### Google 推出 Gemini Omni 1.2 Flash，主打15秒视频与更低定价

11月06日 01:00 · 重要 · 可靠性 A

Google 官方博客介绍 Gemini Omni 1.2 Flash，称其快速、低成本，并支持更长视频片段。页面标题写明该模型支持15秒视频，并采用更低定价。

来源：[blog.google](<https://blog.google/innovation-and-ai/technology/developers-tools/introducing-gemini-omni-1-2-flash/>)

### 百度开源文心5.5 Flash Base，MoE 总参数2800亿

11月05日 15:15 · 重要 · 可靠性 B

据量子位报道，百度11月5日在 Hugging Face 开源基座模型文心5.5 Flash Base（ERNIE 5.5 Flash Base）。模型采用 MoE 架构，总参数2800亿，每个 token 激活140亿，预训练使用33.5万亿 token，预训练上下文最高128K，微调与推理支持最长100万 token。

百度称，该模型在知识、推理、数学、代码、多语言和长上下文等基准上取得同尺寸模型 SOTA，超过 DeepSeek-V4-Flash-Base、Hy3-preview-Base、MiMo-V2.5-Base；这些结果来自百度提供的评测口径。

架构上，模型采用 Latent-Gated Sparse Attention、Multi-Router Latent MoE 和 ECHO 训练目标；百度称低秩门控注意力使门控投影权重参数减少75%。

来源：[qbitai.com](<https://www.qbitai.com/2026/11/507787.html>)

### NVIDIA 发布 Cosmos 3 四个开放权重模型

11月06日 03:35 · 重要 · 可靠性 A

NVIDIA 在 Hugging Face 博客发布 Cosmos 3 系列四个开放权重 checkpoint，用于生成交互式世界模拟和多传感器、多视角驾驶场景；四个模型均为 Cosmos 3 Nano 的后训练版本，有16B可训练参数。

这些模型使用 OpenMDW1.1 许可，允许商业和非商业使用；其中 Transfer-Auto 支持最多11个相机视角和联合 RGB-LiDAR 生成，Sim-Auto 是面向流式生成的变体。

NVIDIA 同时表示，后续仍需衡量这些模型在策略学习与评估中的可靠支持范围，并理解其局限。

来源：[huggingface.co](<https://huggingface.co/blog/nvidia/cosmos-interactive-world-simulation>)

### Perplexity 推出面向工作的 AI 代理 Teammates

11月06日 06:26 · 重要 · 可靠性 B

据 The Verge 报道，Perplexity 推出面向工作的 always-on AI agents“Teammates”，可在工作区承担多个角色，并调用已有项目、技能和记忆；它与 Perplexity Computer 集成。

每个 Teammate 有独立线程，可在 Perplexity 应用查看进度，并在 Slack 中交互；该功能需要每月200美元的 Max 订阅。

CEO Aravind Srinivas 在 X 称，长期愿景是每个组织每人有数百个 teammates。

来源：[theverge.com](<https://www.theverge.com/ai-artificial-intelligence/1028302/perplexity-teammates-ai-agents-work>)

### 淘宝 MNN 开源0.3B端侧模型，iPhone 18 Pro 离线解码约350 token/s

11月06日 11:50 · 重要 · 可靠性 B

据IT之家报道，淘宝 MNN 团队发布并开源 MNN-Pocket-0.3B，约3亿参数，重点支持中英文，INT4 部署文件体积173MB。

团队称，在 iPhone 18 Pro 上通过 MNN 推理引擎完全离线运行，平均解码约350 token/s；在 iPad Pro M5、Metal 后端、512 token 配置下，峰值 Metal 驻留内存较加载前增加228MB，部署体积和峰值内存增量分别比 Qwen3-0.6B 少约49%和47%。

技术报告评测中，英文 IFEval 得分73.20，中文 IFEval-zh 74.59，11项评测平均50.00。上述数据由团队公布。

来源：[ithome.com](<https://www.ithome.com/1/023/212.htm>)

## 航天宇航

### CesiumAstro 完成7.3亿美元D轮并公布737颗卫星星座

11月06日 05:45 · 重要 · 可靠性 B

据SpaceNews刊发的CesiumAstro公告，公司完成7.3亿美元D轮融资，估值超过45亿美元，由Janus Henderson领投；公司称2026年公布融资总额超过12亿美元。

公司同时公布 Synchronicity 计划：一个由737颗AI增强卫星组成的星座，面向商业、主权和国防任务。

CesiumAstro 称首颗卫星 Element-1 已发射并开始在轨运行；新资金将用于先进技术、扩大美国制造能力、下一代航天器开发与生产、Synchronicity 部署和国际增长。公司还计划五年投资5亿美元扩建奥斯汀总部。

来源：[spacenews.com](<https://spacenews.com/cesiumastro-secures-730-million-in-janus-henderson-led-series-d-at-a-valuation-above-4-5-billion-unveils-synchronicity-satellite-constellation-following-fully-successful-element-1-mission/>)

## 硬件

### NVIDIA 称 Vera CPU 在 AI agent 负载中兼顾吞吐与能效

11月06日 04:00 · 重要 · 可靠性 A

NVIDIA 在博客中称，Vera CPU 在100兆瓦数据中心比较中，单颗性能优于最快 x86 CPU 和最能效 x86 CPU；每瓦支持的 AI agent 数量比最快 x86 多1.6倍，agent 速度比最能效 x86 高2倍。

NVIDIA 还列出早期客户数据：Perplexity 的 agentic coding 任务快1.5倍，DeepInfra 的 agent 编排最高快2.2倍。上述数字均来自 NVIDIA 公布的对比。

来源：[blogs.nvidia.com](<https://blogs.nvidia.com/blog/vera-cpu-highest-throughput-fastest-agents/>)
