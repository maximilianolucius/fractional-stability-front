# ROUND-0010 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** `research/coordination/web-to-chief/ROUND-0010_fractional-bifurcation-semantics_RETURN.md`  
**Disposition:** ACCEPT WITH MAJOR NARROWING — D10 SURVIVES AS A FAMILY OF SPECIFIC FRONTIERS

## 1. Executive decision

ROUND-0010 successfully falsifies the broad claim that fractional bifurcation theory is absent or primitive.

Rigorous prior art already includes:

- stable manifolds;
- center-stable manifolds;
- finite-dimensional Caputo center manifolds;
- Caputo Lyapunov–Schmidt reduction;
- Caputo–Hadamard center-manifold / Lyapunov–Schmidt theory;
- fold/transcritical/pitchfork results;
- attractor results for structured Caputo classes;
- exact-periodicity obstruction for finite-lower-terminal autonomous Caputo systems;
- classical center-manifold/Hopf theory for important Volterra convolution equations.

D10 therefore remains in the map only in narrowed forms.

No final research direction is selected.

## 2. Closed or strongly downgraded claims

### 2.1 “Fractional systems lack center manifolds”

False.

Important direct prior includes:

- Ma & Li 2016, DOI `10.1115/1.4031120`;
- Peng, Wang & Yu 2018, DOI `10.15388/NA.2018.5.2`;
- Liao, Wu & Li 2026, DOI `10.1016/j.physd.2026.135122`.

### 2.2 “Fractional systems lack reduction theory”

False.

Caputo Lyapunov–Schmidt reduction exists:

- Li & Ma 2016, DOI `10.1115/1.4033607`.

Operator-adapted Caputo–Hadamard reduction also exists.

### 2.3 “Fold/transcritical/pitchfork existence is fractional novelty”

Generally false when the order occurs only in the left-hand derivative:

[
{}^C D^alpha x=f(x,mu).
]

Equilibria satisfy:

[
f(x,mu)=0.
]

Hence equilibrium branches and their ordinary algebraic fold/cusp location do not move merely because (alpha) changes.

Any future fractional contribution must concern stability, memory-state dynamics, basin/attractor geometry, transient threshold behavior, or operator-correct recurrence.

### 2.4 “Matignon crossing = classical Hopf”

Not acceptable for the standard autonomous finite-lower-terminal Caputo setting.

Tavazoei–Haeri 2009 excludes nonconstant exact periodic solutions under that framework.

Therefore a sector-boundary crossing must not be reported as a classical periodic-orbit Hopf theorem unless the operator/history convention actually permits such recurrent solutions.

## 3. Surviving D10 subfrontiers

### D10-A — Singular Caputo memory-state bifurcation

Search-qualified residual:

> no resolving general center-manifold / normal-form bifurcation theorem was identified for the infinite-dimensional singular Volterra semiflow naturally associated with canonical finite-terminal Caputo equations, with enough structure to classify nonhyperbolic attractor changes.

Strong threat: classical Volterra center-manifold/Hopf theory already exists, but inspected kernel hypotheses do not automatically cover weakly singular algebraically decaying Caputo kernels.

### D10-B — Incommensurate nonhyperbolic reduction

Search-qualified residual:

> no general center-manifold / normal-form / codimension-one-two theorem was identified for genuinely incommensurate multi-order Caputo systems at nonhyperbolic equilibria.

This is attractive because the hyperbolic incommensurate theory is now comparatively strong.

### D10-C — Recurrent bifurcation under an operator that permits recurrence

The finite-terminal autonomous Caputo setting is not the correct place for a classical periodic-orbit Hopf theorem.

Infinite-past / Liouville–Weyl-type formulations can admit periodic solutions, but modern work still reports an incomplete Floquet architecture.

This is mathematically interesting but less specifically connected to Double Allee.

### D10-D — Memory-state basin/threshold bifurcation near strong/Double Allee

This is the closest D10 branch to the project's ecological preference.

The correct distinction is:

[
	ext{equilibrium catastrophe geometry}

eq
	ext{fractional-memory basin / attractor / stability geometry}.
]

No resolving general theorem was found that classifies how memory reorganizes basins, separatrices, attractors or threshold-relative persistence around strong/Double-Allee structures.

## 4. Important adjacent Double-Allee threat found by Chief

The integer-order Double-Allee basin problem is already mathematically deep.

Contreras et al. 2018, DOI `10.1002/mma.4774`, studies **Allee thresholds and basins of attraction in a predation model with double Allee effect** and shows that threshold boundaries can be:
- stable manifolds of equilibria;
- limit cycles;
- homoclinic objects;

with topological changes across bifurcations.

Therefore a future fractional claim cannot present “basin geometry of Double Allee” itself as new.

The fractional question must identify what power-law memory changes relative to this already-rich integer-order geometry.

## 5. Important modern Caputo threat found by Chief

Cheng & Wu 2026, DOI `10.1016/j.jmaa.2026.130509`, gives complete system comparison principles for Caputo fractional-order ODEs under the source framework.

This is especially relevant for threshold invariance and scalar/monotone Allee systems.

A scalar strong-Allee threshold may remain exactly the unstable equilibrium barrier under comparison/order arguments, making some proposed “memory-driven threshold movement” claims false or trivial.

This must be tested before D10-D is treated as fertile.

## 6. D10 versus D11 after this round

### D10
Strength:
- stronger intrinsic FDE content;
- sharper mathematical tension between algebraic equilibrium geometry and memory-state dynamics;
- strong Double-Allee proximity through basin/separatrix changes.

Risk:
- significant manifold/reduction prior art already exists;
- scalar threshold geometry may be largely unchanged.

### D11
Strength:
- directly tied to persistence/extinction;
- natural Allee interpretation after basin-relative reformulation.

Risk:
- may reduce to existing infinite-dimensional persistence theory once the correct history space is chosen.

The most useful next step is therefore not to rank D10 versus D11 abstractly.

It is to audit their **intersection**.

## 7. Next frontier question

The key cross-cutting question is:

> **For strong/Double-Allee systems, what aspects of the extinction-survival basin boundary are invariant under Caputo fractionalization, and what aspects genuinely become memory-state objects?**

This question can potentially:
- kill trivial scalar routes;
- identify the first genuinely fractional basin phenomenon;
- connect D10 bifurcation to D11 threshold-relative persistence;
- stay directly centered on Double Allee.

## 8. Next action

Open:

`ROUND-0011_allee-basin-memory-geometry_REQUEST.md`

No proof program follows from this decision.
