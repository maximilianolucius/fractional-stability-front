# ROUND-0009 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — DEPTH-FIRST / ADVERSARIAL GAP AUDIT  
**Status:** OPEN

## Topic

> **Abstract uniform persistence / permanence for fractional and nonlocal dynamical systems**

This round follows ROUND-0008.

## Why this round exists

ROUND-0008 surfaced a possible asymmetry:

- integer/local dynamical-systems theory has mature abstract uniform-persistence/permanence theorems;
- the searched fractional literature appeared predominantly model-specific.

This may be a genuine fertile gap near Double Allee — or it may already be subsumed by hereditary/Volterra/history-space theory.

Your job is to try to **kill the gap**.

## Terminology warning

Do not confuse ecological/dynamical **uniform persistence / permanence** with the Cresson–Szafrańska use of **fractional persistence problem** in:

DOI `10.1016/j.cnsns.2016.07.016`.

That paper studies preservation under fractional embedding of properties such as positivity, order preservation, equilibria and stability. It is relevant prior art, but it is not automatically the same object as ecological uniform persistence/permanence.

Likewise, model-specific papers proving `liminf x_i(t)>0` or permanence do not by themselves establish an abstract persistence theory.

## Candidate gap to falsify

Search-qualified working hypothesis:

> No abstract theorem has yet been identified that gives general uniform-persistence/permanence criteria for positive Caputo/nonlocal systems in terms comparable to boundary repellers, invariant boundary sets, invasion quantities, acyclicity, persistence functions, or history-state dynamics.

Do not assume this hypothesis is true.

## Mathematical target

For a positive fractional/nonlocal system, investigate whether there already exists a general framework giving one or more of:

- uniform persistence;
- permanence;
- weak-to-uniform persistence upgrades;
- boundary repeller characterizations;
- acyclicity conditions;
- average Lyapunov/persistence functions;
- invasion criteria;
- persistence attractors;
- robust persistence;
- persistence under perturbation.

The key issue is **abstract/general theory**, not one predator–prey or epidemic model.

## Mandatory adjacent literatures

Search all of:

1. Caputo fractional differential equations;
2. Riemann–Liouville / generalized fractional systems where relevant;
3. Volterra integral equations;
4. hereditary dynamical systems;
5. functional differential equations;
6. infinite-delay systems;
7. history-space semiflows;
8. cocycles/processes/skew-product semiflows;
9. monotone systems;
10. nonlocal dynamical systems;
11. resolvent-family formulations;
12. persistence theory for positive semigroups or infinite-dimensional dynamical systems.

## Foundational persistence sources to chase

At minimum inspect/citation-expand around:

- Butler–Freedman–Waltman;
- Hofbauer;
- Hale–Waltman;
- Thieme;
- Smith–Thieme;
- Zhao;
- Fonda–Gidoni 2015, DOI `10.1016/j.na.2014.10.011`.

Determine whether these abstract results can apply directly after a legitimate state-space/history-space formulation of Caputo systems.

## Fractional sources to include

At minimum inspect:

- Cresson & Szafrańska, DOI `10.1016/j.cnsns.2016.07.016`;
- Abbas et al., DOI `10.1007/s12591-014-0219-5`;
- modern fractional population models using “uniform persistence”, “permanence”, “uniformly persistent”, “repeller”, or “persistence attractor”.

Do not stop at those examples.

## Core falsification questions

### Q1 — Direct abstract theorem
Is there already a general fractional theorem equivalent in role to abstract permanence/uniform-persistence theorems?

### Q2 — History-state reduction
Can autonomous Caputo dynamics be embedded into a local semiflow/process on a memory/history space so that existing abstract persistence theory applies with no genuinely new mathematics?

If yes:
- identify the state space;
- identify the semiflow/cocycle theorem;
- state the assumptions;
- explain what remains nontrivial, if anything.

### Q3 — Boundary invariance
For positive Caputo systems, what is the correct notion of boundary invariant set when the state includes memory?

### Q4 — Asymptotic compactness / dissipativity
Do existing Caputo/nonlocal dynamical-system constructions provide the compactness/dissipativity assumptions required by persistence theorems?

### Q5 — Robust persistence
Are there perturbation-robust persistence theorems for fractional/nonlocal systems?

### Q6 — Invasion criteria
Has persistence been characterized through boundary spectral/invasion quantities in a general fractional setting?

### Q7 — Double Allee
Would a general persistence theorem actually say something structurally new for Double/Multiple Allee systems, or would Allee bistability violate the hypotheses commonly used in persistence theory?

This question is essential. Strong Allee systems intentionally contain extinction basins, so **global uniform persistence of all positive initial states may be the wrong notion**.

Search for conditional persistence, persistence above thresholds, basin-restricted persistence, persistence relative to subsets, or permanence on invariant regions.

## Critical conceptual test

Do not assume “uniform persistence” is the right bridge merely because Double Allee concerns persistence/extinction.

A strong Allee effect generally permits positive initial conditions that tend to extinction.

Therefore explicitly determine whether the mathematically relevant object should instead be:

- persistence conditional on a basin/invariant region;
- threshold-separated persistence;
- permanence relative to an interior subset;
- persistence after crossing a critical manifold;
- persistence of selected species/components rather than all positive trajectories.

If standard persistence theory is structurally incompatible with Allee bistability, that is itself an important result for the opportunity map.

## Verdict categories

Return separate verdicts:

1. **Abstract fractional persistence theory:** direct prior / partial / no resolving result found.
2. **History-space subsumption:** direct / partial / unresolved.
3. **Double-Allee relevance:** direct fertile bridge / requires reformulation / structurally mismatched.
4. **Q1 research-opportunity potential:** evidence only; do not select a winner.

## Required output

Create:

`research/coordination/web-to-chief/ROUND-0009_fractional-uniform-persistence-falsification_RETURN.md`

and:

`research/web-search/2026-09-28_fractional-uniform-persistence-falsification.md`

Update corpus/bibliography/search registries as warranted.

## Completion criterion

The Chief must be able to decide whether D11 is:

- a genuine abstract-theory research opportunity;
- already covered by history-space/hereditary persistence theory;
- merely model-specific;
- or conceptually the wrong bridge for Double Allee and therefore in need of reformulation.
