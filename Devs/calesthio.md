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
low_n: true
repos_populated: true
generated_at: "2026-10-24T06:05:01.431039+00:00"
provenance:
  - "6d3bd03b49986330"
pushes_per_week: [0, 0, 13, 1, 0, 0, 0, 0, 0, 1, 0, 5, 0]
windows:
  "7d":
    pushes: 0
    distinct_repos: 0
    active_days: 0
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 6
    distinct_repos: 2
    active_days: 2
    repos_not_owned: 1
    not_owned_basenames: 1
    not_owned_owners: 1
  "90d":
    pushes: 20
    distinct_repos: 10
    active_days: 4
    repos_not_owned: 9
    not_owned_basenames: 1
    not_owned_owners: 9
automation:
  state: "clear"
  push_per_day: 5.0000
  repo_per_active_day: 2.5000
  not_owned_ratio: 0.9000
  basename_concentration: 1.0000
  shapes:
    - "fork_farm_own_upstream"
  shape_evidence:
    - "basename concentration 1.0000 (10 of 10 repos share one basename), 9 not owned across 1 basenames — 5 of 5 sampled repos resolved; 5 fork an upstream this account owns; upstreams: calesthio/OpenMontage"
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
    pushes: 6
    distinct_repos: 2
    pushes_per_repo: 3.0000
    active_days: 2
    repos_not_owned: 1
    not_owned_basenames: 1
    not_owned_owners: 1
  "90d":
    pushes: 20
    distinct_repos: 10
    pushes_per_repo: 2.0000
    active_days: 4
    repos_not_owned: 9
    not_owned_basenames: 1
    not_owned_owners: 9
reasons:
  - "provenance: 1 vault signal(s) — pass"
  - "activity: 4 active days in 90d — below the 5-day line, LABELLED low-n (never suppressed)"
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
    stars_fact: 69262
    first_seen: "2026-06-19T17:17:11.400096+00:00"
    last_push: "2026-10-16"
  - name: "Crucix"
    title: "Crucix"
    description: "Your personal intelligence agent. Watches the world from multiple data sources and pings you when something changes."
    language: "JavaScript"
    topics:
      - "ai"
      - "intelligence"
      - "osint"
    stars_fact: 12129
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
    stars_fact: 205
    first_seen: null
    last_push: "2026-07-14"
  - name: "BreakoutAnalysis"
    title: "BreakoutAnalysis"
    description: null
    language: "Python"
    topics: []
    stars_fact: 279
    first_seen: null
    last_push: "2026-02-23"
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
    stars_fact: 161
    first_seen: null
    last_push: "2026-08-07"
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
    stars_fact: 67
    first_seen: null
    last_push: "2026-06-27"
---

# calesthio

20 pushes across 10 repositories on 4 active days in the last 90 days of public GitHub push activity.

https://github.com/calesthio
