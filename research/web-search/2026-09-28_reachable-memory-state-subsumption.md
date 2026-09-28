# 2026-09-28 — Reachable Memory-State Subsumption Audit

**Round:** ROUND-0012  
**Request:** research/coordination/chief-to-web/ROUND-0012_reachable-memory-state-subsumption_REQUEST.md  
**Role:** WEB SEARCHER  
**Mission:** determine whether the basin-memory candidate survives restriction from the ambient Volterra function space to states actually reachable from standard Caputo IVPs, and whether classical hereditary/Markovian theory already subsumes the remaining problem.

## 1. Sharp result of the round

The audit produces a three-level hierarchy.

### Level 1 — already solved

For general \(d\ge2\), current physical state is not an injective coordinate on the **physically reachable** Caputo memory state. This follows from:

- Cong–Tuan's explicit intersection theorem for higher-dimensional standard Caputo IVPs;
- Doan–Kloeden's exact continuation-state semigroup.

Therefore the possibility of two reachable memory states with the same present is **DIRECT PRIOR**, not a new conjectural phenomenon.

### Level 2 — close prior art, not exact closure

Khalighi et al. 2026 directly studies history-dependent bistable fractional stability landscapes and reports delayed collapse/recovery, rollback, hysteresis and same-observed-state/different-history effects. Classical Volterra/minimal-state theory and infinite-state representations make enlarged memory states routine mathematical objects.

Hence the broad narrative “fractional memory creates path-dependent basins/tipping” is already crowded.

### Level 3 — residual theorem-level question

No source was found that proves or exhibits, under an autonomous standard Caputo IVP,

\[
\phi,\psi\in\mathcal R_\alpha,\qquad
e_0(\phi)=e_0(\psi),\qquad
\phi\in\mathcal B(A_1),\quad
\psi\in\mathcal B(A_2),\quad
A_1\ne A_2.
\]

The exact basin ambiguity of a current-state fiber is therefore the surviving search question.

---

## 2. State-space bookkeeping

For an autonomous Caputo problem

\[
{}^C D^\alpha x(t)=g(x(t)), \quad 0<\alpha<1,
\]

write the equivalent Volterra equation

\[
x(t)=x_0+\int_0^t
\frac{(t-s)^{\alpha-1}}{\Gamma(\alpha)}
g(x(s))\,ds.
\]

Doan–Kloeden use the generalized form

\[
x(t)=f(t)+\int_0^t a(t,s)g(x(s))\,ds
\]

on \(\mathfrak C=C(\mathbb R_+,\mathbb R^d)\).

Their transition is

\[
(T_\tau f)(\theta)=
f(\tau+\theta)
+\int_0^\tau a(\tau+\theta,s)g(x_f(s))\,ds.
\]

The canonical physical embedding is

\[
\iota(x_0)(\theta)=x_0.
\]

The observable current state is

\[
e_0(f)=f(0).
\]

The hierarchy relevant to novelty is:

\[
\iota(X_{\rm phys})
\subset
\mathcal R_\alpha
\subset
\overline{\mathcal R_\alpha}
\subset
\mathfrak C.
\]

The first inclusion is understood via \(t=0\). The ambient \(\mathfrak C\) also admits nonphysical forcing functions used to close the semigroup.

### Consequences

- The constant slice is an initialization surface, not generally an invariant manifold.
- \(\mathcal R_\alpha\) is forward invariant.
- \(\overline{\mathcal R_\alpha}\) is forward invariant by continuity.
- Attractor theory on all of \(\mathfrak C\) cannot automatically be interpreted as a theorem about physically reachable histories.
- Conversely, excluding ambient states does **not** restore finite-dimensional Markovianity: Cong–Tuan supplies collisions inside physically generated trajectories.

---

## 3. Doan–Kloeden theorem-level extraction

**Source:** Doan & Kloeden 2021, DOI 10.1007/s10013-020-00464-6.

### System class

Autonomous Caputo FDE / weakly singular Volterra equation.

### Operator/order

Caputo, \(0<\alpha<1\).

### State

Continuous continuation/input function \(f\in C(\mathbb R_+,\mathbb R^d)\).

### Result strength

Exact semigroup construction under the source's well-posedness assumptions.

### Key result

\(T_\tau\) forms a continuous semigroup on the function space. Standard Caputo initial vector \(x_0\) is represented by a constant function.

### Limitation for this round

The theorem establishes the ambient state dynamics, not intrinsic geometry of the physical orbit-saturation \(\mathcal R_\alpha\).

### Attractor refinement

Cui–Kloeden–Xin 2026, arXiv:2607.05799, constructs a compact absorbing set and an attractor for the Volterra semiflow and proves equi global Hölder regularity of the attractor.

This improves the ambient asymptotic theory but does not identify the exact physically reachable subset or its basin fibers.

---

## 4. Cong–Tuan: decisive physical-reachability result

**Source:** Cong & Tuan 2017, DOI 10.1216/JIE-2017-29-4-585.

### Scalar

Distinct standard solutions do not intersect.

### Triangular

A corresponding nonintersection structure survives strongly enough to generate their nonlocal dynamical-system formulation.

### General \(d\ge2\)

They construct a two-dimensional linear Caputo equation for which distinct solutions with different initial values meet at a finite time. The construction uses a complex zero of a Mittag-Leffler function.

This is exactly the kind of evidence ROUND-0012 required to reject an ambient-space-only interpretation.

### Translation into Doan–Kloeden state language

At the meeting time \(T\),

\[
e_0(T_T\iota(x_{01}))
=
e_0(T_T\iota(x_{02})).
\]

The continuation states remain distinct because they encode different continuation memory; otherwise uniqueness after restarting in the Volterra state would erase the distinction.

Thus:

\[
e_0|_{\mathcal R_\alpha}
\quad\text{is not injective in general.}
\]

### What the theorem does not show

The example is not a bistable extinction/coexistence model and does not supply opposite omega-limits.

---

## 5. Bistable memory prior — Khalighi et al. 2026

**Source:** arXiv:2602.20365.

The paper develops a moving/history-dependent stability-landscape description for bistable fractional systems.

High-value claims/results:

- memory flattens basin floors and changes resilience/resistance;
- the perturbation threshold can evolve after the perturbation;
- delayed collapse or delayed recovery can occur after forcing has ended;
- trajectories can rollback/rebound;
- hysteresis broadens under gradual forcing;
- a memory-free fit can mimic trajectories while shifting inferred tipping locations;
- the manuscript explicitly discusses different histories that can share an observed state while carrying different memory-conditioned landscapes.

### Why it is not the requested killer

The paper is not a general theorem on the Doan–Kloeden reachable set. Its strongest regime-transition examples involve pulse forcing and/or time variation, and it does not prove that an autonomous current-state fiber in \(\mathcal R_\alpha\) intersects two asymptotic basins.

### Novelty implication

Any future project must avoid claims of novelty based only on:

- a moving fractional stability landscape;
- memory-dependent resilience;
- delayed tipping;
- history-dependent transition thresholds;
- hysteresis enlargement.

The novelty burden must be structural/theorem-level.

---

## 6. Hereditary and minimal-state subsumption

### Miller–Sell 1970

Classical topological dynamics for Volterra integral equations already supplies the general program of enlarging state to recover dynamical-system structure.

### Miller–Feldstein 1971

Weakly singular convolution kernels, including \(t^{-p}\), \(0<p<1\), are explicitly treated for regularity. Therefore singularity of the Caputo kernel alone cannot justify a novelty claim.

### Fabrizio–Morro 2005

Equivalent histories can be quotiented into a minimal state. This warns against treating every ambient history coordinate as physically distinct.

### Conti–Marchini–Pata 2010

Minimal-state viscoelastic dynamics can support regular global-attractor theory.

### Gomoyunov 2020

For Caputo optimal control, the value is a functional on a history-of-motion space and satisfies dynamic programming. This is a direct Caputo example where the correct continuation state is explicitly history-dependent.

### Residual limitation

None of these sources was found to classify extinction/survival basin intersections of one current-state fiber inside the canonical physical reachable set of an autonomous Caputo ecological system.

---

## 7. Infinite-state / diffusive representations

**Source:** Trigeassou & Maamri 2024, DOI 10.1016/j.ifacol.2024.08.201.

A fractional system can be decomposed into an infinite-dimensional continuum/set of ordinary differential modes, with frequency-distributed state variables.

This gives:

- a conventional state-space interpretation;
- treatment of initialization;
- fractional energy/stability interpretation;
- finite-dimensional approximations.

Adjacent completely-monotone-kernel Volterra theory gives Hilbert-space Markovian lifts.

### Falsification result

It is incorrect to motivate the candidate by saying fractional memory “cannot be made Markovian.”

The real issue is instead:

> the finite vector of current populations is a projection of the augmented Markov state, and that projection may identify dynamically inequivalent states.

---

## 8. Monotone/competitive/triangular audit

### Direct constraints

- scalar Caputo: no collision of distinct standard solutions;
- triangular Caputo: strong nonintersection/dynamical simplification;
- Doan–Kloeden 2022: under triangular structure/dissipativity, attractor behavior is essentially the same as for the corresponding ODE;
- Cheng–Wu 2026: broad system comparison principles under monotonicity hypotheses.

### Non-kill

Comparison does not automatically imply injectivity of \(e_0|_{\mathcal R_\alpha}\) for arbitrary incomparable initial states in a general multidimensional ecological system.

No theorem was found reducing every competitive predator–prey Caputo model to current-state basin membership.

---

## 9. Explicit counterexample matrix

| Requirement | Cong–Tuan 2017 | Khalighi et al. 2026 | Strict target |
|---|---:|---:|---:|
| standard Caputo IVP | yes | yes in base models, plus forcing protocols | yes |
| physically reachable memory states | yes after Doan–Kloeden translation | broadly yes, but not formalized as \(\mathcal R_\alpha\) theorem | yes |
| same current physical value | yes, rigorously in \(d\ge2\) | discussed phenomenologically | yes |
| distinct future continuation | yes | yes/history-dependent | yes |
| distinct asymptotic attractors for the same-current pair | not shown | transition outcomes exist, strict pair theorem not shown | required |
| autonomous unforced theorem | yes for collision, not bistability | not for strongest transition examples | required |

No source fills the last column.

---

## 10. Double-Allee bridge

The direct Allee literature already establishes:

- fractional model-specific multistability;
- physical-initial-state basin plots;
- commensurate and incommensurate order dependence;
- integer-order Double-Allee separatrices and global bifurcation geometry.

The remaining possible contribution is therefore not another basin picture.

A theoremically meaningful Double-Allee realization would need:

1. an autonomous multidimensional positive Caputo model;
2. extinction and survival/coexistence attractors;
3. two states in \(\mathcal R_\alpha\) sharing exactly the same current populations;
4. one state in each basin;
5. a structural characterization, not just one numerical pair;
6. ideally order-dependent geometry or a transfer theorem to basin-relative persistence.

This round did not find prior art satisfying all six.

---

## 11. Verdicts

1. **Physical embedding invariance:** DIRECT PRIOR.  
2. **Reachable-state structure:** SUBSTANTIAL PARTIAL THEORY.  
3. **Same-present different-memory:** DIRECT PRIOR.  
4. **Same-present opposite-basin:** NO RESOLVING RESULT FOUND.  
5. **Hereditary/Volterra subsumption:** SUBSTANTIAL PARTIAL THEORY.  
6. **Markovian/diffusive-lift subsumption:** SUBSTANTIAL PARTIAL THEORY.  
7. **Monotone-system killer:** SUBSTANTIAL PARTIAL THEORY.  
8. **Double-Allee physical relevance:** CLOSE PRIOR ART.

---

## 12. Novelty boundary after ROUND-0012

### Covered/reformulated

- memory-state augmentation;
- non-Markovianity of the finite physical projection;
- higher-dimensional trajectory intersection;
- history-dependent bistable landscapes;
- delayed memory tipping/rollback/hysteresis;
- infinite-dimensional Markovian representation;
- generic history-space basin language.

### Search-qualified residual

\[
\boxed{
\text{fiberwise multibasin geometry of }
e_0:\mathcal R_\alpha\to X_{\rm phys}
}
\]

especially for positive multidimensional strong/Double-Allee systems and for incommensurate orders.

This is the narrow object that should be tested in any subsequent round.

---

## 13. Negative-search limitation

Searches were extensive but cannot prove that no older hereditary/Volterra paper or recent preprint contains the exact theorem under different terminology.

The correct statement is:

> No result resolving same-present opposite-basin membership on the physically reachable set of an autonomous multidimensional Caputo system was identified in the searched corpus as of 2026-09-28.

---

## 14. Recommended follow-up if Chief retains the candidate

A next round should be theorem-structure-driven, not application-keyword-driven:

- intersecting solutions + multistability + distinct omega limits;
- stable sets in weakly singular/completely monotone Volterra equations;
- minimal-state quotient versus Doan–Kloeden \(\mathcal R_\alpha\);
- planar positive/competitive Caputo systems;
- incommensurate product-history state spaces;
- structural conditions making a current-state fiber single-basin or multibasin.

This would decide whether the residual is a genuine fractional dynamical theorem gap or a special case of mature infinite-dimensional stable-set theory.
