---
name: convert-tacit-to-skill
description: "Convert tacit knowledge into a reusable agent or Codex skill by extracting cues, scoping the task, defining boundaries, and packaging the workflow into SKILL.md plus tests. Use when the user wants a fixed agent, reusable skill, or repeatable copilot based on expert judgment."
---
# Convert Tacit To Skill

Core judgment: do not build a broad agent from vague expertise. Build a narrow agent from repeated expert performance.

## Use When

- The user wants to turn tacit knowledge into a reusable agent or skill
- The user wants a fixed copilot for one recurring type of judgment or task
- A human expert performs well, but the behavior is not yet packaged for reuse

## Target Output

Prefer a single-purpose artifact:

- one agent
- one task family
- one primary user request shape
- one clear escalation boundary

If the request is broad, split it into multiple future skills instead of one bloated skill.

## Workflow

### 1. Scope the Agent

Define:

- role: what the agent is responsible for
- task: what recurring task it performs
- scene: the high-value context where it helps
- success standard: what a good output looks like
- non-goals: what it must not try to do

### 2. Extract the Tacit Layer

Use real cases, walkthroughs, or observed performance.

Pull out:

- trigger phrases
- decision cues
- default sequence
- failure signatures
- escalation boundary

If the tacit layer is still vague, switch to [extract-tacit-knowledge](./../extract-tacit-knowledge/SKILL.md).

### 3. Choose the Right Packaging

Pick one:

- Codex skill: for reusable guidance, procedural structure, references, scripts, and trigger metadata
- fixed prompt or copilot spec: for a narrower internal agent behavior
- human-agent hybrid workflow: when the agent should stop at synthesis and hand off decisions

Default to Codex skill if the task recurs and can benefit from supporting files.

### 4. Build the Skill Skeleton

Define:

- skill name
- frontmatter name and description
- use when triggers
- step-by-step workflow
- required references
- scripts if determinism is needed
- output contract
- do-not-do rules

If you need a format, read `references/skill-blueprint.md`.

### 5. Add Validation

Before calling it reusable, create:

- three trigger examples
- three non-trigger examples
- two success cases
- one failure or escalation case

If you need a format, read `references/skill-test-template.md`.

### 6. Decide Install Shape

Use one of:

- repo-local only
- symlink into `~/.codex/skills`
- copy into shared skills directory

Prefer symlink when the source repo should remain the source of truth.

## Output

Return:

- recommended skill name
- scope statement
- cue and boundary summary
- SKILL.md outline
- required references or scripts
- test cases
- install recommendation

## Do Not

- package a personality instead of a task
- hide unclear boundaries inside vague language
- claim reusability without trigger tests and escalation tests
