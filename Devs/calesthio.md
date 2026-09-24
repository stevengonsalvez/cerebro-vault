---
login: "calesthio"
name: null
discovered_via: "vault"
discovered_via_all:
  - "fanout"
  - "vault"
provenance_repos:
  - "calesthio/OpenMontage"
admitted: true
low_n: false
repos_populated: true
generated_at: "2026-09-24T15:17:54.275119+00:00"
provenance:
  - "6d3bd03b49986330"
pushes_per_week: [14, 13, 2, 6, 0, 0, 13, 0, 1, 0, 0, 0, 0]
windows:
  "7d":
    pushes: 0
    distinct_repos: 0
    active_days: 0
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 0
    distinct_repos: 0
    active_days: 0
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 49
    distinct_repos: 12
    active_days: 17
    repos_not_owned: 9
    not_owned_basenames: 1
    not_owned_owners: 9
automation:
  state: "clear"
  push_per_day: 2.8824
  repo_per_active_day: 0.7059
  not_owned_ratio: 0.7500
  basename_concentration: 0.8333
  shapes:
    - "fork_farm_own_upstream"
  shape_evidence:
    - "basename concentration 0.8333 (10 of 12 repos share one basename), 9 not owned across 1 basenames — 5 of 5 sampled repos resolved; 5 fork an upstream this account owns; upstreams: calesthio/OpenMontage"
  cleared_by: "e01-builder"
  cleared_on: "2026-08-26"
  fork_provenance:
    checked: 5
    own_upstream: 5
    third_party: 0
    no_upstream: 0
    unresolved: 0
    truncated: false
    sampled:
      - "abdel-darwish-27/OpenMontage"
      - "amartya-dev/OpenMontage"
      - "clarkhjc/OpenMontage"
      - "ikohu-66/OpenMontage"
      - "MoltyHeyworth/OpenMontage"
    upstreams:
      - "calesthio/OpenMontage"
  prefilter: "rest_verified"
facets:
  "7d":
    pushes: 0
    distinct_repos: 0
    pushes_per_repo: 0.0000
    active_days: 0
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 0
    distinct_repos: 0
    pushes_per_repo: 0.0000
    active_days: 0
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 49
    distinct_repos: 12
    pushes_per_repo: 4.0833
    active_days: 17
    repos_not_owned: 9
    not_owned_basenames: 1
    not_owned_owners: 9
reasons:
  - "provenance: 1 vault signal(s) — pass"
  - "activity: 17 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "Crucix"
    title: "Crucix"
    description: "Your personal intelligence agent. Watches the world from multiple data sources and pings you when something changes."
    language: "JavaScript"
    topics:
      - "ai"
      - "intelligence"
      - "osint"
    stars_fact: 11969
    first_seen: null
    last_push: "2026-05-20"
  - name: "OpenMontage"
    title: "OpenMontage"
    description: "World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge files. Turn your AI coding assistant into a full video production studio."
    language: "Python"
    topics:
      - "agent"
      - "agentic-ai"
      - "ai"
      - "claude"
      - "copilot"
      - "cursor"
      - "elevenlabs"
      - "ffmpeg"
      - "flux"
      - "image-generation"
      - "open-source"
      - "openai"
      - "python"
      - "remotion"
      - "stable-diffusion"
      - "text-to-speech"
      - "text-to-video"
      - "video-generation"
      - "video-production"
    stars_fact: 60995
    first_seen: "2026-06-19T17:17:11.400096+00:00"
    last_push: "2026-09-06"
  - name: "SessionAnchor"
    title: "SessionAnchor"
    description: "One-command context memory for Claude Code sessions. Local SQLite, zero dependencies."
    language: "Python"
    topics:
      - "claude-code"
      - "context-management"
      - "developer-tools"
      - "llm"
      - "memory"
      - "python"
      - "sqlite"
    stars_fact: 27
    first_seen: null
    last_push: "2026-03-25"
  - name: "PhantomReach"
    title: "PhantomReach"
    description: "Free, open-source local business intelligence audits for marketers and agencies. Run on your machine with real public data, and agentic workflow"
    language: "TypeScript"
    topics:
      - "agentic-ai"
      - "ai"
      - "audits"
      - "business-intelligence"
      - "claude"
      - "copilot"
      - "cursor"
      - "google-places"
      - "lead-generation"
      - "local-business"
      - "marketing"
      - "nextjs"
      - "open-source"
      - "self-hosted"
      - "seo"
      - "sqlite"
      - "typescript"
    stars_fact: 58
    first_seen: null
    last_push: "2026-06-27"
  - name: "generative-media-skills"
    title: "generative-media-skills"
    description: "Research-backed agent skills and tools for premium image, video, audio, voice, and generative media production across AI coding assistants."
    language: "Python"
    topics:
      - "agent"
      - "agentic-ai"
      - "ai"
      - "ai-audio"
      - "ai-video"
      - "claude"
      - "codex"
      - "copilot"
      - "cursor"
      - "generative-media"
      - "github-copilot"
      - "image-generation"
      - "open-source"
      - "openai"
      - "prompt-engineering"
      - "skill"
      - "text-to-speech"
      - "text-to-video"
      - "video-generation"
      - "video-production"
    stars_fact: 181
    first_seen: null
    last_push: "2026-07-14"
  - name: "OptionsCanvas"
    title: "OptionsCanvas"
    description: "Stop getting your stops hunted. SL/TP never touch your broker - only fires when the underlying actually breaches your level. And skip the options chain: drag your levels on the chart, we auto-pick the strike + DTE + contracts. The first open-source platform that does both."
    language: "Python"
    topics:
      - "0dte"
      - "algorithmic-trading"
      - "alpaca"
      - "charting"
      - "day-trading"
      - "fintech"
      - "flask"
      - "lightweight-charts"
      - "local-first"
      - "open-source"
      - "options"
      - "options-trading"
      - "python"
      - "self-hosted"
      - "trading-platform"
      - "vanilla-js"
    stars_fact: 68
    first_seen: null
    last_push: "2026-05-28"
---

# calesthio

49 pushes across 12 repositories on 17 active days in the last 90 days of public GitHub push activity.

https://github.com/calesthio
