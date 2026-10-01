---
login: "teknium1"
name: null
discovered_via: "vault"
discovered_via_all:
  - "fanout"
  - "vault"
provenance_repos:
  - "agentskills/agentskills"
  - "NousResearch/hermes-agent"
admitted: true
low_n: false
repos_populated: true
generated_at: "2026-10-01T06:06:11.188250+00:00"
provenance:
  - "48dbbdd8fd0d3029"
  - "ec2b8bd43eefd65f"
pushes_per_week: [131, 51, 79, 108, 30, 80, 107, 43, 11, 25, 107, 333, 95]
windows:
  "7d":
    pushes: 104
    distinct_repos: 16
    active_days: 7
    repos_not_owned: 15
    not_owned_basenames: 2
    not_owned_owners: 15
  "30d":
    pushes: 560
    distinct_repos: 40
    active_days: 24
    repos_not_owned: 38
    not_owned_basenames: 3
    not_owned_owners: 37
  "90d":
    pushes: 1200
    distinct_repos: 48
    active_days: 75
    repos_not_owned: 45
    not_owned_basenames: 4
    not_owned_owners: 43
automation:
  state: "clear"
  push_per_day: 16.0000
  repo_per_active_day: 0.6400
  not_owned_ratio: 0.9375
  basename_concentration: 0.8750
  shapes:
    - "high_push_rate"
    - "fork_farm_third_party"
  shape_evidence:
    - "16.00 pushes per active day over 90d (1200 pushes / 75 active days), above the 15 review line"
    - "basename concentration 0.8750 (42 of 48 repos share one basename), 45 not owned across 4 basenames — 5 of 5 sampled repos resolved; 5 fork somebody else's repo; upstreams: NousResearch/hermes-agent"
  cleared_by: "e01-builder"
  cleared_on: "2026-08-26"
  fork_provenance:
    checked: 5
    own_upstream: 0
    third_party: 5
    no_upstream: 0
    unresolved: 0
    truncated: false
    sampled:
      - "ajensenwaud/hermes-agent"
      - "amekala/hermes-agent"
      - "AndreasHiltner/hermes-agent"
      - "anpicasso/hermes-agent"
      - "apoapostolov/hermes-agent"
    upstreams:
      - "NousResearch/hermes-agent"
  prefilter: "rest_verified"
facets:
  "7d":
    pushes: 104
    distinct_repos: 16
    pushes_per_repo: 6.5000
    active_days: 7
    repos_not_owned: 15
    not_owned_basenames: 2
    not_owned_owners: 15
  "30d":
    pushes: 560
    distinct_repos: 40
    pushes_per_repo: 14.0000
    active_days: 24
    repos_not_owned: 38
    not_owned_basenames: 3
    not_owned_owners: 37
  "90d":
    pushes: 1200
    distinct_repos: 48
    pushes_per_repo: 25.0000
    active_days: 75
    repos_not_owned: 45
    not_owned_basenames: 4
    not_owned_owners: 43
reasons:
  - "provenance: 2 vault signal(s) — pass"
  - "activity: 75 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "hermes-star-trek-profiles"
    title: "hermes-star-trek-profiles"
    description: "68 installable Star Trek-inspired profile distributions for Hermes Agent"
    language: "Python"
    topics:
      - "ai-agent"
      - "hermes-agent"
      - "personas"
      - "profiles"
      - "star-trek"
    stars_fact: 13
    first_seen: null
    last_push: "2026-07-13"
  - name: "hermetic-codex-tweaks"
    title: "hermetic-codex-tweaks"
    description: "Companion client mod for The Hermetic Codex modpack — configurable Cobblemon party HUD position."
    language: "Java"
    topics: []
    stars_fact: 5
    first_seen: null
    last_push: "2026-06-24"
  - name: "hermetic-codex-docs"
    title: "hermetic-codex-docs"
    description: "Documentation site for The Hermetic Codex — a Minecraft 1.21.1 NeoForge modpack."
    language: null
    topics: []
    stars_fact: 4
    first_seen: null
    last_push: "2026-05-08"
  - name: "nous-discord-archive"
    title: "nous-discord-archive"
    description: "Auto-archived text logs of Nous Research Discord channels (polled every 6h)"
    language: "Python"
    topics: []
    stars_fact: 57
    first_seen: null
    last_push: "2026-08-18"
  - name: "teknium1"
    title: "teknium1"
    description: "Config files for my GitHub profile."
    language: null
    topics:
      - "config"
      - "github-config"
    stars_fact: 15
    first_seen: null
    last_push: "2026-04-20"
  - name: "hermes-lang-pl"
    title: "hermes-lang-pl"
    description: "Polish (Polski) language pack for Hermes Agent — text-only plugin: core, Desktop and TUI catalogs"
    language: null
    topics: []
    stars_fact: 0
    first_seen: null
    last_push: "2026-09-28"
---

# teknium1

1200 pushes across 48 repositories on 75 active days in the last 90 days of public GitHub push activity.

https://github.com/teknium1
