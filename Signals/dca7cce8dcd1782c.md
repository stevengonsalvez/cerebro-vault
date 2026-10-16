---
title: "v2.1.301"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal, release-notes]
topic_tags: [release-notes, ai/agents]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.301
score: 0.85
reason: "Claude Code release: unattended retry watchdog and usage-limit controls."
captured: 2026-10-16T08:25:07.930656+00:00
rating:
---
# v2.1.301

> Claude Code release: unattended retry watchdog and usage-limit controls.

<h2>What's changed</h2>
<ul>
<li>Added <code>CLAUDE_CODE_RETRY_WATCHDOG_MAX_USAGE_LIMIT_WAIT_MS</code> so unattended retry mode (<code>CLAUDE_CODE_RETRY_WATCHDOG</code>) ends a request at a usage limit that resets too far away instead of waiting</li>
<li>Added OpenTelemetry tracing guidance to the <code>claude-api</code> skill, including setting up trace destinations with the <code>ant</code> CLI</li>
<li>Added the <code>%</code> motion to vim mode: jump to the matching bracket, alone or with d/c/y</li>
<li>Added <code>rows</code> to a mod's <code>Input</code>: a text field of several lines in

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.301)
