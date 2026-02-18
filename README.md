# Hacking Growth Skill

## 中文介绍

这是一个给 Codex 使用的增长运营 Skill，帮助你从 0 开始搭建产品增长体系，并持续优化。

它适合你在这些场景使用：
- 刚开始做产品，不知道先看哪些增长指标
- 想系统化做增长实验，而不是靠感觉改功能
- 需要把增长工作变成可执行的每周节奏
- 想根据产品类型（SaaS、内容、平台、电商、开发者工具）定制策略

这个 Skill 会帮助你：
- 定义北极星指标和护栏指标
- 识别当前最大增长瓶颈（AARRR）
- 生成并用 ICE 排优先级
- 产出可执行实验卡（目标、指标、停止规则、负责人）
- 给出每周增长运营节奏和复盘模板

### 安装

1. 克隆仓库  
`git clone https://github.com/tunshusama/hackinggrowth-skill.git`

2. 放到本机 Codex skills 目录（目录名建议保持 `hacking-growth-playbook`）  
`$CODEX_HOME/skills/hacking-growth-playbook/`

3. 确认存在：
- `SKILL.md`
- `agents/openai.yaml`
- `references/`

### 使用方式

在 Codex 对话中直接描述你的增长问题，或点名使用：
- `hacking-growth-playbook`

示例：
- “帮我给一个 0 到 1 的 SaaS 做 4 周增长计划”
- “我们注册很多但留存低，按黑客增长方法给实验方案”
- “给我一个按 ICE 排序的增长实验 backlog”

---

## English

This is a Codex skill for product growth operations. It helps teams go from zero to a repeatable growth system.

Use it when you need to:
- Start growth work from scratch
- Build an experiment-driven process instead of ad-hoc changes
- Set up a weekly operating cadence for growth
- Tailor tactics by product archetype (PLG SaaS, social/content, marketplace, ecommerce, developer tools)

What this skill provides:
- North-star and guardrail metric setup
- Bottleneck diagnosis across AARRR
- Hypothesis generation and ICE prioritization
- Actionable experiment cards (metric, owner, stop rules)
- Weekly execution and review templates

### Install

1. Clone the repo  
`git clone https://github.com/tunshusama/hackinggrowth-skill.git`

2. Place it under your local Codex skills directory (recommended folder name: `hacking-growth-playbook`)  
`$CODEX_HOME/skills/hacking-growth-playbook/`

3. Make sure these files exist:
- `SKILL.md`
- `agents/openai.yaml`
- `references/`

### How to use

In Codex chat, describe your growth problem or call the skill name directly:
- `hacking-growth-playbook`

Example prompts:
- “Build a 4-week growth plan for a 0-to-1 SaaS product.”
- “Signups are high but retention is low. Use Hacking Growth to design experiments.”
- “Generate an ICE-prioritized growth experiment backlog.”
