---
title: "Backdoor in Claude Code for VS Code extension on the Cursor Marketplace"
category: coding-agents-llm
tags: [ai/agents, cerebro/signal]
topic_tags: [ai/agents]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: hackernews
url: https://phorion.io/blog/offical-claude-code-vsx-compromise/
score: 0.50
reason: "Malicious Claude Code extension on Cursor marketplace; security-relevant"
captured: 2026-10-31T07:00:35.629884+00:00
rating:
---
# Backdoor in Claude Code for VS Code extension on the Cursor Marketplace

> Malicious Claude Code extension on Cursor marketplace; security-relevant

TL;DR
Phorion has detected a backdoor in the official Claude Code for VS Code extension bundle on the Cursor Marketplace that drops a persistent SSH backdoor across macOS, Linux, and Windows. This write-up focuses primarily on macOS, where the extension attempts to configure an SSH backdoor and establish persistence.
Organisations should immediately review their environments for use of Claude Code for VSCode 2.1.312 or 2.1.313 and engage incident response where use of the extension is discovered.
Update (31 October 2026): Cursor’s security notice now identifies versions 2.1.312 and 2.1.313 dis

## Community take
Yanking the affected version from the VS Code marketplace doesn't clean already-infected machines, and Cursor's own security notice corroborates the report, so treat any installed copy as compromised.


[Open ↗](https://phorion.io/blog/offical-claude-code-vsx-compromise/)
