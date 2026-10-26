---
title: "Show HN: Proc-CLI – An agent-friendly CLI tool for process and port management"
category: cli-tui
tags: [cerebro/signal, cli/tui]
topic_tags: [cli/tui]
source_tags: []
entity_tags: []
artifact_tags: [cerebro/signal]
workflow_tags: []
source: hackernews
url: https://proc-cli.com/
score: 0.70
reason: "Agent-friendly CLI for process and port management"
captured: 2026-10-26T07:00:51.667363+00:00
rating:
---
# Show HN: Proc-CLI – An agent-friendly CLI tool for process and port management

> Agent-friendly CLI for process and port management

Target processes by port, PID, name or path.
proc is a semantic CLI tool for process management on macOS, Linux and Windows. Find what's on a port, why it's there, and stop it, in one command you'd guess on the first try.
~proc kill :3000
Ends whatever is listening on port 3000 immediately (SIGKILL). Asks first, and --dry-run previews.
A leading colon means a port: proc acts on whatever is listening on it.
brew install yazeed/proc/proc
One command instead of a pipeline
The same jobs, without remembering which flags lsof needs or piping PIDs into kill.
lsof -i :3000 -P -nproc on :3000lsof -i :3

[Open ↗](https://proc-cli.com/)
