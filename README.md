# 出海文案本地化体检工具

> Localization Health Report Generator
>
> 零成本 · 免 API Key · 5 步完成中英文案本地化质量评估

## 在线使用

https://breezelance.github.io/localization-checker/

## 工作原理

```
输入中英文案 → 生成结构化评测 Prompt → 一键打开 DeepSeek/豆包/Claude
  → AI 返回评测结果 → 粘贴回工具 → 自动解析渲染为可视化报告
```

### 为什么不需要 API Key？

工具生成专业的 6 维评测 Prompt（内含完整评分标准和输出格式要求），
用户将其粘贴到**自己已有账号的免费 AI**（DeepSeek 免费版 / 豆包免费版 / Claude）中执行评测，
再将 AI 返回的结果粘贴回工具，工具自动解析并渲染为可视化评分报告。

> **用户花的是 AI 平台已有的免费额度，不需要额外 API Key，零成本。**

## 6 维评分体系

| 维度 | 权重 | 检查内容 |
|------|------|----------|
| **准确性** Accuracy | 30% | 忠实传达原文信息，无遗漏/曲解 |
| **流畅度** Fluency | 25% | 译文自然地道，读起来不像翻译 |
| **术语处理** Terminology | 15% | 专业术语准确且一致 |
| **语境适配** Context | 15% | 匹配目标场景的语域和风格 |
| **文化敏感度** Culture | 10% | 处理文化差异/隐喻/习语 |
| **格式保持** Format | 5% | 段落结构、标点、排版保持 |

## 内置 Demo

3 个典型出海场景的反面案例，附带真实 Claude 评测结果：

| Demo | 场景 | 得分 | 典型问题 |
|------|------|------|----------|
| 电商文案 | 降噪耳机 | 1.6 | "自来水→tap water""交个朋友→make friends""耳塞→earplugs" |
| SaaS 官网 | AI PPT 工具 | 2.5 | "招商→business attraction""路演→roadshows" |
| 社媒文案 | 小红书种草 | 1.2 | "姐妹们→Sisters""必冲→must rush""自来水→pure tap water" |

## 项目价值

- 面向 AI 产品运营 / 出海内容运营岗位的作品集项目
- 展示产品设计能力：将评测框架落地为可交互 Web 工具
- 展示 Prompt Engineering 能力：结构化评测 Prompt 的设计和优化
- 展示前端能力：报告解析、可视化渲染

## 技术栈

纯静态 HTML/CSS/JavaScript，GitHub Pages 部署，零后端。

## 配套项目

- [翻译对比评测](https://github.com/BreezeLance/translation-benchmark) — 4 场景 × 6 维评分体系的理论基础
- [产品调研](https://github.com/BreezeLance/ai-product-research) — 10 款海外 AI 产品分析的商业洞察
- [提示词库 Web 版](https://breezelance.github.io/prompt-library-web/) — 20 条结构化提示词，可搜索、中英双语

## 许可

CC BY 4.0
