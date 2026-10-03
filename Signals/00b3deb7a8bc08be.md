---
title: "mattpocock/sandcastle: Orchestrate sandboxed coding agents in TypeScript with sandcastle.run()"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal, developer/mattpocock, github/cracked-dev, repo/mattpocock/sandcastle, vibe-coding]
topic_tags: [ai/agents, vibe-coding]
source_tags: [github/cracked-dev]
entity_tags: [developer/mattpocock, repo/mattpocock/sandcastle]
artifact_tags: [cerebro/signal]
workflow_tags: []
source: github
url: https://github.com/mattpocock/sandcastle
score: 0.85
reason: "Agentic orchestration framework, novel TypeScript pattern"
stars: 8235
language: "TypeScript"
captured: 2026-10-03T06:01:20.490195+00:00
rating:
---
# mattpocock/sandcastle: Orchestrate sandboxed coding agents in TypeScript with sandcastle.run()

> Agentic orchestration framework, novel TypeScript pattern

A TypeScript library for orchestrating AI coding agents in isolated sandboxes:
- You invoke agents with a single sandcastle.run() .
- Sandcastle handles sandboxing the agent with a configurable branch strategy.
- The commits made on the branches get merged back.
Sandcastle is provider-agnostic — it ships with built-in providers for Docker, Podman, and Vercel, and you can create your own. Great for parallelizing multiple AFK agents, creating review pipelines, or even just orchestrating your own agents.
- Git
- A sandbox provider — Sandcastle needs an isolated environment to run agents in. Built

[Open ↗](https://github.com/mattpocock/sandcastle)
