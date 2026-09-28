# ROUND-0001 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0  
**Status:** OPEN

## Objective

Build the first **verified theorem-level seed corpus** for the exact spectral stability core of finite-dimensional fractional-order linear systems, and use it as a pilot test of the repository extraction protocol.

This round is deliberately foundational. Its purpose is to establish what is genuinely exact before the project starts inferring frontier gaps.

## Exact questions

1. What are the canonical necessary-and-sufficient stability theorems for finite-dimensional linear autonomous fractional-order systems?
2. Precisely which assumptions are required in the classical Matignon-type results: derivative/operator, commensurate versus incommensurate order, admissible order range, dimension, real/complex matrices, autonomous form, and solution notion?
3. Which later papers correct, sharpen, generalize, reformulate, or extend those exact results?
4. What is the strongest exact result currently identified for incommensurate orders?
5. Which results distinguish asymptotic, Mittag-Leffler, BIBO, or other stability notions rather than silently treating them as interchangeable?
6. What exact or near-exact results connect fractional spectral-sector stability to positive/Metzler, M-matrix, diagonal stability, D-stability, sign stability, or structured uncertainty?
7. Is positive diagonal scaling of a matrix with respect to a fractional stability sector already characterized in a general theorem under terminology other than “fractional D-stability”?
8. Which apparently general criteria are only sufficient, LMI-based, low-dimensional, or restricted to a special matrix class?
9. What explicit open problems, missing converses, or dimension/order restrictions are stated by primary sources?

## Working hypotheses to challenge

- H1: The classical finite-dimensional commensurate linear problem has an exact spectral-sector characterization, whereas much of the broader structured/robust literature supplies only sufficient criteria.
- H2: The interaction between positive diagonal scaling (D-stability/diagonal robustness) and Matignon-sector stability may be substantially less developed than ordinary Hurwitz D-stability.
- H3: Some “fractional stability” papers may repackage integer-order structured-matrix results without yielding an exact new characterization.

The Web Searcher should actively seek evidence that invalidates H2 in particular.

## Scope

Include foundational and mathematically substantive work on:

- finite-dimensional linear autonomous fractional differential systems;
- commensurate and incommensurate order;
- Caputo / Riemann–Liouville distinctions where mathematically relevant;
- Matignon-sector spectral criteria;
- exact characteristic-root criteria;
- positive/Metzler/M-matrix structure;
- D-stability and diagonal stability when explicitly linked to fractional sector stability;
- robust/interval/structured uncertainty only when the mathematical result is reusable.

Time coverage: foundational literature through **2026-09-28**.

## Exclusions

- application-only papers whose contribution is merely applying a known criterion to a specific model;
- purely numerical studies without a reusable theorem;
- synchronization/control papers unless they contain a theorem directly relevant to the requested stability core;
- papers whose exact result cannot be verified beyond an abstract-level claim should be marked unverified, not promoted.

## Search requirements

Use multiple passes:

1. canonical terminology;
2. theorem names and author searches;
3. synonym/equivalent formulation searches;
4. backward citations from foundational sources;
5. forward citation chasing;
6. author follow-up work;
7. recent preprint / early-access check;
8. falsification searches for general fractional D-stability / diagonal-scaling sector theorems.

Representative query families should include, but not be limited to:

- fractional order linear system necessary sufficient stability Matignon;
- incommensurate fractional system exact stability criterion;
- fractional sector stable matrix diagonal scaling;
- fractional D-stability matrix;
- D-stable matrices sector stability;
- diagonal stability fractional-order systems;
- Metzler fractional stability necessary sufficient;
- robust fractional-order stability interval matrix exact criterion;
- qualitative / sign stability fractional-order matrix.

Search mathematical formulations even when the phrase “fractional D-stability” is absent.

## Evidence required

For every high-value source record:

- title, authors, year, venue, DOI/stable URL;
- full-text inspection status;
- exact theorem/proposition number where available;
- system class and fractional operator;
- commensurate/incommensurate structure;
- dimension restrictions;
- matrix assumptions;
- stability notion;
- theorem strength (necessary/sufficient/exact/etc.);
- concise theorem statement;
- proof technique if identifiable;
- limitations and explicit open problems;
- relationship to earlier seed results.

Do not infer necessity from a sufficient LMI criterion.

## Repository context

Read at minimum:

- CHIEF_INITIAL_PROMPT.md
- WEB_SEARCHER_INITIAL_PROMPT.md
- STATUS.md
- docs/protocol.md
- docs/research-questions.md
- docs/search-strategy.md
- docs/taxonomy.md
- corpus/README.md
- corpus/papers.csv
- corpus/theorems.csv
- research/theorem-map.md
- research/frontier-map.md
- research/bridges.md
- research/coordination/README.md

## Required deliverables

1. research/coordination/web-to-chief/ROUND-0001_fractional-stability-seed_RETURN.md
2. Create/update the Web Searcher provenance workspace required by WEB_SEARCHER_INITIAL_PROMPT.md, including:
   - research/web-search/SEARCH_LOG.md
   - research/web-search/QUERY_REGISTRY.md
   - research/web-search/SOURCE_REGISTRY.md
   - research/web-search/NOVELTY_CHECKS.md
   - a dated round-specific search note.
3. Populate corpus/papers.csv with the verified foundational seed.
4. Populate corpus/theorems.csv with theorem-level records for the strongest results.
5. Add only verified foundational entries to bibliography/references.bib.
6. Propose, but do not independently finalize, theorem-map/frontier-map consequences in the RETURN.

## Completion criteria

The round is complete only if:

- the canonical exact spectral criterion(s) have been verified from primary or authoritative sources;
- commensurate and incommensurate cases have been explicitly distinguished;
- at least one serious falsification search for general fractional D-stability / diagonal-scaling-sector prior art has been performed;
- the strongest close prior art is identified even if it damages the bridge hypothesis;
- theorem-level extraction has been demonstrated on a useful pilot corpus;
- unresolved ambiguities are stated explicitly.

Target corpus size is **not** a quota, but a useful pilot will likely require roughly 10–20 high-value sources and multiple theorem records.

## Notes

This is an evidence-acquisition round. Do not declare a final frontier or research direction. The Chief will audit the return adversarially.
