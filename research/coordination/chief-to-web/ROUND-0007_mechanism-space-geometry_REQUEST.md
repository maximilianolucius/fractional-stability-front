# ROUND-0007 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — THEOREM-SPECIFIC FALSIFICATION  
**Status:** OPEN

## Objective

Attempt to falsify the strengthened theorem nucleus selected after ROUND-0006.

This round does **not** reopen primary-direction selection. It tests whether the specific mechanism-space geometry and coalition results in:

- research/double-allee/PRIMARY_DIRECTION.md
- research/double-allee/THEOREM_PROGRAM.md
- research/double-allee/PROOF_LEDGER.md

are already known under other terminology.

## Mathematical target

The selected class is

F(x;lambda)
=
b(x)
-
sum_i lambda_i g_i(x),

with mechanism strengths lambda_i >= 0.

The main target results are:

1. convexity/upper-set geometry of
   M(lambda)=max_x F(x;lambda);
2. extinction region
   E={lambda:M(lambda)<=0}
   as an intersection of half-spaces;
3. strong-Allee phase
   L\E
   under component-level concavity/convexity assumptions;
4. exact radial phase window
   no-threshold -> strong-threshold -> extinction;
5. minimal threshold-generating subsets as weighted minimal coalitions filtered by persistence;
6. Boolean-lattice/inclusion-chain phase ordering;
7. mechanism-boundary normal from the maximizing critical density.

## Exact questions

### Convex/viability geometry

1. Has extinction/persistence for ecological populations already been formulated as a convex region in a vector of mechanism intensities using a max-over-density viability function?
2. Is a theorem equivalent to
   E = intersection_x {lambda: lambda dot g(x) >= b(x)}
   already standard in ecological threshold theory?
3. Search robust viability, persistence regions, extinction sets, tipping surfaces, and parameter-space convexity.

### Radial phase theorem

4. Is there prior work deriving two exact critical mechanism-strength values:
   - low-density sign threshold;
   - global extinction threshold;
   with a unique strong-Allee interval between them?
5. Search one-parameter families of multiple Allee mechanisms and “window”/“re-entrant” threshold behavior.

### Minimal threshold-generating coalitions

6. Has multiple-Allee theory used minimal winning coalition / threshold game / Boolean-lattice language?
7. Is there a known theorem that the smallest collections of individually insufficient mechanisms that jointly create an extinction threshold are characterized by a weighted threshold inequality?
8. Search analogous concepts:
   - minimal cut sets;
   - minimal failure sets;
   - minimal sufficient causes;
   - tipping sets;
   - critical species/mechanism sets;
   - weighted voting games;
   - monotone Boolean systems;
   - reliability theory.
9. Determine whether importing minimal-winning-coalition mathematics would be merely terminology or whether ecology-specific persistence filtering creates a genuinely distinct result.

### Shape hypotheses

10. Search log-concavity/log-convexity theorems for products of density-dependent survival/fecundity functions.
11. Search whether component-level convex penalty profiles have already been used to prove unimodality or exact Allee root counts.
12. Search population projection/life-cycle analogues.

### Boundary sensitivity

13. Search envelope/Danskin treatment of ecological extinction/tipping surfaces.
14. Determine whether grad M = -g(x*) has prior ecological interpretation.

## Mandatory adjacent literatures

Search beyond Allee terminology:

- convex analysis of viability/persistence regions;
- robust ecological stability;
- reliability/minimal cut sets;
- weighted threshold games/minimal winning coalitions;
- epidemiological reproduction-number parameter geometry;
- population projection matrices;
- dose-response synergy;
- catastrophe/tipping parameter sets;
- monotone systems;
- survival-fecundity tradeoff models.

## Strongest possible killer

A source kills the strengthened headline if it already gives, at comparable generality:

> a convex mechanism-strength phase classification together with minimal mechanism combinations that cross a low-density failure boundary while retaining positive persistence.

Report that source even if it does not use the term Allee.

## Evidence requirements

For every close theorem record:

- exact variables and parameter space;
- convexity/monotonicity assumptions;
- whether threshold is local-at-zero or global-max based;
- whether multiple mechanisms are separately represented;
- whether minimal subsets/coalitions are classified;
- whether persistence/extinction is included;
- whether result is necessary/sufficient;
- exact relation to THM-P2/P3/P4.

## Required deliverables

1. research/coordination/web-to-chief/ROUND-0007_mechanism-space-geometry_RETURN.md
2. update corpus and bibliography for resolving sources;
3. update web-search provenance files;
4. verdicts for:
   - THM-P2 convex phase geometry;
   - THM-P3 radial threshold window;
   - THM-P4 minimal threshold-generating coalitions;
   - THM-P5 boundary sensitivity.
5. state whether P2–P4 together remain a defensible central contribution.

## Decision categories

- DIRECT PRIOR RESULT FOUND
- COVERED AFTER REFORMULATION
- CLOSE PRIOR ART — NARROW
- NO RESOLVING RESULT FOUND IN SEARCHED CORPUS
- MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT

## Notes

Do not protect the project.

If convexity/intersection-of-half-spaces is standard and the coalition result is just a weighted voting game with renamed variables, say so explicitly.

The key question is whether the **combined ecological phase theorem** yields new mathematical consequences beyond applying two standard toolkits side by side.
