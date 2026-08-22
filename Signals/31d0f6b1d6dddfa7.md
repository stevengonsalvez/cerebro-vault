---
title: "v2.1.239"
category: coding-agents-llm
tags: [ai/llm-mechanics, cerebro/signal, release-notes]
topic_tags: [ai/llm-mechanics, release-notes]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.239
score: 0.80
reason: "Claude cost tracking, US-only inference premium pricing."
captured: 2026-08-22T06:00:03.503933+00:00
rating:
---
# v2.1.239

> Claude cost tracking, US-only inference premium pricing.

<h2>What's changed</h2>
<ul>
<li>Cost estimates (<code>/cost</code>, status line, <code>--max-budget-usd</code>) now include the 1.1× US-only-inference premium for data-residency workspaces</li>
<li>Added the one-time fullscreen renderer offer on Bedrock, Vertex, Foundry and other previously excluded setups; new installs there now start in fullscreen</li>
<li>Added <code>/claude-api upgrade</code> to migrate Python projects from <code>anthropic</code> 0.x to 1.x, and updated the skill's Python reference for 1.x (timeouts use <code>anthropic.Timeout</code>, not <code>httpx.Timeout</code>)</li>

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.239)
