---
login: "roli-lpci"
name: null
discovered_via: "fanout"
discovered_via_all:
  - "fanout"
provenance_repos:
  - "simonw/llm"
admitted: true
low_n: false
repos_populated: true
generated_at: "2026-10-02T06:06:48.484172+00:00"
provenance:
  - "97c4e9cb8b163ddb"
  - "c7515e0fa4368a55"
  - "d3abe74726b22711"
  - "e7c647c4d0689526"
pushes_per_week: [0, 2, 3, 4, 15, 3, 2, 0, 0, 3, 49, 29, 36]
windows:
  "7d":
    pushes: 38
    distinct_repos: 22
    active_days: 6
    repos_not_owned: 13
    not_owned_basenames: 13
    not_owned_owners: 1
  "30d":
    pushes: 117
    distinct_repos: 43
    active_days: 18
    repos_not_owned: 32
    not_owned_basenames: 32
    not_owned_owners: 1
  "90d":
    pushes: 146
    distinct_repos: 49
    active_days: 33
    repos_not_owned: 37
    not_owned_basenames: 37
    not_owned_owners: 1
automation:
  state: "clear"
  push_per_day: 4.4242
  repo_per_active_day: 1.4848
  not_owned_ratio: 0.7551
  basename_concentration: 0.0408
  shapes: []
  shape_evidence: []
  cleared_by: null
  cleared_on: null
  fork_provenance: null
  prefilter: "rest_verified"
facets:
  "7d":
    pushes: 38
    distinct_repos: 22
    pushes_per_repo: 1.7273
    active_days: 6
    repos_not_owned: 13
    not_owned_basenames: 13
    not_owned_owners: 1
  "30d":
    pushes: 117
    distinct_repos: 43
    pushes_per_repo: 2.7209
    active_days: 18
    repos_not_owned: 32
    not_owned_basenames: 32
    not_owned_owners: 1
  "90d":
    pushes: 146
    distinct_repos: 49
    pushes_per_repo: 2.9796
    active_days: 33
    repos_not_owned: 37
    not_owned_basenames: 37
    not_owned_owners: 1
reasons:
  - "provenance: 4 vault signal(s) — pass"
  - "activity: 33 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "roli-lpci"
    title: "roli-lpci"
    description: "Roli Bosch, founder of Hermes Labs. Philosophy of language applied to how AI systems are instructed and evaluated. Research, open-source tools, upstream fixes."
    language: null
    topics: []
    stars_fact: 0
    first_seen: null
    last_push: "2026-09-29"
  - name: "agent-kickstart"
    title: "agent-kickstart"
    description: "A guided onboarding project for people new to Claude Code — no coding or terminal experience required. Asks a few questions, proposes real starter projects shaped around what you care about, and begins one with you."
    language: "JavaScript"
    topics:
      - "ai-agents"
      - "ai-reliability"
      - "ai-tools"
      - "beginner-friendly"
      - "claude"
      - "claude-code"
      - "claude-code-commands"
      - "claude-code-plugin"
      - "cli"
      - "developer-tools"
      - "education"
      - "hermes-labs"
      - "human-ai-interaction"
      - "javascript"
      - "local-first"
      - "onboarding"
      - "privacy"
      - "python"
    stars_fact: 1
    first_seen: null
    last_push: "2026-09-29"
  - name: "claude-router"
    title: "claude-router"
    description: "claude-router is a local prompt router that picks the right Claude model tier and prepends the right scaffold using local embeddings before you call the API. A deterministic routing layer for eval, research, content, and review prompts that helps teams stop overspending on Sonnet and Opus when Haiku plus structure is enough."
    language: "Python"
    topics:
      - "ai-reliability"
      - "anthropic"
      - "claude"
      - "cost-optimization"
      - "developer-tools"
      - "embeddings"
      - "hermes-labs"
      - "llm"
      - "llm-cost"
      - "llm-ops"
      - "llm-routing"
      - "local-embeddings"
      - "local-first"
      - "model-routing"
      - "ollama"
      - "prompt-engineering"
      - "prompt-routing"
      - "python"
    stars_fact: 1
    first_seen: null
    last_push: "2026-09-29"
  - name: "agent-signage"
    title: "agent-signage"
    description: "Road signs for coding agents: one measured fact at the moment of action, silence otherwise"
    language: "Python"
    topics:
      - "agent-harness"
      - "agent-observability"
      - "agent-reliability"
      - "agentic"
      - "ai-agents"
      - "claude-code"
      - "claude-code-hooks"
      - "claude-code-plugin"
      - "coding-agents"
      - "context-engineering"
      - "context-integrity"
      - "developer-tools"
      - "git"
      - "git-worktree"
      - "hermes-labs"
      - "pretooluse"
      - "python"
      - "zero-llm"
    stars_fact: 1
    first_seen: null
    last_push: "2026-09-29"
  - name: "zer0lint"
    title: "zer0lint"
    description: "zer0lint is a memory-extraction health diagnostic for mem0 configs and HTTP memory endpoints. It flags silent failure modes where ingestion reports success but facts never survive the LLM extraction step, then generates a stronger extraction prompt validated on your own model. Works over HTTP with any add/search memory API."
    language: "Python"
    topics:
      - "agent-memory"
      - "ai-agents"
      - "ai-reliability"
      - "ai-safety"
      - "cli"
      - "diagnostics"
      - "extraction"
      - "hermes-labs"
      - "llm"
      - "llm-evaluation"
      - "llm-ops"
      - "mem0"
      - "memory"
      - "memory-security"
      - "prompt-engineering"
      - "python"
    stars_fact: 0
    first_seen: null
    last_push: "2026-09-29"
  - name: "te-drift-detector"
    title: "te-drift-detector"
    description: "Experimental Python tool for inspecting language and task-framing changes across long AI conversations."
    language: "Python"
    topics:
      - "agent-safety"
      - "ai-agents"
      - "ai-reliability"
      - "context-integrity"
      - "conversation-analysis"
      - "deterministic"
      - "drift-detection"
      - "hermes-labs"
      - "llm"
      - "llm-evaluation"
      - "llm-monitoring"
      - "mcp"
      - "multi-turn"
      - "nlp"
      - "python"
      - "session-monitoring"
      - "state-drift"
      - "telemetry"
      - "text-analysis"
    stars_fact: 1
    first_seen: null
    last_push: "2026-09-28"
---

# roli-lpci

146 pushes across 49 repositories on 33 active days in the last 90 days of public GitHub push activity.

https://github.com/roli-lpci
