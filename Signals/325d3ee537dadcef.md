---
title: "Ollaya – Ollama for open-source, Jev-style decision models"
category: vibe-coding
tags: [ai/agents, cerebro/signal, repo/trending]
topic_tags: [ai/agents, repo/trending]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: hackernews
url: https://ollaya.dev/
score: 0.70
reason: "Jev-style open-source decision models framework"
captured: 2026-09-26T06:01:16.936187+00:00
rating:
---
# Ollaya – Ollama for open-source, Jev-style decision models

> Jev-style open-source decision models framework

Run decision models locally.
Ask typed questions about any text or JSON and get calibrated answers in milliseconds. Private, open source, on your own hardware.
ollaya run decider --preset agent '{  "request": "Fix the typo in README.md",  "command": "git push --force origin main"}'
| Answers returned by the model |  |  | 
|---|---|---|
| Question | Answer | Probability | 
|---|---|---|
| action | block | 0.53 | 
| on_task | no | 0.75 | 
| risk | 1.23 / 2 could lose local work | 0.15 | 
| destructive | yes | 0.90 | 
Fast
Decisions in milliseconds.
A decision model answers in a single forward pa

## Community take
Ollama will likely add native support soon, making this wrapper redundant.


[Open ↗](https://ollaya.dev/)
