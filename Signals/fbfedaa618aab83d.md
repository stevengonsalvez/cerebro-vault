---
title: "v2.1.314"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal, release-notes]
topic_tags: [release-notes, ai/agents]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.314
score: 0.85
reason: "Claude Code release: write-path permission controls, core agent tooling"
captured: 2026-10-31T07:00:36.161916+00:00
rating:
---
# v2.1.314

> Claude Code release: write-path permission controls, core agent tooling

<h2>What's changed</h2>
<ul>
<li>Added <code>permissions.blockWritesOutsideWorkingDirectories</code>: Write, Edit and NotebookEdit refuse paths outside the working directories in every permission mode</li>
<li>Added an optional <code>groups</code> list to Claude apps gateway upstreams: only developers in the listed IdP groups are sent to that upstream, on failover too</li>
<li>Added <code>guardrail_trace</code> to Claude apps gateway Bedrock upstreams, to log which Amazon Bedrock guardrail filter fired on a request, without the matched text</li>
<li>Added idle compaction to VS Code and Claude

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.314)
