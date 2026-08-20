---
title: "v2.1.221"
category: coding-agents-llm
tags: [ai/agents, release-notes]
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.221
score: 0.80
reason: "Claude Code Focus view; IDE feature changelog"
captured: 2026-08-04T06:00:06.040272+00:00
rating:
---
# v2.1.221

> Claude Code Focus view; IDE feature changelog

<h2>What's changed</h2>
<ul>
<li>[VSCode] Added Focus view: a chat-menu toggle that hides tool activity behind an expandable per-turn summary with a live running-tool indicator, toggled with <code>Ctrl+Alt+F</code> or the "Claude Code: Toggle Focus view" command</li>
<li>Added <code>mode: "mask"</code> for sandbox credential files on Linux and WSL — sandboxed commands read a sentinel copy (the whole file, or just the spans captured by an <code>extract</code> regex) while the sandbox proxy substitutes the real value on egress; on macOS file masking falls back to <code>deny</code></li>
<li>Added

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.221)
