---
title: "v2.1.191"
category: coding-agents-llm
tags: [release-notes, ai/llm-mechanics]
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.191
score: 0.70
reason: "/rewind feature enables conversation resumption post-clear"
captured: 2026-06-25T06:00:02.146595+00:00
rating:
---
# v2.1.191

> /rewind feature enables conversation resumption post-clear

<h2>What's changed</h2>
<ul>
<li>Added <code>/rewind</code> support for resuming a conversation from before <code>/clear</code> was run</li>
<li>Fixed scroll position jumping to the bottom while reading earlier output during a streaming response</li>
<li>Fixed background agents resurrecting after being stopped — stopping an agent from the tasks panel is now permanent</li>
<li>Fixed <code>/voice</code> showing a generic "not available" message when disabled by an organization's policy — it now explains the restriction</li>
<li>Fixed <code>/login</code> URL opening truncated in Windows Terminal

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.191)
