# Local LLM Hosting

Self-hosting LLMs in 2025/2026 &mdash; Ollama, vLLM, llama.cpp, TGI, SGLang and friends, plus Docker, multi-GPU, quantisation, determinism, and production patterns.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_Local_LLM_Hosting/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [Why Host Locally — The Landscape](https://brendanjameslynskey.github.io/Local_LLM_01_Landscape/) | live | Drivers, cost model, ecosystem map &mdash; Ollama, vLLM, llama.cpp, TGI, SGLang, TensorRT-LLM, LMDeploy, MLC. Interactive picker. |
| 02 | [Ollama — Zero-Friction Local LLMs](https://brendanjameslynskey.github.io/Local_LLM_02_Ollama/) | live | Architecture, Modelfiles, REST and OpenAI-compat APIs, VRAM tuning, the KV-cache-quant trick, sizing calculator. |
| 03 | [Inside vLLM — PagedAttention &amp; Continuous Batching](https://brendanjameslynskey.github.io/Local_LLM_03_vLLM_Architecture/) | live | Why vLLM is 5&ndash;20&times; faster &mdash; KV fragmentation, paged attention, continuous batching, prefix caching, chunked prefill, specdec, multi-LoRA. |
| 04 | [vLLM in Docker on NVIDIA GPUs](https://brendanjameslynskey.github.io/Local_LLM_04_vLLM_Docker/) | live | From a blank Linux box to an OpenAI-compatible vLLM endpoint &mdash; NVIDIA Container Toolkit, the vllm/vllm-openai image, compose, gotchas. |
| 05 | [Multi-GPU Parallelism for Serving](https://brendanjameslynskey.github.io/Local_LLM_05_Multi_GPU_Parallelism/) | live | Tensor, pipeline, data and expert parallel; NVLink, NVSwitch, NCCL, InfiniBand; multi-node patterns; interactive TP/PP/DP/EP planner. |
| 06 | [Framework Shootout](https://brendanjameslynskey.github.io/Local_LLM_06_Frameworks/) | live | Feature matrix and honest throughput/latency numbers across vLLM, Ollama, llama.cpp, TGI, SGLang, TensorRT-LLM, LMDeploy, MLC. |
| 07 | [Quantization for Local Hosting](https://brendanjameslynskey.github.io/Local_LLM_07_Quantization/) | live | GGUF, AWQ, GPTQ, FP8, INT4, MX-FP4 &mdash; bit layouts, perplexity impact, framework support, format picker. |
| 08 | [Deploying on NVIDIA DGX Spark](https://brendanjameslynskey.github.io/Local_LLM_08_DGX_Spark/) | live | Practical vLLM on a GB10 Grace-Blackwell workstation &mdash; unified memory, arm64 gotchas, model/concurrency matrix, two-Spark pairing. |
| 09 | [Sources of Non-Determinism in LLM Serving](https://brendanjameslynskey.github.io/Local_LLM_09_Determinism/) | live | Why the same prompt gives different tokens twice &mdash; sampling, non-associative FP, batch-size dependence, scheduler drift. |
| 10 | [Production Patterns for Local LLM Serving](https://brendanjameslynskey.github.io/Local_LLM_10_Production/) | live | Routing, prefix &amp; semantic caching, speculative decoding, observability, SLOs, rollouts, cost accounting, SLO planner. |
| 11 | [Deploying on NVIDIA GPUs](https://brendanjameslynskey.github.io/Local_LLM_11_NVIDIA_GPUs/) | live | Architectures, memory, multi-GPU, ganging; NVLink/NVSwitch/PCIe P2P/IOMMU; MIG; Ollama/vLLM nuances per GPU class. |

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
