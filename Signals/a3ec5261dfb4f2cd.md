---
title: "v2.1.212"
category: coding-agents-llm
tags: [ai/agents, release-notes]
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.212
score: 0.65
reason: "Claude Code /fork for background agent sessions"
captured: 2026-08-05T06:00:04.474469+00:00
rating:
---
# v2.1.212

> Claude Code /fork for background agent sessions

<h2>What's changed</h2>
<ul>
<li><code>/fork</code> now copies your conversation into a new background session (its own row in <code>claude agents</code>) while you keep working; the in-session subagent it used to launch is now <code>/subtask</code></li>
<li>Added <code>claude auto-mode reset</code> to restore the default auto-mode configuration, with a confirmation prompt (pass <code>--yes</code> to skip)</li>
<li>Added a session-wide limit on WebSearch tool calls (default 200, tunable via <code>CLAUDE_CODE_MAX_WEB_SEARCHES_PER_SESSION</code>) to stop runaway search loops</li>
<li>Added a per

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.212)
