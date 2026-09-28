# ROUND-0011 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — CROSS-FRONTIER / DOUBLE-ALLEE BASIN GEOMETRY  
**Status:** OPEN

## Topic

> **What does fractional memory actually change in Allee threshold and basin geometry?**

This round intersects:

- D10: nonhyperbolic / basin bifurcation;
- D11: basin-/threshold-relative persistence;
- the project's preferred Double/Multiple Allee lens.

It is an adversarial theorem-mapping round.

Do not propose or prove a new model.

## Central question

For systems of the form

[
{}^C D^{alpha_i}x_i=f_i(x;mu),
]

with strong or Double/Multiple Allee structure, determine which of the following are:

1. unchanged from the integer-order vector field (f);
2. altered only through stability-sector conditions;
3. genuinely altered by nonlocal memory in the physical initial-state basin;
4. properly defined only in an enlarged history/memory state.

## Mandatory baseline — integer-order Double Allee basin theory

Inspect and citation-expand:

Contreras et al. 2018, DOI `10.1002/mma.4774`,
**Allee thresholds and basins of attraction in a predation model with double Allee effect**.

Record precisely:
- what counts as an Allee threshold;
- stable-manifold boundaries;
- limit-cycle thresholds;
- homoclinic/heteroclinic boundaries;
- basin rearrangements across local/global bifurcations.

Also inspect related integer-order Allee basin/separatrix papers.

The fractional opportunity must exceed this baseline.

## Search block A — scalar strong-Allee Caputo dynamics

Study the canonical scalar structure:

[
{}^C D^alpha x=f(x),
qquad
f(0)=f(a)=f(K)=0,
]

with strong-Allee sign pattern.

Questions:

### A1
Does a solution with (x_0<a) remain below (a)?

### A2
Does a solution with (x_0>a) remain above (a)?

### A3
Is the unstable equilibrium (a) therefore an order-independent basin boundary for all (0<alphale1) under standard uniqueness/comparison assumptions?

### A4
Can scalar Caputo memory produce a genuine crossing of the ecological Allee threshold even when the autonomous vector field has the standard sign pattern?

Search:
- nonintersection theorems;
- scalar comparison principles;
- positivity/order preservation;
- invariant intervals;
- monotone scalar Caputo equations;
- threshold invariance.

At minimum inspect the comparison-principle literature including:

Cheng & Wu 2026, DOI `10.1016/j.jmaa.2026.130509`.

If scalar threshold geometry is rigid, say so clearly.

## Search block B — multidimensional physical-state basins

For predator–prey / multi-species Caputo systems:

### B1
How is a basin of attraction defined when the physical state (x(t)) alone is not Markov?

### B2
When papers plot a basin over initial points (x(0)), what history convention is implicitly fixed?

### B3
Can the basin boundary on the constant-history/physical-initial-data slice depend on (alpha)?

### B4
Are there rigorous results, or mainly numerical basin plots?

Search:
- basin of attraction fractional differential equations;
- basin stability Caputo;
- separatrix fractional systems;
- stable manifold basin boundary fractional;
- basin dependence on fractional order;
- ecological basin fractional Allee.

## Search block C — history/memory-state basin geometry

Using the Doan–Kloeden Volterra semidynamical representation, search:

- basin of attraction on the Caputo memory state;
- stable sets of memory-state equilibria;
- invariant boundary in function space;
- separatrices in history space;
- basin boundaries for Volterra equations with power-law kernels;
- threshold manifolds in hereditary systems.

Determine whether classical Volterra/hereditary basin theory applies to the singular Caputo kernel.

## Search block D — stable manifolds as thresholds

Since integer-order strong-Allee basin boundaries are often stable manifolds of saddles:

### D1
Do existing fractional stable/center-stable manifold theorems imply an analogous local basin boundary?

### D2
In what state space is that manifold defined?

### D3
Does its intersection with physical initial-data states depend on (alpha)?

### D4
Can it be used as an ecological threshold surface?

Do not assume the answer.

## Search block E — fractional Allee basin prior art

At minimum inspect/citation-expand:

- Ramesh et al., DOI `10.1371/journal.pone.0305179`;
- Mondal et al. 2025, DOI `10.1016/j.cjph.2025.09.020`;
- Pippal & Sati 2026, DOI `10.30538/oms2026.0339`;
- Wang & Han 2025, DOI `10.1007/s12346-024-01212-8`;
- any fractional Allee papers explicitly computing basin stability, separatrices or threshold dependence on fractional order.

Pippal–Sati is particularly important because it uses a **basin-restricted Mittag–Leffler certificate** and explicitly distinguishes Caputo sector transitions from classical Hopf.

Determine whether this is:
- a model-specific Lyapunov region;
- a true basin characterization;
- or only a sufficient invariant subset.

## Search block F — transient threshold crossing

A potentially important memory effect is transient crossing of a biologically defined threshold.

But distinguish:

- crossing an equilibrium threshold (a);
- crossing an externally defined management density;
- overshoot in one component of a multidimensional system;
- crossing a projection of a history-space basin boundary.

Search whether Caputo memory can generate threshold crossing without changing the equilibrium set.

## Search block G — dependence on (alpha)

Separate:

1. equilibrium position;
2. local stability;
3. basin boundary on physical initial data;
4. basin volume;
5. memory-state basin boundary;
6. transient time-to-extinction/recovery.

Which of these are rigorously known to depend on (alpha)?

Which claims are only numerical?

## Search block H — incommensurate Double Allee

For (alpha_i) genuinely different:

- does a physical-state separatrix still make sense;
- is there a general stable-manifold/basin theorem;
- can varying one mechanism/species memory order reorganize survival/extinction basins;
- what prior art exists beyond model-specific numerics?

## Critical falsification tests

### Killer 1 — scalar rigidity
If comparison/nonintersection theory proves that scalar strong-Allee basins are always separated by the same unstable equilibrium independently of (alpha), then scalar basin-shift novelty is closed.

### Killer 2 — history-space subsumption
If standard hereditary/Volterra stable-manifold/basin theory applies directly to canonical Caputo power-law memory, the broad memory-state basin gap collapses.

### Killer 3 — direct fractional Double-Allee prior
If a paper already rigorously characterizes (alpha)-dependent Double-Allee basin boundaries/separatrices in the correct memory-state sense, identify it.

### Killer 4 — purely numerical phenomenon
If apparent basin changes are artifacts of finite-time numerical classification or solver memory initialization, flag them.

## Required verdicts

Return separate verdicts for:

1. scalar strong-Allee threshold rigidity;
2. multidimensional physical-state basin theory;
3. memory-state basin/separatrix theory;
4. (alpha)-dependence of basin boundaries;
5. fractional stable manifolds as ecological thresholds;
6. incommensurate basin theory;
7. Double-Allee-specific prior art;
8. connection to threshold-relative persistence.

Use:
- DIRECT PRIOR;
- SUBSTANTIAL PARTIAL THEORY;
- CLOSE PRIOR ART;
- NO RESOLVING RESULT FOUND;
- AMBIGUOUS / MORE SEARCH REQUIRED.

## Candidate opportunity test

At the end answer:

> Is there a nontrivial, intrinsically fractional basin/threshold problem near Double Allee after scalar rigidity and integer-order basin theory are taken into account?

If yes, formulate it narrowly.

Do not select it as the project winner.

## Required deliverables

Create:

`research/coordination/web-to-chief/ROUND-0011_allee-basin-memory-geometry_RETURN.md`

and:

`research/web-search/2026-09-28_allee-basin-memory-geometry.md`

Update corpus, theorem records, bibliography and provenance registries as warranted.

## Completion criterion

The Chief should be able to decide whether the D10-D/D11 intersection is:

- mathematically trivial in scalar form;
- already covered by existing stable-manifold/history-space theory;
- only numerically explored;
- or a genuinely fertile fractional frontier directly tied to Double/Multiple Allee.
