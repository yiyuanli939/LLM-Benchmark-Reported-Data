# Flagship LLM Benchmark Report

Scope: Flagship LLMs released from 2022-11-30 through 2025-11-24 (current coverage). Flagship size filter: include models with disclosed size >=150B; keep closed/flagship models with undisclosed size. Sources are official release posts, technical reports, or official model cards. Benchmark scores and evaluation settings are recorded in `metadata.csv` (one row per model, one column per benchmark). Benchmark feature metadata (including question counts) is in `benchmark_features.csv`. The local report path is `reports/combined_report.md` and referenced in `metadata.csv`.

## Task Loop Spec (single source of truth)
1. Select the next 10 flagship models (>=150B if disclosed; avoid smaller sibling models when a flagship for the same generation exists).
2. Collect official sources (release posts, tech reports, or official model cards) and extract headline benchmark scores.
3. Update `metadata.csv`: add model row, fill benchmark scores, include `__setting` details, keep rows sorted by `release_date`.
4. Update `benchmark_features.csv`: ensure every benchmark has `num_questions`, and re-order by benchmark usage frequency.
5. Update this report: add model entries, update the Loop Log, and note any missing/approximate dates or missing benchmarks.

## Loop Log
- Loop 1 (completed): 9 models (Claude 3 Haiku removed as non-flagship). Benchmarks/features captured and sorted.
  Models: GPT-3.5 (ChatGPT), GPT-4, Claude 2, Claude 2.1, Claude 3 Opus, Claude 3 Sonnet, GPT-4o, Claude 3.5 Sonnet, GPT-4.1.
- Loop 2 (completed): 10 models added; size filter removed Llama 2 70B and Qwen2.5-72B. Benchmarks/features updated and sorted by usage frequency.
  Models: PaLM 2-L, GPT-4 Turbo, Gemini 1.0 Ultra, Grok-1, Command R+, Mistral Large 2, GLM-4 (flagship), MiniMax (flagship).
- Loop 3 (completed): 10 models added; size filter removed Qwen2-72B and Llama 3.3 70B (Instruct). Benchmarks/features updated and sorted by usage frequency.
  Models: Gemini 1.5 Pro, Mistral Large, DeepSeek-V2, Llama 3.1 405B (Instruct), Grok-2, OpenAI o1 (preview), DeepSeek-V3, DeepSeek-R1.
- Size filter applied: removed models with explicit size <150B (Llama 2 70B, Qwen2-72B, Llama 3.3 70B (Instruct), Qwen2.5-72B).
- Loop 4 (completed): 10 models added. Benchmarks/features updated and sorted by usage frequency.
  Models: Grok-1.5, MiniMax-Text-01, GPT-4.5, OpenAI o3, Claude Opus 4, Claude Sonnet 4, Claude Opus 4.1, GPT-5, Claude Sonnet 4.5, Claude Opus 4.5.
- Loop 5 (partial, completed): 6 Chinese-company flagship models with official benchmark numbers. Benchmarks/features updated and sorted by usage frequency.
  Models: Kimi k1.5, Qwen3-235B-A22B, Hunyuan-Large, Kimi K2, GLM-4.5, Seed-Thinking-v1.5.

---
## Loop 1 Models

### GPT-3.5 (ChatGPT) — OpenAI — 2022-11-30
- Source: https://openai.com/blog/chatgpt
- Benchmarks: No benchmark scores reported in the release post.

### GPT-4 — OpenAI — 2023-03-14
- Source: https://ar5iv.labs.arxiv.org/html/2303.08774
- Benchmarks: Standardized-exam table (law, SAT/GRE, AP, AMC, sommelier exams) and coding-style evaluations (LeetCode). All reported scores are in `metadata.csv`.

### Claude 2 — Anthropic — 2023-07-11
- Source: https://www.anthropic.com/news/claude-2
- Benchmarks (headline): Bar Exam MBE, GRE Reading & Writing, HumanEval, GSM8K.

### Claude 2.1 — Anthropic — 2023-11-21
- Source: https://www.anthropic.com/news/claude-2-1
- Benchmarks: No public benchmark scores reported in the release post.

### Claude 3 Opus — Anthropic — 2024-03-04
- Source: https://www.anthropic.com/news/claude-3-family
- Benchmarks (headline): MMLU, GPQA (Diamond), GSM8K, MATH, MGSM, HumanEval, DROP, BIG-Bench Hard, ARC-Challenge, HellaSwag, MMMU (val), Document VQA (ANLS), MathVista (testmini), AI2D (test), ChartQA (relaxed accuracy).

### Claude 3 Sonnet — Anthropic — 2024-03-04
- Source: https://www.anthropic.com/news/claude-3-family
- Benchmarks: Same suite as Claude 3 Opus; scores recorded in `metadata.csv`.

### GPT-4o — OpenAI — 2024-05-13
- Source: https://openai.com/index/gpt-4o-and-more-tools-to-chatgpt-free/
- Benchmarks: No benchmark scores reported in the release post.

### Claude 3.5 Sonnet — Anthropic — 2024-06-21
- Source: https://www.anthropic.com/news/claude-3-5-sonnet
- Benchmarks (headline): GPQA (Diamond), MMLU (multiple settings), HumanEval, MGSM, DROP, BIG-Bench Hard, MATH, GSM8K, MathVista (testmini), AI2D (test), MMMU (val), ChartQA (relaxed accuracy), Document VQA (ANLS).

### GPT-4.1 — OpenAI — 2025-04-14
- Source: https://openai.com/index/gpt-4-1/
- Benchmarks (headline): SWE-bench Verified, MultiChallenge (Scale), Video-MME (long, no subtitles).

---
## Loop 2 Models

### PaLM 2-L — Google — 2023-05-10
- Source: https://ai.google/static/documents/palm2techreport.pdf
- Benchmarks (headline): WinoGrande, ARC-Challenge, DROP, StrategyQA, CSQA, XCOPA, BIG-Bench Hard.

### GPT-4 Turbo — OpenAI — 2023-11-06
- Source: https://openai.com/index/new-models-and-developer-products-announced-at-devday/
- Benchmarks: No benchmark scores reported in the release post.

### Gemini 1.0 Ultra — Google — 2023-12-06
- Source: https://blog.google/intl/en-africa/company-news/technology/introducing-gemini-our-largest-and-most-capable-ai-model/
- Benchmarks (headline): MMLU, MMMU.

### GLM-4 (flagship) — Zhipu AI — 2024-01-17
- Source: https://www.glm-4.com/
- Benchmarks: Official benchmark scores not found in the release page.

### Grok-1 — xAI — 2024-03-28
- Source: https://x.ai/news/grok-1.5
- Benchmarks (headline): MMLU, MATH, GSM8K, HumanEval.

### Command R+ — Cohere — 2024-04-01
- Source: https://huggingface.co/CohereLabs/c4ai-command-r-plus/blob/main/README.md
- Benchmarks (headline): ARC-Challenge, HellaSwag, MMLU, TruthfulQA, WinoGrande, GSM8K.

### Mistral Large 2 — Mistral AI — 2024-07-24
- Source: https://mistral.ai/news/mistral-large-2407
- Benchmarks (headline): MMLU, MultiPL-E.

### MiniMax (flagship) — MiniMax — 2024-06-01
- Source: (official source not located in this run)
- Benchmarks: Official benchmark scores not found.

---
## Loop 3 Models

### Gemini 1.5 Pro — Google — 2024-02-15
- Source: https://blog.google/innovation-and-ai/products/google-gemini-next-generation-model-february-2024/
- Benchmarks (headline): Needle In A Haystack (1M tokens).

### Mistral Large — Mistral AI — 2024-02-26
- Source: https://mistral.ai/fr/news/mistral-large
- Benchmarks (headline): MMLU, HellaSwag, WinoGrande, ARC-Challenge, TriviaQA, TruthfulQA, HumanEval, MBPP, MATH, GSM8K.

### DeepSeek-V2 — DeepSeek — 2024-05-06
- Source: https://github.com/deepseek-ai/DeepSeek-V2
- Benchmarks (headline): MMLU, BIG-Bench Hard, C-Eval, CMMLU, HumanEval, MBPP, GSM8K, MATH.

### Llama 3.1 405B (Instruct) — Meta — 2024-07-23
- Source: https://huggingface.co/meta-llama/Llama-3.1-405B-Instruct-FP8
- Benchmarks (headline): MMLU, MMLU-Pro, IFEval, ARC-Challenge, GPQA, HumanEval, MBPP, GSM8K, MATH.

### Grok-2 — xAI — 2024-08-13
- Source: https://x.ai/news/grok-2/
- Benchmarks (headline): MMLU, MMLU-Pro, GPQA, MATH, HumanEval, MMMU, MathVista, Document Visual QA (ANLS).

### OpenAI o1 (preview) — OpenAI — 2024-09-12
- Source: https://openai.com/index/introducing-openai-o1-preview/
- Benchmarks (headline): IMO Qualifying Exam, Codeforces percentile.

### DeepSeek-V3 — DeepSeek — 2024-12-26
- Source: https://github.com/deepseek-ai/DeepSeek-V3
- Benchmarks (headline): MMLU, MMLU-redux, MMLU-Pro, DROP, ARC-Challenge, HellaSwag, WinoGrande, BIG-Bench Hard.

### DeepSeek-R1 — DeepSeek — 2025-01-15
- Source: https://github.com/deepseek-ai/DeepSeek-R1
- Benchmarks (headline): MMLU, MMLU-redux, MMLU-Pro, DROP, IFEval, GPQA (Diamond).

---
## Loop 4 Models

### Grok-1.5 — xAI — 2024-03-28
- Source: https://x.ai/news/grok-1.5
- Benchmarks (headline): MMLU, MATH, GSM8K, HumanEval (all with reported shot settings).

### MiniMax-Text-01 — MiniMax — 2025-01-15
- Source: https://github.com/MiniMax-AI/MiniMax-01
- Benchmarks (headline): MMLU, MMLU-Pro, GPQA (Diamond), GSM8K, MATH, DROP, HumanEval, MBPP+, SimpleQA, C-SimpleQA, IFEval, Arena-Hard (0-shot CoT).

### GPT-4.5 — OpenAI — 2025-02-27
- Source: https://openai.com/index/introducing-gpt-4-5/
- Benchmarks (headline): GPQA, AIME '24, MMMLU, MMMU, SWE-Lancer Diamond, SWE-bench Verified (best internal performance).

### OpenAI o3 — OpenAI — 2025-04-16
- Source: https://openai.com/index/introducing-o3-and-o4-mini/
- Benchmarks: Release post cites SOTA on Codeforces, SWE-bench, and MMMU without numeric scores.

### Claude Opus 4 — Anthropic — 2025-05-22
- Source: https://www.anthropic.com/news/claude-4
- Benchmarks (headline): SWE-bench Verified, Terminal-bench, GPQA (Diamond), MMMLU, MMMU, AIME (no extended thinking).

### Claude Sonnet 4 — Anthropic — 2025-05-22
- Source: https://www.anthropic.com/news/claude-4
- Benchmarks (headline): SWE-bench Verified, GPQA (Diamond), MMMLU, MMMU, AIME (no extended thinking).

### Claude Opus 4.1 — Anthropic — 2025-08-05
- Source: https://www.anthropic.com/news/claude-opus-4-1
- Benchmarks (headline): SWE-bench Verified.

### GPT-5 — OpenAI — 2025-08-07
- Source: https://openai.com/index/introducing-gpt-5/
- Benchmarks (headline): AIME 2025, SWE-bench Verified, Aider Polyglot, MMMU, HealthBench Hard.

### Claude Sonnet 4.5 — Anthropic — 2025-09-29
- Source: https://www.anthropic.com/news/claude-sonnet-4-5
- Benchmarks (headline): SWE-bench Verified, OSWorld.

### Claude Opus 4.5 — Anthropic — 2025-11-24
- Source: https://www.anthropic.com/news/claude-opus-4-5
- Benchmarks: Release post provides qualitative benchmark claims; numeric scores shown in images/system card not captured in this run.

---
## Loop 5 Models (Chinese Companies)

### Kimi k1.5 — Moonshot AI — 2025-01-22
- Source: https://huggingface.co/papers/2501.12599
- Benchmarks (headline): AIME, MATH 500, Codeforces percentile, MathVista, LiveCodeBench (short-CoT).

### Seed-Thinking-v1.5 — ByteDance (Seed) — 2025-04-10
- Source: https://github.com/ByteDance-Seed/Seed-Thinking-v1.5
- Benchmarks (headline): AIME 2025, AIME 2024, Beyond AIME, GPQA (Diamond), SuperGPQA, MMLU-Pro, Codeforces avg@8, Codeforces pass@8, LiveCodeBench v5, Aider Polyglot, SWE-bench Verified, ARC-AGI, SimpleQA, Collie, IFEval.

### Qwen3-235B-A22B — Alibaba (Qwen) — 2025-05-14
- Source: https://ar5iv.labs.arxiv.org/html/2505.09388v1
- Benchmarks (headline): MMLU, MMLU-Redux, MMLU-Pro, SuperGPQA, BIG-Bench Hard, GPQA, GSM8K, MATH, EvalPlus, MultiPL-E, MBPP, CRUX-O, MGSM, MMMLU, INCLUDE; plus AIME'24, AIME 2025, LiveCodeBench (v5), Codeforces (ELO), BFCL v3.

### Hunyuan-Large — Tencent — 2025-06-27
- Source: https://huggingface.co/tencent/Hunyuan-A13B-Instruct/blob/c1ef5aa7f0c8fef68b3f859c89232013563a8030/README.md
- Benchmarks (headline): MMLU, MMLU-Pro, MMLU-Redux, BIG-Bench Hard, SuperGPQA, EvalPlus, MultiPL-E, MBPP, CRUX-I, CRUX-O, MATH, CMATH, GSM8K, GPQA.

### Kimi K2 — Moonshot AI — 2025-07-28
- Source: https://huggingface.co/papers/2507.20534
- Benchmarks (headline): AIME 2025, MATH 500, LiveCodeBench (v6), Tau2-Bench, ACEBench (En), SWE-bench Verified, SWE-Bench Multilingual, OJBench, GPQA (Diamond).

### GLM-4.5 — Zhipu AI (Z.ai) — 2025-08-08
- Source: https://huggingface.co/zai-org/GLM-4.5-FP8/blob/main/README.md
- Benchmarks (headline): TAU-Bench, AIME '24, SWE-bench Verified.

---
## Next Loop Targets (incomplete list)
Continue adding remaining flagship models through 2026-01-29 (>=150B or size undisclosed) with official sources and benchmark tables.
