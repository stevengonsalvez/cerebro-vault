---
title: "MoonshotAI/FlashKDA: FlashKDA: high-performance Kimi Delta Attention kernels"
category: coding-agents-llm
tags: [ai/llm-mechanics]
source: github
url: https://github.com/MoonshotAI/FlashKDA
score: 0.70
reason: "High-perf LLM attention kernels, token optimization"
captured: 2026-07-30T06:00:04.626666+00:00
rating:
---
# MoonshotAI/FlashKDA: FlashKDA: high-performance Kimi Delta Attention kernels

> High-perf LLM attention kernels, token optimization

FlashKDA: Flash Kimi Delta Attention — high-performance KDA kernels built on CUTLASS
- 2026-04-22 — Deep-Dive Blog: the design decisions behind FlashKDA v1, read it here.
- SM90 and above
- CUDA 12.9 and above
- PyTorch 2.4 and above
git clone https://github.com/MoonshotAI/FlashKDA.git flash-kda
cd flash-kda
git submodule update --init --recursive
pip install -v --no-build-isolation .By default, the build detects the current CUDA device and compiles for that architecture. For wheel or CI builds, compile all supported architectures explicitly:
FLASH_KDA_CUDA_ARCHS=all pip install -v --no-build-

[Open ↗](https://github.com/MoonshotAI/FlashKDA)
