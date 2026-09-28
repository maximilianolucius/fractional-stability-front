# ROUND-0010 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** `research/coordination/chief-to-web/ROUND-0010_fractional-bifurcation-semantics_REQUEST.md`  
**Status:** COMPLETE

## Executive finding

D10 remains a serious research-opportunity family, but the naive gap is false.

Rigorous fractional bifurcation infrastructure already includes:
- stable and center-stable manifolds;
- a finite-dimensional Caputo center-manifold theorem;
- Caputo Lyapunov–Schmidt reduction;
- Caputo–Hadamard center-manifold and Lyapunov–Schmidt reduction;
- model-/class-specific fold/transcritical/pitchfork theory;
- structured Caputo attractor bifurcation;
- a definitive finite-terminal Caputo periodicity obstruction.

The remaining frontier is not “does bifurcation theory exist?” It is the **architecture and semantics of nonhyperbolic dynamics under fractional memory**.

The strongest residuals are:
1. bifurcation/reduction on the singular power-law Caputo Volterra memory-state semiflow;
2. general nonhyperbolic reduction for genuinely incommensurate systems;
3. periodic/Floquet bifurcation under an infinite-past/operator convention that actually admits periodic solutions;
4. Double-Allee basin/attractor/threshold bifurcation after separating equilibrium algebra from memory effects.

---

# Verdict 1 — Center/invariant manifold theory

**SUBSTANTIAL PARTIAL THEORY.**

Direct prior results include:

- Ma & Li 2016, DOI **10.1115/1.4031120** — local center manifold for finite-dimensional Caputo fractional dynamical systems.
- Cong, Doan, Siegmund & Tuan 2016, DOI **10.1007/s11071-016-3002-z** — stable manifolds near hyperbolic equilibria in arbitrary finite dimension; erratum DOI 10.1007/s11071-016-3039-z should accompany theorem use.
- Wang, Fečkan & Zhou 2017, DOI **10.1016/j.amc.2016.10.014** — center-stable manifold for planar fractional damped equations.
- Peng, Wang & Yu 2018, DOI **10.15388/NA.2018.5.2** — center-stable manifolds for Caputo-type equations, with planar and higher-dimensional coverage.
- Liao, Wu & Li 2026, DOI **10.1016/j.physd.2026.135122** — center-manifold existence via function spaces/fixed-point maps; highlights failure of naive ODE chain-rule calculations.
- Ma & Shu 2025, DOI **10.1115/1.4068728** — center-manifold reduction for Caputo–Hadamard systems.

### What is not closed

No unified theorem was identified covering canonical Caputo memory-state reduction, operator generality and genuine incommensurability.

---

# Verdict 2 — Normal form / Lyapunov–Schmidt

**SUBSTANTIAL PARTIAL THEORY.**

Direct prior:

- Li & Ma 2016, DOI **10.1115/1.4033607**, extends Lyapunov–Schmidt reduction to Caputo fractional differential systems.
- Ma & Shu 2025, DOI **10.1007/s11071-025-11651-w**, establishes Caputo–Hadamard Lyapunov–Schmidt reduction and reduced-equation analysis.
- Qian & Chen 2013, DOI **10.6052/1672-6553-2013-053**, analyzes fundamental one-parameter Caputo fold/transcritical/pitchfork bifurcations.
- Ma & Huang 2024, DOI **10.1016/j.cjph.2024.01.028**, develops Caputo–Hadamard fold normal-form/stability analysis.

No broad theorem family was found that gives operator-correct codimension-one/two normal forms for canonical Caputo memory-state systems and genuinely incommensurate systems.

---

# Verdict 3 — Equilibrium fold/transcritical/pitchfork/cusp

### Fold/transcritical/pitchfork

**DIRECT PRIOR RESULT FOUND.**

More importantly, when fractional order modifies only the derivative operator,

[
{}^C D^alpha x=f(x,mu),
]

the equilibrium branches are still determined by

[
f(x,mu)=0.
]

Thus ordinary equilibrium fold/transcritical/pitchfork/cusp **existence and location are algebraic properties of the RHS** and are not intrinsically fractional.

Doan & Kloeden 2022, DOI **10.1007/s13540-022-00030-6**, adds rigorous attractor/saddle-node/pitchfork results for a structured Caputo class.

### Cusp / codimension two

**CLOSE PRIOR ART / NO GENERAL RESOLVING MEMORY-STATE RESULT FOUND.**

Applied fractional papers use cusp/Bogdanov–Takens terminology, but the generic equilibrium root geometry by itself is not a fractional novelty.

A genuine fractional codimension-two theorem must add stability-sector, memory-state, attractor/basin or recurrent-object information.

---

# Verdict 4 — Hopf / periodicity semantics

**DIRECT PRIOR RESULT FOUND for the key impossibility theorem; global terminology remains OPERATOR-DEPENDENT.**

Tavazoei & Haeri 2009, DOI **10.1016/j.automatica.2009.04.001**, analytically excludes nonconstant exact periodic solutions/limit cycles in the autonomous finite-terminal Caputo setting considered there, including commensurate and incommensurate systems.

Therefore, in that setting:

> a Matignon-sector crossing is not automatically a classical Hopf bifurcation.

Yazdani & Salarieh 2011, DOI **10.1016/j.automatica.2011.04.013**, distinguishes finite-time nonperiodicity from periodic steady-state/infinite-memory interpretations.

Haacker et al. 2026, DOI **10.1007/s11071-025-12196-8**, explicitly adopts a Liouville–Weyl-type framework to admit exact periodic solutions and states that a rigorous fractional Floquet theory is still lacking; their Hill-type method cannot recover algebraically decaying stable modes.

### Required reporting rule

Every future “fractional Hopf” claim should state whether it proves:
- sector stability crossing;
- exact periodic orbit;
- asymptotically periodic solution;
- history-state periodic orbit;
- delay-induced periodic orbit;
- or only numerical oscillation.

---

# Verdict 5 — History-state / Volterra bifurcation

**CLOSE PRIOR ART — NO RESOLVING CAPUTO-SINGULAR-KERNEL THEOREM FOUND.**

Classical memory-system theory is already strong:

Diekmann & van Gils 1984, DOI **10.1016/0022-0396(84)90156-6**, develops a local semiflow, center manifolds and Hopf bifurcation for Volterra convolution equations, with population-biology applications.

Fiedler 1986, DOI **10.1137/0517065**, gives global Hopf bifurcation for convolution Volterra equations.

But the inspected classical hypotheses use kernel classes such as finite-support (L^2) kernels or kernels integrable with an exponential weight. These do not automatically include the canonical weakly singular, algebraically decaying Caputo power-law memory kernel.

Modern Caputo work provides the singular-Volterra infinite-dimensional semiflow and attractor machinery, but no general center-manifold/normal-form bifurcation theorem for that exact memory-state setting was identified.

### Residual candidate

> center-manifold/reduction and nonhyperbolic bifurcation theory for the singular Caputo Volterra semiflow.

This is a genuine D10 subfrontier subject to further specialist search.

---

# Verdict 6 — Incommensurate nonhyperbolic bifurcation

**NO RESOLVING GENERAL RESULT FOUND IN SEARCHED CORPUS.**

Hyperbolic/local incommensurate stability is now relatively strong.

Model-specific incommensurate bifurcation studies exist, including Liu–Li–Huang 2025, DOI **10.1016/j.matcom.2025.04.015**, but no broad theorem was identified providing:
- center manifold;
- normal form;
- codimension-one/two reduction

for genuinely multi-order nonhyperbolic Caputo systems.

The Tavazoei–Haeri periodicity obstruction also applies to incommensurate autonomous finite-terminal Caputo systems, so model-specific “Hopf” terminology requires the same semantic audit.

---

# Verdict 7 — Double/Multiple Allee frontier

**CLOSE PRIOR ART for generic model-specific fractional bifurcation.**

Existing fractional Double-Allee papers already study local Matignon stability, saddle-node/Hopf labels, multistability and basin numerics. Mondal et al. 2025, DOI **10.1016/j.cjph.2025.09.020**, even treats incommensurate order.

The stronger residual is:

**NO RESOLVING GENERAL RESULT FOUND** for a theory that distinguishes

[
	ext{unchanged equilibrium catastrophe geometry}
]

from

[
	ext{fractional-memory stability / basin / attractor / transient-threshold changes}.
]

A particularly relevant future gap is:

> **nonhyperbolic and basin bifurcation near strong/Double-Allee thresholds in the Caputo memory-state semiflow**, especially in genuinely incommensurate multi-species systems.

This is intrinsically fractional in a way that recomputing a fold of (f=0) is not.

---

# Strongest semantic conclusion

For finite-terminal autonomous Caputo dynamics, do not identify a Matignon-sector stability loss with a classical Hopf periodic-orbit bifurcation.

For an equilibrium threshold/fold, do not claim fractional novelty if the derivative order changes but the RHS equilibrium equation does not.

The mathematically meaningful fractional frontier begins where memory affects:
- stability;
- invariant-memory-state geometry;
- basins/separatrices;
- attractor changes;
- transient threshold crossings;
- or recurrent dynamics under an operator that actually permits recurrence.

---

# D10 disposition

**RETAIN AS A HIGH-VALUE OPPORTUNITY FAMILY, STRONGLY NARROWED.**

Best residual subfamilies:

1. **D10-A:** singular-memory Caputo history-state center-manifold/normal-form bifurcation;
2. **D10-B:** incommensurate nonhyperbolic center-manifold/normal-form theory;
3. **D10-C:** rigorous periodic/Floquet bifurcation for infinite-past/Liouville–Weyl-type fractional systems;
4. **D10-D:** memory-state basin/attractor bifurcation near strong/Double-Allee thresholds.

### Double-Allee proximity

- D10-D: **DIRECT / VERY HIGH**
- D10-A/B: **VERY HIGH**
- D10-C: **PLAUSIBLE**, less specifically Allee-driven

## Recommended next comparison

The Chief now has enough evidence to compare narrowed D10 against narrowed D11:
- D10 has stronger intrinsic bifurcation content and a sharp semantic inconsistency in applied literature;
- D11 has stronger persistence/extinction semantics but a larger risk of being subsumed by existing history-space persistence theory.

No final candidate selection is recommended from this round alone.

## Files updated

- `research/web-search/2026-09-28_fractional-bifurcation-semantics.md`
- corpus papers/results
- bibliography
- provenance registries
- this RETURN
