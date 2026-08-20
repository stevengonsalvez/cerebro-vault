---
title: "Show HN: Needle2: 14MB agentic LLM for phones, wearables, smart home and robots"
category: coding-agents-llm
tags: [ai/agents, ai/llm-mechanics]
source: hackernews
url: https://cactuscompute.com/needle
score: 0.75
reason: "14MB agentic LLM for edge devices; lightweight agent mechanics."
captured: 2026-08-11T06:00:08.519319+00:00
rating:
---
# Show HN: Needle2: 14MB agentic LLM for phones, wearables, smart home and robots

> 14MB agentic LLM for edge devices; lightweight agent mechanics.

Today we release Needle 2: an open 45M-parameter model for tool calling, device use and structured extraction. The whole model is a single 14MB binary that runs a full session in 28MB of RAM. It is built on our Simple Attention Network findings, compressed to CQ2-bit with Cactus Quants, and baked into its own engine.
On the tool call and mobile device use benchmarks, Needle 2 trades wins with other small models like FunctionGemma 270M, LFM2.5 230M and Apple FM, at 5× to 70× smaller, and 2 bits against their f16. Needle hits 500 tokens/sec decode speed on a Raspberry Pi 5, between 400–1,500 tok

## Community take
Tiny models fail basic tasks (Needle2 returned confidence=0 on lock_door), raising production reliability doubts.


[Open ↗](https://cactuscompute.com/needle)
