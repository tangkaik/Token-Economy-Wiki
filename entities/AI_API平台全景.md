# AI API平台全景图

> 整理自：Kimi、Claude、SiliconFlow、Fireworks AI、OpenRouter官方资料
> 更新时间：2026-04-27

---

## 什么是AI API平台

AI API平台提供大语言模型的API接口，让开发者/企业能够调用AI能力。

Token经济核心：谁有更低的API成本，谁就能在中间商模式中赚取更多差价。

---

## 主流API平台

### 1. 硅基流动 (SiliconFlow) — 国内聚合平台

**官网**：https://www.siliconflow.com

**核心优势**：
- **高速推理**：语言模型10x+速度提升，图像生成3x+
- **高性价比**：语言模型成本节省46%，生图成本节省66%
- **多芯支持**：支持多种GPU

**主流模型定价（$/M tokens）**：

| 模型 | 输入 | 缓存输入 | 输出 |
|------|------|----------|------|
| DeepSeek-V4-Flash | $0.14 | $0.028 | $0.28 |
| DeepSeek-V4-Pro | $1.74 | $0.145 | $3.48 |
| DeepSeek-V3.2 | $0.27 | $0.135 | $0.42 |
| Qwen3-VL-32B-Instruct | $0.2 | $0.6 | - |
| GLM-5.1 | $1.4 | $0.26 | $4.4 |
| Kimi-K2-Instruct | $0.58 | $2.29 | - |

**为什么重要**：
- 国内最活跃的API聚合平台
- 支持OpenAI兼容格式
- 新用户$1免费额度

---

### 2. Fireworks AI — 国际高速推理

**官网**：https://www.fireworks.ai

**核心定位**：
> "From Inference to Intelligence — Surpass closed models when you train and run your models on Fireworks' frontier inference platform."

From the creators of PyTorch.

**主流模型定价（$/M tokens）**：

| 模型 | 输入 | 输出 | 上下文 |
|------|------|------|--------|
| Kimi K2.5 | $0.6 | $3 | 262144 |
| Kimi K2.6 | $0.95 | $4 | 262144 |
| DeepSeek v3.2 | $0.56 | $1.68 | 163840 |
| MiniMax M2.7 | $0.3 | $1.2 | 196608 |
| GLM 5.1 | $1.4 | $4.4 | 202752 |
| Qwen3.6 Plus | $0.5 | $3 | - |

**为什么重要**：
- PyTorch团队创建
- 主打极速推理
- 训练+推理一体化（Training预览中）

---

### 3. OpenRouter — 全球聚合平台

**官网**：https://openrouter.ai

**核心定位**：
> "Unified API for hundreds of AI models"

**关键数据**：
| 指标 | 数值 |
|------|------|
| 文本模型 | 652 |
| 图像模型 | 18 |
| Embeddings | 26 |
| 音频模型 | 5 |
| 视频模型 | 11 |

**三种接入方式**：
1. **API** — 完全控制，任何语言
2. **Client SDKs** — 类型安全
3. **Agent SDK** — 专为AI Agent设计

**核心功能**：
- **Model Fallbacks**：自动回退
- **自动路由**：选择最便宜选项
- **Zero Data Retention**：零数据保留

**最新模型（2026-04-27）**：
- Qwen3.5 Plus: $0.40/M输入，$2.40/M输出，1M上下文
- Qwen3.6 Flash: $0.25/M输入，$1.50/M输出

**排行榜洞察**：
1. Kimi K2.6 — 1.58T tokens（新上架即登顶）
2. Claude Sonnet 4.6 — 1.36T tokens
3. DeepSeek V3.2 — 1.28T tokens

---

### 4. Kimi API (Moonshot) — 国产旗舰

**官网**：https://platform.moonshot.cn

**核心模型**：
| 模型 | 类型 | 上下文 | 特点 |
|------|------|--------|------|
| **Kimi K2.6** | 多模态 | 256K | 最新旗舰，长程代码更强 |
| **Kimi K2.5** | 多模态 | 256K | 高性价比 |
| moonshot-v1-128k | 文本 | 128K | v1系列 |

**特点**：
- 多模态：支持文本、图片、视频输入
- 思考模型：K2 thinking model
- 联网搜索：官方联网搜索工具

---

### 5. Claude API (Anthropic) — 企业级

**官网**：https://docs.anthropic.com

**核心能力**：
- **扩展思考（Extended Thinking）**
- **自适应思考**
- **结构化输出**
- **多语言支持**
- **PDF支持**

**工具生态**：
- 网页搜索工具
- 网页抓取工具
- 代码执行工具
- 计算机使用工具
- Bash工具

---

### 6. DeepSeek — 开源标杆

**官网**：https://www.deepseek.com

**开源模型（GitHub）**：
- DeepSeek R1 — 推理模型
- DeepSeek V3 — 最新旗舰
- DeepSeek Coder V2 — 代码模型
- DeepSeek VL — 视觉语言模型

**最新动态**：
🎉 DeepSeek-V4 预览版发布，具备世界顶级推理性能

---

## 价格对比（$/M tokens）

| 平台 | DeepSeek-V3.2 | Kimi K2.5 | Qwen3.6 |
|------|----------------|-----------|---------|
| **硅基流动** | $0.27 / $0.42 | - | - |
| **Fireworks** | $0.56 / $1.68 | $0.6 / $3 | $0.5 / $3 |
| **OpenRouter** | - | - | $0.25 / $1.50 |

---

## 关键洞察

### 中间商机会

1. **信息差**：不同平台价格差异可达2-3倍
2. **批量折扣**：大采购有额外折扣
3. **打包服务**：组合多个模型提供解决方案

### 风险

1. **官方降价**：大厂持续降价压缩空间
2. **封号风险**：灰色市场有被封风险
3. **技术迭代**：新模型可能颠覆现有定价

---

## 资源链接

| 平台 | 链接 |
|------|------|
| 硅基流动 | https://www.siliconflow.com |
| Fireworks AI | https://fireworks.ai |
| OpenRouter | https://openrouter.ai |
| Kimi API | https://platform.moonshot.cn |
| Claude API | https://docs.anthropic.com |
| DeepSeek | https://www.deepseek.com |
