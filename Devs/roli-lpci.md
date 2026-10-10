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
generated_at: "2026-10-10T06:04:44.283147+00:00"
provenance:
  - "97c4e9cb8b163ddb"
  - "c7515e0fa4368a55"
  - "d3abe74726b22711"
  - "e7c647c4d0689526"
pushes_per_week: [4, 1, 4, 15, 4, 1, 0, 0, 10, 43, 33, 35, 0]
windows:
  "7d":
    pushes: 1
    distinct_repos: 1
    active_days: 1
    repos_not_owned: 1
    not_owned_basenames: 1
    not_owned_owners: 1
  "30d":
    pushes: 118
    distinct_repos: 44
    active_days: 19
    repos_not_owned: 32
    not_owned_basenames: 32
    not_owned_owners: 1
  "90d":
    pushes: 150
    distinct_repos: 50
    active_days: 35
    repos_not_owned: 37
    not_owned_basenames: 37
    not_owned_owners: 1
automation:
  state: "clear"
  push_per_day: 4.2857
  repo_per_active_day: 1.4286
  not_owned_ratio: 0.7400
  basename_concentration: 0.0400
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
    repos_not_owned: 1
    not_owned_basenames: 1
    not_owned_owners: 1
  "30d":
    pushes: 118
    distinct_repos: 44
    pushes_per_repo: 2.6818
    active_days: 19
    repos_not_owned: 32
    not_owned_basenames: 32
    not_owned_owners: 1
  "90d":
    pushes: 150
    distinct_repos: 50
    pushes_per_repo: 3.0000
    active_days: 35
    repos_not_owned: 37
    not_owned_basenames: 37
    not_owned_owners: 1
reasons:
  - "provenance: 4 vault signal(s) — pass"
  - "activity: 35 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "agent-trash-guard"
    title: "agent-trash-guard"
    description: "Recoverable deletion guard and trash workflow for Claude Code, Codex, and Gemini CLI agents"
    language: "Python"
    topics:
      - "agent-skills"
      - "ai-agents"
      - "claude-code"
      - "claude-code-plugin"
      - "cli"
      - "codex"
      - "developer-tools"
      - "file-recovery"
      - "gemini-cli-extension"
      - "git"
      - "hermes-labs"
      - "safety"
      - "undo"
    stars_fact: 2
    first_seen: null
    last_push: "2026-10-08"
  - name: "hermes-gate"
    title: "hermes-gate"
    description: "Receipt-bound completion rail for coding agents"
    language: "Python"
    topics:
      - "agent-skills"
      - "ai-agents"
      - "ci-cd"
      - "claude-code"
      - "claude-code-plugin"
      - "code-quality"
      - "coding-agents"
      - "continuous-integration"
      - "developer-tools"
      - "github-actions"
      - "hermes-labs"
      - "python"
      - "quality-gate"
      - "reproducibility"
    stars_fact: 3
    first_seen: null
    last_push: "2026-10-01"
  - name: "csv-quality-gate"
    title: "csv-quality-gate"
    description: "csv-quality-gate is a command-line data quality gate that runs CSV preflight validation, failing fast before an ML or LLM pipeline ingests broken, incomplete, duplicated, or junk input. It checks missing columns, empty files, empty cells, and duplicate rows, returning pass, warn, or fail with matching exit codes. Stdlib-only, CI-ready."
    language: "Python"
    topics:
      - "agent-skills"
      - "ai-reliability"
      - "ci"
      - "claude-code-plugin"
      - "cli"
      - "csv"
      - "data-quality"
      - "data-validation"
      - "developer-tools"
      - "etl"
      - "gemini-cli-extension"
      - "github-actions"
      - "hermes-labs"
      - "llm-ops"
      - "ml-pipeline"
      - "pipeline"
      - "pre-commit"
      - "preflight"
      - "python"
      - "quality-gate"
    stars_fact: 1
    first_seen: null
    last_push: "2026-09-29"
  - name: "intent-verify"
    title: "intent-verify"
    description: "intent-verify is a deterministic, zero-LLM CLI that checks whether a repo's source still lexically covers the acceptance items in a markdown spec, INTENT.md, or handoff doc, returning verified, partial, or missing. A fast guardrail for catching spec-vs-code drift before review, release, or handoff. Lexical coverage, not semantic proof."
    language: "Python"
    topics:
      - "agent-skills"
      - "ai-agents"
      - "ai-reliability"
      - "ci"
      - "claude-code-plugin"
      - "cli"
      - "code-quality"
      - "developer-tools"
      - "drift-detection"
      - "gemini-cli-extension"
      - "github-actions"
      - "hermes-labs"
      - "llm"
      - "python"
      - "requirements-traceability"
      - "spec"
      - "spec-drift"
      - "static-analysis"
      - "verification"
      - "zero-llm"
    stars_fact: 1
    first_seen: null
    last_push: "2026-09-29"
  - name: "rule-audit"
    title: "rule-audit"
    description: "Static analyzer for AI system prompts: parses a prompt into normative rules and reports contradictions, coverage gaps, priority ambiguities, and absolute-rule edge cases - no LLM calls. Deterministic pure-Python lint with CLI, Python API, and CI exit codes. pip install rule-audit"
    language: "Python"
    topics:
      - "agent-skills"
      - "ai-agents"
      - "ai-reliability"
      - "ai-safety"
      - "claude-code-plugin"
      - "cli"
      - "contradiction-detection"
      - "developer-tools"
      - "gemini-cli-extension"
      - "github-actions"
      - "hermes-labs"
      - "linter"
      - "llm"
      - "pre-commit"
      - "prompt-engineering"
      - "prompt-linter"
      - "python"
      - "static-analysis"
      - "system-prompts"
      - "zero-llm"
    stars_fact: 3
    first_seen: null
    last_push: "2026-09-29"
  - name: "forgetted"
    title: "forgetted"
    description: "forgetted is a Python library for selective memory governance in AI agents: a context-managed window where the agent keeps full read access but its writes to memory files, session logs, deliverables, and an optional vector store vanish and are cleaned up on exit."
    language: "Python"
    topics:
      - "agent-memory"
      - "agent-safety"
      - "ai-agents"
      - "ai-safety"
      - "claude-code"
      - "context-manager"
      - "data-privacy"
      - "ephemeral-memory"
      - "hermes-labs"
      - "incognito"
      - "llm"
      - "memory-governance"
      - "privacy"
      - "python"
    stars_fact: 3
    first_seen: null
    last_push: "2026-10-03"
---

# roli-lpci

150 pushes across 50 repositories on 35 active days in the last 90 days of public GitHub push activity.

https://github.com/roli-lpci
