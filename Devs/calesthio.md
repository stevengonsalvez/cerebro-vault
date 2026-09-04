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
generated_at: "2026-09-04T06:06:21.234597+00:00"
provenance:
  - "6d3bd03b49986330"
pushes_per_week: [0, 0, 9, 12, 13, 2, 6, 0, 0, 13, 0, 1, 0]
windows:
  "7d":
    pushes: 0
    distinct_repos: 0
    active_days: 0
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 14
    distinct_repos: 9
    active_days: 2
    repos_not_owned: 8
    not_owned_basenames: 1
    not_owned_owners: 8
  "90d":
    pushes: 56
    distinct_repos: 13
    active_days: 20
    repos_not_owned: 10
    not_owned_basenames: 1
    not_owned_owners: 10
automation:
  state: "clear"
  push_per_day: 2.8000
  repo_per_active_day: 0.6500
  not_owned_ratio: 0.7692
  basename_concentration: 0.8462
  shapes:
    - "fork_farm_own_upstream"
  shape_evidence:
    - "basename concentration 0.8462 (11 of 13 repos share one basename), 10 not owned across 1 basenames — 5 of 5 sampled repos resolved; 5 fork an upstream this account owns; upstreams: calesthio/OpenMontage"
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
      - "Diwakar-odds/OpenMontage"
      - "ikohu-66/OpenMontage"
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
    pushes: 14
    distinct_repos: 9
    pushes_per_repo: 1.5556
    active_days: 2
    repos_not_owned: 8
    not_owned_basenames: 1
    not_owned_owners: 8
  "90d":
    pushes: 56
    distinct_repos: 13
    pushes_per_repo: 4.3077
    active_days: 20
    repos_not_owned: 10
    not_owned_basenames: 1
    not_owned_owners: 10
reasons:
  - "provenance: 1 vault signal(s) — pass"
  - "activity: 20 active days in 90d — pass"
  - "automation: clear — pass"
repos:
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
    stars_fact: 55904
    first_seen: "2026-08-12T06:00:08.422592+00:00"
    last_push: "2026-08-22"
  - name: "Crucix"
    title: "Crucix"
    description: "Your personal intelligence agent. Watches the world from multiple data sources and pings you when something changes."
    language: "JavaScript"
    topics:
      - "ai"
      - "intelligence"
      - "osint"
    stars_fact: 11612
    first_seen: null
    last_push: "2026-05-20"
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
    stars_fact: 148
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
    stars_fact: 61
    first_seen: null
    last_push: "2026-05-28"
  - name: "Resonant"
    title: "Resonant"
    description: "Free, local AI music studio for Windows—generate songs, play instruments, arrange, mix, export WAV, and connect Codex or Claude through MCP."
    language: "TypeScript"
    topics:
      - "ace-step"
      - "ai-music"
      - "digital-audio-workstation"
      - "electron"
      - "generative-music"
      - "mcp"
      - "model-context-protocol"
      - "music-production"
      - "open-source"
      - "typescript"
      - "windows"
    stars_fact: 131
    first_seen: null
    last_push: "2026-08-07"
  - name: "BreakoutAnalysis"
    title: "BreakoutAnalysis"
    description: null
    language: "Python"
    topics: []
    stars_fact: 280
    first_seen: null
    last_push: "2026-02-23"
---

# calesthio

56 pushes across 13 repositories on 20 active days in the last 90 days of public GitHub push activity.

https://github.com/calesthio
