# 商业写作 Skill · 证据支持的商业叙事

[简体中文](README.md) · [English](README.en.md)

**0.1.0-rc.1** · Skill-compatible host

[![Repository checks](https://github.com/l0oo0ng/anti-defensive-business-writing-Skill/actions/workflows/repository.yml/badge.svg)](https://github.com/l0oo0ng/anti-defensive-business-writing-Skill/actions/workflows/repository.yml)

本仓库提供以下能力，当前版本的验证范围与限制见下方说明。

## 功能概览

| 能力 |
|---|
| 商业计划与路演文本重构 |
| 围绕真实证据组织商业优势 |
| 审查清单与使用示例 |

## 项目结构

- [skills](skills)

## 安装与使用

```text
# Install the directory skills/anti-defensive-business-writing in your supported Skill host.
# Prompt: 按 anti-defensive-business-writing 重构这份商业计划书。
```

[Quick start / 快速开始](docs/repository-standardization/QUICK_START.md)

## 开发与验证

```text
python scripts/repository_release.py check
```

## 下载与发布

[Candidate v0.1.0-rc.1](https://github.com/l0oo0ng/anti-defensive-business-writing-Skill/releases/tag/v0.1.0-rc.1) · [All releases](https://github.com/l0oo0ng/anti-defensive-business-writing-Skill/releases) · [Actions](https://github.com/l0oo0ng/anti-defensive-business-writing-Skill/actions)

候选包仅在检查成功后发布；尚未发布时请查看 Actions 状态。既有稳定版保持不变。

## 能力边界与安全

- 不能编造客户、收入、合同或成果；结构检查不代表真实模型写作效果评测。

仓库可见性和既有许可证保持不变；本文档不授予额外使用许可。

[贡献 / Contributing](CONTRIBUTING.md) · [安全 / Security](SECURITY.md) · [发布流程 / Releases](docs/repository-standardization/RELEASE.md)

<!-- preserved-history -->
<details>
<summary>原项目指南与历史说明（版本状态以本页上方为准）</summary>

# Anti-Defensive Business Writing

A reusable ChatGPT Skill for rewriting and reviewing business plans around the strongest **truthful, evidence-supported commercial case**.

It is inspired by the idea that a business plan should behave like an investment case rather than a project diary: identify the project's strongest credible advantage, build the narrative around it, and avoid unnecessary self-weakening without fabricating evidence or hiding material risk.

## What it is for

Use it for:

- 商业计划书 / BP / 创业计划书
- 创新创业比赛材料
- 工行杯、挑战杯、大创等项目文本优化
- 融资叙事和项目路演文案
- 产品商业化报告
- 市场、竞争、商业模式、财务、团队等章节重构
- 去除“工作汇报式”“技术堆砌式”“自我削弱式”表达
- 对整份商业计划书进行对抗性审查

## Core idea

> A business plan is not a record of everything the team has done. It is a structured argument for why this project deserves support.

The Skill prioritizes:

**valuable problem -> market opportunity -> differentiated solution -> moat -> evidence -> business model -> go-to-market -> financial logic -> execution credibility**

It does **not** permit fabricated customers, revenue, contracts, data, patents, partnerships, or traction.

## Repository structure

```text
anti-defensive-business-writing/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    └── review-checklist.md
```

## Example prompts

```text
按 anti-defensive-business-writing 的原则，重构这份商业计划书。不要只润色句子，先找到项目真正的商业优势，再重排叙事。
```

```text
用投资人、商业评委、技术评委、行业评委四个视角审查这份创业比赛BP，并直接重写问题最大的章节。
```

```text
把这一章从“技术功能介绍”改成“技术能力 -> 用户价值 -> 经济价值 -> 商业壁垒”的表达。
```

```text
检查这份BP有没有主动给评委递刀子的内容：自我削弱、无证据的大话、错误竞争维度、无法解释的财务预测。
```

## Skill location

The installable Skill lives at:

```text
skills/anti-defensive-business-writing/
```

## Skill package

The same source can be packaged as `skill.zip` for ChatGPT Skill upload/distribution after validation.


</details>
