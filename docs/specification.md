Notes/Ideas (2026-01-30)

- Priority: fill benchmark columns with verified scores from official sources (papers/model cards/release blogs).
- Uncertainty: how to handle existing mixed content in batch.md (multiple unrelated sections). Plan: append new sections for each change batch to avoid overwriting.
- For Llama 3/3.1/3.2/etc., confirm whether benchmarks are for base vs instruct; only use base if model name lacks “Instruct”.
- For models with only leaderboard results (e.g., Open LLM Leaderboard), decide whether to exclude or mark separately; prefer official tables.
- Need a scalable way to reach 1000 models with benchmarks; may require automation + curated sources (papers, HF model cards with tables).
- When a benchmark table omits a metric for a model (e.g., Winogrande/HellaSwag for Qwen2.5-14B), leave blank and note in batch log.

[2026-01-30]
- Unsure about handling duplicate naming variants (e.g., "Qwen2 7B" vs "Qwen2-7B"); decide whether to keep both or normalize and de-dup.
- Unsure whether to copy benchmarks from metadata.csv for models whose source_url/release_date differs from open_metadata.csv (e.g., Qwen2.5-72B); may need official source verification before filling.
- Next steps idea: prioritize families with official benchmark tables (Qwen2.5, Yi-1.5, Llama 3, Gemma 2), use web sources to fill, update batch.md per batch, and grow to 500+ models.
- Consider adding a script to track which models lack benchmarks to drive batching.
- Qwen3-Next release date currently sourced from Alibaba Cloud community post (2025-10-14); confirm if an official Qwen blog lists a different date.
- Apertus ARC result is reported as “ARC” without easy/challenge split; recorded under ARC-Challenge with a setting note.
- Granite 3.1 model cards report Open LLM Leaderboard v1/v2 metrics; recorded with settings noting the leaderboard version and MATH Lvl 5.
