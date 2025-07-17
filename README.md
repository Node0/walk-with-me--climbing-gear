# 🏔️⛏️ Walk With Me — Climbing Gear

> *"Every ascent requires tools. Some you forge, some you find, others you inherit. "* This repo contains the gear we packed for the climb."*

This is the **toolkit repository** for the book *Walk With Me: A Human’s Guide to Cognitive Ascent*.

Where the book serves as trail guide and expedition journal, this repo houses the **field tools** used along the way—from system prompts to Socratic analyzers, from generative simulators to debugging rituals.

Everything here was used in practice, refined through metacognitive recursion, and shared so you too can climb with intention.

---

## 🔍 Repository Structure

This repo is organized by **tool type** at the top level. Each folder contains submodules or toolkits targeting specific functions, platforms, or model families.

```
.
├── prompting/
│   └── system_prompts/
│       └── chatgpt/
│           └── ITPS_system_prompt_design.md
│       └── claude/
│           └── (forthcoming)
│
├── generators/
│   └── prompt_generation/
│       └── ...
│
├── analyzers/
│   └── socratic_analyzers/
│       └── ...
│   └── corpus_analyzers/
│       └── ...
│
├── simulators/
│   └── generation_simulators/
│       └── ...
│
├── debuggers/
│   └── chat_debug_tools/
│       └── ...
│
├── visualizers/
│   └── generative_system_visualizers/
│       └── ...
```

---

## 🧠 Folder Index

### `prompting/`
Core prompts, prompt engineering scaffolds, and interaction design patterns.
- `system_prompts/`: Persistent identity, tone, and mode configuration prompts.
- `task_prompts/`: Disposable task-specific prompts and roleplay scaffolds.

### `generators/`
Prompt generators and template-based scaffolds.
- `prompt_generation/`: DSL-style prompt expansion tools, combinators, and hybrid templates.

### `analyzers/`
Recursive thought tools for evaluating ideas and outputs.
- `socratic_analyzers/`: Dialectical scaffolds like the Chapter Scrutiny Template.
- `corpus_analyzers/`: Tools for evaluating prompt sets, logs, or output batches.
- `cleaners/`, `prompt_qualifiers/`, `corpora_tools/`: For grooming and qualifying input sets.

### `simulators/`
Multi-agent simulators, generation rituals, and modeling aids.
- `generation_simulators/`: Prompt rituals for emulating recursive cognition or roleplay frames.

### `debuggers/`
Prompts and workflows for unblocking, tracing, and refining failing outputs.
- `chat_debug_tools/`: LLM-to-LLM self-debug, fail-mode classifiers, and recovery techniques.

### `visualizers/`
Tools for conceptual mapping, semantic topology, and prompt flow visualization.
- `generative_system_visualizers/`: Latent map renderers, recursive diff visualizers, prompt tree renderers.

---

## 🔎 Featured Tools

| Tool | Type | Location |
|------|------|----------|
| ITPS (Inflection-Tuned Persona Switching) | system prompt | `prompting/system_prompts/chatgpt/ITPS_system_prompt_design.md` |
| Chapter Scrutiny Template | Socratic analyzer | `analyzers/socratic_analyzers/chapter_scrutiny_template.md` |
| Prompt Drift Visualizer | visualizer (planned) | `visualizers/generative_system_visualizers/` |

---

## 🌿 License

All contents licensed under **CC BY-NC-SA 4.0** unless otherwise noted.

Use, remix, adapt — but please credit the climb.

---

## 🌌 Guiding Principle

> *"Every cognitive ascent leaves traces.
> These are mine. You're welcome to use them for yours."*