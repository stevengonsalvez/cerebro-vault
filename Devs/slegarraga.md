---
login: "slegarraga"
name: null
discovered_via: "fanout"
discovered_via_all:
  - "fanout"
provenance_repos:
  - "asamassekou10/ship-safe"
admitted: true
low_n: false
repos_populated: true
generated_at: "2026-10-24T06:05:01.431039+00:00"
provenance:
  - "9e2ff10d772b1e71"
pushes_per_week: [0, 11, 0, 4, 1, 0, 0, 0, 0, 0, 0, 0, 2]
windows:
  "7d":
    pushes: 2
    distinct_repos: 2
    active_days: 2
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 2
    distinct_repos: 2
    active_days: 2
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 18
    distinct_repos: 15
    active_days: 6
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
automation:
  state: "clear"
  push_per_day: 3.0000
  repo_per_active_day: 2.5000
  not_owned_ratio: 0.0000
  basename_concentration: 0.0667
  shapes: []
  shape_evidence: []
  cleared_by: null
  cleared_on: null
  fork_provenance: null
  prefilter: "rest_verified"
facets:
  "7d":
    pushes: 2
    distinct_repos: 2
    pushes_per_repo: 1.0000
    active_days: 2
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 2
    distinct_repos: 2
    pushes_per_repo: 1.0000
    active_days: 2
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 18
    distinct_repos: 15
    pushes_per_repo: 1.2000
    active_days: 6
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
reasons:
  - "provenance: 1 vault signal(s) — pass"
  - "activity: 6 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "tool-schema"
    title: "tool-schema"
    description: "Convert any JSON Schema into a valid tool / function calling schema for OpenAI, Anthropic, Gemini and MCP. Zero dependencies."
    language: "TypeScript"
    topics:
      - "ai-agents"
      - "anthropic"
      - "function-calling"
      - "gemini"
      - "json-schema"
      - "llm"
      - "mcp"
      - "model-context-protocol"
      - "openai"
      - "openai-compatible"
      - "provider-portability"
      - "structured-outputs"
      - "tool-calling"
      - "tool-use"
      - "typescript"
      - "zero-dependencies"
    stars_fact: 2
    first_seen: null
    last_push: "2026-10-19"
  - name: "json-from-llm"
    title: "json-from-llm"
    description: "Extract valid JSON from an LLM response, even when wrapped in reasoning/thinking tags, markdown fences or prose. Zero dependencies."
    language: "TypeScript"
    topics:
      - "ai-agents"
      - "anthropic"
      - "deepseek"
      - "gemini"
      - "json"
      - "json-parser"
      - "llm"
      - "llm-output"
      - "openai"
      - "openai-compatible"
      - "parser"
      - "reasoning"
      - "structured-output"
      - "tool-calling"
      - "typescript"
      - "zero-dependencies"
    stars_fact: 1
    first_seen: null
    last_push: "2026-10-15"
  - name: "llm-errors"
    title: "llm-errors"
    description: "Normalize OpenAI, Anthropic and Gemini API errors into one shape: category, retryable flag and Retry-After delay. Zero dependencies."
    language: "TypeScript"
    topics:
      - "ai"
      - "ai-agents"
      - "anthropic"
      - "api-errors"
      - "error-handling"
      - "gemini"
      - "llm"
      - "openai"
      - "openai-compatible"
      - "provider-portability"
      - "rate-limit"
      - "retry"
      - "retry-after"
      - "typescript"
      - "zero-dependencies"
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-15"
  - name: "llm-portability-demo"
    title: "llm-portability-demo"
    description: "Zero-dependency provider-portability packages for OpenAI-compatible agents working together end to end. Runs offline."
    language: "JavaScript"
    topics:
      - "ai-agents"
      - "anthropic"
      - "example"
      - "gemini"
      - "llm"
      - "mcp"
      - "openai"
      - "openai-compatible"
      - "portability"
      - "provider"
      - "provider-portability"
      - "streaming"
      - "structured-outputs"
      - "tool-calling"
      - "typescript"
      - "zero-dependencies"
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-15"
  - name: "llm-sse"
    title: "llm-sse"
    description: "Parse streaming responses from OpenAI, Anthropic and Gemini into one unified event format. Text and tool-call deltas. Zero dependencies."
    language: "TypeScript"
    topics:
      - "ai"
      - "ai-agents"
      - "anthropic"
      - "gemini"
      - "llm"
      - "openai"
      - "openai-compatible"
      - "provider-portability"
      - "reasoning"
      - "sse"
      - "streaming"
      - "tool-calling"
      - "tool-calls"
      - "typescript"
      - "zero-dependencies"
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-15"
  - name: "llm-messages"
    title: "llm-messages"
    description: "OpenAI-compatible provider portability: convert chat conversations between OpenAI, Anthropic and Gemini. Tool calls, multimodal parts, zero deps."
    language: "TypeScript"
    topics:
      - "ai-agents"
      - "anthropic"
      - "chat-completions"
      - "claude"
      - "function-calling"
      - "gemini"
      - "llm"
      - "messages"
      - "multimodal"
      - "openai"
      - "openai-compatible"
      - "provider-portability"
      - "structured-outputs"
      - "tool-calling"
      - "tool-use"
      - "typescript"
      - "zero-dependencies"
    stars_fact: 3
    first_seen: null
    last_push: "2026-10-13"
---

# slegarraga

18 pushes across 15 repositories on 6 active days in the last 90 days of public GitHub push activity.

https://github.com/slegarraga
