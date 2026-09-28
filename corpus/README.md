# Corpus

The corpus stores literature at paper level and, where necessary, theorem/result level.

## Files

- `papers.csv` — bibliographic and screening index.
- `theorems.csv` — theorem-level mathematical extraction.

## Lifecycle

`candidate -> screened -> included -> extracted -> verified`

Excluded records remain auditable with an exclusion reason.

## Rules

- Prefer DOI or another persistent identifier.
- Preserve original bibliographic metadata.
- Never infer exactness from a merely sufficient theorem.
- Separate author-stated open problems from analyst-inferred gaps.
- Record search provenance.
- When a paper contains multiple important theorems, use multiple theorem rows.
