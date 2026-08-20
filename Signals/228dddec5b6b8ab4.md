---
title: "v2.1.219"
category: coding-agents-llm
tags: [ai/llm-mechanics, release-notes]
source: rss
url: https://github.com/anthropics/claude-code/releases/tag/v2.1.219
score: 0.85
reason: "Claude Opus 5 launch, context & pricing mechanics"
captured: 2026-08-12T06:00:07.705449+00:00
rating:
---
# v2.1.219

> Claude Opus 5 launch, context & pricing mechanics

<h2>What's changed</h2>
<ul>
<li>Added Claude Opus 5 (<code>claude-opus-5</code>), now the default Opus model — 1M context, fast mode at $10/$50 per Mtok</li>
<li>Added <code>sandbox.network.strictAllowlist</code> setting to deny non-allowlisted hosts for sandboxed commands without prompting</li>
<li>Added <code>DirectoryAdded</code> hook that fires after <code>/add-dir</code> or the SDK <code>register_repo_root</code> control request registers a new working directory mid-session</li>
<li>Added <code>mcp_server_errors</code> to the headless stream-json init event, listing <code>--mcp-config</c

[Open ↗](https://github.com/anthropics/claude-code/releases/tag/v2.1.219)
