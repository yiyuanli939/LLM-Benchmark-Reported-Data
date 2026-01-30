# Batch additions (2026-01-30)

Added to open_metadata.csv (new rows only):

| model_name | organization | release_date | source_url | notes |
| --- | --- | --- | --- | --- |
| Mistral Small 3 24B | Mistral AI | 2025-01-30 | https://mistral.ai/fr/news/mistral-small-3 | Open weights; 24B parameters. |
| Qwen2.5-Omni-7B | Alibaba | 2025-03-27 | https://qwenlm.github.io/blog/qwen2.5-omni/ | Open weights; 7B parameters. |
| Homunculus 12B | Arcee AI | 2025-06-30 | https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative | Open weights; 12B parameters. |
| Caller 32B | Arcee AI | 2025-06-30 | https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative | Open weights; 32B parameters. |
| GLM-4-32B-Base-32K | Arcee AI | 2025-06-30 | https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative | Open weights; 32B parameters. |
| SuperNova 70B | Arcee AI | 2025-06-30 | https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative | Open weights; 70B parameters. |
| Virtuoso-Large 72B | Arcee AI | 2025-06-30 | https://www.arcee.ai/blog/arcee-ai-launches-open-weights-initiative | Open weights; 72B parameters. |
| gpt-oss-20B | OpenAI | 2025-08-05 | https://openai.com/index/introducing-gpt-oss/ | Open weights; 20B parameters. |
| gpt-oss-120B | OpenAI | 2025-08-05 | https://openai.com/index/introducing-gpt-oss/ | Open weights; 120B parameters. |
| Apertus 8B | Swiss AI | 2025-09-02 | https://ethz.ch/en/news-and-events/eth-news/news/2025/09/eth-zurich-and-epfl-to-launch-switzerland-s-first-fully-open-large-language-model-apertus.html | Open weights; 8B parameters. |
| Apertus 70B | Swiss AI | 2025-09-02 | https://ethz.ch/en/news-and-events/eth-news/news/2025/09/eth-zurich-and-epfl-to-launch-switzerland-s-first-fully-open-large-language-model-apertus.html | Open weights; 70B parameters. |

# Batch 2026-01-30 (benchmarks)

Synced `open_metadata.csv` columns to match `metadata.csv`. Added benchmark scores for Qwen3 base models from the Qwen3 technical report (Table 6).

Benchmarks recorded: MMLU, MMLU-Pro, BIG-Bench Hard (BBH), GPQA, GSM8K, MATH, MultiPL-E, MBPP, MGSM (with settings per table header).

| model_name | benchmarks source |
| --- | --- |
| Qwen3 1.7B | Qwen3 technical report (arXiv 2505.09388) |
| Qwen3 4B | Qwen3 technical report (arXiv 2505.09388) |
| Qwen3 8B | Qwen3 technical report (arXiv 2505.09388) |
| Qwen3 14B | Qwen3 technical report (arXiv 2505.09388) |
| Qwen3 32B | Qwen3 technical report (arXiv 2505.09388) |
| Qwen3 30B-A3B | Qwen3 technical report (arXiv 2505.09388) |

# Batch additions (2026-01-30, batch 2)

Added to open_metadata.csv (new rows only):

| model_name | organization | release_date | source_url | notes |
| --- | --- | --- | --- | --- |
| Baichuan2 7B | Baichuan | 2023-09-06 | https://github.com/baichuan-inc/Baichuan-7B | Open weights; 7B parameters. |
| Baichuan2 13B | Baichuan | 2023-09-06 | https://github.com/baichuan-inc/Baichuan-7B | Open weights; 13B parameters. |
| Yi 6B | 01.AI | 2023-11-02 | https://github.com/01-ai/Yi | Open weights; 6B parameters. |
| Yi 34B | 01.AI | 2023-11-02 | https://github.com/01-ai/Yi | Open weights; 34B parameters. |
| InternLM2 7B | Shanghai AI Laboratory | 2024-01-17 | https://github.com/InternLM/InternLM | Open weights; 7B parameters. |
| InternLM2 20B | Shanghai AI Laboratory | 2024-01-17 | https://github.com/InternLM/InternLM | Open weights; 20B parameters. |
| InternLM2 1.8B | Shanghai AI Laboratory | 2024-01-31 | https://github.com/InternLM/InternLM | Open weights; 1.8B parameters. |
| StarCoder2 3B | BigCode | 2024-02-28 | https://huggingface.co/blog/starcoder2 | Open weights; 3B parameters. |
| StarCoder2 7B | BigCode | 2024-02-28 | https://huggingface.co/blog/starcoder2 | Open weights; 7B parameters. |
| StarCoder2 15B | BigCode | 2024-02-28 | https://huggingface.co/blog/starcoder2 | Open weights; 15B parameters. |
| CodeGemma 2B | Google | 2024-04-09 | https://developers.googleblog.com/en/gemma-family-expands-with-models-tailored-for-developers-and-researchers/ | Open weights; 2B parameters. |
| CodeGemma 7B | Google | 2024-04-09 | https://developers.googleblog.com/en/gemma-family-expands-with-models-tailored-for-developers-and-researchers/ | Open weights; 7B parameters. |
| Phi-3 Small 7B | Microsoft | 2024-05-21 | https://azure.microsoft.com/en-us/blog/new-models-added-to-the-phi-3-family-available-on-microsoft-azure/ | Open weights; 7B parameters. |
| Phi-3 Medium 14B | Microsoft | 2024-05-21 | https://azure.microsoft.com/en-us/blog/new-models-added-to-the-phi-3-family-available-on-microsoft-azure/ | Open weights; 14B parameters. |
| RecurrentGemma 9B | Google | 2024-06-11 | https://ai.google.dev/gemma/docs/releases | Open weights; 9B parameters. |
| InternLM2.5 7B | Shanghai AI Laboratory | 2024-07-03 | https://github.com/InternLM/InternLM | Open weights; 7B parameters. |
| InternLM2.5 1.8B | Shanghai AI Laboratory | 2024-08-05 | https://github.com/InternLM/InternLM | Open weights; 1.8B parameters. |
| InternLM2.5 20B | Shanghai AI Laboratory | 2024-08-05 | https://github.com/InternLM/InternLM | Open weights; 20B parameters. |

# Batch 2026-01-30 (Qwen/Qwen2 benchmarks)

Filled benchmark results (from official model cards only) in `open_metadata.csv` for the following models:

| model_name | benchmark fields populated |
| --- | --- |
| Qwen 1.8B | MMLU, GSM8K, HumanEval |
| Qwen 7B | MMLU, GSM8K, MATH, HumanEval, MBPP, BIG-Bench Hard |
| Qwen 14B | MMLU, GSM8K, MATH, HumanEval, MBPP, BIG-Bench Hard |
| Qwen 72B | MMLU, GSM8K, MATH, HumanEval, MBPP, BIG-Bench Hard |
| Qwen2 1.5B | MMLU, MMLU-Pro, TheoremQA, HumanEval, MBPP, GSM8K, MATH, BIG-Bench Hard, HellaSwag, WinoGrande, ARC-Challenge, TruthfulQA |
| Qwen2 7B | MMLU, MMLU-Pro, GPQA, TheoremQA, BIG-Bench Hard, HellaSwag, WinoGrande, ARC-Challenge, TruthfulQA, HumanEval, MBPP, MultiPL-E, GSM8K, MATH, Multi-Exam, Multi-Understanding, Multi-Mathematics, Multi-Translation |
| Qwen2 57B-A14B | MMLU, MMLU-Pro, GPQA, TheoremQA, BIG-Bench Hard, HellaSwag, WinoGrande, ARC-Challenge, TruthfulQA, HumanEval, MBPP, MultiPL-E, GSM8K, MATH, Multi-Exam, Multi-Understanding, Multi-Mathematics, Multi-Translation |
| Qwen2 72B | MMLU, MMLU-Pro, GPQA, TheoremQA, BIG-Bench Hard, HellaSwag, WinoGrande, ARC-Challenge, TruthfulQA, HumanEval, MBPP, MultiPL-E, GSM8K, MATH, Multi-Exam, Multi-Understanding, Multi-Mathematics, Multi-Translation |
Qwen2 1.5B,Alibaba,2024-06-07,https://qwenlm.github.io/blog/qwen2/,open reports/combined_report.md,Open weights; 1.5B parameters.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,43.9,25-shot,,,37.2,3-shot,,,,,,,,,,,,,,,,,,,,,,,,,,,58.5,4-shot,66.6,10-shot,31.1,0-shot,,,,,,,,,,,,,21.7,4-shot,37.4,0-shot,,,,,56.5,5-shot,21.8,5-shot,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,15.0,5-shot,,,45.9,0-shot,,,,,,,,,66.2,5-shot,,,,,70.6,5-shot,70.3,5-shot,,,,,,,,
Qwen2 57B-A14B,Alibaba,2024-06-07,https://qwenlm.github.io/blog/qwen2/,open reports/combined_report.md,Open weights; MoE 57B total parameters.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,64.1,25-shot,,,67.0,3-shot,,,,,,,,,,,,,,,34.3,5-shot,,,,,,,,,,,80.7,4-shot,85.2,10-shot,53.0,0-shot,,,,,,,,,,,,,43.0,4-shot,71.9,0-shot,,,,,76.5,5-shot,43.0,5-shot,,,,,,,,,,,,,65.5,M3Exam 5-shot; IndoMMLU 3-shot; ruMMLU 5-shot; mMMLU 5-shot,62.3,MGSM 8-shot,34.5,Flores-101 5-shot,77.0,BELEBELE 5-shot; XCOPA 5-shot; XWinograd 5-shot; XStoryCloze 0-shot; PAWS-X 5-shot,,,49.8,0-shot,,,,,,,,,,,33.5,5-shot,,,57.7,0-shot,,,,,,,,,79.5,5-shot,,,,,87.7,5-shot,88.5,5-shot,,,,,,,,
Qwen2 72B,Alibaba,2024-06-07,https://qwenlm.github.io/blog/qwen2/,open reports/combined_report.md,Open weights; 72B parameters.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,68.9,25-shot,,,82.4,3-shot,,,,,,,,,,,,,,,37.9,5-shot,,,,,,,,,,,89.5,4-shot,87.6,10-shot,64.6,0-shot,,,,,,,,,,,,,51.1,4-shot,76.9,0-shot,,,,,84.2,5-shot,55.6,5-shot,,,,,,,,,,,,,76.6,M3Exam 5-shot; IndoMMLU 3-shot; ruMMLU 5-shot; mMMLU 5-shot,76.0,MGSM 8-shot,37.8,Flores-101 5-shot,80.7,BELEBELE 5-shot; XCOPA 5-shot; XWinograd 5-shot; XStoryCloze 0-shot; PAWS-X 5-shot,,,59.6,0-shot,,,,,,,,,,,43.1,5-shot,,,54.8,0-shot,,,,,,,,,85.1,5-shot,,,,,91.0,5-shot,90.1,5-shot,,,,,,,,
Qwen2 7B,Alibaba,2024-06-07,https://qwenlm.github.io/blog/qwen2/,open reports/combined_report.md,Open weights; 7B parameters.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,60.6,25-shot,,,62.6,3-shot,,,,,,,,,,,,,,,31.8,5-shot,,,,,,,,,,,79.9,4-shot,80.7,10-shot,51.2,0-shot,,,,,,,,,,,,,44.2,4-shot,65.9,0-shot,,,,,70.3,5-shot,40.0,5-shot,,,,,,,,,,,,,59.2,M3Exam 5-shot; IndoMMLU 3-shot; ruMMLU 5-shot; mMMLU 5-shot,57.5,MGSM 8-shot,31.5,Flores-101 5-shot,72.0,BELEBELE 5-shot; XCOPA 5-shot; XWinograd 5-shot; XStoryCloze 0-shot; PAWS-X 5-shot,,,46.3,0-shot,,,,,,,,,,,31.1,5-shot,,,54.2,0-shot,,,,,,,,,77.0,5-shot,,,,,83.2,5-shot,83.9,5-shot,,,,,,,,
Qwen2-1.5B,Alibaba (Qwen Team),2024-06-07,https://qwenlm.github.io/blog/qwen2/,open reports/combined_report.md,Open weights; Apache 2.0 license per Qwen2 release.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,43.9,25-shot,,,37.2,3-shot,,,,,,,,,,,,,,,,,,,,,,,,,,,58.5,4-shot,66.6,10-shot,31.1,0-shot,,,,,,,,,,,,,21.7,4-shot,37.4,0-shot,,,,,56.5,5-shot,21.8,5-shot,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,15.0,5-shot,,,45.9,0-shot,,,,,,,,,66.2,5-shot,,,,,70.6,5-shot,70.3,5-shot,,,,,,,,
Qwen2-57B-A14B,Alibaba (Qwen Team),2024-06-07,https://qwenlm.github.io/blog/qwen2/,open reports/combined_report.md,Open weights; Apache 2.0 license per Qwen2 release.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,64.1,25-shot,,,67.0,3-shot,,,,,,,,,,,,,,,34.3,5-shot,,,,,,,,,,,80.7,4-shot,85.2,10-shot,53.0,0-shot,,,,,,,,,,,,,43.0,4-shot,71.9,0-shot,,,,,76.5,5-shot,43.0,5-shot,,,,,,,,,,,,,65.5,M3Exam 5-shot; IndoMMLU 3-shot; ruMMLU 5-shot; mMMLU 5-shot,62.3,MGSM 8-shot,34.5,Flores-101 5-shot,77.0,BELEBELE 5-shot; XCOPA 5-shot; XWinograd 5-shot; XStoryCloze 0-shot; PAWS-X 5-shot,,,49.8,0-shot,,,,,,,,,,,33.5,5-shot,,,57.7,0-shot,,,,,,,,,79.5,5-shot,,,,,87.7,5-shot,88.5,5-shot,,,,,,,,
Qwen2-72B,Alibaba (Qwen Team),2024-06-07,https://qwenlm.github.io/blog/qwen2/,open reports/combined_report.md,Open weights; Qianwen License per Qwen2 release.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,68.9,25-shot,,,82.4,3-shot,,,,,,,,,,,,,,,37.9,5-shot,,,,,,,,,,,89.5,4-shot,87.6,10-shot,64.6,0-shot,,,,,,,,,,,,,51.1,4-shot,76.9,0-shot,,,,,84.2,5-shot,55.6,5-shot,,,,,,,,,,,,,76.6,M3Exam 5-shot; IndoMMLU 3-shot; ruMMLU 5-shot; mMMLU 5-shot,76.0,MGSM 8-shot,37.8,Flores-101 5-shot,80.7,BELEBELE 5-shot; XCOPA 5-shot; XWinograd 5-shot; XStoryCloze 0-shot; PAWS-X 5-shot,,,59.6,0-shot,,,,,,,,,,,43.1,5-shot,,,54.8,0-shot,,,,,,,,,85.1,5-shot,,,,,91.0,5-shot,90.1,5-shot,,,,,,,,
Qwen2-7B,Alibaba (Qwen Team),2024-06-07,https://qwenlm.github.io/blog/qwen2/,open reports/combined_report.md,Open weights; Apache 2.0 license per Qwen2 release.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,60.6,25-shot,,,62.6,3-shot,,,,,,,,,,,,,,,31.8,5-shot,,,,,,,,,,,79.9,4-shot,80.7,10-shot,51.2,0-shot,,,,,,,,,,,,,44.2,4-shot,65.9,0-shot,,,,,70.3,5-shot,40.0,5-shot,,,,,,,,,,,,,59.2,M3Exam 5-shot; IndoMMLU 3-shot; ruMMLU 5-shot; mMMLU 5-shot,57.5,MGSM 8-shot,31.5,Flores-101 5-shot,72.0,BELEBELE 5-shot; XCOPA 5-shot; XWinograd 5-shot; XStoryCloze 0-shot; PAWS-X 5-shot,,,46.3,0-shot,,,,,,,,,,,31.1,5-shot,,,54.2,0-shot,,,,,,,,,77.0,5-shot,,,,,83.2,5-shot,83.9,5-shot,,,,,,,,

# Batch 2026-01-30 (benchmarks backfill)

Backfilled Qwen2.5 base model benchmarks (1.5B/3B/7B/14B/32B/72B) and settings from the official Qwen2.5 release blog tables. Winogrande and HellaSwag are not listed for Qwen2.5-14B in the table, so those cells remain blank.

| model_name | benchmarks source |
| --- | --- |
| Qwen2.5 1.5B | Qwen2.5 release blog (base model evaluation tables) |
| Qwen2.5 3B | Qwen2.5 release blog (base model evaluation tables) |
| Qwen2.5 7B | Qwen2.5 release blog (base model evaluation tables) |
| Qwen2.5 14B | Qwen2.5 release blog (base model evaluation tables) |
| Qwen2.5 32B | Qwen2.5 release blog (base model evaluation tables) |
| Qwen2.5 72B | Qwen2.5 release blog (base model evaluation tables) |
Llama 2 70B,Meta,2023-07-18,https://about.fb.com/news/2023/07/llama-2/,open reports/combined_report.md,Open weights; 70B parameters.,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,51.2 (accuracy),3-shot,,,,,,,,,,,,,,,,,,,,,,,,,,,56.8 (accuracy),8-shot,,,29.9 (pass@1),0-shot,,,,,,,,,,,,,,,,,,,,,68.9 (accuracy),5-shot,,,,,,,,,,,,,,,,,,,,,,,,,,,33.0 (accuracy),1-shot,,,,,,,,,,,85.0 (accuracy),1-shot,,,,,,,,,,,,,,,,,,,,,,,,,,,,

# Batch 2026-01-30 (Llama 3 base benchmarks)

Filled benchmark results (from official model card only) in `open_metadata.csv` for the following models:

| model_name | benchmark fields populated |
| --- | --- |
| Llama 3 8B | MMLU, WinoGrande, BIG-Bench Hard, ARC-Challenge, TriviaQA, DROP |
| Llama 3 70B | MMLU, WinoGrande, BIG-Bench Hard, ARC-Challenge, TriviaQA, DROP |

# Batch 2026-01-30 (benchmarks backfill - Llama)

Backfilled Llama 3 (8B/70B) and Llama 2 (7B/13B/70B) base model benchmarks from the Meta Llama 3 model card base-pretrained table. Metrics recorded: MMLU, WinoGrande, BIG-Bench Hard, ARC-Challenge, TriviaQA, DROP with settings noted in `__setting` columns.

| model_name | benchmarks source |
| --- | --- |
| Llama 3 8B | Meta Llama 3 model card (base pretrained models table) |
| Llama 3 70B | Meta Llama 3 model card (base pretrained models table) |
| Llama 2 7B | Meta Llama 3 model card (base pretrained models table) |
| Llama 2 13B | Meta Llama 3 model card (base pretrained models table) |
| Llama 2 70B | Meta Llama 3 model card (base pretrained models table) |

# Batch 2026-01-30 (Llama 3/3.1 benchmarks)

Added benchmark scores for Llama 3 and Llama 3.1 base models from the Llama 3 technical report (arXiv 2407.21783), base pretrained table.

Benchmarks recorded: MMLU, MMLU-Pro, GPQA, BIG-Bench Hard (BBH), MATH, GSM8K, ARC-Challenge, HellaSwag, HumanEval, MBPP, MMLU-redux.

| model_name | benchmarks source |
| --- | --- |
| Llama 3 8B | Llama 3 technical report (arXiv 2407.21783) |
| Llama 3 70B | Llama 3 technical report (arXiv 2407.21783) |
| Llama 3.1 8B | Llama 3 technical report (arXiv 2407.21783) |
| Llama 3.1 70B | Llama 3 technical report (arXiv 2407.21783) |

# Batch 2026-01-30 (Llama family benchmarks)

Added benchmark results for Llama 2, Code Llama, Llama 3.2 (text), and Llama 3.3 70B (instruct) using official sources.

Benchmarks recorded:
- Llama 2 7B/13B/70B: MMLU, BIG-Bench Hard, ARC-Challenge, WinoGrande, TriviaQA, DROP (Meta Llama 3 model card base table).
- Code Llama 7B/13B/34B: HumanEval, MBPP (Code Llama paper Table 2).
- Llama 3.2 1B/3B: MMLU, ARC-Challenge, DROP (Meta Llama 3.2 model card base table).
- Llama 3.3 70B: MMLU, MMLU-Pro, IFEval, GPQA (Diamond), HumanEval, MBPP, MATH, MGSM (Meta Llama 3.3 70B Instruct model card).

| model_name | benchmarks source |
| --- | --- |
| Llama 2 7B | Meta Llama 3 model card (base pretrained table) |
| Llama 2 13B | Meta Llama 3 model card (base pretrained table) |
| Llama 2 70B | Meta Llama 3 model card (base pretrained table) |
| Code Llama 7B | Code Llama paper (arXiv 2308.12950v3) |
| Code Llama 13B | Code Llama paper (arXiv 2308.12950v3) |
| Code Llama 34B | Code Llama paper (arXiv 2308.12950v3) |
| Llama 3.2 1B | Meta Llama 3.2 model card (base pretrained table) |
| Llama 3.2 3B | Meta Llama 3.2 model card (base pretrained table) |
| Llama 3.3 70B | Meta Llama 3.3 70B Instruct model card |

# Batch 2026-01-30 (Mistral family benchmarks)

Added benchmark results for Mistral 7B, Mixtral 8x7B, Mixtral 8x22B, Mistral NeMo 12B, and Mistral Small 3 24B using official sources (arXiv paper, official HF model cards, and Mistral AI blog).

Benchmarks recorded:
- Mistral 7B: MMLU, HellaSwag, WinoGrande, ARC-Challenge, Natural Questions, TriviaQA, HumanEval, MBPP, MATH, GSM8K (Mixtral of Experts paper, Table 2).
- Mixtral 8x7B: MMLU, HellaSwag, WinoGrande, ARC-Challenge, Natural Questions, TriviaQA, HumanEval, MBPP, MATH, GSM8K (Mixtral of Experts paper, Table 2).
- Mixtral 8x22B: GSM8K maj@8 and MATH maj@4 from official blog (instructed version).
- Mistral NeMo 12B: HellaSwag, WinoGrande, CSQA, TruthfulQA, MMLU, TriviaQA, Natural Questions (HF model card).
- Mistral Small 3 24B: MMLU-Pro, GPQA, HumanEval, GSM8K (math_instruct), IFEval (HF model card; values reported as fractions 0–1).

| model_name | benchmarks source |
| --- | --- |
| Mistral 7B | Mixtral of Experts paper (arXiv 2401.04088) |
| Mixtral 8x7B | Mixtral of Experts paper (arXiv 2401.04088) |
| Mixtral 8x22B | Mistral AI blog (Mixtral 8x22B) |
| Mistral NeMo 12B | Mistral-Nemo-Base-2407 model card (HF) |
| Mistral Small 3 24B | Mistral-Small-24B-Instruct-2501 model card (HF) |

# Batch 2026-01-30 (Gemma family benchmarks)

Added benchmark results for Gemma, Gemma 2, and RecurrentGemma base models using official model cards. Also added RecurrentGemma 2B.

Benchmarks recorded:
- Gemma 2B/7B: MMLU, HellaSwag, WinoGrande, ARC-Challenge (ARC-c), TriviaQA, Natural Questions, HumanEval, MBPP, GSM8K, MATH (Gemma model card, PT table).
- Gemma 2 2B/9B/27B: MMLU, HellaSwag, WinoGrande, ARC-Challenge (ARC-c), TriviaQA, Natural Questions, HumanEval, MBPP, GSM8K, MATH, DROP (Gemma 2 model card, PT table).
- RecurrentGemma 2B/9B: MMLU, HellaSwag, WinoGrande, ARC-Challenge (ARC-c), TriviaQA, Natural Questions, HumanEval, MBPP, GSM8K, MATH (RecurrentGemma model card, base table).

| model_name | benchmarks source |
| --- | --- |
| Gemma 2B | Gemma model card (official) |
| Gemma 7B | Gemma model card (official) |
| Gemma 2 2B | Gemma 2 model card (official) |
| Gemma 2 9B | Gemma 2 model card (official) |
| Gemma 2 27B | Gemma 2 model card (official) |
| RecurrentGemma 2B | RecurrentGemma model card (official) |
| RecurrentGemma 9B | RecurrentGemma model card (official) |

# Batch 2026-01-30 (Apertus, Qwen3-Next, OLMo 3, Nemotron 3)

Added benchmark results for Apertus base models and added new models released between 2025-09-02 and 2026-01-30 using official model cards.

Benchmarks recorded:
- Apertus 8B/70B: ARC (as reported), HellaSwag, WinoGrande (Apertus model card pretraining eval table).
- Qwen3-Next-80B-A3B Instruct/Thinking: MMLU-Pro, MMLU-redux, GPQA, IFEval; MultiPL-E (Instruct only) from Qwen3-Next model cards.
- OLMo 3 7B Instruct, OLMo 3 32B Think, OLMo 3.1 32B Think: MMLU, GPQA, BIG-Bench Hard, MATH, HumanEval+, MBPP+, IFEval from OLMo model cards.
- NVIDIA Nemotron-3 Nano 30B-A3B: MMLU-Pro, GPQA (no tools) from NVIDIA model card.

| model_name | benchmarks source |
| --- | --- |
| Apertus 8B | Apertus-8B-Instruct-2509 model card (pretraining eval table) |
| Apertus 70B | Apertus-8B-Instruct-2509 model card (pretraining eval table) |
| Qwen3-Next-80B-A3B-Instruct | Qwen3-Next-80B-A3B-Instruct model card (HF) |
| Qwen3-Next-80B-A3B-Thinking | Qwen3-Next-80B-A3B-Thinking model card (HF) |
| OLMo 3 7B Instruct | Olmo-3-7B-Instruct model card (HF) |
| OLMo 3 32B Think | Olmo-3-32B-Think model card (HF) |
| OLMo 3.1 32B Think | Olmo-3.1-32B-Think model card (HF) |
| NVIDIA Nemotron-3 Nano 30B-A3B | NVIDIA-Nemotron-3-Nano-30B-A3B-BF16 model card (HF) |

# Batch 2026-01-30 (Granite 4.0)

Added Granite 4.0 instruct models released on 2025-10-02 using the official IBM Granite 4.0 model cards.

Benchmarks recorded: MMLU, MMLU-Pro, BIG-Bench Hard (BBH), GPQA, GSM8K, HumanEval, HumanEval+, MBPP, MBPP+, MGSM, IFEval (Average).

| model_name | benchmarks source |
| --- | --- |
| Granite 4.0 Micro 3B Instruct | granite-4.0-micro model card (HF) |
| Granite 4.0 H Micro 3B Instruct | granite-4.0-h-micro model card (HF) |
| Granite 4.0 H Tiny 7B Instruct | granite-4.0-h-tiny model card (HF) |
| Granite 4.0 H Small 32B Instruct | granite-4.0-h-small model card (HF) |
