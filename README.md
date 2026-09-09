<div align="center">

# Qwen3 × vLLM on AMD Instinct MI300

### High-Performance LLM Inference on AMD GPU Infrastructure

<br>

<img src="https://img.shields.io/badge/AMD-Instinct%20MI300-ED1C24?style=for-the-badge&logo=amd&logoColor=white" alt="AMD Instinct MI300">
<img src="https://img.shields.io/badge/ROCm-AMD%20GPU%20Software-ED1C24?style=for-the-badge&logo=amd&logoColor=white" alt="ROCm">
<img src="https://img.shields.io/badge/Qwen3-4B%20Instruct-6E56CF?style=for-the-badge" alt="Qwen3">
<img src="https://img.shields.io/badge/vLLM-Inference%20Engine-000000?style=for-the-badge" alt="vLLM">

<br><br>

**Qwen3-4B-Instruct-2507**  
**vLLM · ROCm · AMD Instinct MI300 · Python**

<br>

### Ameer Muhammed

*LLM Inference · GPU Computing · AI/ML*

</div>

---

## ⚡ What I Built

This repository is my hands-on implementation and experimentation with
**LLM inference on AMD GPU infrastructure**.

I worked with **Qwen3-4B-Instruct-2507**, running inference through
**vLLM** on an **AMD Instinct MI300** environment.

The focus is on understanding and experimenting with the inference stack
itself — from conversational context and system prompting to generation
controls and GPU-backed execution.

```text
                 USER
                  │
                  ▼
          ┌───────────────┐
          │ Conversation  │
          │    Context    │
          └───────┬───────┘
                  │
                  ▼
          ┌───────────────┐
          │    Qwen3      │
          │  4B Instruct  │
          └───────┬───────┘
                  │
                  ▼
          ┌───────────────┐
          │     vLLM      │
          │    Runtime    │
          └───────┬───────┘
                  │
                  ▼
          ┌───────────────┐
          │     ROCm      │
          └───────┬───────┘
                  │
                  ▼
          ┌───────────────┐
          │ AMD Instinct  │
          │     MI300     │
          └───────────────┘
