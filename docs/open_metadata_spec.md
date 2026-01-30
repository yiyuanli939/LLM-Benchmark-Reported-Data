# open_metadata.csv specification

Purpose
- Curated list of open-source/open-weights models with parameter sizes between 1B and 150B.
- Coverage window: 2023-01-01 through 2026-01-29 (inclusive).
- Schema aligns with metadata.csv and benchmark_features.csv for compatibility.
- Make sure the open_metadata.csv contains at least 500 differnet model follow the timespan.
- Priority: fill benchmark results for existing models before adding new models.

File format
- CSV, UTF-8, comma-delimited.
- Column order must match metadata.csv exactly.

Inclusion criteria
- Model size between 1B and 150B parameters (inclusive), reflected in the model name.
- Open-source or open-weights release (license noted in the source URL or in notes).
- Release date within the coverage window.

Columns (same as metadata.csv)
- model_name: Human-readable model name including size (for example, "Llama 3 70B").
- organization: Publisher or primary organization.
- release_date: ISO 8601 date (YYYY-MM-DD).
- source_url: Primary announcement or model card URL for release verification.
- report_path: Optional local report path; leave empty if none.
- notes: Optional clarifications (license, architecture, etc.).
- Benchmark columns: All remaining columns mirror metadata.csv and correspond to benchmark_features.csv.
  Use only official model cards to populate benchmark results.
  Leave these empty if an official model card does not report a benchmark.
  For base model entries (no "Instruct" in model_name), record base pretrained benchmark results only.


Update rules
- Keep column order and names in sync with metadata.csv.
- Add new models only if they meet inclusion criteria and have a verifiable source URL.
- Prefer official announcements or model cards for release_date.

The most important things is make sure each model's benchmark results are recorded in the csv file.

Report should be written in open_report.md. 
