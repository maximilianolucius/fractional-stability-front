# ROUND-0011 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** `research/coordination/web-to-chief/ROUND-0011_allee-basin-memory-geometry_RETURN.md`  
**Disposition:** ACCEPT WITH SHARP SPLIT — SCALAR ROUTE CLOSED; MULTIDIMENSIONAL MEMORY-STATE FRONTIER SURVIVES

## 1. Executive decision

ROUND-0011 produces the sharpest Double-Allee result obtained so far.

The candidate separates cleanly into:

### CLOSED
Scalar autonomous Caputo strong-Allee threshold movement.

### SURVIVES
Multidimensional survival/extinction basin geometry in the Caputo memory state, its physical-initial-data slice, and its relation to basin-relative persistence.

No final research direction is selected.

## 2. Scalar route is closed

For a scalar autonomous Caputo IVP with (0<alpha<1), separation/nonintersection theory implies that distinct solution trajectories do not intersect under the standard hypotheses.

If (x=a) is the unstable strong-Allee equilibrium, then the constant solution (x(t)equiv a) is an uncrossable barrier:

[
x_0<a Rightarrow x(t)<a,
qquad
x_0>a Rightarrow x(t)>a.
]

Therefore:

> **Fractional order does not move the scalar equilibrium Allee basin separator when the RHS is unchanged.**

Memory may alter transients and rates but not this threshold.

Any candidate claiming an (alpha)-dependent scalar Allee equilibrium threshold is rejected.

## 3. Integer-order Double-Allee basin geometry is already rich

Contreras Julio & Aguirre (2018), DOI `10.1002/mma.4774`, establishes that in an integer-order Double-Allee predator-prey model, extinction/survival thresholds can be represented by:
- stable manifolds;
- limit cycles;
- homoclinic structures;

with basin topology reorganized by local/global bifurcations.

Hence “Double Allee has complicated basins” is not a fractional novelty.

## 4. What survives in dimension greater than one

For multidimensional Caputo systems:

- current physical state alone is generally not the full dynamical state;
- the natural semidynamical representation is infinite-dimensional;
- physical IVPs embed into this memory-state space;
- published basin plots typically sample the physical-initial-data slice only;
- direct Double-Allee and Allee prior art already reports (alpha)-dependent basin plots numerically;
- no searched source gives a rigorous full-memory survival/extinction separatrix theorem for the canonical singular Caputo kernel.

The surviving frontier is therefore:

> **characterize the survival/extinction basin boundary in the Caputo memory-state semiflow and its intersection with physically initialized states.**

## 5. What ROUND-0011 adds to D11 persistence

This result clarifies the correct persistence object.

Strong Allee dynamics cannot be globally uniformly persistent because part of the positive state space belongs to the extinction basin.

The relevant object is:

> **persistence relative to the survival basin.**

For fractional systems, that survival basin should first be defined in the memory-state semiflow and then related to the physical initial-data embedding.

This is the mathematically coherent D10-D/D11 intersection.

## 6. Strongest intrinsically fractional question

The most important surviving question is not whether a finite-dimensional basin plot changes with (alpha).

It is:

> **Can two dynamically admissible Caputo memory states with the same current physical population vector belong to opposite survival/extinction basins?**

If yes, then the ecological threshold is not a function only of current population state; it is genuinely history-dependent.

That phenomenon has no direct finite-dimensional autonomous ODE analogue.

However, this formulation requires another audit before it can be considered a strong candidate.

## 7. New killer issue: reachability and physical meaning

The Doan–Kloeden memory-state space is larger than the set of constant functions used to initialize standard Caputo IVPs.

Therefore the phrase “two memory states with the same present state” is not enough.

We must distinguish:

1. arbitrary states in the ambient memory-state function space;
2. states reachable from standard physical Caputo initial data under the semiflow;
3. states corresponding to admissible prehistories/infinite-past formulations;
4. merely mathematical forcing states with no intended ecological interpretation.

A future research opportunity is strongest only if the history-dependent basin phenomenon occurs inside a **reachable/physically meaningful subset**.

## 8. Independent Chief search

A targeted search for modern weakly singular / power-law Volterra literature did not identify a direct global invariant-manifold/basin theorem that obviously subsumes the ROUND-0011 problem.

The recent sources found were primarily concerned with:
- regularity;
- numerical approximation;
- convergence;
- weakly singular Gronwall inequalities;
- computational treatment of power-law kernels.

This does not prove absence, but it supports one final specialist subsumption/reachability audit.

## 9. D10-D / D11 status

**RETAIN — HIGH INFORMATION, HIGH SUBSUMPTION RISK.**

Narrow formulation:

> **Reachable memory-state survival/extinction geometry for multidimensional strong/Double-Allee Caputo systems, including the relation between full-memory basin boundaries, the physical IVP slice, fractional order, and basin-relative persistence.**

## 10. Next action

Open:

`ROUND-0012_reachable-memory-state-subsumpion_REQUEST.md`

This round must try to kill the candidate through:
- hereditary/Volterra invariant-manifold theory;
- reachability of the Caputo semigroup lift;
- equivalence/non-equivalence of same-present different-memory states;
- physical relevance of the full memory-state basin.

No theorem proving follows from this decision.
