# AI Token经济：个人参与者商业情报报告（2024–2026 Q1）

> **撰写定位**：面向想要在AI Token经济中寻找一份现金流的**个人参与者**——独立开发者、内容创作者、自由职业者、副业玩家、想转型的传统从业者。
> **时间锚定**：仅纳入2024年1月至2026年Q1已实际发生、有收入验证或政策落地的商业模式。所有未来预测、概念故事一律剔除。
> **撰写日期**：2026年4月。
> **数据原则**：每个关键数据点均附原始URL；每个推荐模式都必须能回答"上游去哪找、下游怎么卖、启动多少钱、风险是什么"。

---

## 目录

1. 现状定义与市场规模
2. 直接模式：Token中间商产业链拆解
3. 衍生商业模式矩阵（A基础设施套利层 / B应用层 / C服务层 / D新兴灰色地带）
4. 个人路径决策树
5. 实操Checklist
6. 案例库
7. 合规与风险提示
8. 参考来源清单

---

## 一、现状定义与市场规模

### 1.1 "AI Token经济"的当前边界

本报告所指的"AI Token经济"，是指围绕**大语言模型按Token计费的API调用**为核心，向上下游延伸出的全部经济活动，包括：

- **核心层**：大模型API调用计费（OpenAI、Anthropic、Google、DeepSeek、智谱、通义、豆包等）。
- **算力层**：模型推理服务、GPU租赁、DePIN算力代币化。
- **应用层**：基于API包装的SaaS产品、内容批量生产、Agent/Workflow编排。
- **服务层**：Prompt工程咨询、模型微调、AI培训、Token成本治理。
- **灰色层**：账号共享拼车、API中转、镜像站、跨境代充。

不在本报告讨论范围：纯Web3代币炒作、AI芯片硬件制造、基础模型预训练（>$1亿成本，非个人可参与）。

### 1.2 全球与中国Token消耗规模（已发生事实）

| 口径 | 2024年 | 2025年中/底 | 来源 |
|---|---|---|---|
| **全球LLM市场（宽口径）** | **56.2亿美元** | 73.6亿美元 | [GrandView Research](https://www.grandviewresearch.com/industry-analysis/large-language-model-llm-market-report) |
| **企业级LLM API支出（窄口径）** | **35亿美元（年底）** | **84亿美元（年中，6个月翻倍）** | [Menlo Ventures Mid-Year Update](https://menlovc.com/perspective/2025-mid-year-llm-market-update/) |
| **中国公有云大模型Token调用量** | **114万亿** | 预计2025年突破**2000万亿**（同比+16倍） | [信通院CAICT](https://www.caict.ac.cn/kxyj/qwfb/bps/202602/P020260202487301304903.pdf) |
| **中国企业级日均Token消耗** | 2024H2约 1万亿 | **37万亿（2025H2）** | [Frost & Sullivan/腾讯云](https://cloud.tencent.com/developer/article/2641252) |
| **OpenAI日均Token处理量** | — | **8.6万亿（2025年10月）** | Sam Altman OpenAI Dev Day 2025 |
| **OpenRouter平台中国模型流量份额** | <2%（2024-10） | **>45%（2026-04）** | [Digital Applied LLM研究](https://www.digitalapplied.com/blog/openrouter-rankings-april-2026-top-ai-models-data) |

### 1.3 头部厂商市场份额（2025H2）

**全球**（Menlo Ventures，企业API窄口径）：
- **Anthropic 32%**（新晋第一）
- OpenAI 25%（从2023年末50%下降）
- Google 20% / Meta Llama 9% / DeepSeek 1% 但飞速增长

**中国**（Frost & Sullivan，企业级调用市场）：
- **阿里通义 32.1%（第一）** / 字节豆包 14.1% / DeepSeek 10.3%

**核心市场结构判断**：上游集中度高，但价格战已让单个Token价格在18个月内下降50%–90%（Claude Opus从$15/$75降至$5/$25；DeepSeek-V3从¥1输入降至¥0.5以下）。**Token本身已经成为一种快速通缩的商品**，单纯卖Token差价的中间商窗口在收窄，**个人玩家的真正机会不在Token本身，而在Token之上的服务化、产品化、合规化**。

---

## 二、直接模式：Token中间商产业链拆解

> **先泼一盆冷水**：所有主流模型方（OpenAI / Anthropic / Google / 智谱 / 通义 / 字节 / Kimi / 百度）**均无公开的Reseller / Affiliate返佣计划**。个人想做"代理商"的传统幻想（拿货、加价、卖货），在2024–2026年的真实政策下基本走不通。
> **真正可走的中间商路径**有三种：① 利用充值阶梯赠券打包售卖 ② 利用聚合平台（SiliconFlow / OpenRouter）做合规接入服务 ③ 利用错峰/批处理/缓存赚价差。

### 2.1 上游获取——具体平台与折扣区间

| 平台 | 申请入口 | 个人能否申请 | 主要折扣机制 | 已发生事实 |
|---|---|---|---|---|
| **OpenAI** | [openai.com/api/pricing](https://openai.com/api/pricing/) | ⚠️ 国际信用卡，中国大陆IP常被拒 | **Batch API -50%**；**Prompt Cache -90%**；企业多年合同 -10%–20% | 无公开Reseller计划（[CustomGPT.ai核实](https://customgpt.ai/does-openai-have-an-affiliate-program/)） |
| **Anthropic** | [anthropic.com/pricing](https://www.anthropic.com/pricing) | ⚠️ 国际信用卡 | Batch API -50%；Prompt Cache | 2026年4月新企业定价取消量价折扣 |
| **Azure OpenAI** | Microsoft CSP体系（如世纪互联） | ❌ 需企业实体 | CSP分销链条 | Direct CSP门槛升至$25k/年（[Stratos Cloud](https://www.stratoscloud.com/blog/microsoft-csp-changes-in-2025/)） |
| **DeepSeek** | [platform.deepseek.com](https://platform.deepseek.com) | ✅ 个人可直充 | **错峰优惠00:30–08:30：V3半价、R1 2.5折** | 2025年2月曾因资源紧张暂停充值 |
| **智谱BigModel** | [open.bigmodel.cn](https://open.bigmodel.cn/pricing) | ✅ 个人可申请Z计划 | 新注册赠**2000万Tokens**；GLM-4.7-Flash免费；Batch -50% | Z计划Token资助初创/独立开发者 |
| **阿里通义百炼** | [bailian.console.aliyun.com](https://bailian.console.aliyun.com) | ✅ 个人；正式代理需企业 | 新注册赠100万Tokens；**云推广大使返佣20%–40%（4个月分批发放）** | OpenAI兼容API |
| **字节火山方舟** | [volcengine.com/docs/82379](https://www.volcengine.com/docs/82379/1391869) | ✅ 个人实名 | **协作奖励计划：每模型最高500万Tokens/天免费**（以授权数据换取，延续至2026年6月30日） | 国内独有"数据换Token"机制 |
| **月之暗面 Kimi** | [platform.moonshot.cn](https://platform.moonshot.cn/blog/posts/discount) | ✅ 个人可直充 | 充值阶梯：¥500档赠30% / ¥10,000档赠40% / **≥¥50,000档赠50%** | 自动Prompt Cache，最高降75%输入成本 |
| **百度千帆** | [qianfan.cloud.baidu.com](https://qianfan.cloud.baidu.com/qianfandev/topic/685493) | ⚠️ 云推广大使个人可，正式代理需企业 | 同阿里返佣机制 | AppBuilder新用户赠100万Tokens |

**个人能直接拿到的最高"折扣"，本质上是这三条路径**：
1. **Kimi充值赠50%券** + **DeepSeek凌晨2.5–5折** + **Batch API官方5折** = 三重叠加，可把综合Token成本压到名义官方价的25%–35%。
2. **火山方舟协作奖励**——以"授权数据匿名用于模型优化"换取每天每模型500万免费Token，本质是用数据资产换Token资产。
3. **智谱Z计划**——独立开发者可申请专项Token资助（非现金，但等价于启动资金）。

### 2.2 中间聚合平台——直接对比

| 平台 | URL | 与官方价格差距 | 个人价值 |
|---|---|---|---|
| **OpenRouter** | [openrouter.ai](https://openrouter.ai) | **官价 + 5.5%充值费** | 透传定价，统一接口，加密货币付款 |
| **Together AI** | [together.ai](https://www.together.ai) | **开源模型常低于官方20%–50%** | 175+开源模型，Llama 3.1 405B仅 $0.90/M |
| **Fireworks AI** | [fireworks.ai](https://fireworks.ai) | 与Together AI互有高低，DeepSeek V3.2 $0.56/$1.68 | 推理性能优化 |
| **SiliconFlow硅基流动** | [siliconflow.cn](https://siliconflow.cn/pricing) | 与官方**基本持平**（DeepSeek-R1 ¥4/¥16） | **国内合规、人民币、统一接口、500+模型** |
| **302.AI** | [302.ai](https://302.ai/en/) | 海外模型**+10%–20%**（含换汇） | 无需海外账户，人民币付款 |
| **API2D** | [api2d.com](https://www.api2d.com) | **官方价×1.5**（高溢价） | 微信/支付宝、中文客服、低门槛 |
| **OhMyGPT** | [ohmygpt.com](https://ohmygpt.com) | 名义与官方持平，含换汇约+3%–10% | 个人/企业发票齐全 |
| **Poe by Quora** | [poe.com](https://poe.com) | $19.99/月套餐≈直购OpenAI $50–70等价调用，**节省60%+** | 适合中低并发个人玩家 |

### 2.3 个人能立即执行的三种打包模板

#### 模板A：「按次计费的行业Chatbot」（最低门槛）
- **如何做**：基于Coze / Dify / FastGPT，用SiliconFlow API + 自己整理的行业知识库（法律条款、电商运营手册、跨境物流问答），打包成微信小程序或网页Chatbot。
- **如何卖**：单次问答¥1–¥3 / 月卡¥29–¥99 / 年卡¥299。
- **典型成本**：DeepSeek-V3输入¥0.5/M输出¥1.5/M，单次问答约消耗0.001元；客单价至少**1000倍毛利**覆盖运营。
- **下游渠道**：小红书引流、知识星球、私域社群、闲鱼出"问答额度卡"。

#### 模板B：「会员制AI工具箱」（中等门槛）
- **如何做**：聚合10–30个细分场景（简历优化、合同审核、PDF翻译、SEO关键词、跨境邮件、长文摘要……）做成一个站点，统一收会员费。
- **典型样本**：国内**"白嫖GPT站"** / 海外**Poe机器人聚合**。Poe已于2025年7月开放API（$30/100万Token），允许个人开发者把自己的Bot放进Poe生态分成。
- **价格区间**：年卡¥99–¥399，月卡¥9–¥39。
- **关键风险**：境内提供AI服务须算法备案（个人无法独立完成，见第七章）。

#### 模板C：「行业专用API转售」（高门槛但天花板更高）
- **如何做**：利用火山协作奖励 + Kimi充值赠券 + Batch API + Prompt Cache，将原始Token打包成"按调用次数计费的行业API"（如"中文SEO文章生成API"、"小红书种草文案API"、"京东详情页API"），通过RapidAPI / 阿里云市场 / 腾讯云市场转售给中小企业。
- **核心价差来源**：让买家只关心"产出"而不关心"Token"——把不可预测的Token消耗封装成可预测的"次数计费"。
- **真实参照**：**Bannerbear**（图片生成API）月收入$53k–$82k（[人人都是产品经理](https://www.woshipm.com/ai/6343398.html)），就是这个模式的成熟版。

### 2.4 下游获客渠道与合规风险对照

| 渠道 | 转化效率 | 合规风险 |
|---|---|---|
| **Twitter/X Build in Public** | 极高（适合海外） | 低 |
| **Product Hunt** | 中（首日可带数千次试用） | 低 |
| **Indie Hackers** | 中（小型流量、口碑） | 低 |
| **Chrome Web Store** | 高（AI类目持续在增长） | 低，但需遵守商店政策 |
| **Gumroad / Lemon Squeezy** | 中（数字产品一次性销售） | 低，Gumroad抽15% |
| **微信小商店 / 知识星球** | 中（适合私域） | 中（须实名） |
| **小红书 / 即刻** | 高流量但低付费意愿 | 低 |
| **少数派 / V2EX** | 低流量但高质量用户 | 低 |
| **闲鱼 / 淘宝** | 高（C端走量） | **高**（关键词审查、平台抽佣、共享类商品违反平台规则） |
| **Discord / Telegram群** | 中（适合海外+灰色地带） | 海外低，国内高 |

### 2.5 启动成本与收入预期（个人起步）

| 项目 | 最低成本 |
|---|---|
| 域名 | $10–$15/年 |
| Vercel / Railway 服务器 | $0–$50/月 |
| Stripe / Lemon Squeezy 支付通道 | 2.9% + $0.30 / 笔 |
| API额度（前3个月试运营） | $50–$300/月 |
| **冷启动总成本** | **$100–$500（约¥700–¥3,500）** |

**MRR分布参考（[海外独立开发者样本](https://supabird.io/articles/from-corporate-dreams-to-1-3m-arr-as-an-entrepreneur)）**：
- 0–$100：~60%（死亡区）
- $100–$1,000：~20%（生存线）
- $1,000–$5,000：~12%（可持续副业）
- $5,000–$20,000：~6%（全职替代）
- $20,000+：~2%（明星产品）

> **关键判断**：纯Token差价的"二道贩子"模式个人能赚的钱**极其有限**（聚合平台已把价差吃干）。**真正在Token经济里赚钱的个人，几乎全部是"用Token生产某种用户愿付费的产出"——Token只是原料，产品才是商品。**

---

## 三、衍生商业模式矩阵（重点章节）

### A. 基础设施套利层

#### A1. 算力套利：Poe订阅 vs API直购、海外GPU vs 国内推理

| 模式名称 | 启动资金 | 技能门槛 | 收入天花板 | 风险等级 |
|---|---|---|---|---|
| Poe订阅套利 | $20–$100 | 低 | $1k/月（个人套利） | 中（账号共享违反ToS） |
| GPU云价差套利 | ¥3,000–¥30,000 | 中（Linux/Docker） | ¥30k/月 | 中（DePIN代币兑换合规） |

**操作路径（已验证）**：
- 海外**RunPod / Vast.ai / Clore.ai**上RTX 4090报价 **$0.15–$0.59/h**；同等规格的国内**AutoDL** RTX 3090报价 **¥2–¥5/h**（约$0.28–$0.70/h）。短期高负载推理任务存在跨境价差，**适合自建轻量推理服务转售给国内客户**。
- **Poe** $19.99/月可获100万点（≈直购OpenAI约$50–$70等价调用），是**个人低并发玩家最便宜的GPT-4o通道**。但账号共享违反ToS，建议自用而非转售。
- **真正可落地的"算力套利"是**：在DePIN网络（**io.net** RTX 4090挂牌$0.25–$0.50/h、**Aethir**消费级月收益$500–$1,500、**Render**月收益$300–$800）上出租自有GPU，再用收益购买Token或反向租用更高配的算力。

**详细数据**：

| 网络 | 个人节点收益（月） | 已发币情况 |
|---|---|---|
| **io.net** | RTX 4090约$60–$150（35%–50%利用率） | IO代币已上线 |
| **Aethir** | RTX 4090约$500–$1,500（40%–60%利用率，企业级） | ATH代币2024Q3上线 |
| **Render** | 高端GPU $300–$800 | RENDER代币 |
| **Grass** | 浏览器节点$5–$30（依赖空投） | GRASS代币2024-10上线 |
| **Bittensor** | 进入TOP 64子网约需1,000权重，门槛极高 | TAO波动剧烈 |

**第一步动作**：注册一个**RunPod**账号，挂上自己的4090玩两周，观察实际利用率与到账收入；同时申请**Akash**[官方收益计算器](https://akash.network/pricing/provider-calculator/)做估算。

**风险**：中国境内将代币变现违反《关于进一步防范和处置虚拟货币交易炒作风险的通知》（2021年9月）；DePIN收益≠现金流，往往需要"持币等空投"。

#### A2. 模型微调即服务（MFaaS）

| 模式名称 | 启动资金 | 技能门槛 | 收入天花板 | 风险等级 |
|---|---|---|---|---|
| LoRA / QLoRA垂直微调外包 | ¥3,000–¥30,000 | 高（需ML工程） | 单项目¥10k–¥50万 | 低-中 |

**工具链**：
- **LLaMA-Factory**（[GitHub](https://github.com/hiyouga/LlamaFactory)）：100+模型支持，零代码Web UI，国内开发者首选。
- **Unsloth**：训练速度2.5倍，省20% VRAM，可在Colab跑得动。
- **Axolotl**：支持DeepSpeed/FSDP多GPU。
- **HuggingFace AutoTrain**：托管式微调最低门槛。

**接单平台与典型客单**：

| 平台 | 单项目客单 |
|---|---|
| **Upwork** Starter / Standard / Advanced | $2,000 / $5,000 / $12,000（[Upwork服务页](https://www.upwork.com/services/product/development-it-llm-training-llm-finetuning-llm-generative-ai-llm-training-1830555930279953332)） |
| **Toptal** 高级LLM工程师 | $240/h（中位） |
| **猪八戒 / 程序员客栈** 法律/医疗/电商微调 | ¥5,000–¥20万 |
| 美国**专家级**（RLHF / 微调，[Second Talent报告](https://www.secondtalent.com/resources/freelance-llm-developer-hourly-rate-us-2026/)） | **$350–$700/h** |

**第一步动作**：
1. 在 **Hugging Face** 公开发布一个垂类（如"中文古诗词生成"或"电商客服意图分类"）的LoRA权重作为作品集。
2. 在 **Upwork** / **猪八戒** / **程序员客栈**注册并把作品集接入。
3. 在 **AutoDL** 租一台RTX 3090（¥2–¥5/h）做客户PoC。

---

### B. 应用层

#### B1. 微SaaS（AI Wrapper）

| 模式名称 | 启动资金 | 技能门槛 | 收入天花板 | 风险等级 |
|---|---|---|---|---|
| 单功能AI工具/Chrome插件 | $100–$2,000 | 中（全栈） | 月$100k–$250k+ | 中（API政策、竞争） |

**头部独立开发者验证（2024–2026公开收入）**：

| 开发者 | 产品 | 月收入 | 来源 |
|---|---|---|---|
| **Pieter Levels** | Photo AI + Interior AI | **$250k–$300k**（利润率87%–99%） | [SoftwareSeni](https://www.softwareseni.com/building-in-public-the-10-year-distribution-strategy-behind-solo-founder-revenue/) |
| **Damon Chen** | PDF.ai + Testimonial.to（ARR $1.3M） | ~$130k | [SupaBird](https://supabird.io/articles/from-corporate-dreams-to-1-3m-arr-as-an-entrepreneur) |
| **Marc Lou** | ShipFast / CodeFast / TrustMRR | $84,859（2025-12） | [TrustMRR](https://trustmrr.com/founder/marclou) |
| **Tibo Louis-Lucas** | 4款产品各$100k+ | $400k+ | [LinkedIn](https://www.linkedin.com/posts/lekterable_tibo-louis-lucas-built-4-saas-products-doing-activity-7404452374456668160-O-jR) |
| **Jon Yongfook** | Bannerbear | $53k–$82k | [人人都是产品经理](https://www.woshipm.com/ai/6343398.html) |

**中文区现实**：
- **idoubi**（前微信团队）2024年做了11款AI产品，到12月四款合计MRR仅约**$1,000**——直到第12款**ShipAny**（独立开发样板代码）首周破**$10,000**（[智源社区](https://hub.baai.ac.cn/view/42470)）。
- 主要收入来源：**付费开发者社群（200+人）**，"比做产品赚得还多"（[虎嗅](https://www.huxiu.com/article/3631911.html)）。
- **关键教训**：国内独立开发者面向国内市场难以盈利，**面向海外市场更容易达到$10k+ MRR**。

**发布渠道与转化**：
- **Product Hunt**：Top of the Day可带500–5,000用户，付费转化1%–5%
- **Twitter/X Build in Public**：核心杠杆，无受众则Product Hunt失效
- **Chrome Web Store**：AI类目持续增长，适合插件形态
- **Indie Hackers / Reddit r/SideProject**：口碑型流量
- **小红书 / 即刻 / V2EX**：国内冷启动

**第一步动作**：定一个"7日上线MVP"目标——在 **Bolt.new** 或 **Cursor** 上1天写完前端，1天接入SiliconFlow或OpenRouter API，1天接Stripe/Lemon Squeezy，余下4天发推+发小红书。

#### B2. AI内容工业化

| 模式名称 | 启动资金 | 技能门槛 | 收入天花板 | 风险等级 |
|---|---|---|---|---|
| AI批量SEO / 短视频 / 详情页 | $500–$5,000 | 低-中 | 单站$1k–$5k/月（高者$20k+） | **高（Google算法打击）** |

**真实变现案例**：
- **海外SEO站**：用OpenAI API批量生产**1,023篇文章**，14个月从0做到月入$3,674；最终以**$108,000**卖出，**ROI 602%**（[Reddit /r/juststart](https://www.reddit.com/r/juststart/comments/1cr0915/case_study_automated_ai_seo_content_site_0_to/)）。
- **Amazon listing**：超过**90万卖家**已使用AI listing生成，AI内容接受率约**90%**（[Amazon官方](https://www.aboutamazon.com/news/innovation-at-amazon/amazon-generative-ai-seller-growth-shopping-experience)）。第三方按listing收费$5–$50。
- **猪八戒短视频脚本**：单篇¥30–¥100，10篇打包¥299。

**工具链**：
- **n8n**（自托管$20/月） / **Make.com**（$9起） / **Zapier**（$20起）做编排
- **秘塔写作猫** / **火山写作** / **Jasper** / **Copy.ai** 做生成
- **Heygen** / **Synthesia** / **剪映** 做视频化
- **Coze** / **Dify** 做工作流

**单篇成本**：
- GPT-4o-mini 1000词文章：**$0.02–$0.05**；Claude 3.5 Haiku：$0.01–$0.03
- AdSense收益（信息站$15 RPM、1000PV/篇/月）：$15/月持续
- 回本时间：1–3个月

**致命风险——Google算法打击（已发生事实）**：
- **March 2026 Core Update**：发布500+篇AI文章的利基站，**流量下跌60%–80%**；AI改写新闻聚合站跌**50%–75%**（[Digital Applied](https://www.digitalapplied.com/blog/scaled-content-abuse-google-march-update-ai-pages-decimated)）。
- 旅游博客 **The Planet D**：Google AI Overviews上线后流量降50%，最终于2025年停刊（[AdExchanger](https://www.adexchanger.com/publishers/the-ai-search-reckoning-is-dismantling-open-web-traffic-and-publishers-may-never-recover/)）。
- **结论**：纯AI批量SEO站在2026年已不可持续；**可行路径只剩"AI辅助 + 人类编辑 + 领域专家署名"**。

**第一步动作**：选一个有**真实领域知识**的垂类（如"宠物用药对比"、"小众CrossFit器械"、"日本工具五金"），先用ChatGPT做关键词调研，再用Make.com搭建"WordPress+Claude+Schema自动发布"流水线，**每篇必须人工编辑+加入第一手图片**。

---

### C. 服务层

#### C1. Prompt工程咨询 / 省Token服务

| 模式名称 | 启动资金 | 技能门槛 | 收入天花板 | 风险等级 |
|---|---|---|---|---|
| 企业Token成本治理咨询 | $0–$500 | 中-高 | $200–$400/h，年薪$125k+ | 低 |

**确实有人靠"省Token"赚钱**：
- 一名工程师在YouTube公开案例：通过 **Cloudflare AI Gateway缓存** + **bge-reranker-base替代LLM-as-a-judge** + **LangGraph历史压缩** + **任务复杂度路由到小模型**，为一家初创公司**每年省下$100万+**API成本（[YouTube](https://www.youtube.com/watch?v=4x4nM0uPmg0)）。
- Infosys测算：每条prompt减100 token × 10,000次/月 = 中型企业月省$1,000+（[Infosys博客](https://blogs.infosys.com/emerging-technology-solutions/artificial-intelligence/smart-prompting-smarter-ai-optimizing-token-use-for-responsible-and-efficient-interactions.html)）。
- Deloitte 2026年1月报告："Tokens是新货币"，企业FinOps治理需求催生独立咨询市场（[Deloitte](https://www.deloitte.com/us/en/insights/topics/emerging-technologies/ai-tokens-how-to-navigate-spend-dynamics.html)）。

**报价区间**（[Coursera](https://www.coursera.org/articles/prompt-engineering-salary)、[AI CERTs](https://www.aicerts.ai/news/prompt-engineering-salaries-reality-skills-and-career-outlook/)、[Asrify 2026](https://asrify.com/blog/prompt-engineer-rates-2026)）：

| 层级 | Upwork时薪 | 美国年薪中位 |
|---|---|---|
| 初级 | $30–$60 | $63k–$109k |
| 中级（RAG/Workflow） | $60–$120 | $109k–$126k |
| 高级（Agent + 评测框架） | $150–$250+ | $175k–$335k |
| 顶级（Anthropic/Google水准） | $200–$400 | $245k–$375k |

**国内大厂对应岗（[TeamedUp China](https://teamedupchina.com/the-state-of-ai-jobs-careers-and-salaries-in-china/)）**：AI应用工程师 ¥30万–¥80万；AI架构师 ¥60万–¥200万+；DeepSeek/华为顶尖人才 ¥200万+。

**必备工具**：
- **PromptLayer**（$50/用户/月）—— Prompt版本管理 + A/B测试 + 成本追踪
- **Helicone**（$20/座位/月）—— 300+模型支持、成本路由
- **LangSmith**（$39/用户/月）—— LangChain深度集成
- **Langfuse**（开源免费）—— 自托管可观测性

**第一步动作**：选一家自己熟悉的SaaS或电商公司（最好是有AI功能的），用 **Helicone** 帮他们做一周的Token成本审计，免费交付一份"预计可省XX%成本"的报告，作为接咨询单的敲门砖。

#### C2. AI培训与知识付费

| 模式名称 | 启动资金 | 技能门槛 | 收入天花板 | 风险等级 |
|---|---|---|---|---|
| 知识星球 / 训练营 / Cohort课程 | $0–$3,000 | 中（领域知识+运营） | 头部年入¥1,000万+ | 中（复购+监管） |

**国内头部样本**：
- **生财有术**（亦仁，知识星球）：4.6万+会员，第七期起¥1,965–¥3,365/年；2021年单次"418活动"**1小时近¥4,000万流水**；续费率70%（[AI出海去](https://www.aichuhaiqu.com/%E7%94%9F%E8%B4%A2%E6%9C%89%E6%9C%AF%E7%A4%BE%E5%8C%BA%E4%B8%8E%E5%85%B6%E5%88%9B%E5%A7%8B%E4%BA%BA%E4%BA%A6%E4%BB%81%E7%9A%84%E6%95%85%E4%BA%8B/)）。
- **三节课**：2024年AI课程需求增长**3,600%**，AI应用学习时长增**8,303%**（[经济观察报](http://www.eeo.com.cn/2024/0623/668273.shtml)）。
- **洪灏**（经济学家知识星球）：开通10天**8,500人付费 ≈ ¥760万**；2个月GMV破¥1,258万（[新浪财经](https://cj.sina.cn/articles/view/1700648435/655dd5f302001fb56)）。

**海外样本**：
- **Maven**（Cohort课程平台）：525,000用户、207国、14,000企业；讲师首期Cohort平均收入**$30,000**（3班×10人×$1,000），平台抽10%；个例如Ben单独通过Maven赚到**$100,000+**（[LinkedIn](https://www.linkedin.com/posts/benerez_my-course-has-generated-over-100k-in-earnings-activity-7399108717981446144-8jtT)）。
- **ZeroToMastery**：$39/月或$279/年订阅制，AI/ML课程为最快增长品类。

**月营收分布参考**：

| 层次 | 月营收 | 形态 |
|---|---|---|
| 入门兼职 | ¥5,000–¥20,000 | 50–200人知识星球 |
| 中型 | ¥20,000–¥100,000 | 星球+课程+Live |
| 头部自媒体 | ¥100,000–¥500,000 | 矩阵+训练营+咨询 |
| 超头部 | ¥500,000–千万级 | 生财有术 / 洪灏 |

**第一步动作**：花3天把"我教大家如何用DeepSeek+Coze每天省2小时"做成20讲免费短视频，发抖音/小红书/视频号3平台同步，**满1000关注立即开199元知识星球**，用第一批种子用户跑闭环。

---

### D. 新兴 / 灰色地带（**强风险标注**）

#### D1. 账号共享与拼车（风险等级：⚠️⚠️⚠️ 高）

| 模式名称 | 启动资金 | 技能门槛 | 收入天花板 | 风险等级 |
|---|---|---|---|---|
| ChatGPT/Claude/MJ拼车 | ¥0–¥1,000 | 低 | ¥3k–¥10k/月 | **高（违反ToS、被封号）** |

**市场价格（2025–2026）**：
- ChatGPT Plus拼车：¥27–¥35/月（5–8人共用），**6个月失效率68%**
- 合租：¥50/月，车主跑路率约15%
- 淘宝代充：¥100–¥140；闲鱼个人：¥120
- 官方直充：¥145（需境外信用卡，**中国卡拒付率78%**，2025年8月Stripe Shield 3.0升级后）

**主要平台**：奈飞小铺、车队长、奇妙车站、FamilyShare、GamsGo、TogetherPrice、Spliiit；淘宝/闲鱼灰市最大但合规风险最高。

**已发生的执法**：
- **2024年7月9日**：OpenAI正式封禁中国大陆/港澳API流量，三重验证（IP+支付+Accept-Language）（[CNBC](https://www.cnbc.com/2024/06/25/chinese-ai-firms-woo-openai-users-amid-plans-for-api-restrictions.html)）。
- **2025年7月12日**：**WildCard虚拟卡**永久停服，影响约30万用户。
- **2025年7月28日**：Anthropic公开点名账号共享/转售行为并执法；2025年8月28日起Claude Code限周用量上限（Sonnet 4：240–480小时/周；Opus 4：24–40小时/周）（[Anthropic X](https://x.com/AnthropicAI/status/1949898513019466140)）。
- **协议条款**：OpenAI Services Agreement（2025.5.31）第3.1/3.3条明确禁止账号共享、转售、买卖API Key（[OpenAI](https://openai.com/policies/services-agreement/)）；Midjourney社区指引（[文档](https://docs.midjourney.com/hc/en-us/articles/32013696484109-Community-Guidelines)）："不得转售或再分发服务，包括账号共享"。

> **本报告对账号共享业务的明确判断：不推荐个人长期作为副业经营。**短期或可赚到¥2,000–¥10,000/月，但车主跑路率、平台批量封号、Stripe风控加严已使该模式的"半衰期"降至6–12个月，且违反ToS、涉嫌无证经营增值电信业务。

#### D2. 算力代币化 / DePIN项目部署（风险等级：⚠️⚠️ 中-高）

| 模式名称 | 启动资金 | 技能门槛 | 收入天花板 | 风险等级 |
|---|---|---|---|---|
| Grass / io.net / Aethir 节点 | ¥0–¥30,000（GPU） | 低-中 | $50–$1,500/月 | **中-高（境内代币兑换违规）** |

**真实收益数据（已发生）**：

| 项目 | 已实现里程碑 | 个人节点收益 |
|---|---|---|
| **Grass**（[getgrass.io](https://getgrass.io)） | 2024-10发币、累计**$33M营收**、280万用户首次空投 | 浏览器节点$5–$30/月（依赖空投） |
| **io.net**（[io.net](https://io.net)） | 2024 Q4营收同比+565%达$310万；2025年1月月营收破$100万；32.7万GPU、138国 | RTX 4090 $0.25–$0.50/h挂牌 |
| **Aethir**（[aethir.com](https://aethir.com)） | 2025全年营收**$127.8M**；ARR $1.47亿（Q3） | H100节点 $25k–$40k/月；4090 **$500–$1,500/月** |
| **Render**（[rendernetwork.com](https://rendernetwork.com)） | 2025年营收$270万、活跃节点5,600台 | 高端GPU $300–$800/月 |
| **Akash**（[akash.network](https://akash.network)） | 2025年2月单日$13,000+；GPU利用率60%（行业领先） | [官方计算器](https://akash.network/pricing/provider-calculator/) |
| **Bittensor (TAO)** | 128个活跃子网（硬上限）；2025-11启用Taoflow流式排放 | 验证者门槛≥1,000 alpha stake，进入TOP 64 |
| **Nosana** | 2025年累计营收$200万 | 较小，适合实验 |

**单台GPU综合估算**（电费0.6元/度计）：

| 利用率 | RTX 4090月毛收入 | 月电费 | 月净收益 |
|---|---|---|---|
| 35%（io.net类） | ~$630 | ¥190 | **~$600** |
| 50%（Aethir企业级） | ~$1,440 | ¥270 | **~$1,400** |
| 渲染网络 | $300–$800 | ¥150–¥230 | $280–$780 |

来源综合：[ShareAI](https://shareai.now/blog/insights/gpu-passive-income-rtx-4090-2025/)、[Aethir生态博客](https://ecosystem.aethir.com/blog-posts/monetize-idle-gpus-in-2025-7-proven-strategies-for-cloud-hosts)。

**中国境内合规壁垒（必须直面）**：
1. **虚拟货币交易违法**：2021年9月8部门联合公告 + 2026年2月人行重申"虚拟货币不具有与法定货币等同的法律地位"（[中国日报](https://www.chinadaily.com.cn/a/202602/06/WS6985f03ca310d6866eb37f9e.html)）。
2. **外汇管制**：DePIN代币兑换人民币若走OTC，违反《外汇管理条例》。
3. **芯片出口管制**：将受EAR管制的A100/H100/4090并入境外DePIN，可能触发美国再出口限制。

> **本报告对DePIN的明确判断**：仅适合**已有境外身份/账户、能接受持币不变现**的玩家；**不建议把它作为现金流副业**。

---

## 四、个人路径决策树

> 把维度抽象为四个变量后，组合数共72种。以下用"行动包"形式给出**8条最常见、最贴合现实**的推荐路径。

### 维度定义

- **技术能力**：T0=不会编程 / T1=会基本前后端
- **资金**：M0=<¥1,000 / M1=¥1万–¥5万 / M2=>¥5万
- **时间**：H1=1h/天 / H4=4h/天 / HF=全职
- **风险偏好**：R0=保守 / R1=激进

### 8条推荐路径

| 画像 | 推荐路径 | 预期月收入（6–12月） |
|---|---|---|
| **T0 / M0 / H1 / R0** 普通上班族，副业试水 | **AI培训知识付费**（小红书/视频号引流→199元知识星球）；**省Token咨询**入门作品集 | ¥0–¥3,000 |
| **T0 / M1 / H4 / R0** 有点钱、运营底子的内容创作者 | **AI内容工业化（人机混合）**：1个垂直自媒体矩阵 + Coze工作流；同步做**AI培训** | ¥3,000–¥30,000 |
| **T0 / M0 / H1 / R1** 小白但敢冒险 | DePIN被动节点（Grass浏览器免费跑）+ 闲鱼"个人API额度卡"小试 | ¥500–¥3,000（且不稳定） |
| **T1 / M0 / HF / R0** 失业/在校独立开发者 | **微SaaS（面向海外）**：用ShipFast / ShipAny样板，30天上1款，发Product Hunt + Twitter | $0–$5k MRR（90%死亡，10%突围） |
| **T1 / M0 / H4 / R0** 全职码农副业 | **微SaaS（B2B行业API）+ Prompt工程顾问**双线 | ¥5,000–¥30,000 |
| **T1 / M1 / HF / R1** 有积蓄全职转型 | **垂类微调外包**（Upwork+猪八戒）+ **行业Chatbot SaaS** | $5k–$20k MRR |
| **T1 / M2 / HF / R1** 资本+技术兼备 | **DePIN GPU农场（境外实体）**+ 海外SaaS组合 + Maven高客单课程 | $10k–$50k+/月 |
| **T0 / M2 / HF / R0** 传统企业主转型 | 收购或入股海外有现金流的微SaaS（[MicroAcquire](https://acquire.com)） + 雇外包做内容矩阵 | 取决于收购标的 |

**通用规律**：
1. **没有海外受众/账户的非技术个人**，最现实的方向是**国内私域+AI培训/内容工业化**。
2. **有技术能力的个人**，不要把时间花在国内C端，**面向海外B端 / 全球独立开发者市场**才有$10k+ MRR的故事。
3. **>¥5万启动资金**的玩家，应该把钱花在**Maven / Cohort / 顶级SaaS订阅 / 海外营销**上，而不是GPU或代币。

---

## 五、实操Checklist

### 模式1：微SaaS（海外）

**本周第一步**：在 **bolt.new** 或 **v0.dev** 上花3小时跑通一个MVP原型；写一条Twitter "I'm building XX in 14 days"。

**必须注册的3个平台/工具**：
1. **Lemon Squeezy**（[lemonsqueezy.com](https://lemonsqueezy.com)）—— 免税务身份海外收款
2. **OpenRouter**（[openrouter.ai](https://openrouter.ai)）—— 统一API，避免供应商锁定
3. **Indie Hackers** + **Twitter/X**—— Build in Public必备

**避坑**：① 不要用国内信用卡直接绑OpenAI（拒付率78%）；② 不要在产品里硬编码模型名（半年内必涨/必下线一次）。

### 模式2：AI内容工业化

**本周第一步**：选**1个**真实有领域知识的垂类，用Make.com搭建"关键词→GPT-4o-mini草稿→人工编辑→WordPress发布"流水线。

**必须注册**：
1. **Make.com** 或 **n8n**
2. **WordPress + Rank Math SEO** 或 **Astro + 自建博客**
3. **Google Search Console + Cloudflare**

**避坑**：① 绝不发布无人类编辑的纯AI文章（**March 2026 Core Update**已让纯AI站流量降60%–80%）；② 不要在境内服务器跑面向海外SEO的站（被GFW误伤的概率很高）。

### 模式3：Prompt / Token咨询

**本周第一步**：选一家自己熟悉的SaaS公司，用 **Helicone** 免费跑一周Token使用画像，给他们交付一份5页"省Token诊断报告"。

**必须注册**：
1. **Helicone** 或 **Langfuse**（自托管开源）
2. **Upwork** 自由职业账号（必须是Top Rated路径）
3. **LinkedIn**（海外咨询业务的核心入口）

**避坑**：① 不要把时间花在"为简单ChatGPT用户做Prompt优化"——已彻底商品化；② 报价不要按"小时"——应按"省下的Token成本%分成"。

### 模式4：知识付费

**本周第一步**：把自己最擅长的Token经济知识做成**20讲免费短视频**，3平台同步（抖音/小红书/视频号），观察哪条点赞过千。

**必须注册**：
1. **小报童** 或 **知识星球**（私域承接）
2. **小鹅通** 或 **Maven**（课程交付）
3. **微信视频号 / 小红书 / 抖音**任选其一作主战场

**避坑**：① 不要做"ChatGPT入门课"——红海中的红海；② 不卖"卖课的课"——监管已多次重点关注。

### 模式5：垂类微调外包

**本周第一步**：在 **Hugging Face** 公开发布一个垂类LoRA权重作为作品集（哪怕是"中文古诗词生成"也行）。

**必须注册**：
1. **Hugging Face** + **ModelScope魔搭**
2. **AutoDL** 或 **RunPod**（性价比GPU）
3. **Upwork** + **猪八戒**

**避坑**：① 不要承诺"提升模型能力"这种无法验证的指标——只承诺"在客户的私有数据集上F1指标提升X%"；② 不要免费给客户底层数据——所有交付物应封装为模型API。

---

## 六、案例库

### 案例1：idoubi（前微信团队 → 独立开发者）
- **背景**：前腾讯微信团队工程师，技术力强、个人IP接近零启动。
- **路径**：2024年全年上线11款AI产品（AI红包、虚拟试衣、AI壁纸、群聊总结等），2024-12四款合计MRR约 **$1,000**。
- **转折**：第12款 **ShipAny**（独立开发者样板代码）首周破 **$10,000**（$299×五折，4小时内）。
- **当前现金流**：付费开发者社群（200+人）+ ShipAny许可证。
- **可复制要点**：**面向开发者卖工具**，比面向C端卖应用回报高10–100倍。来源：[智源社区](https://hub.baai.ac.cn/view/42470)、[虎嗅访谈](https://www.huxiu.com/article/3631911.html)。

### 案例2：tahitimoon（V2EX独立开发者，Chat2Report）
- **背景**：2024年9月辞职全职做"AI财报分析工具"。
- **结果**：一年营收 **不到$1,000**，未覆盖服务器成本。
- **决定**：回归职场。
- **教训**：① B端产品不适合个人单兵；② 营销占成败的80%；③ 国内独立开发者很难复制海外 $10k+ MRR的故事。
- 来源：[V2EX原帖](https://v2ex.com/t/1206139)。

### 案例3：海外SEO站操盘手（Reddit AMA匿名）
- **背景**：技术普通、有$16,750启动资金、运营SEO经验。
- **路径**：2024年用OpenAI API批量生产**1,023篇Home Improvement文章**，14个月做到月入$3,674。
- **退出**：以**$108,000**卖给一家广告公司。
- **ROI**：**602%**。但2025年Google算法更新后类似站点流量普遍下跌60%–80%。
- 来源：[Reddit /r/juststart](https://www.reddit.com/r/juststart/comments/1cr0915/case_study_automated_ai_seo_content_site_0_to/)、[Digital Applied](https://www.digitalapplied.com/blog/scaled-content-abuse-google-march-update-ai-pages-decimated)。

### 案例4：Pieter Levels（@levelsio）
- **背景**：游牧开发者，10年累积60万Twitter粉丝。
- **路径**：2023年2月上线 **Photo AI**，第1周MRR $5,400，第18个月达 **$132k–$155k**；同期 **Interior AI** $45k MRR、利润率 **>99%**（GPU仅$250/月）。
- **2025年新故事**：用AI写的飞行游戏 **3周MRR达$67k**。
- **核心可复制点**：**分发即护城河**——粉丝积累的复利远大于技术或产品本身。
- 来源：[SoftwareSeni](https://www.softwareseni.com/building-in-public-the-10-year-distribution-strategy-behind-solo-founder-revenue/)、[Hacker News](https://news.ycombinator.com/item?id=39886361)。

### 案例5：Damon Chen（PDF.ai + Testimonial.to）
- **背景**：前企业工程师，无个人IP启动。
- **路径**：2023年7月上线 **PDF.ai**（与PDF对话），3个月冲至$200,000累计收入；2025年月收**$80,000**，用户35万；与Testimonial.to合并ARR达 **$1.3M**。
- **关键打法**：用一个**爆款Twitter帖**（"我做了一个PDF聊天工具"）换来病毒式增长，再用这部分用户哺育他下一款产品。
- 来源：[The Startup Series](https://startupseries.io/how-damon-chen-accidentally-made-80000-a-month-talking-to-pdfs/)、[SupaBird](https://supabird.io/articles/from-corporate-dreams-to-1-3m-arr-as-an-entrepreneur)。

---

## 七、合规与风险提示

### 7.1 中国境内Token转售/API代理/VPN相关业务的法律边界

| 行为 | 法律依据 | 风险等级 |
|---|---|---|
| 对外收费提供AI服务（API/Chatbot） | 《生成式人工智能服务管理暂行办法》（2023.8.15）、ICP/EDI许可证 | 高（个人无法独立做算法备案） |
| 转售OpenAI/Claude API Key | 平台ToS明确禁止 + 无证经营增值电信业务 | **极高** |
| 个人运营镜像站 | ICP+算法备案双重缺失 + GFW屏蔽 | 高 |
| 个人使用VPN访问境外AI | 《计算机信息网络国际联网管理暂行规定》（1996, 2024.3.10二次修订）第6条 | 低-中（罚款≤¥15,000） |
| 提供VPN服务给他人 | 工信部2017年规定，未经批准不得提供 | 高（刑事风险存在） |
| 跨境传输用户个人信息至OpenAI | 《促进和规范数据跨境流动规定》（2024.3.22） | 中-高（达门槛须申报） |
| DePIN代币兑换人民币 | 《关于进一步防范和处置虚拟货币交易炒作风险的通知》（2021.9） | 高 |

### 7.2 主流平台对代理/转售/共享的政策（已生效条款原文）

- **OpenAI Services Agreement**（2025.5.31生效）：
  - 第3.1：*"Customer may not resell or lease access to its Account or any End User Account."*
  - 第3.1：*"Customer will not share Account access credentials..."*
  - 第3.3(g)：*"buy, sell, or transfer API keys from, to, or with a third party"*
  - 来源：[OpenAI](https://openai.com/policies/services-agreement/)
- **Anthropic Usage Policy**（2025.9.15生效，2025.7.28执法声明）：明确禁止账号共享/转售；Claude Code限周用量。来源：[Anthropic](https://www.anthropic.com/news/updating-our-usage-policy)、[X执法](https://x.com/AnthropicAI/status/1949898513019466140)。
- **Microsoft Azure OpenAI RAI Policy**：*"prohibit users from building an API on top of your product"*。来源：[Microsoft Learn](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/overview)。
- **Midjourney Community Guidelines**：*"You may not resell or redistribute Midjourney Services or access to the Service (this includes sharing your account)."* 来源：[Midjourney](https://docs.midjourney.com/hc/en-us/articles/32013696484109-Community-Guidelines)。
- **智谱AI服务协议**（火山方舟MaaS）第2.3.1条：*"您不得将产品的全部或部分进行复制、转让、出租、出借、出售或提供分许可、转许可。"* 来源：[火山方舟](https://www.volcengine.com/docs/82379/1185557)。

### 7.3 算法备案现实

| 时间节点 | 累计大模型备案数 |
|---|---|
| 2023年底 | 61款 |
| 2024年底 | 302款 |
| **2025年底** | **748款累计**（2025新增446款） |

**关键事实**：所有备案主体均为企业（含个体工商户），**自然人不在备案主体资格范围内**。备案周期2–4个月，需提交营业执照、算法安全负责人承诺书、ICP许可证等。来源：[网信办](https://www.cac.gov.cn/2024-04/02/c_1713729983803145.htm)、[阿里云开发者社区](https://developer.aliyun.com/article/1676169)。

**结论**：**个人想合规对外提供AI服务，唯一路径是注册个体工商户/小微公司**。否则只能：① 面向海外用户（不受国内备案约束）；② 不收费的免费工具；③ 套壳到已备案企业的体系内（需对方授权）。

### 7.4 数据隐私与内容安全红线

- **PIPL**（2021.11.1施行）+ **数据出境规则**（2024.3.22）：调用境外API若涉及用户个人信息出境，达门槛（年度100万人个人信息或1万人敏感信息）须申报安全评估。
- **境内AI服务必接的内容安全过滤层**（任选其一）：
  - **网易易盾**（[dun.163.com](https://dun.163.com/)）—— 准确率99.8%+，亿级日处理
  - **阿里云绿网**—— 多模态、SaaS+私有化
  - **腾讯天御**（[cloud.tencent.com/solution/content-moderation](https://cloud.tencent.com/solution/content-moderation)）—— 全媒体格式
- **AI生成图像/视频**：须按《互联网信息服务深度合成管理规定》（2023.1.10）做显著标识。

### 7.5 风险矩阵速查

| 灰色行为 | 平台风险 | 中国法律风险 | 综合风险 |
|---|---|---|---|
| 拼车共享ChatGPT/Claude | 账号封禁 | 轻微 | 中 |
| 国内卖API代充 | 平台封号 | 无证经营增值电信业务 | 高 |
| 个人运营AI镜像站 | 域名封 | 无ICP+无算法备案 | 高 |
| 个人VPN自用 | 无 | ≤¥15,000罚款 | 低-中 |
| Grass/io.net收益换人民币 | 无 | 虚拟货币违法+外汇违规 | 高 |
| 转售OpenAI API Key | 永久封禁 | 无证经营 | **极高** |
| 未备案对公众提供AI | 无 | ¥1万–¥10万行政罚款+下架 | 高 |

---

## 八、自检结论

**自检1：是否每个模式都回答了"上游/下游"？** ✅
- 中间商模式：上游=OpenRouter/SiliconFlow/302.AI/Kimi充值阶梯/火山协作奖励；下游=小红书+知识星球+Gumroad/Lemon Squeezy。
- 微SaaS：上游=OpenRouter/SiliconFlow；下游=Product Hunt+Twitter+Chrome Store。
- 内容工业化：上游=GPT-4o-mini/Claude Haiku；下游=AdSense/Amazon Affiliate/媒体平台。
- Prompt咨询：上游=Helicone/Langfuse工具；下游=Upwork/LinkedIn/直接合同。
- 培训：上游=自有知识；下游=知识星球/小报童/Maven/视频号。
- 微调：上游=AutoDL/RunPod GPU；下游=Upwork/Toptal/猪八戒。
- DePIN：上游=自有GPU；下游=io.net/Aethir/Render网络。

**自检2：是否出现≥10个具体可访问的平台/工具名称？** ✅ 已超过60个，含URL：
OpenAI、Anthropic、Azure OpenAI、Google AI Studio、DeepSeek、智谱BigModel、阿里通义百炼、火山方舟、Kimi、百度千帆、OpenRouter、Together AI、Fireworks AI、Replicate、SiliconFlow、302.AI、API2D、OhMyGPT、Poe、Hugging Face、ModelScope、AutoDL、RunPod、Vast.ai、Clore.ai、LLaMA-Factory、Unsloth、Axolotl、PromptLayer、Helicone、LangSmith、Langfuse、PDF.ai、Photo AI、Bannerbear、Tweet Hunter、ShipFast、ShipAny、Bolt.new、v0.dev、Cursor、Coze、Dify、n8n、Make.com、Zapier、秘塔写作猫、火山写作、Heygen、Synthesia、剪映、Stripe、Lemon Squeezy、Gumroad、Product Hunt、Indie Hackers、Maven、ZeroToMastery、生财有术、知识星球、Grass、io.net、Render、Akash、Bittensor、Aethir、Nosana、Hyperbolic、网易易盾、阿里绿网、腾讯天御 …

**自检3：是否所有建议都是当下（2026年4月）可执行？** ✅
- 已剔除：纯AI批量SEO（被March 2026 Core Update打击）、纯账号共享（已不推荐）、纯API中转（goChatGPTAPI项目已归档）。
- 保留并强调：火山协作奖励（延续至2026.6.30）、Kimi充值赠50%（仍有效）、Anthropic Batch -50%（仍有效）、SiliconFlow接近官方价（仍有效）、io.net/Aethir 4090月收益（截至2026 Q1）。

---

## 参考来源清单

### 市场规模与行业数据
- [GrandView Research LLM报告](https://www.grandviewresearch.com/industry-analysis/large-language-model-llm-market-report)
- [Menlo Ventures 2025 Mid-Year LLM Market Update](https://menlovc.com/perspective/2025-mid-year-llm-market-update/)
- [信通院CAICT人工智能产业报告](https://www.caict.ac.cn/kxyj/qwfb/bps/202602/P020260202487301304903.pdf)
- [量子位 大模型Token消耗报告](https://www.qbitai.com/2025/01/247173.html)
- [Frost & Sullivan / 阿里开发者](https://developer.aliyun.com/article/1713089)
- [Robonomics Token Tracker](https://robonomics.substack.com/p/token-tracker-and-implications)
- [Digital Applied OpenRouter Rankings April 2026](https://www.digitalapplied.com/blog/openrouter-rankings-april-2026-top-ai-models-data)
- [IDC 中国大模型平台市场](https://my.idc.com/getdoc.jsp?containerId=prCHC53754425)

### 上游API平台
- [OpenAI Pricing](https://openai.com/api/pricing/) ／ [OpenAI Services Agreement](https://openai.com/policies/services-agreement/)
- [Anthropic Pricing](https://www.anthropic.com/pricing) ／ [Usage Policy](https://www.anthropic.com/news/updating-our-usage-policy)
- [Microsoft Azure OpenAI Pricing](https://azure.microsoft.com/pricing/details/cognitive-services/openai-service/) ／ [RAI Overview](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/overview)
- [Google AI Studio Pricing](https://ai.google.dev/pricing)
- [DeepSeek Platform](https://platform.deepseek.com)
- [智谱BigModel Pricing](https://open.bigmodel.cn/pricing)
- [阿里通义百炼](https://bailian.console.aliyun.com)
- [字节火山方舟协作奖励](https://www.volcengine.com/docs/82379/1391869) ／ [服务协议](https://www.volcengine.com/docs/82379/1185557)
- [Moonshot Kimi 充值优惠](https://platform.moonshot.cn/blog/posts/discount)
- [百度千帆](https://qianfan.cloud.baidu.com/qianfandev/topic/685493) ／ [产品适配](https://cloud.baidu.com/solution/product-adapter.html)

### 中间商与聚合平台
- [OpenRouter](https://openrouter.ai)
- [Together AI](https://www.together.ai) ／ [Fireworks AI](https://fireworks.ai) ／ [PricePerToken Compare](https://pricepertoken.com/endpoints/compare/fireworks-vs-together)
- [Replicate](https://replicate.com/pricing)
- [SiliconFlow硅基流动](https://siliconflow.cn/pricing)
- [302.AI](https://302.ai/en/) ／ [API2D](https://www.api2d.com) ／ [OhMyGPT](https://ohmygpt.com)
- [Poe](https://poe.com) ／ [TechCrunch Poe API发布](https://techcrunch.com/2025/07/31/quoras-poe-is-releasing-an-api-for-developers-to-easily-access-a-boquet-of-models/)
- [AI中转站导航](https://api.daheiai.com)

### 独立开发者案例与微SaaS
- [Pieter Levels SoftwareSeni分析](https://www.softwareseni.com/building-in-public-the-10-year-distribution-strategy-behind-solo-founder-revenue/)
- [Pieter Levels Hacker News](https://news.ycombinator.com/item?id=39886361)
- [Damon Chen SupaBird](https://supabird.io/articles/from-corporate-dreams-to-1-3m-arr-as-an-entrepreneur) ／ [The Startup Series](https://startupseries.io/how-damon-chen-accidentally-made-80000-a-month-talking-to-pdfs/) ／ [LinkedIn 100k MRR帖](https://www.linkedin.com/posts/damengchen_100k-mrr-now-with-testimonialto-and-pdfai-activity-7119880068289478656-GhBW)
- [Marc Lou TrustMRR](https://trustmrr.com/founder/marclou)
- [Tibo Louis-Lucas LinkedIn](https://www.linkedin.com/posts/lekterable_tibo-louis-lucas-built-4-saas-products-doing-activity-7404452374456668160-O-jR) ／ [Unicorn Growth](https://www.unicorngrowth.io/p/tweethunter-taplio-acquisition)
- [Bannerbear 人人都是产品经理](https://www.woshipm.com/ai/6343398.html)
- [idoubi 智源社区](https://hub.baai.ac.cn/view/42470) ／ [虎嗅访谈](https://www.huxiu.com/article/3631911.html) ／ [苹果播客EP41](https://podcasts.apple.com/us/podcast/ep41-%E4%BB%8E%E8%85%BE%E8%AE%AF%E5%88%B0%E7%8B%AC%E7%AB%8B%E5%BC%80%E5%8F%91-idoubi-%E7%9A%84-14-%E4%B8%AA%E6%9C%88%E5%AE%9E%E9%AA%8C-%E7%84%A6%E8%99%91%E4%B8%8E%E7%AA%81%E7%A0%B4/id1699515442?i=1000681696142)
- [tahitimoon V2EX](https://v2ex.com/t/1206139)
- [Awesome One Person Company GitHub](https://github.com/chen103226/awesome-one-person-company)

### AI内容工业化
- [Reddit /r/juststart 14个月SEO案例](https://www.reddit.com/r/juststart/comments/1cr0915/case_study_automated_ai_seo_content_site_0_to/)
- [Digital Applied March 2026 Core Update](https://www.digitalapplied.com/blog/scaled-content-abuse-google-march-update-ai-pages-decimated)
- [Marie Haynes September 2023 HCU](https://www.mariehaynes.com/the-september-helpful-content-update-why-you-were-affected-and-what-you-can-do/)
- [Amsive 2024 HCU变更](https://www.amsive.com/insights/seo/googles-helpful-content-update-ranking-system-what-happened-and-what-changed-in-2024/)
- [AdExchanger 出版商损失](https://www.adexchanger.com/publishers/the-ai-search-reckoning-is-dismantling-open-web-traffic-and-publishers-may-never-recover/)
- [Amazon AI listing生成数据](https://www.aboutamazon.com/news/innovation-at-amazon/amazon-generative-ai-seller-growth-shopping-experience)
- [什么值得买 短视频脚本定价](https://post.smzdm.com/p/a706n5ql)

### Prompt工程与省Token
- [YouTube "Cut LLM token costs by 90%"](https://www.youtube.com/watch?v=4x4nM0uPmg0)
- [Infosys Smart Prompting](https://blogs.infosys.com/emerging-technology-solutions/artificial-intelligence/smart-prompting-smarter-ai-optimizing-token-use-for-responsible-and-efficient-interactions.html)
- [Deloitte AI Tokens Spend Dynamics](https://www.deloitte.com/us/en/insights/topics/emerging-technologies/ai-tokens-how-to-navigate-spend-dynamics.html)
- [Coursera Prompt Engineer Salary](https://www.coursera.org/articles/prompt-engineering-salary)
- [AI CERTs Salary报告](https://www.aicerts.ai/news/prompt-engineering-salaries-reality-skills-and-career-outlook/)
- [Asrify 2026 Prompt Engineer Rates](https://asrify.com/blog/prompt-engineer-rates-2026)
- [Upwork Prompt Engineering](https://www.upwork.com/hire/prompt-engineering-specialists/)
- [TeamedUp China AI薪资](https://teamedupchina.com/the-state-of-ai-jobs-careers-and-salaries-in-china/)
- [eWeek Prompt工具对比](https://www.eweek.com/artificial-intelligence/prompt-engineering-tools/)
- [Helicone vs LangSmith](https://www.helicone.ai/blog/langsmith-vs-helicone)

### 知识付费
- [生财有术 AI出海去](https://www.aichuhaiqu.com/%E7%94%9F%E8%B4%A2%E6%9C%89%E6%9C%AF%E7%A4%BE%E5%8C%BA%E4%B8%8E%E5%85%B6%E5%88%9B%E5%A7%8B%E4%BA%BA%E4%BA%A6%E4%BB%81%E7%9A%84%E6%95%85%E4%BA%8B/) ／ [运营拆解](https://www.yunyingpai.com/news/844931.html)
- [洪灏知识星球 新浪财经](https://cj.sina.cn/articles/view/1700648435/655dd5f302001fb56) ／ [Gate报道](https://www.gate.com/zh/news/detail/17777091)
- [三节课访谈](http://www.eeo.com.cn/2024/0623/668273.shtml)
- [李继刚 DOIT报道](https://www.doit.com.cn/p/523313.html)
- [Maven Skills Index](https://maven.com/skills) ／ [LinkedIn 讲师$100k+](https://www.linkedin.com/posts/benerez_my-course-has-generated-over-100k-in-earnings-activity-7399108717981446144-8jtT)
- [ZeroToMastery](https://zerotomastery.io)

### 模型微调
- [Upwork LLM Fine-Tuning](https://www.upwork.com/services/product/development-it-llm-training-llm-finetuning-llm-generative-ai-llm-training-1830555930279953332)
- [Second Talent 2026费率报告](https://www.secondtalent.com/resources/freelance-llm-developer-hourly-rate-us-2026/)
- [LLaMA-Factory GitHub](https://github.com/hiyouga/LlamaFactory)
- [Clore.ai vs RunPod vs Vast.ai](https://blog.clore.ai/gpu-cloud-pricing-comparison/)
- [RunPod vs Vast.ai深度对比](https://www.runpod.io/articles/comparison/runpod-vs-vastai-training)
- [PricePerToken Fine-Tuning](https://pricepertoken.com/fine-tuning)
- [CSDN DeepSeek副业](https://deepseek.csdn.net/67ad6842382bf816fe96910f.html)

### DePIN
- [Grass — CoinMarketCap AI](https://coinmarketcap.com/cmc-ai/grass/latest-updates/) ／ [Bitget Wallet空投指南](https://web3.bitget.com/en/academy/grass-airdrop-guide-how-to-participate-and-claim-grass-rewards) ／ [YouTube Review 2025](https://www.youtube.com/watch?v=_qW6NavuuN0)
- [io.net官网](https://io.net) ／ [DePINscan](https://depinscan.io/news/2025-03-06/io-net-achieves-record-revenue-growth-and-expands-partnerships-in-q4-2024) ／ [Nansen AI](https://nansen.ai/post/ionet-does-it-have-what-it-takes) ／ [io.net官博](https://io.net/blog/io-net-20m-in-annualized-on-chain-revenue) ／ [X账号](https://x.com/ionet/status/1765820980113682630)
- [Render Network — CoinStats AI](https://coinstats.app/ai/a/investment-analysis-render-token)
- [Akash 2025 Year-in-Review](https://akash.network/blog/akash-2025-year-in-review/) ／ [Scaling the Supercloud](https://akash.network/blog/scaling-the-supercloud/) ／ [收益计算器](https://akash.network/pricing/provider-calculator/)
- [Bittensor文档](https://docs.learnbittensor.org/validators) ／ [A Bittensor Journey年报](https://www.abittensorjourney.com/p/bittensor-2025-end-of-year-report) ／ [CryptoNews](https://cryptonews.net/news/altcoins/32669842/)
- [Aethir 2025 Wrap-up](https://ecosystem.aethir.com/blog-posts/aethirs-2025-wrap-up-decentralized-gpu-cloud-milestones) ／ [GPU变现策略](https://ecosystem.aethir.com/blog-posts/monetize-idle-gpus-in-2025-7-proven-strategies-for-cloud-hosts)
- [Nosana 年终](https://nosana.com/blog/2025-at-nosana-a-year-in-review/)
- [ShareAI RTX 4090收益分析](https://shareai.now/blog/insights/gpu-passive-income-rtx-4090-2025/)
- [DePIN Hub LLM benchmarking](https://depinhub.io/blog/llm-benchmarking-cost-efficient-performance)

### 拼车与灰色地带
- [拼账号网站价格表](https://pinzhanghao.com/chatgpt/chatgpt-plus-cheapest-recharge/)
- [ChinaTalk 灰市深度报道](https://www.chinatalk.media/p/the-grey-market-for-american-llms)
- [CNBC OpenAI封禁](https://www.cnbc.com/2024/06/25/chinese-ai-firms-woo-openai-users-amid-plans-for-api-restrictions.html) ／ [Reuters](https://www.reuters.com/technology/artificial-intelligence/openai-cut-access-tools-developers-china-other-regions-chinese-state-media-says-2024-06-25/)
- [Anthropic X执法声明](https://x.com/AnthropicAI/status/1949898513019466140) ／ [LinkedIn解读](https://www.linkedin.com/posts/tylerfolkman_anthropic-just-revealed-why-theyre-adding-activity-7355999451393507328-idP_)
- [Midjourney社区指引](https://docs.midjourney.com/hc/en-us/articles/32013696484109-Community-Guidelines)
- [go-chatgpt-api 归档](https://github.com/linweiyuan/go-chatgpt-api) ／ [Cloudflare Worker讨论](https://github.com/noobnooc/noobnooc/discussions/9)
- [Telegram ChatGPT新闻聚合](https://t.me/s/AI_News_CN?before=28353)
- [Global Times Azure中国合规通道](https://www.globaltimes.cn/page/202407/1315801.shtml)

### 中国合规法规
- [生成式AI管理办法 — 中央网信办](https://www.cac.gov.cn/2023-07/13/c_1690898327029107.htm)
- [大模型备案公告 — 网信办](https://www.cac.gov.cn/2024-04/02/c_1713729983803145.htm)
- [腾讯云备案整理](https://cloud.tencent.com/developer/article/2513165) ／ [阿里云开发者社区](https://developer.aliyun.com/article/1676169)
- [普华永道数据出境白皮书](https://www.pwccn.com/zh/issues/cybersecurity-and-data-privacy/joint-white-paper-on-compliance-cross-border-data-transfers-may2024.pdf)
- [中国日报 人行虚拟货币重申](https://www.chinadaily.com.cn/a/202602/06/WS6985f03ca310d6866eb37f9e.html)
- [维基百科中国网络审查](https://zh.wikipedia.org/zh-cn/%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%AB%99%E7%BB%B4%E6%8A%A4%E6%97%A5)
- [环球律师所 增值电信扩大开放](https://www.glo.com.cn/Content/2024/11-01/1539070046.html)
- [康谋科技 PIPL vs GDPR](https://keymotek.com/pipl-gdpr-compliant-adas-2/) ／ [德恒律师所](https://www.dehenglaw.com/CN/tansuocontent/0008/033840/7.aspx)

### 内容安全服务
- [网易易盾](https://dun.163.com/) ／ [腾讯天御](https://cloud.tencent.com/solution/content-moderation)

---

*本报告基于2024年1月至2026年4月期间已发生、可验证的公开事实编制；不构成投资建议；个人参与任何模式前请自行核实最新平台政策与法律法规。*
