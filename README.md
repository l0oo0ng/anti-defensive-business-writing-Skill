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
