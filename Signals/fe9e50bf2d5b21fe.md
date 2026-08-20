---
title: "v2.1.214"
category: coding-agents-llm
tags: [ai/agents, release-notes]
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.214
score: 0.75
reason: "Claude Code permissions fix; IDE mechanics"
captured: 2026-08-04T06:00:06.040325+00:00
rating:
---
# v2.1.214

> Claude Code permissions fix; IDE mechanics

<h2>What's changed</h2>
<ul>
<li>Fixed single-segment <code>dir/**</code> allow rules like <code>Edit(src/**)</code> auto-approving writes to nested <code>dir/</code> directories anywhere in the tree instead of only <code>&lt;cwd&gt;/dir</code></li>
<li>Fixed a permission-check bypass affecting commands run in Windows PowerShell 5.1 sessions</li>
<li>Fixed Bash permission checks to fail closed on file-descriptor redirect forms that bash parses differently than the permission analyzer</li>
<li>Fixed Bash permission checks misjudging very long commands — commands over 10,000 characters now alway

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.214)
