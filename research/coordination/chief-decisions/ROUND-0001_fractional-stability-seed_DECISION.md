# ROUND-0001 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** research/coordination/web-to-chief/ROUND-0001_fractional-stability-seed_RETURN.md  
**Disposition:** ACCEPT WITH RESERVATIONS

## Adversarial assessment

The round succeeds at its main purpose: it establishes the exact commensurate spectral core, distinguishes stability notions, and—most importantly—falsifies the broad novelty hypothesis that multiplicative positive-diagonal preservation of a fractional/conic stability sector is essentially unstudied.

The decisive prior art is Kushel–Pavani's generalized D-stability in unbounded LMI regions, with conic-sector cases and multiplicative positive diagonal perturbations. The companion diagonal-dominance work explicitly connects conic-region D-stability to fractional-order systems.

This changes the research program materially: **general fractional-sector D-stability is not a defensible primary novelty claim.**

## Evidence accepted

1. **Commensurate fixed-order core is mature and exact.**
   - Matignon 1998 remains the canonical spectral-sector anchor.
   - Brandibur–Garrappa–Kaslik 2021 is accepted as a modern Caputo clarification, especially for boundary/Jordan-index issues.

2. **Non-commensurate exact BIBO testing exists.**
   - Sabatier–Farges–Trigeassou 2013 is accepted for the abstract-level claim that the proposed BIBO test is necessary and sufficient.
   - It is *not* yet accepted at full theorem-assumption granularity because the round did not inspect the full theorem.

3. **Generalized multiplicative D-stability in conic/LMI regions is direct prior art.**
   - Kushel–Pavani 2022 is accepted as a major novelty blocker.
   - Kushel–Pavani 2021 is accepted as a sufficient-condition/diagonal-dominance companion and explicit fractional-order bridge.

4. **Fractional positive-system diagonal-stability prior art exists.**
   - Zhang–Huang 2017 is accepted at the publisher-abstract level as a necessary-and-sufficient result for the authors' *extended diagonal stability* notion.
   - This notion must not be conflated with unrestricted multiplicative D-stability.

5. **Stability notions must remain separated.**
   - asymptotic state stability;
   - BIBO stability;
   - Mittag-Leffler stability;
   - quadratic/common-Lyapunov stability;
   - robust spectral stability;
   - multiplicative regional D-stability.

## Claims rejected or downgraded

### R1 — Broad missing-bridge hypothesis

Rejected:

> fractional-sector stability under arbitrary positive diagonal scaling is an essentially missing theory.

The searched corpus contains a direct general matrix-theoretic framework.

### R2 — “Exact incommensurate stability” as a single solved object

Downgraded.

The verified 2013 result is a necessary-and-sufficient **BIBO** test. This does not by itself settle all incommensurate *state-stability*, structured-matrix, or simple algebraic-characterization questions.

### R3 — TFS003 theorem granularity

Keep in the corpus, but verification status must remain metadata/abstract-level until full assumptions and theorem statement are inspected.

### R4 — TFS009 terminology

Keep Zhang–Huang as a distinct extended-diagonal-stability result. Do not use it as evidence for classical multiplicative D-stability without a definition-level comparison.

## Novelty threats

The strongest threats are now:

1. generalized (D-region, positive-diagonal)-stability theory;
2. conic-sector relative D-stability;
3. generalized diagonal dominance sufficient criteria;
4. positive/Metzler fractional diagonal-stability theory;
5. recent exact/equivalent LMI formulations for fixed-matrix fractional LTI systems.

Routine reformulation of Matignon-sector stability or its LMI encoding is not a research frontier.

## Mathematical implications

The broad structured-matrix question must be narrowed from:

> Does fractional D-stability exist?

to something of the form:

> For which structured matrix/Jacobian classes can conic-sector multiplicative D-stability be characterized **exactly, finitely, and structurally**, without a universal quantifier over all positive diagonal scalings?

Potential structure classes worth testing include:

- sign/qualitative classes;
- Metzler or eventually positive classes;
- graph-sparse interaction matrices;
- ecological Jacobian families with row/column factorization;
- low-rank or rank-one interaction perturbations;
- fixed sign pattern plus uncertain magnitudes.

A result is potentially strong only if it sharpens the general Kushel–Pavani framework rather than renaming it.

## Frontier-map consequences

Create/maintain the following frontier distinctions:

- **F-001:** general conic-sector multiplicative D-stability exists — not a gap.
- **F-002:** finite/quantifier-free exact characterization for structured subclasses — unresolved search hypothesis.
- **F-003:** topology/sign characterization of conic-sector D-stability for ecological Jacobians — unresolved bridge hypothesis.
- **F-004:** exact incommensurate state-stability versus BIBO/algorithmic root tests — unresolved distinction requiring dedicated audit.

## Open questions

1. Are there known complexity-hardness or impossibility results for generalized/conic D-stability?
2. Are exact finite tests known in dimensions 2, 3, or special sign classes?
3. Does qualitative/sign D-stability for sectors already exist under another name?
4. When does diagonal Lyapunov stability become necessary for conic-sector multiplicative D-stability?
5. Can ecological Jacobian factorization reduce the universal diagonal-scaling problem to a finite sign/topology condition?

## Required next action

Open a dedicated matrix-analysis falsification round focused on exact finite characterizations, sign/graph classes, complexity, and diagonal-stability equivalences.

## Files to update

- research/theorem-map.md
- research/frontier-map.md
- research/open-problems.md
- research/bridges.md
- STATUS.md
- new ROUND-0003 request
