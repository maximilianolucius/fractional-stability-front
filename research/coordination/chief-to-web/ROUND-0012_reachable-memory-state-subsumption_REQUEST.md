# ROUND-0012 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — FINAL KILLER AUDIT OF BASIN-MEMORY CANDIDATE  
**Status:** OPEN

## Topic

> **Reachable memory states, hereditary subsumption, and survival/extinction basins in Caputo systems**

This round follows ROUND-0011.

## Candidate under attack

Search-qualified candidate:

> For multidimensional strong/Double-Allee Caputo systems, survival/extinction may be a genuinely memory-state property: the basin boundary in the singular Volterra semidynamical system may not reduce to a boundary in current physical state, and its physically reachable slice may depend on fractional order.

The strongest possible manifestation is:

> two **reachable/admissible** memory states with the same current physical population vector belong to opposite survival/extinction basins.

Your task is to try to destroy this candidate.

## Critical distinction

Do not confuse:

1. the ambient function space used to obtain a semigroup;
2. the subset reached from standard Caputo IVPs (x(0)=x_0);
3. the orbit closure of that subset;
4. admissible history functions in a hereditary/infinite-past formulation;
5. arbitrary forcing functions admitted only for mathematical closure of the semigroup.

A phenomenon occurring only in arbitrary ambient states may have weak ecological significance.

## Search block A — Doan–Kloeden state-space interpretation

Read the Doan–Kloeden semidynamical-system construction at theorem/proof level.

Determine:

- exact state variable in the lifted function space;
- embedding (iota(x_0));
- formula for (T_tiota(x_0));
- whether evolved states are nonconstant;
- what evaluation at zero represents;
- whether the image of the physical embedding is invariant;
- define the reachable set

[
mathcal R_alpha
=
{T_tiota(x_0):tge0, x_0in X_{m phys}}.
]

Determine what is known about (mathcal R_alpha):
- invariance;
- closure;
- regularity;
- dimension;
- relation to attractors.

## Search block B — same-present / different-memory states

Search for rigorous results or examples in:

- Caputo FDEs;
- Volterra equations;
- hereditary systems;
- delay equations;
- viscoelastic memory systems;

where two admissible histories/states have the same current value but different future trajectories.

This is standard in delay systems, but the question is whether the **Caputo reachable set** admits the analogous phenomenon.

Questions:

### B1
Can two distinct states (phi,psiinmathcal R_alpha) satisfy

[
phi(0)=psi(0)
]

while (phi
epsi)?

### B2
If yes, can their future physical trajectories differ?

### B3
Can they lie in different attractor basins?

### B4
Is there a theorem preventing this for special monotone/competitive/cooperative Caputo classes?

## Search block C — hereditary/Volterra basin subsumption

Search classical and modern theory for:

- global stable sets;
- basin boundaries;
- invariant manifolds;
- persistence;
- bistability;
- separatrices;

for Volterra integral equations with:
- weakly singular kernels;
- completely monotone kernels;
- algebraic tails;
- fractional resolvent kernels;
- power-law kernels.

The key question is not whether general Volterra theory exists.

It is:

> does an existing theorem apply essentially directly to the canonical Caputo kernel and yield the survival/extinction basin structure required here?

If yes, identify exact theorem/hypotheses and what remains only ecological interpretation.

## Search block D — Markovian embeddings / diffusive representations

Caputo/fractional memory can sometimes be represented by:
- diffusive representations;
- continuum-of-modes Markovian lifts;
- Prony/exponential approximations;
- infinite-dimensional semigroups.

Search whether these representations already provide:
- positive cones;
- invariant manifolds;
- basin theory;
- threshold surfaces;
- persistence theory.

Determine whether the singular Volterra formulation is equivalent to a more standard infinite-dimensional dynamical system where existing basin theory applies.

## Search block E — physical IVP slice versus reachable orbit set

ROUND-0011 focused on the constant-initial-data slice

[
iota(X_{m phys}).
]

But after positive time the system moves into nonconstant memory states.

Determine whether the ecologically meaningful state space should be:
- only (iota(X_{m phys}));
- the reachable set (mathcal R_alpha);
- its closure;
- a larger history space.

This matters because a basin boundary in an ambient space may be irrelevant if trajectories never reach most of it.

## Search block F — basin dependence on memory within reachable states

Search for any result showing that long-term outcome cannot be determined from current physical state alone.

For bistable Caputo systems, look for:
- same (x(t_0)), different prior history, different future;
- memory-induced basin ambiguity;
- history-dependent tipping;
- memory-dependent resilience;
- fractional hysteresis;
- non-Markovian tipping.

Separate:
- external forcing/history before (t=0);
- ordinary finite-terminal Caputo IVPs initialized at (t=0);
- states reached after evolving such IVPs.

## Search block G — Double/Multiple Allee relevance

Ask whether a realistic Double-Allee system can realize this memory dependence.

Potential mechanisms:
- prey and predator histories producing identical current densities but different accumulated memory;
- species-specific incommensurate orders;
- different recovery trajectories after disturbance;
- history-dependent extinction risk at the same observed abundance.

Search ecology/conservation literature for:
- historical contingency;
- ecological memory;
- same abundance different extinction/recovery risk;
- Allee effect + history dependence;
- hysteresis + memory.

Do not let biological narrative substitute for theorem evidence.

## Search block H — monotone/competitive systems as possible killer

Many ecological systems have order/competitive structure.

Search whether monotone fractional systems admit:
- order-preserving reachable states;
- graph/order properties that force outcome to depend only on current state;
- scalarization/comparison strong enough to kill same-present different-basin behavior.

If a natural Double-Allee model class is monotone enough that memory-state basin complexity disappears, report that.

## Search block I — explicit counterexample hunt

Try to locate a low-dimensional Caputo or Volterra bistable example where:

1. two reachable histories have the same present state;
2. future solutions separate;
3. they converge to different attractors.

If none is published, determine whether analogous hereditary/delay examples suggest plausibility.

Do not construct a new proof; only locate prior evidence.

## Verdicts required

Return separate verdicts for:

1. physical embedding invariance;
2. reachable-state structure;
3. same-present different-memory possibility;
4. same-present opposite-basin prior art;
5. hereditary/Volterra theorem subsumption;
6. Markovian/diffusive-lift subsumption;
7. monotone-system killer;
8. Double-Allee physical relevance.

Use:
- DIRECT PRIOR;
- SUBSTANTIAL PARTIAL THEORY;
- CLOSE PRIOR ART;
- NO RESOLVING RESULT FOUND;
- AMBIGUOUS / MORE SEARCH REQUIRED.

## Candidate survival criterion

The candidate survives only if all of the following remain plausible:

1. the relevant memory states are reachable/admissible;
2. current physical state does not determine future basin membership;
3. existing Volterra/hereditary theory does not already provide the needed result almost verbatim;
4. the phenomenon is natural for multidimensional strong/Double-Allee systems;
5. the gap is theorem-level, not only numerical.

## Required deliverables

Create:

`research/coordination/web-to-chief/ROUND-0012_reachable-memory-state-subsumption_RETURN.md`

and:

`research/web-search/2026-09-28_reachable-memory-state-subsumption.md`

Update corpus/theorem/bibliography/search registries as warranted.

## Completion criterion

The Chief should be able to classify the basin-memory candidate as:

- **KILLED — ambient-space artifact**;
- **KILLED — classical hereditary theorem already applies**;
- **SURVIVES ONLY AS APPLICATION/translation**;
- **SURVIVES AS A GENUINE FRACTIONAL DYNAMICAL GAP**;
- or **AMBIGUOUS**.

No final project winner should be selected by the Web Searcher.
