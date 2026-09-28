# 2026-09-28 — Variable- and Distributed-Order Dynamical Systems Audit

**Round:** ROUND-0014  
**Request:** research/coordination/chief-to-web/ROUND-0014_variable-distributed-order-dynamics_REQUEST.md  
**Role:** WEB SEARCHER  
**Mission:** reconstruct theorem architecture beyond existence/numerics for systems whose fractional memory law varies in time/state or across an order distribution.

## 1. Executive map

The most important result is a maturity split.

| Operator class | Current theorem maturity |
|---|---|
| fixed single Caputo order | mature core; mapped in earlier rounds |
| finite multi-term | substantial linear/stability theory; special discrete distributed-order case |
| fixed continuous distributed order | strong operator/resolvent + linear exact + nonlinear Lyapunov theory |
| prescribed variable order \(\alpha(t)\) | existence/continuation/stability growing; global dynamical-system theory thin |
| state-dependent order \(\alpha(x,t)\) | foundational existence/stability; process architecture thin |
| distributed-variable order \(c(\alpha,t,x)\) | sparse general theory; high foundational/modeling risk |
| uncertain fixed-order box | robust-uncertainty problem from ROUND-0013, not a DO operator |

The strongest opportunity is therefore not generic distributed-order stability. It lies in global nonlinear dynamics under an **evolving memory law**.

---

## 2. Operator taxonomy

Ding et al. 2021, DOI 10.3390/e23010110, is the main review anchor.

A fixed distributed-order operator is a superposition of fixed fractional orders:

\[
D^{(c)}x
=
\int c(\alpha)D^\alpha x\,d\alpha.
\]

A variable-order operator changes \(\alpha\) itself:

\[
D^{\alpha(t)}x
\quad\text{or}\quad
D^{\alpha(x,t)}x.
\]

Distributed-variable order permits the weight/order law to vary:

\[
\int c(\alpha,t,x)D^\alpha x\,d\alpha.
\]

A multi-term operator is recovered by a discrete measure

\[
c(\alpha)=\sum_j c_j\delta(\alpha-\alpha_j).
\]

An uncertainty family \(\alpha\in[\alpha_-,\alpha_+]\) instead represents multiple possible fixed-order models and is not equivalent to integrating all those orders in one operator.

---

## 3. Fixed distributed-order state/evolution theory

### Bazhlekova 2015

DOI 10.1080/10652469.2015.1039224.

Abstract distributed-order Caputo/RL evolution equations are reformulated as Volterra integral equations.

The kernel is shown to have complete-monotonicity properties. This supports:
- well-posedness;
- positivity in ordered Banach spaces;
- subordination;
- series representations.

### Jia–Peng–Li 2014

DOI 10.3934/cpaa.2014.13.605.

Uses functional calculus for abstract distributed-order Cauchy problems and obtains bounded analytic resolvent families / \(C_0\)-semigroup results under source hypotheses.

### Li 2022

DOI 10.3934/math.2022650.

Develops representation, analytic structure, stability and decay estimates for distributed-order resolvent families.

### Interpretation

The correct statement is not “fixed distributed order has no state-space theory.”

Rather:

> fixed DO has a mature abstract evolution/resolvent framework, but a general nonlinear dissipative semiflow/attractor/persistence theory was not identified.

---

## 4. Linear distributed-order stability

### Saberi Najafi et al. 2011

DOI 10.1155/2011/175323.

Introduces a characteristic function for distributed-order systems and establishes robust/asymptotic stability criteria; the principal linear theorem gives a characteristic-root equivalence in the source class.

### Jiao–Chen–Zhong 2013

DOI 10.1002/asjc.578.

Establishes BIBO stability for LTI distributed-order systems and derives sufficient and necessary conditions for two weighting-function classes.

### Consequence

Linear distributed-order stability is direct prior and cannot carry broad novelty.

---

## 5. Nonlinear distributed-order stability

### Fernández-Anaya et al. 2017

DOI 10.1016/j.cnsns.2017.01.020.

Extends Lyapunov direct-method machinery to distributed-order nonlinear time-varying systems.

Result strength:
- sufficient stability/asymptotic-stability conditions;
- equilibrium centered;
- not a global attractor/basin theorem.

### Derakhshan–Aminataei 2020

DOI 10.1155/2020/1896563.

Extends nonlinear distributed-order Lyapunov analysis to Prabhakar fractional derivatives.

### Consequence

The nonlinear frontier begins **after** Lyapunov equilibrium stability.

---

## 6. Variable-order foundational theory

### Sarwar 2022

DOI 10.3390/fractalfract6020051.

Caputo-type variable order \(\alpha(t)\):
- local existence/uniqueness;
- continuation;
- global existence;
- Ulam–Hyers stability.

The equation is represented through a weakly singular Volterra integral equation with a time-dependent exponent.

### Lenka 2025

DOI 10.1016/j.chaos.2025.116935.

Nonautonomous time-varying-order systems:
- time-varying-order comparison principle;
- Lyapunov theorems;
- generalized convex inequalities;
- time-varying-order Mittag-Leffler asymptotic stability;
- finite-time non-blow-up conditions.

This is a substantive theory paper, not merely numerics.

### Benkerrouche et al. 2026

DOI 10.1016/j.cam.2025.117235.

Introduces a nonautonomous variable-order FDE with order depending in the source formulation on time/state; establishes:
- existence;
- uniqueness;
- uniform stability;
- approximate examples.

### Consequence

Variable-order equilibrium stability is no longer empty. What remains missing is a mature global dynamical-system layer.

---

## 7. Why semigroup structure is harder for variable order

A fixed-order autonomous Caputo kernel is translation structured in a way exploited by Volterra-history-state constructions.

For \(\alpha=\alpha(t)\), the Volterra kernel is schematically

\[
K(t,s)
=
\frac{(t-s)^{\alpha(t)-1}}{\Gamma(\alpha(t))}.
\]

This is nonconvolution in the relevant sense when \(\alpha\) varies.

Moreover, variable-order fractional integrals do not generally obey the simple semigroup law

\[
I^{\alpha(t)}I^{\beta(t)}
=
I^{\alpha(t)+\beta(t)}.
\]

Therefore one should expect:
- a process rather than an autonomous flow for prescribed \(\alpha(t)\);
- a skew-product only after specifying a driving dynamics for the order law;
- a more complex history state for state-dependent order.

No general canonical construction was found.

---

## 8. Attractors/global dynamics

Searches for theorem-level:
- global attractor;
- pullback attractor;
- absorbing set;
- asymptotic compactness;
- omega-limit structure;
- cocycle/process

were negative at the general nonlinear VO/DO systems level.

Many papers call numerically plotted chaotic sets “attractors”; these do not count as global-attractor theorems.

The fixed-DO abstract theory provides decay/stability of resolvent families but does not by itself establish a nonlinear compact dissipative attractor.

**Search-qualified gap:** global dissipative dynamics for VO/state-dependent/DVO systems.

---

## 9. Bifurcation

The search found many application papers with:
- local characteristic equations;
- critical order surfaces;
- numerical continuation;
- “Hopf” terminology.

No broad:
- center manifold;
- center-stable manifold;
- normal form;
- Lyapunov–Schmidt;
- codimension-one/codimension-two classification

was found for variable/distributed order.

Baghel 2026, DOI 10.1016/j.fraope.2025.100460, is an important ecological prior:
- distributed-order predator–prey;
- positivity/boundedness;
- equilibria;
- invasion threshold;
- memory-weight-dependent “Hopf” boundary.

It remains model-specific.

---

## 10. Persistence/extinction

The search found model-specific epidemiological/ecological results including sufficient global extinction/global-stability criteria.

This proves the branch is not empty.

However no general distributed-/variable-order analogue of classical:
- uniform persistence;
- permanence;
- robust permanence;
- invasion-measure criteria;
- basin-relative persistence

was located.

This is especially relevant for strong Allee dynamics, where global permanence is impossible on the full positive region.

---

## 11. Equilibrium geometry versus memory law

For standard Caputo-type definitions and fixed RHS, constants have zero fractional derivative.

Thus equilibrium conditions remain

\[
f(x;\theta)=0.
\]

Changing:
- \(\alpha(t)\);
- a fixed weight \(c(\alpha)\);
- or a state-dependent memory law

does not automatically move equilibrium locations if the RHS is unchanged.

But it may alter:
- stability;
- rates;
- transient crossings;
- basin geometry;
- attraction/persistence.

This distinction prevents cosmetic “memory changes Allee threshold” claims.

---

## 12. Ecology and Double Allee

### Direct VO ecology

Khan et al. 2021, DOI 10.1186/s13662-021-03340-w:
variable-order predator–prey with Mittag-Leffler kernel; existence/uniqueness and numerical dynamics.

### Direct DO ecology

Baghel 2026, DOI 10.1016/j.fraope.2025.100460:
distributed-order climate/fear predator–prey with positivity, boundedness, equilibria and local threshold/stability analysis.

### Double Allee

No direct variable-/distributed-order Double-Allee theorem paper was identified.

That is insufficient by itself for novelty.

A meaningful future bridge would need to explain why:
- multiple Allee mechanisms imply heterogeneous memory scales;
- a continuous memory distribution is better justified than arbitrary scalar orders;
- evolving memory changes a survival/extinction theorem rather than merely the numerical trajectory.

Without this, D14 risks becoming operator decoration.

---

## 13. Identifiability

### Distributed-order weights

DOI 10.1016/j.camwa.2016.06.030 proves uniqueness for recovering the distributed-order weight from one interior point observation in a diffusion setting.

DOI 10.1016/j.cam.2019.112564 gives another uniqueness result for distributed-order inversion in ultraslow diffusion.

### Variable-order learning

Singh–Mehra–Gulyani, DOI 10.1002/num.22796, develops data-driven recovery of parameters in systems of variable-order FDEs, with source examples using data from only one observed state variable.

Recent PINN work also targets recovery of \(\alpha(t)\).

### Remaining issue

Parameter recoverability inside a chosen model class does not prove **model-class distinguishability**.

The open applied-theory question is whether realistic data can distinguish:
- one fixed order;
- multiple discrete orders;
- a continuous distribution;
- a variable order.

---

## 14. Theorem-strength map

| Branch | Strongest result type found | Main limitation |
|---|---|---|
| fixed DO linear | exact/N&S characteristic/BIBO criteria | linear |
| fixed DO abstract evolution | well-posed resolvent/subordination/positivity | not full nonlinear global dynamics |
| fixed DO nonlinear | Lyapunov sufficient asymptotic stability | equilibrium-centered |
| VO existence | existence/uniqueness/continuation/global existence | no general process/attractor |
| VO nonlinear stability | comparison + Lyapunov/ML sufficient theory | equilibrium-centered |
| state-dependent VO | existence/uniqueness/uniform stability | foundational |
| DVO | operator/modeling framework | very sparse global theorem theory |
| VO/DO bifurcation | model-specific/local/numerical | no broad reduction theory |
| VO/DO persistence | model-specific positivity/extinction | no abstract persistence framework |
| inverse DO/VO | uniqueness/learning in selected settings | cross-class distinguishability unresolved |

---

## 15. Novelty killers

### Killer 1 — “distributed order lacks stability theory”

**FIRES.**

False: direct linear exact and nonlinear Lyapunov theory exists.

### Killer 2 — “variable order lacks nonlinear stability theory”

**PARTLY FIRES.**

Modern comparison/Lyapunov theory exists, but global dynamical-system architecture remains thin.

### Killer 3 — “no state/evolution representation for distributed order”

**FIRES.**

Abstract Volterra/resolvent/subordination frameworks exist.

### Killer 4 — “VO/DO bifurcation is untouched”

**PARTLY FIRES.**

Many model-specific bifurcation studies exist. No general center-manifold/normal-form theory was found.

### Killer 5 — “VO/DO ecological thresholds are untouched”

**PARTLY FIRES.**

Model-specific ecological/epidemic threshold and extinction results exist. No abstract persistence/threshold framework was identified.

### Killer 6 — “Double-Allee + VO/DO is automatically a strong novelty”

**FIRES AS A METHODOLOGICAL WARNING.**

Absence of the phrase is not enough; the memory law must generate a theorem-level mechanism.

---

## 16. Search-qualified residuals

### R14-A — Variable-order process theory

Construct a history-state process/cocycle for nonlinear time-varying-order equations with rigorous continuity, compactness and dissipativity.

### R14-B — State-dependent-order global dynamics

Develop a state-space theory when the memory exponent depends on \(x\), including well-posed continuation and invariant/attractor geometry.

### R14-C — Distributed-order global nonlinear dynamics

For a fixed positive distribution \(c\), extend from equilibrium Lyapunov stability to:
- absorbing sets;
- attractors;
- global basins;
- persistence;
- extinction;
- dependence on the weight distribution.

### R14-D — Nonhyperbolic reduction

Center-manifold/normal-form/LS theory for variable/distributed memory operators.

### R14-E — Positive threshold systems

General persistence/extinction theory for VO/DO positive systems, including basin-relative variants for strong Allee.

### R14-F — Model distinguishability

A structural theorem specifying when fixed-order, multi-term, continuous-DO and VO dynamics are observationally distinguishable.

---

## 17. Overall assessment

D14 is a **real global-dynamics frontier** but a mixed opportunity.

Strengths:
- mathematically nontrivial;
- operator variation genuinely changes the problem;
- important global theory is missing;
- active modern literature.

Risks:
- foundational/operator-theory burden is high;
- rapidly moving literature lowers novelty confidence;
- some candidate formulations may become abstract rather than ecological;
- Double-Allee proximity is currently moderate-to-low;
- flexible memory laws can become difficult to identify empirically.

The Chief should retain D14 as an independent frontier and compare it against D6/D10/D11 rather than selecting it on the basis of terminology scarcity.
