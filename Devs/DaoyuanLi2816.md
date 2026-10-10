---
login: "DaoyuanLi2816"
name: null
discovered_via: "fanout"
discovered_via_all:
  - "fanout"
provenance_repos:
  - "bytedance/deer-flow"
  - "deepseek-ai/DeepSpec"
admitted: true
low_n: false
repos_populated: true
generated_at: "2026-10-10T06:04:44.283147+00:00"
provenance:
  - "16389f32495280ea"
  - "50b9cd6dfa9f75d1"
  - "939f60d749009d51"
pushes_per_week: [10, 6, 13, 9, 10, 1, 0, 0, 1, 1, 1, 2, 2]
windows:
  "7d":
    pushes: 4
    distinct_repos: 3
    active_days: 2
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 6
    distinct_repos: 4
    active_days: 4
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 56
    distinct_repos: 9
    active_days: 25
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
automation:
  state: "clear"
  push_per_day: 2.2400
  repo_per_active_day: 0.3600
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
    pushes: 4
    distinct_repos: 3
    pushes_per_repo: 1.3333
    active_days: 2
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 6
    distinct_repos: 4
    pushes_per_repo: 1.5000
    active_days: 4
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "90d":
    pushes: 56
    distinct_repos: 9
    pushes_per_repo: 6.2222
    active_days: 25
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
reasons:
  - "provenance: 3 vault signal(s) — pass"
  - "activity: 25 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "mini-verl"
    title: "mini-verl"
    description: "verl for a single consumer GPU. PPO, GRPO and on-policy distillation on NVIDIA GPUs."
    language: "Python"
    topics:
      - "agentic-rl"
      - "alignment"
      - "consumer-gpu"
      - "grpo"
      - "knowledge-distillation"
      - "llm"
      - "llm-agents"
      - "llm-alignment"
      - "on-policy-distillation"
      - "peft"
      - "post-training"
      - "ppo"
      - "qlora"
      - "qwen"
      - "reinforcement-learning"
      - "single-gpu"
      - "tool-use"
      - "verl"
    stars_fact: 306
    first_seen: null
    last_push: "2026-09-15"
  - name: "molgen"
    title: "molgen"
    description: "Lightweight toolkit for de novo molecular generation: SMILES & SELFIES tokenizers, CharRNN / MolGPT / VAE models, training, sampling, and MOSES-style metrics."
    language: "Python"
    topics:
      - "ai4science"
      - "cheminformatics"
      - "chemistry"
      - "deep-learning"
      - "drug-discovery"
      - "generative-model"
      - "molecular-generation"
      - "molgpt"
      - "pytorch"
      - "rdkit"
      - "selfies"
      - "smiles"
      - "transformer"
      - "vae"
    stars_fact: 16
    first_seen: null
    last_push: "2026-07-11"
  - name: "can-i-finetune-this"
    title: "can-i-finetune-this"
    description: "Single-GPU LLM fine-tuning preflight: memory estimates, runnable LoRA/QLoRA recipes, and local measurements."
    language: "Python"
    topics:
      - "bitsandbytes"
      - "fine-tuning"
      - "gpu"
      - "hugging-face"
      - "llm"
      - "lora"
      - "memory-estimation"
      - "peft"
      - "pytorch"
      - "qlora"
      - "transformers"
      - "vram"
    stars_fact: 793
    first_seen: null
    last_push: "2026-10-08"
  - name: "pairjudge"
    title: "pairjudge"
    description: "Pairwise LLM judges (A/B/tie): budget-aware multi-turn packing, position-bias correction, pseudo-label distillation. Generalized from the 4th-place (gold) solution to Kaggle LMSYS Chatbot Arena."
    language: "Python"
    topics:
      - "chatbot-arena"
      - "gold-medal"
      - "kaggle-competition"
      - "kaggle-solution"
      - "llm"
      - "llm-as-judge"
      - "lora"
      - "nlp"
      - "preference-learning"
      - "reward-model"
      - "rlhf"
    stars_fact: 170
    first_seen: null
    last_push: "2026-10-09"
  - name: "laptop-llm-cn"
    title: "laptop-llm-cn"
    description: "前沿 LLM 中文代码教材：KDA、AttnRes、MSA、mHC、Engram、MTP、Muon、Agent RL、多教师蒸馏、FP4 与本地 Serving · 18 章课程 · 无需云资源"
    language: "Python"
    topics:
      - "agent-rl"
      - "chinese"
      - "dpo"
      - "education"
      - "fastapi"
      - "grpo"
      - "kda"
      - "knowledge-distillation"
      - "laptop"
      - "llm"
      - "llm-training"
      - "moe"
      - "pytorch"
      - "quantization"
      - "rlhf"
      - "sparse-attention"
      - "speculative-decoding"
    stars_fact: 0
    first_seen: null
    last_push: "2026-10-04"
  - name: "delta-mfp-local-agents"
    title: "delta-mfp-local-agents"
    description: "Delta-MFP: counterfactual-replay failure diagnosis for local tool-use agents (FAGEN @ ICML 2026)"
    language: "Python"
    topics:
      - "ai-agents"
      - "counterfactual-replay"
      - "failure-analysis"
      - "local-llm"
      - "reproducible-research"
      - "tool-use"
    stars_fact: 51
    first_seen: null
    last_push: "2026-10-03"
---

# DaoyuanLi2816

56 pushes across 9 repositories on 25 active days in the last 90 days of public GitHub push activity.

https://github.com/DaoyuanLi2816
