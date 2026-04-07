# Tacit Skills

Turn tacit knowledge into reusable agents and skills.

The most valuable operating systems in a company are almost never fully written down. They live in judgment, timing, escalation, taste, and refusal. That invisible layer is where quality compounds, onboarding breaks, and expert performance becomes hard to scale.

`Tacit Skills` is an open-source system for converting tacit knowledge into reusable AI agents, Codex skills, and training workflows. It packages Michael Polanyi's core insight, "we know more than we can tell," into something operational: extract the hidden cues, structure the learning path, define the transfer boundary, and turn expert behavior into software or repeatable practice.

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](./LICENSE)
[![Star History Chart](https://api.star-history.com/svg?repos=11Yuxuanyang/tacit-skills&type=Date)](https://www.star-history.com/#11Yuxuanyang/tacit-skills&Date)

## Why This Matters

Most teams do not lose leverage because they lack information. They lose leverage because their best judgment is trapped inside a few people.

- Your best operator leaves, and your margin leaves with them.
- Your onboarding looks complete, but new hires still cannot perform.
- Your AI agent can automate syntax, but not judgment.
- Your team can repeat the words, but not reproduce the outcome.

Tacit knowledge is the hidden layer behind all of that. If you can extract it, you can scale it. If you can package it, you can productize it.

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

## Repository Structure

```text
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

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=11Yuxuanyang/tacit-skills&type=Date)](https://www.star-history.com/#11Yuxuanyang/tacit-skills&Date)

## License

MIT. See [LICENSE](./LICENSE).
