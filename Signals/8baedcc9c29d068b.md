---
title: "agentplugins/agent-plugins-spec: Agent Plugins Specification v1.0.0 — A minimal standard for packaging agent extensions into distributable plugins"
category: coding-agents-llm
tags: [ai/agents, ai/tool-pairing]
source: github
url: https://github.com/agentplugins/agent-plugins-spec
score: 0.85
reason: "Agent plugin specification standard — emerging infrastructure"
captured: 2026-08-09T06:00:06.171864+00:00
rating:
---
# agentplugins/agent-plugins-spec: Agent Plugins Specification v1.0.0 — A minimal standard for packaging agent extensions into distributable plugins

> Agent plugin specification standard — emerging infrastructure

Agent Plugins is an open, vendor-neutral standard for packaging reusable components that extend AI agents into distributable plugins. It defines a portable package format for Agent Skills and MCP servers.
This README is a non-normative introduction. The versioned specification defines the portable contract.
Agent Plugins Specification 1.0.0 is the current published release.
The smallest useful plugin is a directory with one skill:
hello-plugin/
├── plugin.json
└── skills/
    └── greet/
        └── SKILL.md
In plugin.json:
{
  "$schema": "https://agent-plugins.org/schemas/1.0.0/plugin.schema.j

[Open ↗](https://github.com/agentplugins/agent-plugins-spec)
