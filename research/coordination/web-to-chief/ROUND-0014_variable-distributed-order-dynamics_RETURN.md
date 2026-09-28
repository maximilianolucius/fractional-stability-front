# ROUND-0014 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** research/coordination/chief-to-web/ROUND-0014_variable-distributed-order-dynamics_REQUEST.md  
**Status:** COMPLETE

## RETURN TO CHIEF

### Question investigated

Reconstruct the theorem architecture for fractional dynamical systems when the **memory operator itself varies**, distinguishing:

1. prescribed variable order \(\alpha=\alpha(t)\);
2. state-/solution-dependent order \(\alpha=\alpha(x,t)\);
3. fixed distributed order with weight \(c(\alpha)\);
4. distributed-variable order \(c(\alpha,t,x)\);
5. finite multi-term mixtures;
6. uncertain fixed-order boxes, which belong to ROUND-0013 rather than this branch.

The target was not merely existence or numerical modeling. The search tested for:
- state-space/process/semigroup structure;
- exact linear stability;
- nonlinear Lyapunov/global stability;
- attractors/dissipativity;
- rigorous bifurcation/nonhyperbolic theory;
- persistence/extinction;
- identifiability;
- a natural Double/Multiple-Allee bridge.

---

## Executive finding

This branch is **highly nonuniform**. “Variable/distributed-order dynamics” should not be treated as one maturity class.

### A. Fixed distributed-order systems are substantially mature at the operator, linear-stability, and Lyapunov-stability levels

Direct prior includes:

- abstract Volterra reformulations and resolvent/evolution families;
- positivity/subordination for distributed-order evolution equations;
- exact or necessary-and-sufficient linear stability/BIBO criteria in important classes;
- nonlinear Lyapunov/asymptotic-stability theorems;
- distributed-order Prabhakar extensions;
- inverse uniqueness for the order-weight function in diffusion settings.

Thus:

> “distributed order lacks a mathematical dynamical/stability foundation”

is false.

### B. Prescribed variable-order systems are materially less mature

The strongest general results found are concentrated in:

- existence/uniqueness;
- continuation/global existence;
- Ulam–Hyers stability;
- comparison principles;
- Lyapunov and time-varying-order Mittag-Leffler stability;
- non-blow-up bounds.

Because the kernel/order law varies explicitly with time, the system is naturally **nonautonomous**. No general process/cocycle/history-state theory comparable to the Doan–Kloeden fixed-order Caputo semidynamical construction was identified.

### C. State-dependent order and distributed-variable-order are thinner still

Recent work studies nonlinear/state/history-dependent orders, but largely at the level of existence, uniqueness, stability, and numerics. The distributed-variable-order literature is dominated by constitutive/modeling applications and operator formulation.

No broad theorem-level architecture was identified for:
- cocycles/processes;
- absorbing sets/global or pullback attractors;
- invariant manifolds;
- center manifolds/normal forms;
- persistence/permanence;
- basin geometry.

### D. The strongest surviving mathematical frontier is global nonlinear dynamics under an evolving memory law

For fixed distributed order, the frontier begins **after** well-posedness and equilibrium Lyapunov stability.

For variable/state-dependent/distributed-variable order, even the dynamical-system state architecture remains incomplete.

A defensible residual is:

> **Develop global dynamical-systems and threshold theory for nonlinear positive systems whose fractional memory law varies in time/state or across a distribution: process/cocycle construction, dissipativity/attractors, persistence/extinction, and nonhyperbolic threshold dynamics.**

However, the Double-Allee link is currently weaker than for the retained robustness and basin-memory candidates. Direct ecological variable/distributed-order models exist, but no searched source established a specifically Double-Allee theorem program, and the biological interpretation of an evolving/order distribution must be justified rather than appended decoratively.

---

# 1. Taxonomic separation

The review literature, especially Ding–Patnaik–Sidhardh–Semperlotti (Entropy 2021, DOI 10.3390/e23010110), makes the following distinctions essential.

## 1.1 Fixed constant order

\[
{}^C D^\alpha x=f(x),\qquad \alpha=\text{constant}.
\]

This is the mature fixed-order branch mapped elsewhere in the project.

## 1.2 Variable order

\[
{}^C D^{\alpha(t)}x=f(t,x),
\]

or more generally

\[
{}^C D^{\alpha(x,t)}x=f(t,x).
\]

The memory kernel itself varies with time/state.

## 1.3 Fixed distributed order

\[
\int_0^1 c(\alpha)\,{}^C D^\alpha x(t)\,d\alpha
=
f(t,x).
\]

The distribution \(c\) is fixed in time. This is not merely “an uncertain \(\alpha\)”: the operator is a superposition over a continuum of orders.

## 1.4 Distributed-variable order

Schematically,

\[
\int c(\alpha,t,x)\,D^\alpha x\,d\alpha.
\]

Both the order distribution and the dynamics may vary. The searched review literature regards this as a much less developed class.

## 1.5 Multi-term systems

A finite mixture

\[
\sum_{j=1}^m c_j D^{\alpha_j}x
\]

is a special/discrete distributed-order case when the weight is a finite sum of Dirac masses.

It should not be conflated with a continuous order distribution.

## 1.6 Uncertain-order boxes

A family of fixed-order models

\[
\alpha\in[\alpha_-,\alpha_+]
\]

or

\[
\boldsymbol\alpha\in\prod_i[\alpha_i^-,\alpha_i^+]
\]

is a robust-uncertainty problem from ROUND-0013, not a distributed-order operator.

### Verdict 7 — variable versus distributed-order distinction

**DIRECT PRIOR.**

The classes are mathematically and physically distinct; combining them under one “changing fractional order” label obscures the theorem frontier.

---

# 2. State-space / process architecture

## 2.1 Fixed distributed order: substantial abstract theory

### Bazhlekova 2015

*Completely monotone functions and some classes of fractional evolution equations*, DOI 10.1080/10652469.2015.1039224.

For distributed-order Caputo/Riemann–Liouville abstract evolution equations with a generator \(A\) of a \(C_0\)-semigroup on a Banach space, the problem is reformulated as an abstract Volterra integral equation.

The work establishes:
- well-posedness;
- complete monotonicity properties of the kernel;
- positivity in ordered Banach spaces;
- a subordination representation.

This is strong state/evolution prior.

### Jia–Peng–Li 2014

*Well-posedness of abstract distributed-order fractional diffusion equations*, DOI 10.3934/cpaa.2014.13.605.

Under suitable sectorial/operator assumptions, distributed-order fractional operators generate bounded analytic resolvent families or \(C_0\)-semigroups in the source formulation.

### Li 2022

*Representation and stability of distributed order resolvent families*, DOI 10.3934/math.2022650.

Develops representation, subordination, analyticity and decay estimates for distributed-order resolvent families.

### Interpretation

Fixed distributed order has an established **Volterra/resolvent-family architecture**.

It is not correct to say that it lacks a state-space theory.

However, a resolvent family is not automatically the same object as a finite-dimensional autonomous semiflow on \(x(t)\). Global nonlinear dynamical-system questions still require care.

## 2.2 Prescribed variable order

Sarwar 2022, DOI 10.3390/fractalfract6020051, treats a Caputo variable-order IVP and proves:
- existence/uniqueness;
- continuation;
- global existence;
- Ulam–Hyers stability.

The equation is represented as a weakly singular Volterra-type integral equation whose exponent depends on time.

The changing exponent destroys the simple convolution/time-translation structure used in fixed-order autonomous Caputo theory.

Accordingly, a prescribed \(\alpha(t)\) is naturally nonautonomous.

Lenka 2025, DOI 10.1016/j.chaos.2025.116935, develops a nonautonomous time-varying-order Lyapunov/comparison theory, but not a general process/cocycle/attractor theory.

## 2.3 State-dependent order

The 2026 paper *Fractional differential equations of non-autonomous variable-order*, DOI 10.1016/j.cam.2025.117235, allows an order depending on time and the unknown state in the source formulation and proves existence, uniqueness and uniform stability.

This is direct evidence that state-dependent order is active, but the theorem architecture remains foundational.

## 2.4 Distributed-variable order

The Ding et al. review identifies distributed-variable-order operators as a further generalization whose distribution/order law changes with the independent/dependent variables. Applications are much thinner than for fixed distributed order.

No broad process/cocycle theory was identified.

### Verdict 1 — state-space/process architecture

**SUBSTANTIAL PARTIAL THEORY.**

- fixed distributed order: strong abstract Volterra/resolvent framework;
- prescribed variable order: well-posed nonautonomous Volterra formulation, but no general process/cocycle architecture found;
- state-dependent/distributed-variable order: foundational results, no mature dynamical-system framework identified.

---

# 3. Linear exact stability

## 3.1 Distributed-order linear systems

### Saberi Najafi–Refahi Sheikhani–Ansari 2011

*Stability Analysis of Distributed Order Fractional Differential Equations*, DOI 10.1155/2011/175323.

For important linear distributed-order classes, stability is characterized through the distributed-order characteristic function and an inertia concept relative to the density.

The source gives a necessary-and-sufficient-type characteristic-root result for its principal linear formulation.

### Jiao–Chen–Zhong 2013

*Stability Analysis of Linear Time-Invariant Distributed-Order Systems*, DOI 10.1002/asjc.578.

Establishes BIBO stability conditions for LTI distributed-order systems over \((0,1)\), including sufficient-and-necessary conditions for two classes of weighting functions.

Thus exact linear distributed-order stability is not a frontier in broad form.

## 3.2 Variable-order linear systems

The searched variable-order literature contains:
- frozen/quasi-static spectral tests;
- order-dependent numerical analysis;
- time-varying-order Lyapunov sufficient conditions.

No comparably broad exact characteristic-root theory was identified for general \(\alpha(t)\) or \(\alpha(x,t)\), which is expected because time-translation invariance is lost.

### Verdict 2 — linear exact stability

**DIRECT PRIOR for fixed distributed order; SUBSTANTIAL PARTIAL THEORY for variable order.**

Broad novelty cannot rest on linear distributed-order stability.

---

# 4. Nonlinear stability

## 4.1 Fixed distributed order

Fernández-Anaya et al. 2017, DOI 10.1016/j.cnsns.2017.01.020, generalizes the Lyapunov direct method to nonlinear time-varying distributed-order systems.

The results include sufficient Lyapunov/asymptotic-stability criteria and extensions of fixed-order Caputo inequalities.

Derakhshan–Aminataei 2020, DOI 10.1155/2020/1896563, extends distributed-order nonlinear time-varying stability analysis to Prabhakar fractional derivatives.

Thus nonlinear distributed-order Lyapunov theory is substantial.

## 4.2 Variable order

Lenka 2025 develops:
- a time-varying-order comparison principle;
- Lyapunov stability;
- time-varying-order Mittag-Leffler asymptotic stability;
- convex Lyapunov derivative inequalities;
- non-blow-up estimates.

This significantly raises the novelty bar for equilibrium stability.

Recent variable-order comparison-principle work further strengthens that branch.

### What is not mature

No general converse Lyapunov theory, global attractor theory, basin/separatrix theory, or persistence framework comparable to the fixed-order Caputo branch was identified.

### Verdict 3 — nonlinear stability

**SUBSTANTIAL PARTIAL THEORY.**

Equilibrium-centered sufficient theory is real and growing. Global nonlinear dynamics remains thin.

---

# 5. Attractors / dissipativity / global dynamics

Targeted searches covered:
- global attractor;
- pullback attractor;
- absorbing set;
- asymptotic compactness;
- omega-limit set;
- gradient structure;
- process/cocycle;
- variable/distributed order.

The search recovered many papers using “attractor” in the numerical-chaos sense, especially variable-order Lorenz/Arneodo/Rössler-type studies.

Those are not global-attractor theorems.

No general theorem comparable to modern fixed-order Caputo results on:
- compact absorbing sets;
- global attractors;
- pullback/skew-product attractors;
- global Hölder compactness

was identified for nonlinear variable-/state-dependent-order finite-dimensional systems.

For fixed distributed-order abstract evolution equations there is mature resolvent-family/decay theory, but this did not amount in the searched corpus to a broad nonlinear dissipative-semiflow theory.

### Verdict 4 — attractor/global dynamics

**NO RESOLVING GENERAL RESULT FOUND.**

This is one of the clearest theorem-level frontiers.

---

# 6. Bifurcation / nonhyperbolic dynamics

Searches for:
- center manifold;
- center-stable manifold;
- normal form;
- Lyapunov–Schmidt reduction;
- saddle-node/fold;
- pitchfork/transcritical;
- cusp;
- rigorous Hopf/periodic bifurcation

found mainly:
- model-specific local characteristic equations;
- numerical bifurcation diagrams;
- frozen-time/instantaneous spectral criteria;
- “Hopf threshold” labels.

No broad center-manifold or normal-form theory was identified for:
- prescribed variable order;
- state-dependent order;
- fixed continuous distributed order;
- distributed-variable order.

The semantic warning from ROUND-0010 remains important: a local spectral/sector transition is not automatically a theorem proving birth of a classical periodic orbit in a finite-terminal fractional formulation.

### Direct ecological example

Baghel 2026, DOI 10.1016/j.fraope.2025.100460, develops a distributed-order predator–prey model and derives positivity, boundedness, equilibria, invasion quantities and a model-specific “Hopf” threshold affected by memory weights.

This is strong application prior, but not a general nonhyperbolic-reduction theorem.

### Verdict 5 — bifurcation/nonhyperbolic theory

**NO RESOLVING GENERAL RESULT FOUND; CLOSE MODEL-SPECIFIC PRIOR ART.**

---

# 7. Persistence / extinction / positivity

## 7.1 Positivity

Fixed distributed-order abstract evolution theory includes positivity results under ordered-Banach-space assumptions via subordination/complete monotonicity.

Model-specific ecological and epidemiological papers prove positivity/boundedness routinely.

## 7.2 Model-specific thresholds

Recent distributed-order ecological/epidemic papers establish:
- disease-free/endemic equilibria;
- invasion/reproduction thresholds;
- sufficient global extinction/global-stability conditions;
- local coexistence stability;
- model-specific bifurcation thresholds.

For example, 2026 distributed-order SEIRS work derives \(R_0\), local stability, and a sufficient global disease-extinction result using a distributed-order Lyapunov construction.

## 7.3 General persistence theory

No abstract analogue of:
- Hale–Waltman/Thieme uniform persistence;
- invasion-measure robust permanence;
- basin-relative persistence for strong Allee

was identified for variable- or distributed-order nonlinear systems.

No general theorem was found characterizing how a changing order law or order distribution affects a persistence/extinction boundary.

### Verdict 6 — persistence/extinction theory

**SUBSTANTIAL PARTIAL THEORY at the model level; NO RESOLVING GENERAL THEORY FOUND.**

---

# 8. Operator variation as a dynamical variable

This block is conceptually important.

## Prescribed \(\alpha(t)\)

If \(\alpha(t)\) is externally specified, the equation is a **nonautonomous memory system**.

A process/cocycle formulation is more natural than an autonomous flow, but no general theorem architecture was identified.

## Dynamically generated order

If

\[
\dot z=h(z),\qquad \alpha=\alpha(z),
\]

one can formally augment the state by \(z\).

But this does not automatically produce a standard finite-dimensional Markov system, because the fractional memory integral still encodes the past and the kernel itself now changes along the trajectory.

Thus “add \(\alpha\) as one more ODE state variable” is not a general killer.

## State-dependent \(\alpha(x,t)\)

The operator and solution are coupled. Recent papers prove well-posedness/stability, but no broad autonomous skew-product/semiflow reduction was found.

## Distributed-variable order

An evolving weight \(c(\alpha,t,x)\) is even more general. No mature global dynamical theory was located.

---

# 9. Distributed-order spectral structure

For

\[
\int_0^1 c(\alpha)D^\alpha x(t)\,d\alpha
=
Ax(t),
\]

the Laplace-domain characteristic object depends on

\[
B(s)=\int_0^1 c(\alpha)s^\alpha\,d\alpha.
\]

The 2011/2013 linear-stability literature shows that:
- the weight function enters the characteristic/root geometry explicitly;
- exact/N&S stability criteria exist for important LTI classes.

The 2022 resolvent-family literature shows that distribution shape affects decay rates and analytic representation.

Finite mixtures of Dirac weights recover multi-term systems.

### Open structural question found

The search did **not** identify a general nonlinear theorem translating:
- support of \(c\);
- low-order mass;
- moments/shape of \(c\)

into global basin/persistence geometry.

That would need to exceed existing linear/root and decay results.

---

# 10. Equilibria and Double/Multiple Allee

For standard Caputo/distributed-Caputo operators, the derivative of a constant is zero.

Hence if the right-hand side \(f(x;\theta)\) is unchanged, equilibrium locations satisfy

\[
f(x;\theta)=0
\]

and are not moved merely by replacing fixed-order memory with variable/distributed order.

This parallels ROUND-0010/0013.

Memory-law variation can still alter:
- local stability;
- transient threshold crossing;
- convergence rates;
- basin geometry in multidimensional systems;
- persistence/extinction outcomes.

## Direct ecological prior

Variable-order predator–prey models already exist, e.g. Khan et al. 2021, DOI 10.1186/s13662-021-03340-w.

Distributed-order predator–prey models now exist as well, e.g. Baghel 2026, DOI 10.1016/j.fraope.2025.100460.

Direct fixed-order Allee models are already abundant from earlier rounds.

### Direct Double-Allee search

No direct variable-order or distributed-order **Double Allee** theorem-level paper was identified in the searched corpus.

That absence alone is not evidence of a strong gap.

### Biological plausibility

A distributed order can be interpreted as a superposition of multiple memory scales and may be biologically more defensible than assigning an arbitrary single \(\alpha\) when a population aggregates heterogeneous memory processes.

But linking each Double-Allee mechanism to a different memory distribution is presently a modeling hypothesis, not a theorem-backed necessity.

### Verdict 9 — Double-Allee proximity

**AMBIGUOUS / MORE SEARCH REQUIRED.**

The connection is mathematically plausible through threshold/persistence dynamics, but weaker and more model-dependent than D6 robustness or the retained basin-memory candidate.

---

# 11. Identifiability / model distinguishability

## Distributed-order inverse problems

Li et al. 2017, DOI 10.1016/j.camwa.2016.06.030, proves uniqueness for recovery of the distributed-order weight function from one interior observation in a time-fractional diffusion problem.

Related 2020 work proves uniqueness for inversion of distributed orders in ultraslow diffusion.

Thus:

> “the distributed-order weight is intrinsically unidentifiable”

is false.

## Variable-order learning

Singh–Mehra–Gulyani 2023, DOI 10.1002/num.22796, develops data-driven parameter learning for systems of variable-order FDEs and demonstrates recovery even when data from only one system variable are available in source examples.

Recent PINN/inverse work also infers time-varying order functions.

## Remaining gap

These are model-specific inverse problems.

No general structural distinguishability theorem was identified for choosing among:
- fixed single order;
- finite multi-term;
- continuous distributed order;
- prescribed variable order;
- state-dependent order.

A flexible memory law may fit data without being scientifically distinguishable from a simpler alternative.

### Verdict 8 — identifiability/model distinguishability

**SUBSTANTIAL PARTIAL THEORY.**

Specific inverse uniqueness and learning results exist; broad cross-operator model distinguishability remains unresolved.

---

# 12. Required verdict summary

| Item | ROUND-0014 verdict | Core reason |
|---|---|---|
| 1. state-space/process architecture | **SUBSTANTIAL PARTIAL THEORY** | strong fixed-DO Volterra/resolvent theory; VO/state-dependent/DVO process theory thin |
| 2. linear exact stability | **DIRECT PRIOR** for fixed DO; **SUBSTANTIAL PARTIAL THEORY** for VO | N&S/BIBO results exist for DO LTI |
| 3. nonlinear stability | **SUBSTANTIAL PARTIAL THEORY** | DO and time-varying-order Lyapunov theories exist, mainly sufficient/equilibrium-centered |
| 4. attractor/global dynamics | **NO RESOLVING GENERAL RESULT FOUND** | no broad nonlinear attractor/process theory identified |
| 5. bifurcation/nonhyperbolic theory | **NO RESOLVING GENERAL RESULT FOUND** | model-specific spectral/numerical work, no general center-manifold/normal-form architecture |
| 6. persistence/extinction theory | **SUBSTANTIAL PARTIAL THEORY** | positivity/model-specific threshold results; no abstract persistence framework found |
| 7. VO vs DO distinction | **DIRECT PRIOR** | established operator taxonomy; not interchangeable |
| 8. identifiability/distinguishability | **SUBSTANTIAL PARTIAL THEORY** | inverse uniqueness/learning exists; cross-class distinguishability unresolved |
| 9. Double-Allee proximity | **AMBIGUOUS / MORE SEARCH REQUIRED** | ecological models exist, direct Double-Allee operator-varying theory not located |
| 10. strongest unresolved theorem frontier | **NO RESOLVING GENERAL RESULT FOUND** | global nonlinear process/attractor/persistence/bifurcation theory for evolving memory laws |

---

## Foundational sources

- Ding et al. 2021, DOI 10.3390/e23010110 — operator taxonomy and applications review.
- Saberi Najafi et al. 2011, DOI 10.1155/2011/175323 — linear DO stability.
- Jiao–Chen–Zhong 2013, DOI 10.1002/asjc.578 — LTI DO BIBO stability.
- Bazhlekova 2015, DOI 10.1080/10652469.2015.1039224 — abstract DO Volterra/evolution theory.
- Jia–Peng–Li 2014, DOI 10.3934/cpaa.2014.13.605 — distributed-order abstract Cauchy well-posedness/resolvents.
- Fernández-Anaya et al. 2017, DOI 10.1016/j.cnsns.2017.01.020 — nonlinear DO Lyapunov theory.
- Sarwar 2022, DOI 10.3390/fractalfract6020051 — variable-order existence/continuation/Ulam-Hyers.
- Lenka 2025, DOI 10.1016/j.chaos.2025.116935 — time-varying-order Lyapunov stability.
- Benkerrouche et al. 2026, DOI 10.1016/j.cam.2025.117235 — nonautonomous/state-dependent variable-order existence, uniqueness, uniform stability.

## Strongest-known results

- exact/N&S linear distributed-order stability in important LTI classes;
- abstract distributed-order Volterra/resolvent families;
- positivity and subordination for fixed distributed order;
- nonlinear distributed-order Lyapunov/asymptotic stability;
- time-varying-order comparison and Lyapunov/ML stability;
- inverse uniqueness for distributed-order weights in diffusion;
- data-driven recovery for variable-order models.

## Recent frontier sources

- Lenka 2025 time-varying-order stability;
- Benkerrouche et al. 2026 nonautonomous variable-order FDEs;
- Baghel 2026 distributed-order ecological stability/invasion thresholds;
- 2026 numerical variable-order chaos/order-modulation papers;
- recent history-dependent variable-order existence theory.

---

## Strongest unresolved theorem-level frontiers

### F-VO1 — Process/cocycle theory for prescribed variable order

Construct a canonical history-state process/cocycle for nonlinear \(\alpha(t)\)-Caputo systems and determine continuity/compactness/dissipativity properties.

**Search status:** no resolving general result found.

### F-VO2 — State-dependent-order dynamical systems

For \(\alpha=\alpha(x,t)\), characterize well-posed memory state, autonomy/nonautonomy, and whether a genuine skew-product/semiflow formulation exists.

**Search status:** foundational existence/stability prior; no global architecture found.

### F-DO1 — Global nonlinear distributed-order dynamics

For fixed positive weight \(c\), go beyond Lyapunov equilibrium stability to:
- absorbing sets;
- global attractors;
- basin geometry;
- persistence/extinction;
- robustness with respect to \(c\).

**Search status:** no general resolving theorem found.

### F-DO2 — Nonhyperbolic/bifurcation reduction

Develop center-manifold/normal-form/Lyapunov–Schmidt theory for continuous distributed-order or variable-order memory operators.

**Search status:** no broad theorem located.

### F-DVO1 — Distributed-variable-order dynamics

For \(c=c(\alpha,t,x)\), construct a rigorous global dynamical-system framework and identify conditions for stability/persistence.

**Search status:** very thin; high foundational risk.

### F-ID1 — Cross-memory-model distinguishability

Determine when trajectory data can distinguish fixed order, multi-term, continuous distributed order, and variable/state-dependent order.

**Search status:** specific inverse problems solved; general structural taxonomy unresolved.

---

## Evidence against broad novelty

The following are not defensible novelty claims:

- distributed-order fractional calculus itself;
- linear distributed-order stability;
- BIBO stability for distributed-order LTI systems;
- abstract distributed-order evolution/resolvent theory;
- nonlinear distributed-order Lyapunov stability;
- variable-order existence/uniqueness;
- variable-order Ulam–Hyers stability;
- time-varying-order Lyapunov/ML stability;
- variable-order predator–prey modeling;
- distributed-order predator–prey modeling;
- identifiability of a distributed-order weight in all formulations.

---

## Double-Allee assessment

D14 is a **real mathematical frontier**, but its Double-Allee connection is not yet as strong as several retained alternatives.

A non-decorative future formulation would have to make the memory law structurally necessary, for example:

> heterogeneous memory scales alter survival/extinction basin geometry or basin-relative persistence while the equilibrium threshold set remains fixed.

or

> evolving memory order couples to population state and creates a new threshold mechanism that cannot be reproduced by a fixed-order family.

No searched theorem presently establishes such a Double-Allee mechanism.

Therefore retain D14 in the domain map, but do not elevate it solely because direct “variable-order Double Allee” papers were not found.

---

## Remaining uncertainty

1. Some distributed-order PDE literature may contain attractor theorems under terminology not retrieved in this round; no general finite-dimensional nonlinear threshold counterpart was identified.
2. A general nonautonomous Volterra process theorem might subsume portions of variable-order dynamics once its nonconvolution kernel satisfies suitable hypotheses.
3. Recent variable-order literature is rapidly expanding, so novelty confidence around process/cocycle theory is lower than for older branches.
4. “Hopf” claims in VO/DO application papers require operator-specific scrutiny before being treated as rigorous periodic-orbit bifurcation theorems.
5. The biological identifiability of evolving memory laws remains much weaker than mathematical parameter recoverability in controlled inverse problems.

---

## Files updated

- research/coordination/web-to-chief/ROUND-0014_variable-distributed-order-dynamics_RETURN.md
- research/web-search/2026-09-28_variable-distributed-order-dynamics.md
- research/web-search/SEARCH_LOG.md
- research/web-search/QUERY_REGISTRY.md
- research/web-search/SOURCE_REGISTRY.md
- research/web-search/NOVELTY_CHECKS.md
- corpus/papers.csv
- corpus/theorems.csv
- bibliography/references.bib

---

## Searcher's bottom line

D14 is **not** a uniformly immature branch.

\[
\boxed{
\text{Fixed distributed order: mature linear/operator + substantial Lyapunov theory}
}
\]

while

\[
\boxed{
\text{variable/state-dependent/distributed-variable order:}
\;
\text{global dynamical-systems theory remains thin}
}
\]

The strongest research frontier is not “use variable/distributed order in an ecological model.”

It is:

> **construct and analyze global nonlinear dynamics for evolving memory operators — process/cocycle state spaces, attractors, persistence/extinction and rigorous nonhyperbolic bifurcation — while proving that the added memory law is structurally distinguishable and scientifically meaningful.**

This branch should remain in the opportunity portfolio as a genuine domain frontier, with **moderate-to-low current Double-Allee proximity** unless a stronger mechanistic bridge is established.
