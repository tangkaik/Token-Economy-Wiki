# Token Economy Wiki - Schema

> 本Wiki采用Karpathy的LLM Wiki方法论，专注于AI Token经济领域的知识管理。

## 目录结构

```
Token-Economy-Wiki/
├── raw/              # 原始来源（访谈/报告/文章），只放原始材料
├── queries/          # 调研产物（基于raw整理的分析）
├── concepts/         # 概念定义（什么是Token、什么是中间商等）
├── entities/         # 实体（平台、公司、产品）
├── comparisons/      # 对比分析（平台对比、模式对比）
├── _meta/            # 元数据
├── index.md          # 入口文件
├── log.md            # 更新日志
└── SCHEMA.md         # 本文件
```

## 命名规范

### 文件命名
- 使用英文或中文拼音
- 单词间用 `-` 连接
- 版本号用 `_v1`, `_v2` 后缀

### 示例
```
openai-api-pricing_2025.md
kimi-api-shilu-fenxi.md
token-zhongjian-shang-duibi.md
```

## 元数据规范

每个概念/实体页面顶部应包含：

```yaml
---
type: concept|entity|comparison
tags: [token, api, middleman]
created: 2026-04-27
updated: 2026-04-27
source: raw/xxx.md
---
```

## 概念页面结构

```markdown
# 概念名称

## 定义
> 一句话定义

## 详细说明
- 背景
- 原理
- 运作方式

## 关键数据
| 指标 | 数据 |
|------|------|

## 参考来源
- [来源名称](URL)
```

## 实体页面结构

```markdown
# 实体名称

## 基本信息
- **官网**: URL
- **成立时间**: YYYY
- **总部**: 地点

## 核心产品/服务

## Token相关业务

## 商业模式

## 关键数据

## 参考来源
```

## 对比页面结构

```markdown
# 对比主题

## 对比维度

| 维度 | 实体A | 实体B | 实体C |
|------|-------|-------|-------|
| 价格 | ... | ... | ... |
| 规模 | ... | ... | ... |

## 分析结论

## 参考来源
```

## 质量标准

1. **可溯源**：每个知识点必须有来源
2. **时效性**：标注数据的时间范围
3. **一致性**：同概念多处引用应保持一致
4. **完整性**：核心问题必须回答Who/What/How/Why
