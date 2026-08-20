---
title: "Unclecheng-li/VulnClaw: 基于 AI Agent + MCP 工具链 + 渗透 Skill 编排， 配合大语言模型， 自然语言输入 → 自动完成「信息收集 → 漏洞发现 → 漏洞利用 → 报告生成」全流程。"
category: coding-agents-llm
tags: [ai/agents, vibe-coding]
source: github
url: https://github.com/Unclecheng-li/VulnClaw
score: 0.75
reason: "AI Agent security automation with MCP tool-chaining on-topic"
captured: 2026-06-30T06:00:04.277771+00:00
rating:
---
# Unclecheng-li/VulnClaw: 基于 AI Agent + MCP 工具链 + 渗透 Skill 编排， 配合大语言模型， 自然语言输入 → 自动完成「信息收集 → 漏洞发现 → 漏洞利用 → 报告生成」全流程。

> AI Agent security automation with MCP tool-chaining on-topic

AI 驱动的渗透测试 CLI 工具 — 说人话，打漏洞。
🌐 English version: README_EN.md
本项目是可独立运行的 AI 渗透测试 Agent。
基于 LLM Agent + MCP 工具链 + 渗透 Skill 编排， 配合 OpenAI / MiniMax / DeepSeek 等兼容模型， 自然语言输入 → 自动完成「信息收集 → 漏洞发现 → 漏洞利用 → 报告生成」全流程。
输入自然语言，AI 自动执行渗透测试全流程：
用户输入：帮我对 http://target.example.com 进行渗透测试
VulnClaw 自动执行：
  Round 1:  信息收集 → 指纹识别、端口扫描、目录枚举
  Round 2:  漏洞发现 → 检测注入点、已知 CVE、配置缺陷
  Round 3:  漏洞利用 → PoC 验证、权限获取
  Round 4:  报告生成 → 结构化报告 + Python PoC 脚本
适用于已授权的渗透测试、CTF 竞赛、安全教学、红队演练等场景。
- 目标驱动求解引擎（默认） — 抛弃固定轮数工作流，以「目标达成 / 探索前沿耗尽 / 安全预算」为终止条件，自动收敛
- 黑板图状态空间搜索 — 把渗透建模为从 origin 向 goal 的搜索：Fact（已确认事实）+ Intent（探索方向），结构上杜绝"原地打

[Open ↗](https://github.com/Unclecheng-li/VulnClaw)
