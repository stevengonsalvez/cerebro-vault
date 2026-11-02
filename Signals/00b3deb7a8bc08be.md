---
title: "mattpocock/sandcastle: Orchestrate sandboxed coding agents in TypeScript with sandcastle.run()"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal, developer/mattpocock, github/cracked-dev, repo/mattpocock/sandcastle]
topic_tags: [ai/agents]
source_tags: [github/cracked-dev]
entity_tags: [developer/mattpocock, repo/mattpocock/sandcastle]
artifact_tags: [cerebro/signal]
workflow_tags: []
source: github
url: https://github.com/mattpocock/sandcastle
score: 0.85
reason: "Sandboxed coding-agent orchestration in TypeScript; direct agent-pattern match"
stars: 8746
language: "TypeScript"
captured: 2026-10-03T06:01:20.490195+00:00
rating:
---
# mattpocock/sandcastle: Orchestrate sandboxed coding agents in TypeScript with sandcastle.run()

> Sandboxed coding-agent orchestration in TypeScript; direct agent-pattern match

A TypeScript library for orchestrating AI coding agents in isolated sandboxes:
- You invoke agents with a single sandcastle.run() .
- Sandcastle handles sandboxing the agent with a configurable branch strategy.
- The commits made on the branches get merged back.
Sandcastle is provider-agnostic. It ships with native sandboxes that use your OS's own process sandbox (Bubblewrap on Linux and WSL2, Seatbelt on macOS), image-based providers for Docker and Podman, and cloud providers for Vercel and Daytona, and you can create your own. Great for parallelizing multiple AFK agents, creating review pipe

[Open ↗](https://github.com/mattpocock/sandcastle)
