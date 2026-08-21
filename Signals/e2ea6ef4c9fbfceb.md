---
title: "v2.1.236"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal, release-notes]
topic_tags: [ai/agents, release-notes]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.236
score: 0.70
reason: "Claude Code env var for model selection."
captured: 2026-08-21T06:00:19.146670+00:00
rating:
---
# v2.1.236

> Claude Code env var for model selection.

<h2>What's changed</h2>
<ul>
<li>Added <code>ANTHROPIC_DEFAULT_MODEL</code> environment variable: sets the model new sessions start on, while a <code>/model</code> pick still overrides it and persists across restarts (unlike <code>ANTHROPIC_MODEL</code>)</li>
<li>Added <code>notify_when_idle</code> to cross-session <code>SendMessage</code>: ask another Claude Code session on this machine to send one notice when it next goes idle — opt-in, one-shot, no polling (macOS and Linux)</li>
<li>Sandbox: on macOS, wildcard read-deny rules (e.g. <code>**/.env</code>) now take precedence inside allowed re

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.236)
