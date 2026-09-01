# Outisseus

**Ex-NIQ data scientist → builder.** I build around AI agents, infrastructure, information systems, automation, and open networks — and write along the way.

[Website](https://outisseus.github.io/) · [Builder matrix](https://outisseus.github.io/builder/) · [Follow the builds on X → @ChoeyCui](https://x.com/ChoeyCui)

## Two boundaries for long-running agents

My current infrastructure work separates two problems that are often collapsed into “memory + tools”:

```text
source evidence → personal-context → minimum working projection
                                      ↓
                              agent / planner
                                      ↓
verified usage proof ← DeTool ← authorized external action
          ↓
candidate context update → policy / review → personal-context
```

- **[`personal-context`](https://github.com/outisseus/personal-context)** governs internal state: provenance, temporal truth, minimum disclosure, and controlled write-back. The repository now includes the runnable local graphical workbench and a paper workspace.
- **[`detool`](https://github.com/outisseus/detool)** governs external action: capability identity, provider resolution, authority, state-transition verification, usage proof, and scoped reliability.

Context does not silently grant authority. A successful action does not silently rewrite context.

## Infrastructure

| Project | Thesis | Status |
| --- | --- | --- |
| [`personal-context`](https://github.com/outisseus/personal-context) | Source-backed internal state, purpose-limited projections, controlled write-back, and a local graphical workbench. | Building |
| [`detool`](https://github.com/outisseus/detool) | A capability execution network for authorized, verifiable external state transitions. | Building |
| `intentgraph` | Turn natural-language intent into constraints, task graphs, tool selection, execution, and verification. | Design |
| `agent-skills` | Reusable reasoning and action skills with explicit sources, critics, plans, and verification. | Experiment |
| [`session-health-probe`](https://github.com/outisseus/session-health-probe) | Make browser and agent session reliability observable with explicit health states. | Building |
| `official-source-monitor` | Stateful delta monitoring with cursors, source coverage, list verification, and alerts. | Design |

## Applications

| Project | What it does | Status |
| --- | --- | --- |
| [`guatian-mvp`](https://github.com/outisseus/guatian-mvp) | Maps competing narratives, actors, timelines, branches, and evidence in public stories. [Live demo](https://outisseus.github.io/guatian-mvp/) | Live MVP |
| `fuzzy-photo-search` | Finds personal photos from vague natural-language memories using multimodal retrieval and metadata signals. | Planned MVP |
| `jarvis` | A synthetic public reference app for collaborative intelligence, built on `personal-context`. | Design |
| `content-growth-engine` | Approval-first research → draft → publish → read-back verification → telemetry. | Building |

## Writing

I am publishing [《雾港校准局》](https://github.com/outisseus/wugang-calibration-bureau), an original serialized near-future mystery. Public chapters stay separate from private outlines, future plot details, and drafts.

The first joint research outline for Personal Context and DeTool lives in [`personal-context/papers`](https://github.com/outisseus/personal-context/tree/main/papers). Draft claims remain visibly separate from implemented evidence and synthetic tests.

## What I share

- Build logs with working demos, architecture, benchmarks, and failures
- Original theses grounded in shipped systems
- Useful replies and quotes in AI agent, infrastructure, information, and open-network conversations
- Occasional fiction and creative work

## Public-work boundary

Public repositories use synthetic examples and sanitized abstractions. Personal context, client data, credentials, browser profiles, private prompts, and real business data stay private.

---

**Inspect the proof, follow the process, and join the conversation on [X](https://x.com/ChoeyCui).**
