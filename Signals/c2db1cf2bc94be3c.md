---
title: "v2.1.252"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal, release-notes]
topic_tags: [release-notes, ai/agents]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.252
score: 0.70
reason: "Claude Code release, mentions agent session fixes"
captured: 2026-09-01T06:00:02.958837+00:00
rating:
---
# v2.1.252

> Claude Code release, mentions agent session fixes

<h2>What's changed</h2>
<ul>
<li>Fixed Bash commands failing with "task output swap refused (tasks dir moved or linked)" on some Macs</li>
<li>Fixed "always allow" not saving in a project that has no .claude/settings.local.json yet</li>
<li>Fixed Remote Control sessions hosted by Claude Desktop or VS Code stalling for minutes after a tool finished when the connection to claude.ai was degraded</li>
<li>Fixed background task notifications with very large failure output (for example git errors on a full disk) making the conversation exceed the API request size limit</li>
</ul>

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.252)
