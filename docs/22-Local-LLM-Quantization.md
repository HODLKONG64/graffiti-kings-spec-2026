**Local LLM Quantization & Mega Mode**

**What is Quantization?**
Quantization is smart compression for AI models so they run on phones while keeping most intelligence.

**2026 Standards (GGUF)**
- Q4_K_M = Best balance (~3-5% quality loss) — Recommended default
- Q5_K_M = Better quality (~1-2% loss) — 12GB+ RAM phones
- Q8_0 = Near-lossless — High-end devices

**Best Models for Mega Mode**
- Phi-4 Mini (3.8B) Q4_K_M → Top pick for most users
- Qwen 3 7-8B Q4_K_M → Best all-rounder
- Llama 3.3 8B Q4_K_M → Safe default

**Mega Mode Toggle**
- Fast Mode = Q4_K_M (default)
- Mega Mode = Q5_K_M or Q6_K (if device supports it)

SPARK explains: “Your phone has 12 GB RAM — nice. I just switched you to Mega Mode (Q5_K_M).”