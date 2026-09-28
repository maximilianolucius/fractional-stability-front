# ROUND-0010 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — DEPTH-FIRST / FRACTIONAL BIFURCATION ARCHITECTURE  
**Status:** OPEN

## Topic

> **Rigorous bifurcation and nonhyperbolic dynamics for fractional differential equations**

This is a theorem-map round, not a search for examples of papers using the word “bifurcation”.

## Project context

The project maps:

> **Dynamical Systems and Stability Theory — Fractional Differential Equations**

and seeks fertile research gaps preferably directly involving Double/Multiple Allee or otherwise very close to it.

This round does not select or solve a research problem.

## Why this round is necessary

ROUND-0008 identified D10 as a potentially fertile frontier, but independent Chief verification shows the branch already contains significant rigorous mathematics:

- Tavazoei & Haeri 2009, DOI `10.1016/j.automatica.2009.04.001`;
- Peng, Wang & Yu 2018, DOI `10.15388/NA.2018.5.2`;
- Doan & Kloeden 2022, DOI `10.1007/s13540-022-00030-6`;
- Ma & Shu 2025, DOI `10.1115/1.4068728`;
- Liao, Wu & Li 2026, DOI `10.1016/j.physd.2026.135122`;
- Lyapunov–Schmidt reduction work cited by these sources.

Therefore do **not** test the naive claim “fractional bifurcation theory is missing”.

Instead reconstruct the exact theorem architecture.

## Central objective

Determine what rigorous bifurcation theory currently exists for continuous-time fractional differential systems and what, if anything, remains missing at a level naturally relevant to Double Allee thresholds.

## Mandatory distinctions

Do not merge the following:

1. equilibrium branch bifurcation;
2. stability loss of an equilibrium;
3. attractor bifurcation;
4. periodic-orbit bifurcation;
5. appearance of long-lived numerical oscillations;
6. asymptotically periodic behavior;
7. exact periodic solution;
8. periodic orbit in an enlarged memory/history state;
9. chaos/numerical complexity.

Likewise distinguish:
- Caputo finite lower terminal;
- Caputo with effectively infinite-past/steady-state formulation;
- Riemann–Liouville;
- Caputo–Hadamard;
- commensurate;
- incommensurate;
- delay fractional systems;
- discrete fractional systems.

Discrete fractional maps are adjacent evidence, not substitutes for continuous-time Caputo theory.

## Search block A — invariant and center manifolds

Map theorem-level results on:

- stable manifolds;
- center-stable manifolds;
- center manifolds;
- invariant manifolds;
- reduction principles.

At minimum inspect and citation-expand:

- Peng–Wang–Yu 2018;
- Liao–Wu–Li 2026;
- Ma–Shu 2025;
- the semilinear center-manifold paper cited by Liao–Wu–Li;
- Cong/Tuan-related invariant-manifold literature.

For each result record:
- operator;
- order range;
- dimension;
- state space;
- spectral assumptions;
- whether manifold is truly invariant in what dynamical sense;
- whether reduced dynamics is derived;
- whether a usable normal form follows.

## Search block B — Lyapunov–Schmidt / normal forms

Search explicitly:

- “fractional Lyapunov-Schmidt reduction”;
- “fractional normal form”;
- “Caputo normal form”;
- “fractional center manifold reduction”;
- “Crandall Rabinowitz fractional”;
- “codimension one bifurcation fractional differential equations”;
- “codimension two fractional differential equations”.

Determine whether classical bifurcation equations can be rigorously derived despite the lack of an ordinary chain rule.

## Search block C — equilibrium bifurcations

Map rigorous results for:

- saddle-node / fold;
- transcritical;
- pitchfork;
- cusp;
- Bogdanov–Takens-type equilibrium degeneracies;
- hysteresis/multistability.

Key question:

> Since equilibria are still roots of (f(x,mu)=0), which bifurcation statements are merely algebraic/ODE-identical, and which genuinely depend on fractional memory?

This is critical for Double Allee: a simple fold in the equilibrium equation may contain almost no new fractional mathematics.

## Search block D — Hopf terminology audit

The 2009 periodicity obstruction must be treated as foundational.

Determine how later rigorous sources define “fractional Hopf bifurcation”.

Classify claims into:

- only Matignon-sector stability crossing;
- numerical sustained oscillation;
- asymptotically periodic solution;
- exact periodic orbit;
- memory-state periodic orbit;
- delay-induced periodic behavior;
- infinite-past/Weyl-type formulation.

Search for:
- theorem definitions;
- corrections/criticisms;
- papers explicitly denying Hopf in finite-terminal Caputo;
- papers defending a modified Hopf notion;
- exact existence/nonexistence results.

Do not report “Hopf exists” merely because a paper uses the phrase.

## Search block E — history-state / Volterra bifurcation

Because Caputo FDEs admit an infinite-dimensional Volterra semidynamical representation under suitable assumptions, search:

- bifurcation of the Volterra semiflow;
- center manifolds on the memory state;
- periodic orbits in the history-state dynamics;
- attractor bifurcation;
- invariant-set bifurcation;
- relation between history-state recurrent objects and physical Caputo trajectories.

This is a potential killer or deepening route.

## Search block F — incommensurate systems

Search whether rigorous:
- center manifolds;
- normal forms;
- nonhyperbolic bifurcation;
- fold/cusp;
- attractor bifurcation

exist for genuinely incommensurate multi-order systems.

Diethelm et al. 2024 closes much of hyperbolic/local stability; this round asks what happens at the nonhyperbolic boundary.

## Search block G — Double/Multiple Allee relevance

Double Allee should not be forced into a generic Hopf question.

Investigate which bifurcation structures are actually intrinsic to strong/multiple Allee systems:

- fold creation/destruction of threshold equilibria;
- cusp organization of threshold multiplicity;
- hysteresis;
- basin-boundary/separatrix changes;
- codimension-two interaction with predator/prey or dispersal modes;
- threshold collisions under memory/order variation.

Ask explicitly:

### G1
Does fractional order change the **existence/location** of equilibria when only the derivative order changes?

If not, do not call the equilibrium fold itself a fractional novelty.

### G2
Can memory change stability, basin geometry, attractor structure, transient threshold crossing or extinction/persistence despite unchanged equilibrium branches?

### G3
Is there a rigorous theorem connecting such changes to Double Allee threshold dynamics?

### G4
Are cusp/basin/hysteresis questions under fractional memory less covered than the heavily studied “Hopf” literature?

## Strongest killer definition

D10 should be downgraded if a general theorem family already provides, for broad Caputo/incommensurate systems:

- center-manifold reduction;
- reduced normal forms;
- standard codimension-one/two local bifurcation classification;
- correct recurrent-object interpretation in memory state.

If only special operators/classes are covered, identify the precise restrictions.

## Output verdicts

Return separate verdicts for:

1. center/invariant manifold theory;
2. normal-form / Lyapunov–Schmidt theory;
3. equilibrium fold/transcritical/pitchfork/cusp theory;
4. Hopf/periodicity semantics;
5. history-state bifurcation;
6. incommensurate nonhyperbolic bifurcation;
7. Double-Allee-specific frontier.

For each:
- DIRECT PRIOR;
- SUBSTANTIAL PARTIAL THEORY;
- CLOSE PRIOR ART;
- NO RESOLVING RESULT FOUND;
- AMBIGUOUS / MORE SEARCH REQUIRED.

## Candidate-gap discipline

If a residual gap survives, formulate it narrowly.

Examples of acceptable forms:

> “No resolving theorem was identified for X under assumptions Y and Z.”

Not:

> “Fractional bifurcation theory is undeveloped.”

## Required deliverables

Create:

`research/coordination/web-to-chief/ROUND-0010_fractional-bifurcation-semantics_RETURN.md`

and:

`research/web-search/2026-09-28_fractional-bifurcation-semantics.md`

Update corpus, bibliography and provenance registries as warranted.

## Completion criterion

The Chief should be able to decide:

1. whether D10 remains a serious research-opportunity family;
2. exactly which parts are already mature;
3. whether a residual gap is intrinsically fractional rather than an algebraic ODE bifurcation;
4. whether that residual gap is naturally and deeply connected to Double Allee.

