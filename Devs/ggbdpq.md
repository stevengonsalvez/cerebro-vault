---
login: "ggbdpq"
name: null
discovered_via: "fanout"
discovered_via_all:
  - "fanout"
provenance_repos:
  - "apache/maka"
admitted: true
low_n: false
repos_populated: true
generated_at: "2026-10-28T07:04:58.274214+00:00"
provenance:
  - "4d1450729e6ff44d"
pushes_per_week: [0, 0, 0, 0, 0, 5, 3, 2, 21, 10, 8, 2, 6]
windows:
  "7d":
    pushes: 6
    distinct_repos: 5
    active_days: 2
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 38
    distinct_repos: 11
    active_days: 16
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 57
    distinct_repos: 11
    active_days: 24
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
automation:
  state: "clear"
  push_per_day: 2.3750
  repo_per_active_day: 0.4583
  not_owned_ratio: 0.0000
  basename_concentration: 0.0909
  shapes: []
  shape_evidence: []
  cleared_by: null
  cleared_on: null
  fork_provenance: null
  prefilter: "rest_verified"
facets:
  "7d":
    pushes: 6
    distinct_repos: 5
    pushes_per_repo: 1.2000
    active_days: 2
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 38
    distinct_repos: 11
    pushes_per_repo: 3.4545
    active_days: 16
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 57
    distinct_repos: 11
    pushes_per_repo: 5.1818
    active_days: 24
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
reasons:
  - "provenance: 1 vault signal(s) — pass"
  - "activity: 24 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "ggbdpq"
    title: "ggbdpq"
    description: "Frontend Engineer → AI Developer Tooling · LLM gateway · agent runtime · agent skills"
    language: "Python"
    topics: []
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-26"
  - name: "coding-agent"
    title: "coding-agent"
    description: "Specification-driven Coding Agent Runtime：一套行为规范（specs/ 七篇 SSOT）在 TS / Python / Go / Rust / C# 五种语言运行时实现，可执行一致性套件以同一 scenario 驱动五 runtime、归一化后跨版比对，输出 PASS / ALLOW_DIFF / DRIFT。亮点：能力线对齐 v0.5.0（九工具、权限三态闸门、40 轮熔断、Plan Mode、apply_patch 原子补丁）；diff 裁决 fail closed，不可归类差异一律判漂移；sha256 构建新鲜度门防陈旧产物假象。核心主张：行为契约比任何一份实现都稳定，期望值只取自 specs，禁止从参考实现抄录。"
    language: "JavaScript"
    topics: []
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-25"
  - name: "agent-hub"
    title: "agent-hub"
    description: "Agent 工程演示：巡检多智能体 + 持久化运行时 + MCP/Skill + 混合检索 + 评测"
    language: "Python"
    topics:
      - "agent-ui"
      - "ai-agents"
      - "fastapi"
      - "langgraph"
      - "llm-evaluation"
      - "mcp"
      - "multi-agent"
      - "pydantic"
      - "rag"
      - "react"
      - "sse"
      - "streaming"
      - "zod"
      - "zustand"
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-25"
  - name: "qoder-proxy-api"
    title: "qoder-proxy-api"
    description: "本地多 Provider 协议网关：把 Gateway 私有协议、qodercli 子进程、Cloud Agents 官方 API 三条异构 Qoder 上游统一成一套 OpenAI / Anthropic 兼容 API（含流式），Claude Code 等客户端直连。亮点：下游协议 ↔ Canonical Event ↔ 上游 Provider 三层解耦，adapter 边界由 CI 架构检查强制，新增 Provider 协议层零改动；显式路由无 fallback，上游失败原样报错；89 项离线测试 + 真实 SSE 抓包 fixtures，无凭证 30 秒 demo。重难点：私有协议逆向与跨 chunk 流边界的协议级 characterization 测试。零第三方运行时依赖。"
    language: "TypeScript"
    topics:
      - "agent"
      - "anthropic"
      - "api-gateway"
      - "llm"
      - "openai"
      - "protocol-gateway"
      - "qoder"
      - "sse"
    stars_fact: 3
    first_seen: null
    last_push: "2026-10-20"
  - name: "cursor-loc"
    title: "cursor-loc"
    description: "为 Cursor IDE 专有界面提供简体中文汉化：覆盖 Settings、Agent、Composer、Review 等 Microsoft 官方语言包 NLS 无法触及的区域，英文界面下也可用。重难点：0.0.9 注入引擎重写为增量翻译——移除每 100ms 全页扫描、attachShadow 原型劫持与 DOM 变更全页重扫三个卡顿根源，exact 词条走 O(1) Map、变更只处理涉及节点，打字与滚动不再被拖慢；补丁仅手动应用时写入安装目录，卸载自动还原，缺备份时如实报告受限项不猜测拼接。"
    language: "TypeScript"
    topics: []
    stars_fact: 5
    first_seen: null
    last_push: "2026-10-10"
  - name: "agent-skills"
    title: "agent-skills"
    description: "实战沉淀的 Agent Skills 公开合集，Codex / Claude Code / Cursor 等支持 Skills 的工具可直接装配：npx skills add ggbdpq/agent-skills 整仓或按单个 skill 安装。当前提供 minimal-diff-fix（不扩散改动面的局部修复）、tech-writer（技术文档英译中与发布级终稿）、mentor-me（导师式概念讲解，结合真实项目举例）。维护原则：SKILL.md 跨工具核心，.curated / .experimental 分层，新 skill 先试验后转正。"
    language: "Python"
    topics: []
    stars_fact: 1
    first_seen: null
    last_push: "2026-09-30"
---

# ggbdpq

57 pushes across 11 repositories on 24 active days in the last 90 days of public GitHub push activity.

https://github.com/ggbdpq
