---
login: "teamchong"
name: null
discovered_via: "vault"
discovered_via_all:
  - "fanout"
  - "vault"
provenance_repos:
  - "cloudflare/cloudflare-os"
  - "teamchong/pxpipe"
admitted: true
low_n: false
repos_populated: true
generated_at: "2026-09-26T06:06:37.922852+00:00"
provenance:
  - "1320ae46b426dee5"
  - "386c24cf5e18fd90"
pushes_per_week: [8, 8, 9, 15, 5, 5, 8, 2, 0, 0, 0, 0, 1]
windows:
  "7d":
    pushes: 1
    distinct_repos: 1
    active_days: 1
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 1
    distinct_repos: 1
    active_days: 1
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 61
    distinct_repos: 11
    active_days: 30
    repos_not_owned: 4
    not_owned_basenames: 2
    not_owned_owners: 4
automation:
  state: "clear"
  push_per_day: 2.0333
  repo_per_active_day: 0.3667
  not_owned_ratio: 0.3636
  basename_concentration: 0.3636
  shapes: []
  shape_evidence: []
  cleared_by: null
  cleared_on: null
  fork_provenance: null
  prefilter: "rest_verified"
facets:
  "7d":
    pushes: 1
    distinct_repos: 1
    pushes_per_repo: 1.0000
    active_days: 1
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 1
    distinct_repos: 1
    pushes_per_repo: 1.0000
    active_days: 1
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 61
    distinct_repos: 11
    pushes_per_repo: 5.5455
    active_days: 30
    repos_not_owned: 4
    not_owned_basenames: 2
    not_owned_owners: 4
reasons:
  - "provenance: 2 vault signal(s) — pass"
  - "activity: 30 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "pxpipe"
    title: "pxpipe"
    description: "cut Claude Code token usage by rendering text context as images"
    language: "TypeScript"
    topics: []
    stars_fact: 7431
    first_seen: "2026-07-06T06:00:04.675243+00:00"
    last_push: "2026-09-16"
  - name: "turboquant-wasm"
    title: "turboquant-wasm"
    description: "TurboQuant WASM SIMD vector compression — 3 bits/dim with fast dot product. Requires relaxed SIMD (Chrome 114+, Firefox 128+, Safari 18+, Node 20+)"
    language: "Zig"
    topics: []
    stars_fact: 322
    first_seen: null
    last_push: "2026-04-19"
  - name: "vectorjson"
    title: "vectorjson"
    description: "O(n) streaming JSON parser for LLM tool calls. Agents act sooner, abort bad outputs early. WASM SIMD, up to 2000× faster than stock AI SDK parsers."
    language: "JavaScript"
    topics:
      - "ai-sdk"
      - "json"
      - "llm"
      - "parser"
      - "partial-json"
      - "simd"
      - "simdjson"
      - "streaming"
      - "wasm"
      - "zig"
    stars_fact: 18
    first_seen: null
    last_push: "2026-03-10"
  - name: "wardex"
    title: "wardex"
    description: "Run any coding-agent CLI (claude, codex, aider, ...) behind two boundaries it can't ignore: a logging/enforcing egress proxy and a zero-install, kernel-enforced filesystem jail."
    language: "Go"
    topics: []
    stars_fact: 0
    first_seen: null
    last_push: "2026-08-04"
  - name: "gitmode"
    title: "gitmode"
    description: "Git server & client as npm package for Cloudflare Workers — Zig/WASM engine with SIMD128, libgit2, R2 chunk storage, Durable Objects (per-repo SQLite)"
    language: "TypeScript"
    topics: []
    stars_fact: 3
    first_seen: null
    last_push: "2026-06-01"
  - name: "textsift"
    title: "textsift"
    description: "Local-first PII detection + redaction running openai/privacy-filter on-device. Same engine in browser (WebGPU), Node native (Metal/Vulkan/Dawn), CLI, pre-commit hook, and GitHub Action."
    language: "TypeScript"
    topics:
      - "dawn"
      - "github-action"
      - "local-first"
      - "metal"
      - "openai"
      - "pii"
      - "pre-commit-hook"
      - "privacy"
      - "privacy-filter"
      - "redaction"
      - "sarif"
      - "vulkan"
      - "wasm"
      - "webgpu"
    stars_fact: 3
    first_seen: null
    last_push: "2026-08-02"
---

# teamchong

61 pushes across 11 repositories on 30 active days in the last 90 days of public GitHub push activity.

https://github.com/teamchong
