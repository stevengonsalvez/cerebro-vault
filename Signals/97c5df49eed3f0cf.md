---
title: "v2.1.310"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal, release-notes]
topic_tags: [release-notes, ai/agents]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.310
score: 0.80
reason: "Claude Code release; Monitor tool, direct changelog."
captured: 2026-10-24T06:00:36.285759+00:00
rating:
---
# v2.1.310

> Claude Code release; Monitor tool, direct changelog.

<h2>What's changed</h2>
<ul>
<li>Added the Monitor tool and plugin monitors on Bedrock, Vertex, and Foundry, and when telemetry or nonessential traffic is disabled; long foreground sleeps are now blocked there too</li>
<li>Fixed requests failing behind some gateways and compatible servers that reject the <code>effort-2025-11-24</code> beta value or mid-conversation system messages; Claude Code now retries without them</li>
<li>Fixed background cleanup deleting some recent files, such as pasted images, when <code>cleanupPeriodDays</code> is set to a very large value</li>
<li>Fixed compaction af

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.310)
