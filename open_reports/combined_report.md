# Open-Source LLM Benchmark Report (Open Models)

Scope: Open-weight models (1B-150B). Target coverage window: 2023-01-01 through 2026-01-29. Current data range: 2023-04-20 to 2025-12-15. Sources and benchmark values are recorded in `data/open_metadata.csv`, with evaluation settings in the corresponding `__setting` columns.

## Coverage Summary
- Total models: 133
- Release date range: 2023-04-20 to 2025-12-15
- Models with benchmark values: 71
- Models without benchmark values: 62

## 1) StableLM-Alpha 3B - Stability AI - 2023-04-20
- Source: https://github.com/Stability-AI/StableLM
- Notes: Open weights; 3B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 2) StableLM-Alpha 7B - Stability AI - 2023-04-20
- Source: https://github.com/Stability-AI/StableLM
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 3) MPT-7B - MosaicML - 2023-05-05
- Source: https://www.businesswire.com/news/home/20230622195151/en/MosaicML-Releases-Open-Source-MPT-30B-LLMs-Trained-on-H100s-to-Power-Generative-AI-Applications
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 4) RedPajama-INCITE 3B - Together - 2023-05-05
- Source: https://www.together.ai/blog/redpajama-models-v1
- Notes: Open weights; 3B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 5) Falcon 40B - Technology Innovation Institute - 2023-05-25
- Source: https://www.tii.ae/news/uaes-technology-innovation-institute-launches-open-source-falcon-40b-large-language-model
- Notes: Open weights; 40B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 6) RedPajama-INCITE 7B - Together - 2023-06-06
- Source: https://www.together.ai/blog/redpajama-7b
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 7) MPT-30B - MosaicML - 2023-06-22
- Source: https://www.businesswire.com/news/home/20230622195151/en/MosaicML-Releases-Open-Source-MPT-30B-LLMs-Trained-on-H100s-to-Power-Generative-AI-Applications
- Notes: Open weights; 30B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 8) Llama 2 13B - Meta - 2023-07-18
- Source: https://about.fb.com/news/2023/07/llama-2/
- Notes: Open weights; 13B parameters. Benchmarks from Meta Llama 3 model card (base pretrained models table).
- Benchmarks: 6 fields populated in `data/open_metadata.csv` (see `__setting` columns): ARC-Challenge, BIG-Bench Hard, DROP, MMLU, TriviaQA, WinoGrande.

## 9) Llama 2 70B - Meta - 2023-07-18
- Source: https://about.fb.com/news/2023/07/llama-2/
- Notes: Open weights; 70B parameters. Benchmarks from Meta Llama 3 model card (base pretrained models table).
- Benchmarks: 9 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, DROP, GSM8K, HumanEval, MMLU, Natural Questions, TriviaQA; plus 1 more.

## 10) Llama 2 7B - Meta - 2023-07-18
- Source: https://about.fb.com/news/2023/07/llama-2/
- Notes: Open weights; 7B parameters. Benchmarks from Meta Llama 3 model card (base pretrained models table).
- Benchmarks: 6 fields populated in `data/open_metadata.csv` (see `__setting` columns): ARC-Challenge, BIG-Bench Hard, DROP, MMLU, TriviaQA, WinoGrande.

## 11) Qwen 7B - Alibaba - 2023-08-03
- Source: https://qwenlm.github.io/blog/qwen/
- Notes: Open weights; 7B parameters.
- Benchmarks: 6 fields populated in `data/open_metadata.csv` (see `__setting` columns): BIG-Bench Hard, GSM8K, HumanEval, MATH, MBPP, MMLU.

## 12) Code Llama 13B - Meta - 2023-08-24
- Source: https://about.fb.com/news/2023/08/code-llama-ai-for-coding/
- Notes: Open weights; 13B parameters. Benchmarks from Code Llama paper (arXiv 2308.12950v3), Table 2.
- Benchmarks: 2 fields populated in `data/open_metadata.csv` (see `__setting` columns): HumanEval, MBPP.

## 13) Code Llama 34B - Meta - 2023-08-24
- Source: https://about.fb.com/news/2023/08/code-llama-ai-for-coding/
- Notes: Open weights; 34B parameters. Benchmarks from Code Llama paper (arXiv 2308.12950v3), Table 2.
- Benchmarks: 2 fields populated in `data/open_metadata.csv` (see `__setting` columns): HumanEval, MBPP.

## 14) Code Llama 7B - Meta - 2023-08-24
- Source: https://about.fb.com/news/2023/08/code-llama-ai-for-coding/
- Notes: Open weights; 7B parameters. Benchmarks from Code Llama paper (arXiv 2308.12950v3), Table 2.
- Benchmarks: 2 fields populated in `data/open_metadata.csv` (see `__setting` columns): HumanEval, MBPP.

## 15) Baichuan2 13B - Baichuan - 2023-09-06
- Source: https://github.com/baichuan-inc/Baichuan-7B
- Notes: Open weights; 13B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 16) Baichuan2 7B - Baichuan - 2023-09-06
- Source: https://github.com/baichuan-inc/Baichuan-7B
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 17) Qwen 14B - Alibaba - 2023-09-25
- Source: https://qwenlm.github.io/blog/qwen/
- Notes: Open weights; 14B parameters.
- Benchmarks: 6 fields populated in `data/open_metadata.csv` (see `__setting` columns): BIG-Bench Hard, GSM8K, HumanEval, MATH, MBPP, MMLU.

## 18) Mistral 7B - Mistral AI - 2023-09-27
- Source: https://mistral.ai/news/announcing-mistral-7b
- Notes: Open weights; 7B parameters. Benchmarks from Mixtral of Experts paper (arXiv 2401.04088) Table 2; MBPP uses hand-verified subset and TriviaQA has no Wikipedia context (per paper).
- Benchmarks: 10 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU, Natural Questions; plus 2 more.

## 19) Yi 34B - 01.AI - 2023-11-02
- Source: https://github.com/01-ai/Yi
- Notes: Open weights; 34B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 20) Yi 6B - 01.AI - 2023-11-02
- Source: https://github.com/01-ai/Yi
- Notes: Open weights; 6B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 21) Qwen 1.8B - Alibaba - 2023-11-30
- Source: https://qwenlm.github.io/blog/qwen/
- Notes: Open weights; 1.8B parameters.
- Benchmarks: 3 fields populated in `data/open_metadata.csv` (see `__setting` columns): GSM8K, HumanEval, MMLU.

## 22) Qwen 72B - Alibaba - 2023-11-30
- Source: https://qwenlm.github.io/blog/qwen/
- Notes: Open weights; 72B parameters.
- Benchmarks: 6 fields populated in `data/open_metadata.csv` (see `__setting` columns): BIG-Bench Hard, GSM8K, HumanEval, MATH, MBPP, MMLU.

## 23) Mixtral 8x7B - Mistral AI - 2023-12-11
- Source: https://legal.mistral.ai/ai-governance/models/mixtral-8-7b
- Notes: Open weights; MoE 46.7B total parameters. Benchmarks from Mixtral of Experts paper (arXiv 2401.04088) Table 2; MBPP uses hand-verified subset and TriviaQA has no Wikipedia context (per paper).
- Benchmarks: 10 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU, Natural Questions; plus 2 more.

## 24) Phi-2 2.7B - Microsoft - 2023-12-12
- Source: https://www.microsoft.com/en-us/research/blog/phi-2-the-surprising-power-of-small-language-models/
- Notes: Open weights; 2.7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 25) InternLM2 20B - Shanghai AI Laboratory - 2024-01-17
- Source: https://github.com/InternLM/InternLM
- Notes: Open weights; 20B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 26) InternLM2 7B - Shanghai AI Laboratory - 2024-01-17
- Source: https://github.com/InternLM/InternLM
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 27) InternLM2 1.8B - Shanghai AI Laboratory - 2024-01-31
- Source: https://github.com/InternLM/InternLM
- Notes: Open weights; 1.8B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 28) OLMo 1B - Ai2 - 2024-02-01
- Source: https://allenai-web-sandbox.allen.ai/olmo/release-notes
- Notes: Open weights; 1B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 29) OLMo 7B - Ai2 - 2024-02-01
- Source: https://allenai-web-sandbox.allen.ai/olmo/release-notes
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 30) Qwen1.5 1.8B - Alibaba - 2024-02-04
- Source: https://qwenlm.github.io/blog/qwen1.5/
- Notes: Open weights; 1.8B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 31) Qwen1.5 110B - Alibaba - 2024-02-04
- Source: https://qwenlm.github.io/blog/qwen1.5/
- Notes: Open weights; 110B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 32) Qwen1.5 14B - Alibaba - 2024-02-04
- Source: https://qwenlm.github.io/blog/qwen1.5/
- Notes: Open weights; 14B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 33) Qwen1.5 32B - Alibaba - 2024-02-04
- Source: https://qwenlm.github.io/blog/qwen1.5/
- Notes: Open weights; 32B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 34) Qwen1.5 4B - Alibaba - 2024-02-04
- Source: https://qwenlm.github.io/blog/qwen1.5/
- Notes: Open weights; 4B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 35) Qwen1.5 72B - Alibaba - 2024-02-04
- Source: https://qwenlm.github.io/blog/qwen1.5/
- Notes: Open weights; 72B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 36) Qwen1.5 7B - Alibaba - 2024-02-04
- Source: https://qwenlm.github.io/blog/qwen1.5/
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 37) Gemma 2B - Google - 2024-02-21
- Source: https://ai.google.dev/gemma/docs/releases
- Notes: Open weights; 2B parameters. Benchmarks from Gemma model card (PT results table).
- Benchmarks: 10 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU, Natural Questions; plus 2 more.

## 38) Gemma 7B - Google - 2024-02-21
- Source: https://ai.google.dev/gemma/docs/releases
- Notes: Open weights; 7B parameters. Benchmarks from Gemma model card (PT results table).
- Benchmarks: 10 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU, Natural Questions; plus 2 more.

## 39) StarCoder2 15B - BigCode - 2024-02-28
- Source: https://huggingface.co/blog/starcoder2
- Notes: Open weights; 15B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 40) StarCoder2 3B - BigCode - 2024-02-28
- Source: https://huggingface.co/blog/starcoder2
- Notes: Open weights; 3B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 41) StarCoder2 7B - BigCode - 2024-02-28
- Source: https://huggingface.co/blog/starcoder2
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 42) DBRX 132B - Databricks - 2024-03-27
- Source: https://www.databricks.com/company/newsroom/press-releases/databricks-launches-dbrx-new-standard-efficient-open-source-models
- Notes: Open weights; MoE 132B total parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 43) Stable LM 2 1.6B - Stability AI - 2024-04-08
- Source: https://stability.ai/news/introducing-stable-lm-2-12b
- Notes: Open weights; 1.6B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 44) Stable LM 2 12B - Stability AI - 2024-04-08
- Source: https://stability.ai/news/introducing-stable-lm-2-12b
- Notes: Open weights; 12B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 45) CodeGemma 2B - Google - 2024-04-09
- Source: https://developers.googleblog.com/en/gemma-family-expands-with-models-tailored-for-developers-and-researchers/
- Notes: Open weights; 2B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 46) CodeGemma 7B - Google - 2024-04-09
- Source: https://developers.googleblog.com/en/gemma-family-expands-with-models-tailored-for-developers-and-researchers/
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 47) Mixtral 8x22B - Mistral AI - 2024-04-17
- Source: https://mistral.ai/news/mixtral-8x22b/
- Notes: Open weights; MoE 141B total parameters. Benchmarks from Mistral AI Mixtral 8x22B blog; values are for instructed version (GSM8K maj@8, Math maj@4).
- Benchmarks: 2 fields populated in `data/open_metadata.csv` (see `__setting` columns): GSM8K, MATH.

## 48) Llama 3 70B - Meta - 2024-04-18
- Source: https://about.fb.com/ltam/news/2024/04/presentamos-meta-llama-3-el-modelo-de-lenguaje-de-gran-tamano-mas-potente-hasta-la-fecha/
- Notes: Open weights; 70B parameters. Benchmarks from Meta Llama 3 model card (base pretrained models table). Benchmarks from Llama 3 technical report (arXiv 2407.21783) base pretrained table.
- Benchmarks: 14 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, DROP, GPQA, GSM8K, HellaSwag, HumanEval, MATH; plus 6 more.

## 49) Llama 3 8B - Meta - 2024-04-18
- Source: https://about.fb.com/ltam/news/2024/04/presentamos-meta-llama-3-el-modelo-de-lenguaje-de-gran-tamano-mas-potente-hasta-la-fecha/
- Notes: Open weights; 8B parameters. Benchmarks from Meta Llama 3 model card (base pretrained models table). Benchmarks from Llama 3 technical report (arXiv 2407.21783) base pretrained table.
- Benchmarks: 14 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, DROP, GPQA, GSM8K, HellaSwag, HumanEval, MATH; plus 6 more.

## 50) Phi-3 Mini 3.8B - Microsoft - 2024-04-23
- Source: https://www.microsoft.com/en-us/research/publication/phi-3-technical-report-a-highly-capable-language-model-locally-on-your-phone/
- Notes: Open weights; 3.8B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 51) Falcon 2 11B - Technology Innovation Institute - 2024-05-13
- Source: https://www.tii.ae/index.php/news/falcon-2-uaes-technology-innovation-institute-releases-new-ai-model-series-outperforming-metas
- Notes: Open weights; 11B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 52) Yi-1.5-34B - 01.AI - 2024-05-13
- Source: https://github.com/01-ai/Yi
- Notes: Open-source release (Yi-1.5 announcement).
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 53) Yi-1.5-6B - 01.AI - 2024-05-13
- Source: https://github.com/01-ai/Yi
- Notes: Open-source release (Yi-1.5 announcement).
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 54) Yi-1.5-9B - 01.AI - 2024-05-13
- Source: https://github.com/01-ai/Yi
- Notes: Open-source release (Yi-1.5 announcement).
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 55) PaliGemma 3B - Google - 2024-05-14
- Source: https://ai.google.dev/gemma/docs/releases
- Notes: Open weights; 3B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 56) Phi-3 Medium 14B - Microsoft - 2024-05-21
- Source: https://azure.microsoft.com/en-us/blog/new-models-added-to-the-phi-3-family-available-on-microsoft-azure/
- Notes: Open weights; 14B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 57) Phi-3 Small 7B - Microsoft - 2024-05-21
- Source: https://azure.microsoft.com/en-us/blog/new-models-added-to-the-phi-3-family-available-on-microsoft-azure/
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 58) Qwen2 1.5B - Alibaba - 2024-06-07
- Source: https://qwenlm.github.io/blog/qwen2/
- Notes: Open weights; 1.5B parameters.
- Benchmarks: 14 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU; plus 6 more.

## 59) Qwen2 57B-A14B - Alibaba - 2024-06-07
- Source: https://qwenlm.github.io/blog/qwen2/
- Notes: Open weights; MoE 57B total parameters.
- Benchmarks: 20 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, MATH, MBPP; plus 12 more.

## 60) Qwen2 72B - Alibaba - 2024-06-07
- Source: https://qwenlm.github.io/blog/qwen2/
- Notes: Open weights; 72B parameters.
- Benchmarks: 20 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, MATH, MBPP; plus 12 more.

## 61) Qwen2 7B - Alibaba - 2024-06-07
- Source: https://qwenlm.github.io/blog/qwen2/
- Notes: Open weights; 7B parameters.
- Benchmarks: 20 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, MATH, MBPP; plus 12 more.

## 62) Qwen2-1.5B - Alibaba (Qwen Team) - 2024-06-07
- Source: https://qwenlm.github.io/blog/qwen2/
- Notes: Open weights; Apache 2.0 license per Qwen2 release.
- Benchmarks: 14 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU; plus 6 more.

## 63) Qwen2-57B-A14B - Alibaba (Qwen Team) - 2024-06-07
- Source: https://qwenlm.github.io/blog/qwen2/
- Notes: Open weights; Apache 2.0 license per Qwen2 release.
- Benchmarks: 20 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, MATH, MBPP; plus 12 more.

## 64) Qwen2-72B - Alibaba (Qwen Team) - 2024-06-07
- Source: https://qwenlm.github.io/blog/qwen2/
- Notes: Open weights; Qianwen License per Qwen2 release.
- Benchmarks: 20 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, MATH, MBPP; plus 12 more.

## 65) Qwen2-7B - Alibaba (Qwen Team) - 2024-06-07
- Source: https://qwenlm.github.io/blog/qwen2/
- Notes: Open weights; Apache 2.0 license per Qwen2 release.
- Benchmarks: 20 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, MATH, MBPP; plus 12 more.

## 66) RecurrentGemma 9B - Google - 2024-06-11
- Source: https://ai.google.dev/gemma/docs/releases
- Notes: Open weights; 9B parameters. Benchmarks from RecurrentGemma model card (base results table).
- Benchmarks: 10 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU, Natural Questions; plus 2 more.

## 67) Gemma 2 27B - Google - 2024-06-27
- Source: https://blog.google/innovation-and-ai/technology/developers-tools/google-gemma-2/
- Notes: Open weights; 27B parameters. Benchmarks from Gemma 2 model card (PT results table).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, DROP, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU; plus 3 more.

## 68) Gemma 2 9B - Google - 2024-06-27
- Source: https://blog.google/innovation-and-ai/technology/developers-tools/google-gemma-2/
- Notes: Open weights; 9B parameters. Benchmarks from Gemma 2 model card (PT results table).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, DROP, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU; plus 3 more.

## 69) InternLM2.5 7B - Shanghai AI Laboratory - 2024-07-03
- Source: https://github.com/InternLM/InternLM
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 70) Mistral NeMo 12B - Mistral AI - 2024-07-18
- Source: https://mistral.ai/it/news/mistral-nemo
- Notes: Open weights; 12B parameters. Benchmarks from Mistral-Nemo-Base-2407 model card (official HF).
- Benchmarks: 7 fields populated in `data/open_metadata.csv` (see `__setting` columns): CSQA, HellaSwag, MMLU, Natural Questions, TriviaQA, TruthfulQA, WinoGrande.

## 71) Llama 3.1 70B - Meta - 2024-07-24
- Source: https://about.fb.com/es/news/2024/07/presentamos-llama-3-1-nuestro-modelo-de-ia-mas-capaz-hasta-la-fecha/
- Notes: Open weights; 70B parameters. Benchmarks from Llama 3 technical report (arXiv 2407.21783) base pretrained table.
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, MATH, MBPP; plus 3 more.

## 72) Llama 3.1 8B - Meta - 2024-07-24
- Source: https://about.fb.com/es/news/2024/07/presentamos-llama-3-1-nuestro-modelo-de-ia-mas-capaz-hasta-la-fecha/
- Notes: Open weights; 8B parameters. Benchmarks from Llama 3 technical report (arXiv 2407.21783) base pretrained table.
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, MATH, MBPP; plus 3 more.

## 73) Gemma 2 2B - Google - 2024-07-31
- Source: https://ai.google.dev/gemma/docs/releases
- Notes: Open weights; 2B parameters. Benchmarks from Gemma 2 model card (PT results table).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, DROP, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU; plus 3 more.

## 74) InternLM2.5 1.8B - Shanghai AI Laboratory - 2024-08-05
- Source: https://github.com/InternLM/InternLM
- Notes: Open weights; 1.8B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 75) InternLM2.5 20B - Shanghai AI Laboratory - 2024-08-05
- Source: https://github.com/InternLM/InternLM
- Notes: Open weights; 20B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 76) Qwen2.5 1.5B - Alibaba - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; 1.5B parameters. Benchmarks from Qwen2.5 base model evaluation (settings per release blog).
- Benchmarks: 22 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, HumanEval+, MATH; plus 14 more.

## 77) Qwen2.5 14B - Alibaba - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; 14B parameters. Benchmarks from Qwen2.5 base model evaluation (settings per release blog).
- Benchmarks: 20 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HumanEval, HumanEval+, MATH, MBPP; plus 12 more.

## 78) Qwen2.5 32B - Alibaba - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; 32B parameters. Benchmarks from Qwen2.5 base model evaluation (settings per release blog).
- Benchmarks: 22 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, HumanEval+, MATH; plus 14 more.

## 79) Qwen2.5 3B - Alibaba - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; 3B parameters. Benchmarks from Qwen2.5 base model evaluation (settings per release blog).
- Benchmarks: 22 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, HumanEval+, MATH; plus 14 more.

## 80) Qwen2.5 72B - Alibaba - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; 72B parameters. Benchmarks from Qwen2.5 base model evaluation (settings per release blog).
- Benchmarks: 22 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, HumanEval+, MATH; plus 14 more.

## 81) Qwen2.5 7B - Alibaba - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; 7B parameters. Benchmarks from Qwen2.5 base model evaluation (settings per release blog).
- Benchmarks: 22 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, HumanEval, HumanEval+, MATH; plus 14 more.

## 82) Qwen2.5-1.5B - Alibaba (Qwen Team) - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; Apache 2.0 license per Qwen2.5 release.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 83) Qwen2.5-14B - Alibaba (Qwen Team) - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; Apache 2.0 license per Qwen2.5 release.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 84) Qwen2.5-32B - Alibaba (Qwen Team) - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; Apache 2.0 license per Qwen2.5 release.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 85) Qwen2.5-72B - Alibaba (Qwen Team) - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; non-Apache license per Qwen2.5 release.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 86) Qwen2.5-7B - Alibaba (Qwen Team) - 2024-09-19
- Source: https://qwenlm.github.io/blog/qwen2.5/
- Notes: Open weights; Apache 2.0 license per Qwen2.5 release.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 87) Llama 3.2 11B - Meta - 2024-09-25
- Source: https://about.fb.com/ltam/news/2024/09/llama-3-2-revolucionando-la-ia-y-la-vision-de-vanguardia-con-modelos-abiertos-y-personalizables/
- Notes: Open weights; 11B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 88) Llama 3.2 1B - Meta - 2024-09-25
- Source: https://about.fb.com/ltam/news/2024/09/llama-3-2-revolucionando-la-ia-y-la-vision-de-vanguardia-con-modelos-abiertos-y-personalizables/
- Notes: Open weights; 1B parameters. Benchmarks from Meta Llama 3.2 model card (base pretrained models table).
- Benchmarks: 3 fields populated in `data/open_metadata.csv` (see `__setting` columns): ARC-Challenge, DROP, MMLU.

## 89) Llama 3.2 3B - Meta - 2024-09-25
- Source: https://about.fb.com/ltam/news/2024/09/llama-3-2-revolucionando-la-ia-y-la-vision-de-vanguardia-con-modelos-abiertos-y-personalizables/
- Notes: Open weights; 3B parameters. Benchmarks from Meta Llama 3.2 model card (base pretrained models table).
- Benchmarks: 3 fields populated in `data/open_metadata.csv` (see `__setting` columns): ARC-Challenge, DROP, MMLU.

## 90) Llama 3.2 90B - Meta - 2024-09-25
- Source: https://about.fb.com/ltam/news/2024/09/llama-3-2-revolucionando-la-ia-y-la-vision-de-vanguardia-con-modelos-abiertos-y-personalizables/
- Notes: Open weights; 90B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 91) OLMo 2 13B - Ai2 - 2024-11-26
- Source: https://allenai-web-sandbox.allen.ai/olmo/release-notes
- Notes: Open weights; 13B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 92) OLMo 2 7B - Ai2 - 2024-11-26
- Source: https://allenai-web-sandbox.allen.ai/olmo/release-notes
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 93) Llama 3.3 70B - Meta - 2024-12-06
- Source: https://techcrunch.com/2024/12/06/meta-unveils-a-new-more-efficient-llama-model/
- Notes: Open weights; 70B parameters. Benchmarks from Meta Llama 3.3 70B Instruct model card (instruction-tuned results).
- Benchmarks: 8 fields populated in `data/open_metadata.csv` (see `__setting` columns): GPQA (Diamond), HumanEval, MATH, MBPP, MGSM, MMLU, MMLU-Pro, IFEval.

## 94) Mistral Small 3 24B - Mistral AI - 2025-01-30
- Source: https://mistral.ai/fr/news/mistral-small-3
- Notes: Open weights; 24B parameters. Benchmarks from Mistral-Small-24B-Instruct-2501 model card (publicly accessible benchmarks); scores reported as fractions (0-1).
- Benchmarks: 5 fields populated in `data/open_metadata.csv` (see `__setting` columns): GPQA, GSM8K, HumanEval, MMLU-Pro, IFEval.

## 95) OLMo 2 32B - Ai2 - 2025-03-13
- Source: https://allenai-web-sandbox.allen.ai/olmo/release-notes
- Notes: Open weights; 32B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 96) Qwen2.5-Omni-7B - Alibaba - 2025-03-27
- Source: https://qwenlm.github.io/blog/qwen2.5-omni/
- Notes: Open weights; 7B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 97) Qwen3 1.7B - Alibaba - 2025-04-29
- Source: https://qwenlm.github.io/blog/qwen3/
- Notes: Open weights (Apache 2.0 for dense models per release blog). Benchmarks from Qwen3 technical report (arXiv 2505.09388).
- Benchmarks: 9 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, MATH, MBPP, MGSM, MMLU, MMLU-Pro; plus 1 more.

## 98) Qwen3 14B - Alibaba - 2025-04-29
- Source: https://qwenlm.github.io/blog/qwen3/
- Notes: Open weights (Apache 2.0 for dense models per release blog). Benchmarks from Qwen3 technical report (arXiv 2505.09388).
- Benchmarks: 9 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, MATH, MBPP, MGSM, MMLU, MMLU-Pro; plus 1 more.

## 99) Qwen3 30B-A3B - Alibaba - 2025-04-29
- Source: https://qwenlm.github.io/blog/qwen3/
- Notes: Open weights; Qwen3 30B-A3B is a MoE model open-weighted per release blog. Benchmarks from Qwen3 technical report (arXiv 2505.09388).
- Benchmarks: 9 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, MATH, MBPP, MGSM, MMLU, MMLU-Pro; plus 1 more.

## 100) Qwen3 32B - Alibaba - 2025-04-29
- Source: https://qwenlm.github.io/blog/qwen3/
- Notes: Open weights (Apache 2.0 for dense models per release blog). Benchmarks from Qwen3 technical report (arXiv 2505.09388).
- Benchmarks: 9 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, MATH, MBPP, MGSM, MMLU, MMLU-Pro; plus 1 more.

## 101) Qwen3 4B - Alibaba - 2025-04-29
- Source: https://qwenlm.github.io/blog/qwen3/
- Notes: Open weights (Apache 2.0 for dense models per release blog). Benchmarks from Qwen3 technical report (arXiv 2505.09388).
- Benchmarks: 9 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, MATH, MBPP, MGSM, MMLU, MMLU-Pro; plus 1 more.

## 102) Qwen3 8B - Alibaba - 2025-04-29
- Source: https://qwenlm.github.io/blog/qwen3/
- Notes: Open weights (Apache 2.0 for dense models per release blog). Benchmarks from Qwen3 technical report (arXiv 2505.09388).
- Benchmarks: 9 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, MATH, MBPP, MGSM, MMLU, MMLU-Pro; plus 1 more.

## 103) OLMo 2 1B - Ai2 - 2025-05-01
- Source: https://allenai-web-sandbox.allen.ai/olmo/release-notes
- Notes: Open weights; 1B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 104) Caller 32B - Arcee AI - 2025-06-30
- Source: https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative
- Notes: Open weights; 32B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 105) GLM-4-32B-Base-32K - Arcee AI - 2025-06-30
- Source: https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative
- Notes: Open weights; 32B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 106) Homunculus 12B - Arcee AI - 2025-06-30
- Source: https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative
- Notes: Open weights; 12B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 107) SuperNova 70B - Arcee AI - 2025-06-30
- Source: https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative
- Notes: Open weights; 70B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 108) Virtuoso-Large 72B - Arcee AI - 2025-06-30
- Source: https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative
- Notes: Open weights; 72B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 109) gpt-oss-120B - OpenAI - 2025-08-05
- Source: https://openai.com/index/introducing-gpt-oss/
- Notes: Open weights; 120B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 110) gpt-oss-20B - OpenAI - 2025-08-05
- Source: https://openai.com/index/introducing-gpt-oss/
- Notes: Open weights; 20B parameters.
- Benchmarks: No benchmark scores recorded in `data/open_metadata.csv`.

## 111) Apertus 70B - Swiss AI - 2025-09-02
- Source: https://ethz.ch/en/news-and-events/eth-news/news/2025/09/eth-zurich-and-epfl-to-launch-switzerland-s-first-fully-open-large-language-model-apertus.html
- Notes: Open weights; 70B parameters. Benchmarks from Apertus model card (pretraining eval).
- Benchmarks: 3 fields populated in `data/open_metadata.csv` (see `__setting` columns): ARC-Challenge, HellaSwag, WinoGrande.

## 112) Apertus 8B - Swiss AI - 2025-09-02
- Source: https://ethz.ch/en/news-and-events/eth-news/news/2025/09/eth-zurich-and-epfl-to-launch-switzerland-s-first-fully-open-large-language-model-apertus.html
- Notes: Open weights; 8B parameters. Benchmarks from Apertus model card (pretraining eval).
- Benchmarks: 3 fields populated in `data/open_metadata.csv` (see `__setting` columns): ARC-Challenge, HellaSwag, WinoGrande.

## 113) RecurrentGemma 2B - Google - 2024-06-11
- Source: https://ai.google.dev/gemma/docs/recurrentgemma/model_card
- Notes: Open weights; 2B parameters. Benchmarks from RecurrentGemma model card (base results table).
- Benchmarks: 10 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, GSM8K, HellaSwag, HumanEval, MATH, MBPP, MMLU, Natural Questions; plus 2 more.

## 114) Qwen3-Next-80B-A3B-Instruct - Alibaba - 2025-10-14
- Source: https://www.alibabacloud.com/blog/qwen3-next-towards-ultimate-training-%26-inference-efficiency_603319
- Notes: Open weights; 80B total parameters (A3B); instruction-tuned. Benchmarks from Qwen3-Next model card.
- Benchmarks: 5 fields populated in `data/open_metadata.csv` (see `__setting` columns): GPQA, MMLU-Pro, MMLU-redux, MultiPL-E, IFEval.

## 115) Qwen3-Next-80B-A3B-Thinking - Alibaba - 2025-10-14
- Source: https://www.alibabacloud.com/blog/qwen3-next-towards-ultimate-training-%26-inference-efficiency_603319
- Notes: Open weights; 80B total parameters (A3B); thinking model. Benchmarks from Qwen3-Next model card.
- Benchmarks: 4 fields populated in `data/open_metadata.csv` (see `__setting` columns): GPQA, MMLU-Pro, MMLU-redux, IFEval.

## 116) OLMo 3 7B Instruct - AI2 - 2025-11-20
- Source: https://allenai.org/blog/olmo-3
- Notes: Open weights; 7B parameters; instruction-tuned. Benchmarks from OLMo 3 model card.
- Benchmarks: 7 fields populated in `data/open_metadata.csv` (see `__setting` columns): BIG-Bench Hard, GPQA, HumanEval+, MATH, MBPP+, MMLU, IFEval.

## 117) OLMo 3 32B Think - AI2 - 2025-11-20
- Source: https://allenai.org/blog/olmo-3
- Notes: Open weights; 32B parameters; thinking model. Benchmarks from OLMo 3 model card.
- Benchmarks: 7 fields populated in `data/open_metadata.csv` (see `__setting` columns): BIG-Bench Hard, GPQA, HumanEval+, MATH, MBPP+, MMLU, IFEval.

## 118) OLMo 3.1 32B Think - AI2 - 2025-12-12
- Source: https://allenai.org/blog/olmo-3
- Notes: Open weights; 32B parameters; thinking model. Benchmarks from OLMo 3.1 model card.
- Benchmarks: 7 fields populated in `data/open_metadata.csv` (see `__setting` columns): BIG-Bench Hard, GPQA, HumanEval+, MATH, MBPP+, MMLU, IFEval.

## 119) NVIDIA Nemotron-3 Nano 30B-A3B - NVIDIA - 2025-12-15
- Source: https://huggingface.co/nvidia/NVIDIA-Nemotron-3-Nano-30B-A3B-BF16
- Notes: Open weights; 30B total parameters (A3B). Benchmarks from NVIDIA Nemotron 3 model card (no tools).
- Benchmarks: 2 fields populated in `data/open_metadata.csv` (see `__setting` columns): GPQA, MMLU-Pro.

## 120) Granite 4.0 Micro 3B Instruct - IBM - 2025-10-02
- Source: https://huggingface.co/ibm-granite/granite-4.0-micro
- Notes: Open weights (Apache 2.0); 3B parameters; instruction-tuned. Benchmarks from Granite 4.0 model card (evaluation results table).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, HumanEval, HumanEval+, MBPP, MBPP+, MGSM; plus 3 more.

## 121) Granite 4.0 H Micro 3B Instruct - IBM - 2025-10-02
- Source: https://huggingface.co/ibm-granite/granite-4.0-h-micro
- Notes: Open weights (Apache 2.0); 3B parameters; instruction-tuned. Benchmarks from Granite 4.0 model card (evaluation results table).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, HumanEval, HumanEval+, MBPP, MBPP+, MGSM; plus 3 more.

## 122) Granite 4.0 H Tiny 7B Instruct - IBM - 2025-10-02
- Source: https://huggingface.co/ibm-granite/granite-4.0-h-tiny
- Notes: Open weights (Apache 2.0); 7B parameters; instruction-tuned. Benchmarks from Granite 4.0 model card (evaluation results table).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, HumanEval, HumanEval+, MBPP, MBPP+, MGSM; plus 3 more.

## 123) Granite 4.0 H Small 32B Instruct - IBM - 2025-10-02
- Source: https://huggingface.co/ibm-granite/granite-4.0-h-small
- Notes: Open weights (Apache 2.0); 32B parameters; instruction-tuned. Benchmarks from Granite 4.0 model card (evaluation results table).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: BIG-Bench Hard, GPQA, GSM8K, HumanEval, HumanEval+, MBPP, MBPP+, MGSM; plus 3 more.

## 124) Llama 3 8B Instruct - Meta - 2024-04-18
- Source: https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct
- Notes: Open weights; 8B parameters; instruction-tuned. Benchmarks from Llama 3 8B Instruct model card (instruction-tuned table includes 70B).
- Benchmarks: 5 fields populated in `data/open_metadata.csv` (see `__setting` columns): GPQA, GSM8K, HumanEval, MATH, MMLU.

## 125) Llama 3 70B Instruct - Meta - 2024-04-18
- Source: https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct
- Notes: Open weights; 70B parameters; instruction-tuned. Benchmarks from Llama 3 8B Instruct model card (instruction-tuned table includes 70B).
- Benchmarks: 5 fields populated in `data/open_metadata.csv` (see `__setting` columns): GPQA, GSM8K, HumanEval, MATH, MMLU.

## 126) Llama 3.1 8B Instruct - Meta - 2024-07-24
- Source: https://huggingface.co/meta-llama/Meta-Llama-3.1-8B-Instruct
- Notes: Open weights; 8B parameters; instruction-tuned. Benchmarks from Llama 3.1 8B Instruct model card (instruction-tuned table includes 70B).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, GPQA, GSM8K, HumanEval, MATH, MBPP+, MGSM, MMLU; plus 3 more.

## 127) Llama 3.1 70B Instruct - Meta - 2024-07-24
- Source: https://huggingface.co/meta-llama/Meta-Llama-3.1-8B-Instruct
- Notes: Open weights; 70B parameters; instruction-tuned. Benchmarks from Llama 3.1 8B Instruct model card (instruction-tuned table includes 70B).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, GPQA, GSM8K, HumanEval, MATH, MBPP+, MGSM, MMLU; plus 3 more.

## 128) Llama 3.2 1B Instruct - Meta - 2024-09-25
- Source: https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct
- Notes: Open weights; 1B parameters; instruction-tuned. Benchmarks from Llama 3.2 1B Instruct model card (instruction-tuned MMLU table includes 3B).
- Benchmarks: 1 fields populated in `data/open_metadata.csv` (see `__setting` columns): MMLU.

## 129) Llama 3.2 3B Instruct - Meta - 2024-09-25
- Source: https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct
- Notes: Open weights; 3B parameters; instruction-tuned. Benchmarks from Llama 3.2 1B Instruct model card (instruction-tuned MMLU table includes 3B).
- Benchmarks: 1 fields populated in `data/open_metadata.csv` (see `__setting` columns): MMLU.

## 130) Granite 3.1 1B-A400M Instruct - IBM - 2024-12-18
- Source: https://huggingface.co/ibm-granite/granite-3.1-2b-instruct
- Notes: Open weights (Apache 2.0); 1B parameters; instruction-tuned. Benchmarks from Granite 3.1 2B Instruct model card (Open LLM Leaderboard v1/v2 tables include multiple sizes).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, MATH, MMLU, MMLU-Pro; plus 3 more.

## 131) Granite 3.1 2B Instruct - IBM - 2024-12-18
- Source: https://huggingface.co/ibm-granite/granite-3.1-2b-instruct
- Notes: Open weights (Apache 2.0); 2B parameters; instruction-tuned. Benchmarks from Granite 3.1 2B Instruct model card (Open LLM Leaderboard v1/v2 tables include multiple sizes).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, MATH, MMLU, MMLU-Pro; plus 3 more.

## 132) Granite 3.1 3B-A800M Instruct - IBM - 2024-12-18
- Source: https://huggingface.co/ibm-granite/granite-3.1-2b-instruct
- Notes: Open weights (Apache 2.0); 3B parameters; instruction-tuned. Benchmarks from Granite 3.1 2B Instruct model card (Open LLM Leaderboard v1/v2 tables include multiple sizes).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, MATH, MMLU, MMLU-Pro; plus 3 more.

## 133) Granite 3.1 8B Instruct - IBM - 2024-12-18
- Source: https://huggingface.co/ibm-granite/granite-3.1-2b-instruct
- Notes: Open weights (Apache 2.0); 8B parameters; instruction-tuned. Benchmarks from Granite 3.1 2B Instruct model card (Open LLM Leaderboard v1/v2 tables include multiple sizes).
- Benchmarks: 11 fields populated in `data/open_metadata.csv` (see `__setting` columns). Includes: ARC-Challenge, BIG-Bench Hard, GPQA, GSM8K, HellaSwag, MATH, MMLU, MMLU-Pro; plus 3 more.

# Open Model Benchmark Report (Batch 2026-01-30) — Llama Instruct + Granite 3.1 Instruct

## Llama 3 / 3.1 / 3.2 instruction-tuned models
- Benchmark sources:
  - https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct
  - https://huggingface.co/meta-llama/Meta-Llama-3.1-8B-Instruct
  - https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct
- Models: Llama 3 8B Instruct, Llama 3 70B Instruct, Llama 3.1 8B Instruct, Llama 3.1 70B Instruct, Llama 3.2 1B Instruct, Llama 3.2 3B Instruct
- Benchmarks recorded: MMLU; GPQA, HumanEval, GSM8K, MATH (Llama 3); MMLU-Pro, IFEval, ARC-C, MBPP++, MultiPL-E (HumanEval), MGSM (Llama 3.1); MMLU (bf16) for Llama 3.2 instruct.

## Granite 3.1 instruction-tuned models
- Benchmark source: https://huggingface.co/ibm-granite/granite-3.1-2b-instruct
- Models: Granite 3.1 1B-A400M Instruct, Granite 3.1 2B Instruct, Granite 3.1 3B-A800M Instruct, Granite 3.1 8B Instruct
- Benchmarks recorded (Open LLM Leaderboard v1): ARC-Challenge, HellaSwag, MMLU, TruthfulQA, WinoGrande, GSM8K.
- Benchmarks recorded (Open LLM Leaderboard v2): IFEval, BIG-Bench Hard, MATH (Lvl 5), GPQA, MMLU-Pro.
