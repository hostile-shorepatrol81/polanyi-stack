---
name: extract-tacit-knowledge
description: "Extract tacit knowledge from expert performance using think-aloud, observation, and critical incident interviews. Use when the user wants to uncover implicit judgment, hidden cues, or '会做但说不清' know-how and turn it into transferable artifacts."
---
# Extract Tacit Knowledge

Core judgment: do not start from theory. Start from performance under real constraints.

## Use When

- The user mentions tacit knowledge, implicit know-how, intuition, or "we know more than we can tell"
- The goal is to turn expert judgment into a checklist, decision tree, rubric, or agent behavior
- A team can see good performance but cannot explain what makes it good

## Do First

Define the target narrowly:

- one role
- one task
- one high-value situation
- one acceptance standard

If the scope is broad, compress it before doing anything else.

## Evidence Standard

Do not abstract too early. Ask for or reconstruct:

- one real walkthrough
- one success incident
- one failure or near-miss incident
- three representative artifacts, cases, or outputs

If none of this exists, say so and treat the result as a first draft, not a finished method.

## Workflow

### 1. Capture Performance

Use one or more:

- think-aloud narration during execution
- direct observation or screen recording
- critical incident interview after a success or failure

If you need prompts, read `references/interview-prompts.md`.

### 2. Extract the Hidden Layer

Pull out five things:

- trigger signals: what changes the expert's move
- decision cues: what they are actually noticing
- embodied actions: what they do automatically and may forget to mention
- failure signatures: what usually appears before a mistake
- escalation boundaries: when normal handling stops and handoff begins

### 3. Repackage Only After Extraction

Convert the findings into one or more:

- cue list
- checklist
- decision tree
- failure rubric
- escalation rule

### 4. Validate on a Fresh Case

Test the artifact on an unseen case with a novice, peer, or agent.

Success means:

- they can act, not just restate
- they notice the right cues
- they know when not to continue

## Output

Return a compact package with:

- task definition
- cue list
- trigger list
- failure signatures
- escalation boundary
- recommended transfer format

## Do Not

- confuse the expert's explanation with the expert's real decision process
- turn one anecdote into a universal rule
- ship a polished framework without at least one failure case
