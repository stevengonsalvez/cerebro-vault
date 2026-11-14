---
login: "TwelveNights"
name: null
discovered_via: "fanout"
discovered_via_all:
  - "fanout"
provenance_repos:
  - "addyosmani/agent-skills"
admitted: true
low_n: false
repos_populated: true
generated_at: "2026-11-14T07:04:52.615903+00:00"
provenance:
  - "dae9f02535f7c22f"
pushes_per_week: [0, 0, 0, 0, 0, 0, 2, 0, 1, 2, 1, 0, 0]
windows:
  "7d":
    pushes: 0
    distinct_repos: 0
    active_days: 0
    repos_not_owned: 0
    not_owned_basenames: 0
    not_owned_owners: 0
  "30d":
    pushes: 3
    distinct_repos: 3
    active_days: 2
    repos_not_owned: 1
    not_owned_basenames: 1
    not_owned_owners: 1
  "90d":
    pushes: 6
    distinct_repos: 5
    active_days: 5
    repos_not_owned: 1
    not_owned_basenames: 1
    not_owned_owners: 1
automation:
  state: "clear"
  push_per_day: 1.2000
  repo_per_active_day: 1.0000
  not_owned_ratio: 0.2000
  basename_concentration: 0.2000
  shapes: []
  shape_evidence: []
  cleared_by: null
  cleared_on: null
  fork_provenance: null
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
    pushes: 3
    distinct_repos: 3
    pushes_per_repo: 1.0000
    active_days: 2
    repos_not_owned: 1
    not_owned_basenames: 1
    not_owned_owners: 1
  "90d":
    pushes: 6
    distinct_repos: 5
    pushes_per_repo: 1.2000
    active_days: 5
    repos_not_owned: 1
    not_owned_basenames: 1
    not_owned_owners: 1
reasons:
  - "provenance: 1 vault signal(s) — pass"
  - "activity: 5 active days in 90d — pass"
  - "automation: clear — pass"
repos:
  - name: "ComfyUI-3D-rocm"
    title: "ComfyUI-3D-rocm"
    description: "Image to textured 3D asset in ComfyUI on AMD GPUs (ROCm, Windows + Linux): TripoSG and Hunyuan3D-2.1 PBR texturing nodes, no CUDA extensions"
    language: "Python"
    topics:
      - "3d-generation"
      - "amd"
      - "amd-gpu"
      - "comfyui"
      - "comfyui-custom-nodes"
      - "comfyui-nodes"
      - "game-assets"
      - "hunyuan3d"
      - "image-to-3d"
      - "pbr-texture"
      - "radeon"
      - "rocm"
      - "triposg"
      - "windows"
    stars_fact: 0
    first_seen: null
    last_push: "2026-11-14"
  - name: "Hunyuan3D-2.1-rocm"
    title: "Hunyuan3D-2.1-rocm"
    description: "Hunyuan3D-2.1 image-to-3D with PBR textures on AMD GPUs (ROCm, Linux and Windows): no CUDA/C++ extensions or Blender, texturing fits 16 GB"
    language: "Python"
    topics:
      - "3d-generation"
      - "amd"
      - "amd-gpu"
      - "diffusers"
      - "game-assets"
      - "generative-ai"
      - "hunyuan3d"
      - "image-to-3d"
      - "mesh-generation"
      - "pbr"
      - "pytorch"
      - "radeon"
      - "rocm"
      - "sageattention"
      - "texturing"
      - "windows"
    stars_fact: 0
    first_seen: null
    last_push: "2026-11-14"
  - name: "TripoSG-rocm"
    title: "TripoSG-rocm"
    description: "TripoSG image-to-3D on AMD GPUs (ROCm, Linux and Windows): no CUDA-only dependencies, faster settings, works with current diffusers"
    language: "Python"
    topics:
      - "3d-generation"
      - "amd"
      - "amd-gpu"
      - "diffusers"
      - "game-assets"
      - "generative-ai"
      - "image-to-3d"
      - "mesh-generation"
      - "pytorch"
      - "radeon"
      - "rocm"
      - "sageattention"
      - "text-to-3d"
      - "triposg"
      - "windows"
    stars_fact: 0
    first_seen: null
    last_push: "2026-11-14"
  - name: "nunchaku-rocm"
    title: "nunchaku-rocm"
    description: "4-bit SVDQuant (Nunchaku) diffusion inference on AMD GPUs (ROCm): Triton backend, native RDNA3 int4 kernels, FLUX.1, FLUX.2 [klein], Qwen-Image, Z-Image-Turbo, SDXL, LoRA, ComfyUI nodes"
    language: "Python"
    topics:
      - "4-bit"
      - "amd"
      - "amd-gpu"
      - "comfyui"
      - "diffusion-models"
      - "flux"
      - "generative-ai"
      - "int4"
      - "lora"
      - "nunchaku"
      - "pytorch"
      - "quantization"
      - "qwen-image"
      - "radeon"
      - "rocm"
      - "sdxl"
      - "svdquant"
      - "text-to-image"
      - "triton"
      - "z-image"
    stars_fact: 1
    first_seen: null
    last_push: "2026-11-13"
  - name: "ComfyUI-nunchaku-rocm"
    title: "ComfyUI-nunchaku-rocm"
    description: "ComfyUI nodes for Nunchaku 4-bit models on AMD GPUs (ROCm): FLUX.2 [klein], FLUX.1, Qwen-Image, Z-Image-Turbo, SDXL"
    language: "Python"
    topics:
      - "amd"
      - "comfyui"
      - "comfyui-nodes"
      - "flux"
      - "nunchaku"
      - "qwen-image"
      - "rocm"
      - "sdxl"
      - "svdquant"
      - "z-image"
    stars_fact: 0
    first_seen: null
    last_push: "2026-11-14"
  - name: "beatfit"
    title: "beatfit"
    description: "Retime video clips so chosen moments land on the beats of a song."
    language: "Python"
    topics:
      - "audio"
      - "beat-sync"
      - "dynamic-programming"
      - "ffmpeg"
      - "montage"
      - "music"
      - "python"
      - "retiming"
      - "video-editing"
      - "video-processing"
    stars_fact: 0
    first_seen: null
    last_push: "2026-11-07"
---

# TwelveNights

6 pushes across 5 repositories on 5 active days in the last 90 days of public GitHub push activity.

https://github.com/TwelveNights
