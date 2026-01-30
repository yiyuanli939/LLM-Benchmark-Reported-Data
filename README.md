# Open LLM Benchmark Dataset

A curated dataset of large language models and their benchmark results, with a focus on open-source/open-weights releases. The project keeps structured CSVs for analysis and append-only reports/logs for provenance.

## Something Written by the Author 

This project tries to keep the as less files as possible and try our best to fully automate this model seeking processes. Currently, this is a personally maintained dataset aim to help me thesis about designing a benchmark for datascience. If it can help you, I would be really glad. 

## Scope
- Open models: 1B to 150B parameters, released 2023-01-01 through 2026-01-29.
- Flagship models: >=150B parameters (or undisclosed flagship sizes), released through 2025-01-30.
- Benchmark results are taken from official sources only (model cards, technical reports, or release posts).

## Repository layout
- `data/open_metadata.csv` — main open-model dataset. Schema matches `data/metadata.csv` and `data/benchmark_features.csv`.
- `data/metadata.csv` — flagship model dataset.
- `data/benchmark_features.csv` — benchmark metadata (e.g., question counts).
- `docs/open_metadata_spec.md` — specification and inclusion rules for open models.
- `docs/batch.md` — append-only batch log of updates.
- `docs/specification.md` — working notes and decisions.
- `open_reports/combined_report.md` — narrative report for open models.
- `flagship_reports/combined_report.md` — narrative report for flagship models.
- `flagship_reports/open_report.md` — pointer to the open-models report.

## Data conventions
- Column order must match `data/metadata.csv` exactly.
- Only official sources are used to fill benchmark values.
- If a benchmark is not reported for a model, the cell is left blank.
- Base models (no "Instruct" in name) only use base/pretrained benchmark results.
- Each benchmark has an optional `__setting` column with the evaluation setup.

## Updating the open-model dataset (high level)
1. Add or update rows in `data/open_metadata.csv` using official sources.
2. Fill benchmark values and `__setting` fields where reported.
3. Append a batch entry to `docs/batch.md`.
4. Update `open_reports/combined_report.md` with a short narrative and sources.

## Notes
See `docs/open_metadata_spec.md` for the full specification and required coverage targets.
