# Tacit Skills

Turn tacit knowledge into reusable agents and skills.

把“会做但说不清”的能力，转成可复用的 agent、skill 和训练系统。

The most valuable operating systems in a company are almost never fully written down. They live in judgment, timing, escalation, taste, and refusal. That invisible layer is where quality compounds, onboarding breaks, and expert performance becomes hard to scale.

`Tacit Skills` is an open-source system for converting tacit knowledge into reusable AI agents, Codex skills, and training workflows. It packages Michael Polanyi's core insight, "we know more than we can tell," into something operational: extract the hidden cues, structure the learning path, define the transfer boundary, and turn expert behavior into software or repeatable practice.

`Tacit Skills` 不是一个“知识管理”仓库，而是一个把默会知识产品化的框架。它关心的不是你写下了多少文档，而是你能不能把专家的判断、注意力切换、升级边界和失败前兆，真正沉淀成别人能复用的系统。

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](./LICENSE)
[![Star History Chart](https://api.star-history.com/svg?repos=11Yuxuanyang/tacit-skills&type=Date)](https://www.star-history.com/#11Yuxuanyang/tacit-skills&Date)

Documentation site:

- https://11yuxuanyang.github.io/tacit-skills/

## Why This Matters

Most teams do not lose leverage because they lack information. They lose leverage because their best judgment is trapped inside a few people.

- Your best operator leaves, and your margin leaves with them.
- Your onboarding looks complete, but new hires still cannot perform.
- Your AI agent can automate syntax, but not judgment.
- Your team can repeat the words, but not reproduce the outcome.

Tacit knowledge is the hidden layer behind all of that. If you can extract it, you can scale it. If you can package it, you can productize it.

中文直白版：

- 多数团队的问题不是“没知识”，而是最值钱的判断只活在少数人脑子里。
- 文档能复制流程，复制不了火候、边界感和取舍。
- AI 能处理显性规则，但真正拉开差距的，往往是 tacit knowledge。
- 谁先把默会知识提炼成 agent 和 skill，谁就先把人的能力变成组织资产。

## What Is Tacit Knowledge?

Tacit knowledge is knowledge embedded in expert judgment, timing, pattern recognition, escalation sense, and embodied action. People use it constantly, but they often cannot fully explain it in explicit step-by-step language.

This matters because documentation can copy sequence, but it usually cannot copy feel, boundary sense, or the ability to notice the right signal at the right time. That hidden layer is exactly what strong AI agents, strong training systems, and strong onboarding workflows need.

Further reading:

- [What is tacit knowledge?](./docs/what-is-tacit-knowledge.html)
- [Michael Polanyi for AI builders](./docs/michael-polanyi-ai.html)

## How to Turn Tacit Knowledge into an AI Agent

To turn tacit knowledge into an AI agent, do not start with broad expertise. Start with one role, one recurring task, one high-value scene, and one boundary where the system must stop and escalate. Then extract cues, trigger phrases, failure signatures, and default moves from real expert performance.

Once that hidden layer is visible, you can package it into a reusable AI agent, Codex skill, copilot, or onboarding workflow. If you skip the extraction step, you usually end up with a polished but shallow prompt.

Further reading:

- [How to turn tacit knowledge into an AI agent](./docs/tacit-knowledge-to-ai-agent.html)
- [How to convert expert judgment into a Codex skill](./docs/expert-judgment-to-codex-skill.html)

## What This Repo Does

This repo gives you a fixed set of skills for turning invisible expertise into reusable assets.

| Skill | What it does |
|------|---------------|
| `convert-tacit-to-skill` | Converts a narrow expert workflow into a reusable agent or Codex skill |
| `extract-tacit-knowledge` | Pulls hidden cues, trigger signals, failure signatures, and escalation boundaries out of expert performance |
| `design-embodied-learning` | Designs practice ladders for tacit or judgment-heavy skills |
| `map-personal-knowledge` | Separates direct understanding from borrowed language and weak assumptions |
| `design-apprenticeship-transfer` | Builds mentor-led transfer and onboarding for tacit work |
| `train-attention-switching` | Trains focal and subsidiary attention switching for diagnosis, debugging, review, and other expert work |

## Commercial Use

This is not just a philosophy repo. It is a commercialization layer for expertise.

Use it to:

- turn a founder's judgment into a repeatable copilot
- turn a senior engineer's review instinct into a reusable skill
- turn sales, diagnosis, or content taste into a teachable system
- reduce onboarding time for judgment-heavy roles
- build agents that know when to act and when to escalate

The open-source core is the framework. The commercial upside is what you build on top of it.

中文商业化理解：

- 把创始人的判断变成固定 copilot
- 把资深员工的经验变成 onboarding 系统
- 把高质量服务背后的“感觉”变成可交付产品
- 把原本只能靠少数高手完成的工作，变成可训练、可复制、可放大的能力

## Use Cases

- Tacit knowledge for code review
- Tacit knowledge for onboarding judgment-heavy roles
- Tacit knowledge for debugging and diagnosis
- Tacit knowledge for design critique and creative review
- Tacit knowledge for founder judgment and specialized copilots

Use case page:

- [Tacit knowledge examples](./docs/tacit-knowledge-examples.html)

## Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/11Yuxuanyang/tacit-skills.git
cd tacit-skills
```

### 2. Install the skills into Codex

If your Codex setup reads from `~/.codex/skills`, symlink the skill folders you want to use:

```bash
ln -s "$(pwd)/skills/convert-tacit-to-skill" ~/.codex/skills/convert-tacit-to-skill
ln -s "$(pwd)/skills/extract-tacit-knowledge" ~/.codex/skills/extract-tacit-knowledge
ln -s "$(pwd)/skills/design-embodied-learning" ~/.codex/skills/design-embodied-learning
ln -s "$(pwd)/skills/map-personal-knowledge" ~/.codex/skills/map-personal-knowledge
ln -s "$(pwd)/skills/design-apprenticeship-transfer" ~/.codex/skills/design-apprenticeship-transfer
ln -s "$(pwd)/skills/train-attention-switching" ~/.codex/skills/train-attention-switching
```

### 3. Start from the orchestrator

The main entry point is:

- [`skills/convert-tacit-to-skill/SKILL.md`](./skills/convert-tacit-to-skill/SKILL.md)

Use it when you want to turn one narrow type of expert judgment into a reusable agent or skill.

Example prompts:

```text
Use convert-tacit-to-skill to turn my code review judgment into a reusable Codex skill.
```

```text
Help me convert the way I evaluate short-video hooks into a fixed agent with escalation boundaries.
```

```text
Use the tacit skills to extract the hidden cues behind our best sales call diagnosis.
```

Chinese examples:

```text
用 convert-tacit-to-skill 帮我把代码 review 的 tacit knowledge 做成一个可复用的 Codex skill。
```

```text
帮我把我判断短视频开头好坏的经验，转成一个固定 agent，并定义清楚升级边界。
```

## Repository Structure

```text
docs/
├── index.html
├── what-is-tacit-knowledge.html
├── tacit-knowledge-to-ai-agent.html
├── expert-judgment-to-codex-skill.html
├── michael-polanyi-ai.html
└── tacit-knowledge-examples.html

skills/
├── convert-tacit-to-skill/
├── extract-tacit-knowledge/
├── design-embodied-learning/
├── map-personal-knowledge/
├── design-apprenticeship-transfer/
└── train-attention-switching/
```

Each skill contains:

- `SKILL.md`: the trigger and operating instructions
- `references/`: the minimum templates needed to run the workflow

## Design Principle

Do not try to automate "expertise" in the abstract.

Start with:

- one role
- one task
- one high-value scene
- one boundary where the system must stop and escalate

That is how tacit knowledge becomes durable instead of vague.

## GEO Notes

This repository is intentionally written for keyword discovery, not only for brand discovery.

Core keyword clusters:

- tacit knowledge
- Michael Polanyi
- expert judgment
- AI agents
- Codex skills
- knowledge transfer
- onboarding
- diagnosis
- code review

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=11Yuxuanyang/tacit-skills&type=Date)](https://www.star-history.com/#11Yuxuanyang/tacit-skills&Date)

## License

MIT. See [LICENSE](./LICENSE).
