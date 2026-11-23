# Changes

## v1.2.1 (2026-11-23)

Correct the citation metadata repository link to the UCR dataset. Data values are unchanged from v1.2.0; the preprocessing updates below remain included.

## v1.2.0 (2026-11-23)

This update improves data preprocessing and quality.

- VLSQ-8: correct the total-score calculation; totals decrease by 5 and individual answers are unchanged.
- Experience log: preserve all checkbox selections in nine additional columns. Existing first-choice summaries remain available and are labelled accordingly.
- Wellbeing diary: clarify the adapted score labels and ranges (1–25 raw; 4–100 scaled). Numeric scores are unchanged.
- Wrist light: apply trial-window trimming before timestamp rounding and regenerate the native and minute exports. All 39 participants remain included.
- Reproducibility: bundle the metadata helpers and codebooks, refresh affected summary tables, and remove superseded importers and stale generated reports.

Comparison baseline: [v1.1.1](https://github.com/MeLiDosProject/Sancho-SalasEtAl_Dataset_2025/releases/tag/v1.1.1).
