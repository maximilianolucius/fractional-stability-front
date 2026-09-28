# 2026-09-28 — Double-Allee Basin–Memory Geometry Audit

**Round:** ROUND-0011  
**Request:** `research/coordination/chief-to-web/ROUND-0011_allee-basin-memory-geometry_REQUEST.md`  
**Role:** WEB SEARCHER  
**Mission:** determine what Caputo memory genuinely changes in strong/Double-Allee threshold and basin geometry after integer-order basin theory, scalar comparison/nonintersection, and history-state dynamics are taken into account.

## Executive result

ROUND-0011 produces a sharp split.

### Closed scalar route

For scalar autonomous Caputo equations of order (0<alpha<1), distinct solution trajectories do not intersect under the standard well-posedness hypotheses used in the separation literature.

Hence, if

[
{}^C D^alpha x=f(x),qquad f(0)=f(a)=f(K)=0,
]

and (a) is the strong-Allee unstable equilibrium, then the constant solution (x(t)equiv a) is an uncrossable barrier:

[
x_0<a Longrightarrow x(t)<a,
qquad
x_0>a Longrightarrow x(t)>a.
]

Thus the equilibrium threshold (a) is an **order-independent scalar basin separator** for the canonical autonomous problem. Memory can change rates/transients, but not move this barrier.

### Surviving multidimensional route

For general multidimensional Caputo systems:
- the physical state (x(t)inmathbb R^d) is not, by itself, a Markov/semiflow state;
- different physical trajectories may meet;
- the natural semidynamical system lives in a function/memory space through the Volterra representation;
- published ecological “basins of attraction” are usually computed by varying the initial population vector (x(0)), i.e. on the canonical physical-initial-data slice, not over the full memory state;
- direct Double-Allee prior art already shows (alpha)-dependent basin-stability plots numerically, including incommensurate cases;
- no searched source rigorously characterizes an (alpha)-dependent Double-Allee separatrix/basin boundary in the full Caputo memory-state semiflow.

The strongest residual frontier is therefore:

> **multidimensional basin/separatrix geometry for strong/Double-Allee Caputo systems on the memory-state semiflow, together with a theorem relating that full basin to the physically initialized slice and to threshold-relative persistence.**

This is intrinsically fractional and survives all four killer tests, but with high subsumption risk from hereditary/Volterra stable-manifold theory.

---

# 1. Integer-order Double-Allee baseline

## Contreras Julio & Aguirre (2018)

**Source:** *Allee thresholds and basins of attraction in a predation model with double Allee effect*, Mathematical Methods in the Applied Sciences 41, 2699–2714.  
DOI **10.1002/mma.4774**.

This is a mandatory benchmark for any future fractional basin claim.

The source does not define the Allee threshold as only a scalar prey density. It identifies the extinction/survival threshold with the **phase-space basin boundary**, and this boundary may be:

- the stable manifold of an equilibrium;
- a limit cycle;
- a homoclinic orbit.

The paper computes a full bifurcation diagram. Local bifurcations include:
- saddle-node;
- transcritical;
- Hopf.

Global phenomena include:
- homoclinic bifurcation;
- heteroclinic connections;
- heteroclinic cycles.

The central dynamical fact is that basin boundaries are invariant objects whose topology can change at bifurcations. Rearrangements of stable/unstable invariant manifolds reorganize the extinction and coexistence basins. The source also studies dynamics near infinity to determine when basins are bounded or unbounded.

### Consequence for fractional novelty

A future fractional paper cannot claim novelty merely because:
- it plots extinction/coexistence basins;
- it uses a saddle stable manifold as a threshold;
- it observes basin rearrangement across a parameter bifurcation.

Those are already deep integer-order Double-Allee results.

## Related integer-order baseline

Arancibia-Ibarra (2019), *The basins of attraction in a modified May–Holling–Tanner predator–prey model with Allee affect*, Nonlinear Analysis 185, 15–28, DOI **10.1016/j.na.2019.03.004**, proves separatrices dividing oscillation/coexistence/extinction basins and identifies homoclinic/limit-cycle and Bogdanov–Takens structure.

The fractional contribution must therefore identify what **memory/order** changes relative to a mature invariant-manifold baseline.

---

# 2. Block A — Scalar strong-Allee Caputo threshold rigidity

## 2.1 Separation / nonintersection theory

### Diethelm & Ford (2012)

*Volterra integral equations and fractional calculus: Do neighboring solutions intersect?*  
Journal of Integral Equations and Applications 24, 25–37.  
DOI **10.1216/JIE-2012-24-1-25**.

This belongs to the separation-theorem line for scalar fractional IVPs.

### Cong & Tuan (2017)

*Generation of nonlocal fractional dynamical systems by fractional differential equations*.  
Journal of Integral Equations and Applications 29, 585–608.  
DOI **10.1216/JIE-2017-29-4-585**.

The key theorem-level statement for this round:

> in a one-dimensional Caputo FDE, two distinct solution trajectories either coincide or do not intersect.

The same source stresses the multidimensional contrast: different trajectories can meet.

### Modern comparison theory

Wu (2020), *A general comparison principle for Caputo fractional order ordinary differential equations*, DOI **10.1142/S0218348X2050070X**, establishes a general scalar comparison principle under weak hypotheses.

Cheng & Wu (2026), *Analysis of Caputo fractional order systems: The complete system comparison principles*, JMAA 559, 130509, DOI **10.1016/j.jmaa.2026.130509**, completes the system comparison framework and explicitly places scalar comparison as already fully established.

## 2.2 Strong-Allee barrier theorem as a corollary

Take the equilibrium solution

[
x_a(t)equiv a.
]

If (x_0<a), nonintersection prevents a solution from ever meeting (a). By continuity,

[
x(t)<aquadorall t
]

on its interval of existence.

Likewise,

[
x_0>aLongrightarrow x(t)>a.
]

Therefore:

### Verdict A1
**DIRECT PRIOR / IMMEDIATE COROLLARY:** a scalar solution initialized below (a) cannot cross above (a).

### Verdict A2
**DIRECT PRIOR / IMMEDIATE COROLLARY:** a scalar solution initialized above (a) cannot cross below (a).

### Verdict A3
**DIRECT PRIOR / CLOSED SCALAR NOVELTY ROUTE:** under the standard scalar Caputo IVP hypotheses, the unstable equilibrium (a) is an order-independent barrier for (0<alpha<1).

If the remaining sign/global-attraction assumptions imply trajectories below (a) converge to extinction and above (a) to (K), then the scalar basin split itself is the same threshold split as in the ODE.

### Verdict A4
**NO for the equilibrium threshold itself.**

Memory may produce different transient shape/time scales, but cannot cause a scalar trajectory to cross the equilibrium barrier (a) without violating the separation theorem.

This does **not** prohibit crossing:
- an externally defined management density (c
e a);
- a coordinate threshold in a multidimensional system;
- a projection of a higher-dimensional/history-space basin boundary.

## Killer 1

**FIRES.**

Scalar “memory shifts the strong-Allee threshold” is not a viable novelty direction for the canonical autonomous Caputo IVP.

---

# 3. Block B — What is a basin in a multidimensional Caputo system?

## 3.1 Physical state alone is not the dynamical state

Doan & Kloeden (2021), *Semi-Dynamical Systems Generated by Autonomous Caputo Fractional Differential Equations*, DOI **10.1007/s10013-020-00464-6**, represents the Caputo IVP as a singular Volterra problem and constructs a semidynamical system on

[
C(mathbb R_+,mathbb R^d).
]

For a physical initial vector (x_0), the canonical IVP is embedded by the constant function

[
f_0(t)equiv x_0.
]

The physical solution is recovered from the memory-state semiflow by evaluation.

Crucially:
- the ambient function-space state is the Markov/semiflow state;
- the finite-dimensional physical state (x(t)) alone generally does not generate a semiflow;
- the constant-function injection is a physically meaningful slice, but it is not generally an invariant finite-dimensional phase space.

Cong & Tuan (2017) independently emphasizes the contrast:
- scalar trajectories do not intersect;
- in higher dimensions, different physical trajectories may meet.

## 3.2 Correct basin terminology

Let (T_t) denote the memory-state semiflow and let (iota(x_0)) denote the canonical constant-function embedding.

The mathematically natural full basin of an attractor (mathcal A) is

[
mathcal B_C(mathcal A)
=
{phiin C:operatorname{dist}(T_tphi,mathcal A)	o0}.
]

A basin plotted by varying only physical initial populations is instead the slice

[
mathcal B_{m phys}(mathcal A)
=
{x_0:iota(x_0)inmathcal B_C(mathcal A)}.
]

This sliced basin is meaningful, but it is **not the full invariant basin geometry** of the memory system.

## 3.3 Analogue from delay dynamics

Leng, Lin & Kurths (2016), *Basin stability in delayed dynamics*, Scientific Reports 6, 21449, DOI **10.1038/srep21449**, explicitly treats basin stability when the initial-condition space is infinite-dimensional.

They emphasize:
- basin volume in a function space is fundamentally different from ODE basin area/volume;
- numerical computation requires a finite-dimensional sampling/projection convention for histories.

This is not a Caputo theorem, but it is a strong conceptual warning: basin “volume” depends on the distribution/sampling convention in history space.

## Verdict — multidimensional physical-state basin

**SUBSTANTIAL NUMERICAL/MODEL-SPECIFIC THEORY; NO GENERAL RIGOROUS BASIN-BOUNDARY THEORY FOUND.**

A physical-initial-data basin is well-defined as a slice through the memory-state basin. It may depend on (alpha), but that dependence cannot be inferred solely from local Matignon stability.

---

# 4. Block C — Memory-state basin and separatrix geometry

Modern Caputo theory now supplies:
- a legitimate semidynamical system in the Volterra memory space;
- dissipativity/compact absorbing sets and attractors under modern assumptions;
- local stable/center-stable manifolds in several fractional formulations.

Classical hereditary/Volterra systems also have strong invariant-manifold theory.

However, the ROUND-0010 audit already found a critical mismatch:
- classical Volterra center-manifold/Hopf theorems inspected there use kernel/function-space hypotheses that do not automatically cover the canonical weakly singular, algebraically decaying Caputo kernel.

ROUND-0011 found no general source that additionally gives:
- global stable-set/basin-boundary characterization for the singular Caputo memory semiflow;
- separatrix topology in the full memory space;
- a theorem transferring that boundary to the physical initial-data slice;
- (alpha)-dependent basin-boundary regularity;
- an Allee-specific threshold interpretation of such a memory-state stable set.

## Killer 2

**DOES NOT FULLY FIRE.**

Hereditary/Volterra theory is **CLOSE PRIOR ART**, but direct subsumption of the canonical Caputo power-law memory-state basin problem was not verified.

---

# 5. Block D — Fractional stable manifolds as ecological thresholds

Existing fractional invariant-manifold papers include:
- Cong, Doan, Siegmund & Tuan (2016), stable manifolds near hyperbolic equilibria, DOI **10.1007/s11071-016-3002-z** (with erratum);
- Wang, Fečkan & Zhou (2017), center-stable manifold for planar fractional damped equations, DOI **10.1016/j.amc.2016.10.014**;
- Peng, Wang & Yu (2018), center-stable manifolds for Caputo-type equations, DOI **10.15388/NA.2018.5.2**.

These establish that “fractional systems have no stable-manifold theory” is false.

But they do not automatically prove that:

1. the manifold is the **global extinction/survival basin boundary**;
2. it is defined in the same full memory state as the Doan–Kloeden semidynamical representation;
3. its intersection with the physical-data embedding is a global ecological threshold surface;
4. this surface varies smoothly/monotonically with (alpha).

### Verdict

**SUBSTANTIAL PARTIAL THEORY.**

Local invariant manifolds are direct prior. Their promotion to a global, memory-state ecological separatrix remains unresolved in the searched corpus.

---

# 6. Block E — Fractional Allee basin prior art

## 6.1 Ramesh et al. (2025)

DOI **10.1371/journal.pone.0305179**.

Direct fractional Double-Allee prior art:
- Caputo model;
- well-posedness/positivity/boundedness;
- equilibrium and Matignon local stability;
- Lyapunov global-stability results under model conditions;
- numerical simulations.

No basin/separatrix characterization was identified in the article text searched in this round.

## 6.2 Mondal et al. (2025)

DOI **10.1016/j.cjph.2025.09.020**.

This is the closest direct prior.

The paper explicitly:
- studies Double Allee + group defense + fractional memory;
- has multiple stable alternatives, including extinction;
- plots **basins of attraction** over initial population densities;
- computes **basin stability**, i.e. probability of convergence from randomly sampled physical initial conditions;
- compares integer and fractional orders;
- studies incommensurate ((alpha_1,alpha_2)).

But the basin analysis is numerical/model-specific. The searched material does not provide:
- a rigorous separatrix equation;
- a global stable-manifold basin-boundary theorem;
- a full memory-state basin;
- a theorem proving smooth or monotone (alpha)-dependence of the boundary.

### Classification

**DIRECT NUMERICAL PRIOR; NOT A RESOLVING MEMORY-STATE THEOREM.**

## 6.3 Saha et al. (2026)

Arnabi Saha, Debjit Pal, Dipak Kesh, Debasis Mukherjee,  
*A Fractional-Order Commensurate and Incommensurate Study on Predator-Prey System with Allee in Predator and Fear Effect*, Fractional Calculus and Applied Analysis 29(3), 1486–1515.  
DOI **10.1007/s13540-026-00515-8**.

This strengthens the prior-art threat:
- Caputo commensurate and incommensurate orders;
- explicit basin-of-attraction plots over physical initial populations;
- different basins for extinction/predator extinction/coexistence;
- two-parameter ((alpha_1,alpha_2)) diagrams;
- local stability and numerical bifurcation analysis.

Again, this is model-specific numerical basin geometry, not a general history-space basin theorem.

## 6.4 Pippal & Sati (2026)

DOI **10.30538/oms2026.0339**.

This source is particularly careful.

It states:
- strong Allee makes extinction locally stable;
- coexistence therefore cannot globally attract the whole positive quadrant;
- a Volterra-type logarithmic functional yields a **basin-restricted Mittag–Leffler certificate** on positively invariant sets separated from the coordinate axes;
- (alpha) changes the stability sector and transient relaxation;
- finite-terminal autonomous Caputo oscillations should not be interpreted as exact limit cycles.

### Classification of the “basin-restricted” result

It is **not an exact basin characterization**.

It is best classified as:

> **a sufficient Lyapunov/Mittag–Leffler stability certificate on a prescribed positively invariant subset.**

It does not identify the exact basin boundary/separatrix.

## 6.5 Wang & Han (2025)

DOI **10.1007/s12346-024-01212-8**.

Caputo predator–prey model with refuge and Allee effect:
- well-posedness;
- equilibria;
- global stability results;
- fractional-order Hopf-labeled analysis;
- delayed variant;
- numerical comparison.

No exact basin-boundary/separatrix theorem was identified.

## Killer 3

**DOES NOT FIRE in the rigorous memory-state sense.**

Direct fractional Allee basin prior art exists, including Double Allee and incommensurate basin plots, but no source found rigorously characterizes the (alpha)-dependent basin boundary in the full memory-state semiflow.

---

# 7. Block F — Transient threshold crossing

The term “threshold crossing” must be split.

## 7.1 Scalar equilibrium Allee threshold

For scalar autonomous Caputo strong-Allee dynamics:

[
x=a
]

is an equilibrium trajectory and, by separation/nonintersection, cannot be crossed.

**Rigorous answer:** no crossing.

## 7.2 External management threshold

For a chosen density (c
e a), nothing in the separation theorem prevents a trajectory from crossing (c).

Fractional memory can alter:
- transient speed;
- overshoot/undershoot relative to non-equilibrium thresholds;
- recovery/extinction time.

But this is not a change in the mathematical Allee basin separator.

## 7.3 Multidimensional component threshold

In predator–prey systems, a coordinate condition such as

[
x_{m prey}=a
]

need not itself be an invariant separatrix of the full system.

A component can cross that coordinate level while the full memory-state orbit remains in the same basin.

Thus “prey crossed the Allee threshold parameter” is not automatically equivalent to “the full system crossed the extinction basin boundary.”

## 7.4 Projection of a memory-state boundary

A projected physical-state crossing is even more delicate: different memory states may share the same current physical vector.

Therefore a basin boundary that is simple in history space need not project to a single-valued curve in current physical state.

No general Caputo theorem resolving this projection geometry was found.

---

# 8. Block G — Dependence on fractional order

| Object | Status of (alpha)-dependence |
|---|---|
| equilibrium position | **rigorously unchanged** if RHS (f) is unchanged |
| scalar equilibrium Allee threshold | **rigorously unchanged barrier** for (0<alpha<1) under scalar separation assumptions |
| local stability | **rigorously (alpha)-dependent** through fractional spectral-sector conditions |
| convergence/decay/transient time | **rigorously/numerically (alpha)-dependent** in broad fractional theory |
| physical-initial-data basin boundary in (d>1) | **model-specific numerical evidence; no general theorem found** |
| basin volume / basin stability | **direct numerical evidence of (alpha)-dependence**; depends on sampling convention |
| full memory-state basin boundary | **well-posed concept in the memory semiflow; general (alpha)-dependence theorem not found** |
| exact separatrix geometry | **no general Caputo theorem found** |
| incommensurate basin reorganization | **direct numerical prior; no general theorem found** |

A key methodological warning follows:

> a change in local Matignon stability does not by itself prove a basin boundary moved.

---

# 9. Block H — Incommensurate Double-Allee basin theory

Direct model-specific prior now exists:

- Mondal et al. 2025, Double Allee + group defense, commensurate/incommensurate Caputo;
- Saha et al. 2026, Allee + fear, commensurate/incommensurate Caputo with explicit physical-initial-data basin plots.

These papers support the empirical/numerical statement that varying species-specific memory orders can change observed long-term outcomes and the sampled basin fractions.

What was **not** found:
- a general incommensurate stable-manifold theorem yielding the survival/extinction basin separator;
- a memory-state basin theorem for genuinely different orders;
- a theorem characterizing how the physical slice of a separatrix varies with one (alpha_i);
- rigorous basin-volume sensitivity with respect to multi-order vectors.

### Verdict

**DIRECT NUMERICAL/MODEL-SPECIFIC PRIOR; NO RESOLVING GENERAL THEORY FOUND.**

---

# 10. Numerical-basin artifact risk

## Killer 4

**PARTLY FIRES as a methodological warning, not as a falsification of all basin change.**

Three issues must be separated:

### 10.1 Finite-time classification

Fractional trajectories can relax algebraically and very slowly. A finite integration horizon may classify a long transient as an attractor or as nonconvergence.

Pippal–Sati 2026 explicitly performs grid/convergence checks and warns against confusing transient oscillations with periodic asymptotics.

### 10.2 Initial-memory convention

A basin plotted over (x(0)) fixes one canonical initialization convention. It does not sample the full memory-state space.

Changing the admissible history/forcing state could change basin volume dramatically.

### 10.3 Basin-volume measure

Even in delay systems, basin volume in infinite-dimensional history space requires a choice of finite-dimensional projection/sampling measure (Leng–Lin–Kurths 2016).

Thus a numerical “basin stability probability” is conditional on:
- the sampled physical/history family;
- the sampling distribution;
- integration horizon;
- solver tolerance/memory discretization;
- convergence classifier.

This does not make the result meaningless, but it must not be promoted to an invariant full-memory basin volume without qualification.

---

# 11. Required verdicts

## 11.1 Scalar strong-Allee threshold rigidity

**DIRECT PRIOR / CLOSED.**

For (0<alpha<1), scalar separation/nonintersection makes the equilibrium (a) an uncrossable barrier. No scalar (alpha)-dependent threshold-shift frontier remains for the standard autonomous Caputo IVP.

## 11.2 Multidimensional physical-state basin theory

**SUBSTANTIAL PARTIAL THEORY.**

Physical-initial-data basin plots are abundant and meaningful as slices. General rigorous global boundary theory is not mature.

## 11.3 Memory-state basin/separatrix theory

**CLOSE PRIOR ART / NO RESOLVING RESULT FOUND.**

Caputo memory semiflows and classical hereditary invariant-manifold theory exist, but no direct theorem was found giving the global survival/extinction separatrix for the canonical singular Caputo kernel.

## 11.4 (alpha)-dependence of basin boundaries

**DIRECT NUMERICAL PRIOR; GENERAL RIGOROUS RESULT NOT FOUND.**

Local stability depends rigorously on (alpha). Full basin-boundary movement is demonstrated numerically in models, but no general theorem was identified.

## 11.5 Fractional stable manifolds as ecological thresholds

**SUBSTANTIAL PARTIAL THEORY.**

Local fractional stable/center-stable manifolds exist. Their role as global ecological basin boundaries in the full memory state remains unproved at generality.

## 11.6 Incommensurate basin theory

**NO RESOLVING GENERAL RESULT FOUND; DIRECT MODEL-SPECIFIC NUMERICAL PRIOR.**

## 11.7 Double-Allee-specific prior art

**DIRECT PRIOR for basin numerics; CLOSE PRIOR ART for rigorous geometry.**

Mondal et al. 2025 is the strongest direct Double-Allee threat. It does not close the memory-state basin problem.

## 11.8 Threshold-relative persistence connection

**CREDIBLE AND NONTRIVIAL, BUT STATE-SPACE SENSITIVE.**

For strong Allee effects, global persistence of all positive physical initial states is structurally wrong.

The right object is closer to:

[
	ext{persistence conditional on membership in the survival basin}.
]

In Caputo systems, this should ultimately be defined in the memory-state semiflow, with a theorem transferring the result to the physical-data slice.

This is the natural D10-D/D11 intersection.

---

# 12. Candidate opportunity test

## Is there a nontrivial intrinsically fractional basin/threshold problem left?

**YES — but only after removing the scalar and purely algebraic routes.**

A narrowly defensible formulation is:

> **Memory-state survival/extinction basin geometry for multidimensional strong/Double-Allee Caputo systems:** characterize a basin boundary or stable set in the singular Volterra memory-state semiflow, determine how its intersection with the canonical physical-initial-data embedding depends on (alpha) (or (alpha_i)), and relate the survival side to threshold-/basin-relative persistence.

A stronger theorem family would answer at least one of:

1. Under what conditions is the memory-state survival/extinction boundary a stable manifold (local or global)?
2. When does its physical-initial-data slice vary with (alpha), despite fixed equilibrium locations?
3. Can the sliced boundary be ordered or differentiated with respect to (alpha)?
4. When is basin-relative persistence robust under perturbation of vector field/order/kernel?
5. For genuinely incommensurate systems, can one characterize the effect of one species' memory order on the survival basin?
6. How do history states with the same current physical population but different memory content lie on opposite sides of the survival boundary?

The sixth question is especially intrinsically fractional: it has no finite-dimensional ODE analogue.

## Main killer risk

The broad gap could collapse if one proves that an existing hereditary/Volterra invariant-manifold/persistence theorem applies directly to the Caputo singular kernel and its positive ecological boundary with routine verification.

That direct subsumption was **not** found in ROUND-0011.

---

# 13. Final round disposition

- Scalar basin-shift novelty: **REJECT**.
- Generic fractional Allee basin plots: **CROWDED / direct prior**.
- Full-memory basin geometry: **RETAIN as search-qualified frontier**.
- Physical-slice vs full-memory transfer: **RETAIN**.
- Incommensurate basin geometry: **RETAIN with high uncertainty**.
- Basin-relative persistence on Caputo memory state: **RETAIN as D10-D/D11 intersection**.

No project winner is selected in this round.
