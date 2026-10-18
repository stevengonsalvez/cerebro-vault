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
generated_at: "2026-10-18T06:04:36.280265+00:00"
provenance:
  - "4d1450729e6ff44d"
pushes_per_week: [0, 0, 0, 0, 0, 0, 0, 8, 2, 7, 21, 7, 4]
windows:
  "7d":
    pushes: 5
    distinct_repos: 4
    active_days: 4
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 40
    distinct_repos: 9
    active_days: 15
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 49
    distinct_repos: 9
    active_days: 21
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
automation:
  state: "clear"
  push_per_day: 2.3333
  repo_per_active_day: 0.4286
  not_owned_ratio: 0.0000
  basename_concentration: 0.1111
  shapes: []
  shape_evidence: []
  cleared_by: null
  cleared_on: null
  fork_provenance: null
  prefilter: "rest_verified"
facets:
  "7d":
    pushes: 5
    distinct_repos: 4
    pushes_per_repo: 1.2500
    active_days: 4
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 40
    distinct_repos: 9
    pushes_per_repo: 4.4444
    active_days: 15
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 49
    distinct_repos: 9
    pushes_per_repo: 5.4444
    active_days: 21
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
reasons:
  - "provenance: 1 vault signal(s) — pass"
  - "activity: 21 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "ggbdpq"
    title: "ggbdpq"
    description: "Frontend Engineer → AI Developer Tooling · LLM gateway · agent runtime · agent skills"
    language: "Python"
    topics: []
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-17"
  - name: "cursor-loc"
    title: "cursor-loc"
    description: "为 Cursor IDE 专有界面提供简体中文汉化：覆盖 Settings、Agent、Composer、Review 等 Microsoft 官方语言包 NLS 无法触及的区域，英文界面下也可用。重难点：0.0.9 注入引擎重写为增量翻译——移除每 100ms 全页扫描、attachShadow 原型劫持与 DOM 变更全页重扫三个卡顿根源，exact 词条走 O(1) Map、变更只处理涉及节点，打字与滚动不再被拖慢；补丁仅手动应用时写入安装目录，卸载自动还原，缺备份时如实报告受限项不猜测拼接。"
    language: "TypeScript"
    topics: []
    stars_fact: 5
    first_seen: null
    last_push: "2026-10-10"
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
    last_push: "2026-10-01"
  - name: "agent-skills"
    title: "agent-skills"
    description: "实战沉淀的 Agent Skills 公开合集，Codex / Claude Code / Cursor 等支持 Skills 的工具可直接装配：npx skills add ggbdpq/agent-skills 整仓或按单个 skill 安装。当前提供 minimal-diff-fix（不扩散改动面的局部修复）、tech-writer（技术文档英译中与发布级终稿）、mentor-me（导师式概念讲解，结合真实项目举例）。维护原则：SKILL.md 跨工具核心，.curated / .experimental 分层，新 skill 先试验后转正。"
    language: "Python"
    topics: []
    stars_fact: 1
    first_seen: null
    last_push: "2026-09-30"
  - name: "react-helper-toolkit"
    title: "react-helper-toolkit"
    description: "React Hooks 工具库：零运行时依赖、UI 无关。Core 层纯函数可在 Node / Worker 任意 JS 环境运行，Hooks 层对 Core 薄封装、仅依赖 React。亮点：公开 API 稳定可预测，渐进接入不破坏；tree-shaking 友好，统一导出与自动化验证；ref + effect cleanup 模式保持最新回调并兼容 StrictMode 双调用；React 16.8+ 原生状态与副作用模型，不引入额外响应式抽象，附中文注释契约。"
    language: "TypeScript"
    topics: []
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-10"
  - name: "syntax-party"
    title: "syntax-party"
    description: "中英双语五后端语言对照学习站：同一主题 Python / Node / Java / Go / Rust 并排展示。亮点：不止语法对照——15 个可运行实验室服务分三档关卡（Hello → Todo CRUD → JWT 鉴权），配全栈核心四层地图（HTTP→鉴权→数据→上线）6 天主线与 JSON / Git / MySQL 工具课；npm test 机器校验实验室入口齐全、端口不冲突。Vite + React 19 + TypeScript + Tailwind + Prism.js，面向前端工程师转全栈。"
    language: "TypeScript"
    topics: []
    stars_fact: 1
    first_seen: null
    last_push: "2026-10-10"
---

# ggbdpq

49 pushes across 9 repositories on 21 active days in the last 90 days of public GitHub push activity.

https://github.com/ggbdpq
