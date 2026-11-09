---
title: "v2.1.321"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal, release-notes]
topic_tags: [release-notes, ai/agents]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.321
score: 0.80
reason: "Claude Code changelog: new Fable model, cache pricing, flags"
captured: 2026-11-09T23:32:07.995645+00:00
rating:
---
# v2.1.321

> Claude Code changelog: new Fable model, cache pricing, flags

<h2>What's changed</h2>
<ul>
<li>Added Claude Fable 5.2 (<code>claude-fable-5-2</code>), now the default Fable model — 1M context, $8/$40 per Mtok with $0.20/Mtok cache reads</li>
<li>Added <code>--settings &lt;file&gt;</code> to <code>claude remote-control</code>, which applies a settings file to every session it starts; if the file changes, no new session starts until you restart <code>claude remote-control</code></li>
<li>Fixed MCP OAuth requests sending secrets such as refresh tokens to another host when a server redirected them</li>
<li>Fixed a case where a read-only Bash command ran outs

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.321)
