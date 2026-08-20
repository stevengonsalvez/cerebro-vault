---
title: "v2.1.211"
category: coding-agents-llm
tags: [ai/agents, ai/llm-mechanics, release-notes]
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.211
score: 0.85
reason: "Subagent text forwarding; core LLM mechanics"
captured: 2026-08-04T06:00:06.040337+00:00
rating:
---
# v2.1.211

> Subagent text forwarding; core LLM mechanics

<h2>What's changed</h2>
<ul>
<li>Added <code>--forward-subagent-text</code> flag and <code>CLAUDE_CODE_FORWARD_SUBAGENT_TEXT</code> environment variable to include subagent text and thinking in stream-json output</li>
<li>Fixed permission previews relayed to chat channels not neutralizing bidirectional-override, zero-width, and look-alike quote characters, so tool inputs cannot visually alter the approval message</li>
<li>Fixed auto mode overriding a PreToolUse hook's <code>ask</code> decision for unsandboxed Bash — a hook <code>ask</code> now floors the decision at a prompt</li>
<li>Fixed par

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.211)
