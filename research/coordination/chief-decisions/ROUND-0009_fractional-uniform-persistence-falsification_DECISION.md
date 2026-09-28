# ROUND-0009 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** `research/coordination/web-to-chief/ROUND-0009_fractional-uniform-persistence-falsification_RETURN.md`  
**Disposition:** ACCEPT WITH STRONG NARROWING — RETAIN D11 AS HIGH-RISK CANDIDATE OPPORTUNITY

## 1. Executive decision

ROUND-0009 does not establish a new fractional persistence theorem gap in broad form.

It does establish a more precise frontier hypothesis:

> **Can abstract persistence theory be transferred to positive Caputo systems through the Volterra/history-state semiflow in a way that yields an ecologically meaningful persistence function, invariant extinction boundary, physical-state lower bounds, perturbation robustness, and basin-/threshold-relative persistence for strong-Allee dynamics?**

This remains unresolved in the searched corpus.

No research direction is selected.

## 2. What is now closed as a broad gap

### 2.1 “Caputo systems have no dynamical-system/semiflow framework”

False in broad form.

Doan & Kloeden (2021), DOI `10.1007/s10013-020-00464-6`, represent autonomous Caputo FDEs as singular Volterra equations generating an infinite-dimensional semidynamical system on a function space under their hypotheses.

Modern work also develops attractor/dissipativity machinery on this memory-state representation.

Therefore lack of a semiflow is **not** the opportunity.

### 2.2 “Persistence theory is only finite-dimensional”

False.

Hale–Waltman and later persistence theory already operate on infinite-dimensional/asymptotically smooth semigroups, processes, functional differential equations and related settings.

Therefore infinite dimensionality alone creates no novelty.

### 2.3 “Any fractional persistence theorem would be new”

False.

Model-specific fractional permanence/uniform-persistence results already exist.

The relevant issue is abstraction, state-space transfer and threshold-relative structure.

## 3. What survives

The following issues remain search-qualified unresolved:

1. construction of the ecologically correct positive invariant subset in Caputo memory state;
2. characterization of the invariant extinction boundary in that state space;
3. a persistence function whose memory-space conclusion transfers rigorously to physical population components;
4. robust persistence under perturbations of vector field, order and/or kernel;
5. general invasion-rate / boundary-measure criteria for fractional memory dynamics;
6. basin-/threshold-relative persistence appropriate to strong Allee systems.

The last item is especially important.

## 4. Double Allee correction

Ordinary global uniform persistence is structurally incompatible with a strong Allee effect whenever strictly positive initial states below threshold converge to extinction.

Conditional persistence is already established terminology in Allee-effect literature; Roth & Schreiber (2014), DOI `10.1080/17513758.2014.962631`, is an important adjacent source.

Therefore the relevant future object is not simply:

[
inf_{x_0>0}liminf_{t	oinfty}x(t)>0.
]

The more natural search target is one of:

- basin-relative persistence;
- threshold-relative persistence;
- persistence on a positively invariant survival region;
- persistence relative to a memory-state interior/boundary pair induced by an Allee separatrix/threshold.

This is a conceptual improvement over the initial D11 candidate.

## 5. Main killer risk

The candidate could still collapse.

If one can choose a positive invariant history space and persistence function so that:

1. Hale–Waltman / Smith–Thieme hypotheses hold directly;
2. evaluation at the physical present state is continuous and gives the desired lower bound;
3. the Allee survival region corresponds to an invariant subset;

then most of the theorem may be an application of mature persistence theory rather than a new general framework.

Hence D11 is:

**CREDIBLE / HIGH INFORMATION / HIGH SUBSUMPTION RISK.**

It remains in the opportunity portfolio, but is not promoted.

## 6. Independent Chief verification

The Chief independently verified:

- Hale–Waltman (1989) formulates persistence for asymptotically smooth (C^0)-semigroups in infinite-dimensional spaces, with boundary-flow and global-attractor conditions;
- Doan–Kloeden (2021) gives a function-space semidynamical representation for autonomous Caputo FDEs under global-Lipschitz hypotheses;
- Roth–Schreiber (2014) explicitly distinguishes persistence, extinction and conditional persistence in Allee-effect models.

These checks support, rather than weaken, the Searcher's narrowed conclusion.

## 7. D11 portfolio formulation after this round

Replace the broad candidate

> abstract fractional persistence/permanence

with:

> **Memory-state and basin-relative persistence theory for positive Caputo systems, with physical-state transfer and strong-Allee threshold structure.**

This wording is more accurate and substantially harder to preempt by terminology alone.

## 8. Why the next round is D10

D10 now has comparable Double-Allee proximity and stronger intrinsic bifurcation relevance.

However, independent verification found important prior art that must be included before calling it a gap:

- Tavazoei–Haeri 2009: exact-periodicity obstruction for time-invariant Caputo systems;
- Peng–Wang–Yu 2018: center-stable manifolds for Caputo-type FDEs;
- Doan–Kloeden 2022: attractors plus scalar saddle-node/pitchfork;
- Ma–Shu 2025: Caputo–Hadamard center-manifold reduction;
- Liao–Wu–Li 2026, DOI `10.1016/j.physd.2026.135122`: center-manifold existence for fractional differential equations;
- earlier Lyapunov–Schmidt work cited by the 2026 paper.

Thus ROUND-0010 must not ask “does fractional bifurcation theory exist?”

It must reconstruct exactly what exists and identify the residual frontier.

## 9. Next action

Open:

`ROUND-0010_fractional-bifurcation-semantics_REQUEST.md`

Priority questions:
- center-manifold and normal-form coverage;
- rigorous saddle-node/transcritical/pitchfork/cusp results;
- meaning and validity of “Hopf” in finite-lower-terminal Caputo systems;
- function-space/history-state bifurcation;
- incommensurate and multidimensional nonhyperbolic systems;
- which residual problem is naturally exposed by Double Allee dynamics.

