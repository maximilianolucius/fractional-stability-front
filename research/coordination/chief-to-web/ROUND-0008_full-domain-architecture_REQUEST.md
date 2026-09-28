# ROUND-0008 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — DOMAIN ARCHITECTURE / BREADTH-FIRST STATE-OF-ART  
**Status:** OPEN

## Authoritative mission

Read first:

- `docs/PROJECT_CHARTER.md`
- `CHIEF_INITIAL_PROMPT.md`
- `WEB_SEARCHER_INITIAL_PROMPT.md`
- `STATUS.md`
- `research/DOMAIN_MAP.md`

The project maps:

> **Dynamical Systems and Stability Theory — Fractional Differential Equations**

and seeks fertile research gaps, preferably directly involving Double/Multiple Allee or otherwise very close to them.

This project does **not** solve the chosen gap.

## Objective

Perform a **breadth-first architecture and coverage audit** of the full domain.

The purpose is to prevent the project from overfitting to the already well-searched Double Allee branch.

Do not select a final research direction.

## Required domain branches

Audit at least:

1. linear commensurate spectral stability;
2. incommensurate / multi-order stability;
3. nonlinear local stability and linearization;
4. Lyapunov / Mittag-Leffler / global stability;
5. structured matrices: D-stability, diagonal stability, positive/Metzler, M-matrix, sign structure;
6. robustness and uncertainty, including fractional-order uncertainty;
7. delay and neutral systems;
8. switched / impulsive / stochastic / hybrid fractional systems;
9. networks, synchronization, consensus and graph topology;
10. bifurcation, multistability, tipping and resilience;
11. persistence/extinction and population dynamics;
12. variable/distributed-order stability;
13. identifiability/inverse problems where stability/threshold relevance is material;
14. time-fractional reaction-diffusion/spatial dynamics;
15. Double/Multiple Allee as a cross-cutting lens.

## For each branch, find

### A. Canonical foundation
- foundational theorem(s);
- canonical terminology;
- canonical review/monograph if available.

### B. Strongest known result
Prefer:
- exact/N&S;
- arbitrary dimension;
- least restrictive operator/order assumptions;
- strongest robustness/topology statement.

### C. Dominant limitations
Examples:
- only sufficient;
- low dimension;
- commensurate only;
- rational order ratios;
- special sign class;
- fixed topology;
- local only;
- no uncertainty;
- no converse.

### D. Modern frontier
Find representative high-value results from approximately 2021–2026, plus older decisive results when necessary.

### E. Explicit open problems
Prioritize primary-source statements of open questions.

### F. Inferred frontier
Where an exact theorem stops short, describe the missing extension cautiously.

### G. Double Allee relevance
Tag:
- DIRECT;
- VERY CLOSE;
- PLAUSIBLE BRIDGE;
- REMOTE.

Explain why.

## Coverage deliverable

For each branch classify repository evidence coverage:

- THIN;
- SEED;
- MODERATE;
- DEEP.

This is coverage of our repository, not field maturity.

## Candidate-gap rule

You may surface candidate gaps, but do not call them novel or recommend a winner.

For each candidate gap report:

- exact mathematical formulation;
- strongest known neighboring theorem;
- why it might matter;
- closest likely killer literature;
- Double Allee proximity;
- evidence still missing.

## Critical search behavior

The repository currently has disproportionate evidence around Double Allee.

Correct this imbalance.

Search beyond current vocabulary and beyond ecology.

Pay special attention to subfields that could yield **very close Double Allee bridges**, especially:

- nonlinear fractional stability;
- fractional bifurcation;
- persistence/extinction;
- robust stability under order/parameter uncertainty;
- delay/memory versus fractional memory;
- graph/dispersal threshold theory;
- converse/exactness questions.

## Mandatory falsification discipline

If a purported frontier appears to reduce to mature standard theory, report that immediately.

Search equivalent mathematics in:
- control theory;
- matrix analysis;
- monotone systems;
- functional differential equations;
- dynamical-systems bifurcation theory;
- robust optimization;
- positive systems;
- network systems.

## Required deliverables

Create:

`research/coordination/web-to-chief/ROUND-0008_full-domain-architecture_RETURN.md`

and a dated evidence report:

`research/web-search/2026-09-28_full-domain-architecture.md`

Update as appropriate:

- `corpus/papers.csv`
- `corpus/theorems.csv`
- `bibliography/references.bib`
- `research/web-search/SEARCH_LOG.md`
- `QUERY_REGISTRY.md`
- `SOURCE_REGISTRY.md`

Do **not** rewrite Chief synthesis files such as `DOMAIN_MAP.md` or `OPPORTUNITY_PORTFOLIO.md`.

## Return structure

### Executive map
One compact table across all branches.

### Branch-by-branch evidence
For each branch:
- canonical result;
- strongest known result;
- recent frontier;
- limitations;
- open problems;
- Double Allee proximity;
- confidence/coverage.

### Cross-branch observations
Identify:
- duplicated theorem families;
- bridge gaps;
- apparently mature/closed routes;
- under-mapped high-potential areas.

### Candidate gaps
Only evidence-backed hypotheses.

### Survey implications
Which branches are mature enough for synthesis and which require more search before a survey would be credible?

## Completion criterion

The Chief should be able to decide, after this return:

1. which branches need depth-first follow-up rounds;
2. whether the current theorem map is badly imbalanced;
3. which 3–6 candidate frontier areas deserve adversarial investigation;
4. which candidates are closest to Double Allee without being cosmetic.
