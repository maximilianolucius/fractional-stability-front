# 2026-09-28 — Fractional Uniform-Persistence / Permanence Falsification

**Round:** ROUND-0009  
**Request:** research/coordination/chief-to-web/ROUND-0009_fractional-uniform-persistence-falsification_REQUEST.md  
**Role:** WEB SEARCHER

## Executive result

No direct abstract theorem was identified that gives, for a broad class of positive Caputo systems, the analogue of Hale–Waltman / Thieme / Smith–Thieme persistence theory in terms of invariant extinction sets, boundary repellers, acyclicity, persistence functions, invasion rates, robust persistence and interior attractors.

The strongest subsumption threat is nevertheless substantial: autonomous Caputo FDEs can be represented as singular Volterra equations generating an infinite-dimensional continuous semiflow on a function space, and recent work supplies dissipativity and attractor theory on that state space.

Therefore the residual question is not whether Caputo dynamics has a dynamical-system representation. It is whether ecological persistence theory can be transferred to that memory-state semiflow with the correct positive cone, extinction boundary, persistence function, perturbation topology, invasion quantities and relation back to the physical trajectory x(t).

For strong/Double Allee systems, ordinary global uniform persistence of every positive initial state is structurally mismatched because the defining bistability permits low positive states to converge to extinction. The natural bridge is conditional / basin-relative / threshold-relative persistence.

## 1. Terminology warning

Cresson & Szafrańska (2017), DOI 10.1016/j.cnsns.2016.07.016, use “fractional persistence problem” for preservation under fractional embedding of positivity, order preservation, equilibria and stability. This is not ecological uniform persistence/permanence.

Their positivity/order theory is relevant as prerequisite structure only.

## 2. Mature abstract persistence theory

Butler–Freedman–Waltman (1986), DOI 10.1090/S0002-9939-1986-0822433-4, provides weak-to-uniform persistence criteria.

Hale–Waltman (1989), DOI 10.1137/0520025, is the central killer threat. It treats persistence for an asymptotically smooth C0-semigroup on an infinite-dimensional state space and gives boundary-flow criteria, with dissipativity/global-attractor structure.

Thieme (2000), DOI 10.1016/S0025-5564(00)00018-3, develops uniform strong persistence for nonautonomous semiflows and applies it to retarded functional differential equations.

Magal–Zhao (2005), DOI 10.1137/S0036141003439173, develops interior global-attractor consequences for uniformly persistent dynamical systems on complete metric spaces.

Faria (2016), DOI 10.1007/s10884-015-9462-x, gives persistence/permanence results for broad cooperative infinite-delay FDEs.

Fonda–Gidoni (2015), DOI 10.1016/j.na.2014.10.011, gives a necessary-and-sufficient permanence theorem for local dynamical systems on suitable topological spaces.

Conclusion: persistence theory is already infinite-dimensional, history-aware and flexible with respect to extinction subsets. Any fractional novelty must lie in the Caputo-to-persistence transfer.

## 3. Caputo history-state semiflow

Doan & Kloeden (2021), DOI 10.1007/s10013-020-00464-6, consider

\[
{}^C D^\alpha_{0+}x(t)=g(x(t)), \qquad 0<\alpha<1,
\]

and embed the corresponding singular Volterra equation into

\[
\mathfrak C=C(\mathbb R_+,\mathbb R^d)
\]

with compact-open topology.

For general f in the function space,

\[
x(t)=f(t)+\int_0^t a(t,s)g(x(s))\,ds.
\]

The physical Caputo initial datum x(0)=x0 corresponds to the constant function f0(t)=x0.

They construct operators T_tau on the function space and prove a continuous semigroup property. Thus the general statement “Caputo FDEs have no semiflow” is false after a legitimate memory-state enlargement.

The important subtlety is that the full function space is larger than the physical constant-initial-data manifold. The latter is generally not invariant under the history semiflow.

The authors also note that attractors may contain nonconstant functions and physical omega-limit points are recovered through evaluation at zero. Therefore the physical state and the full memory-state attractor cannot simply be identified.

## 4. Modern attractor machinery

Cui & Kloeden (2024), DOI 10.1063/5.0214041, construct a nonautonomous skew-product semiflow on a weighted continuous-function space times a compact driving base and obtain a bounded closed attractor under uniform dissipativity.

Cui, Kloeden & Xin (2026), arXiv:2607.05799, construct a compact absorbing set and an attractor for the autonomous Volterra semiflow and prove global Hölder regularity of attractor functions.

Doan, Kloeden & Tuan (2026), DOI 10.1007/978-3-032-05511-8, consolidates Caputo semidynamical systems, dissipativity and attractors.

Hence lack of compactness/dissipativity infrastructure is not a defensible broad gap.

## 5. Why history-space subsumption is not automatic

To invoke Hale–Waltman or Smith–Thieme one needs a persistence setup

\[
X_0=\{f\in X:\rho(f)>0\},\qquad
\partial X_0=\{f:\rho(f)=0\},
\]

with suitable forward invariance and attractor/compactness hypotheses.

For all-species persistence a natural current-state functional is

\[
\rho(f)=\min_i f_i(0).
\]

But rho^{-1}(0) is not automatically the invariant extinction boundary of the full Volterra semiflow.

The correct object is closer to the maximal invariant subset

\[
M_\partial=\{f\in\partial X_0:T_t f\in\partial X_0\ \forall t\ge0\}.
\]

A general Caputo ecological theory must prove:
- positivity of the relevant memory-state subset;
- forward invariance of X0;
- characterization of the invariant boundary;
- compatibility of boundary dynamics with ecological extinction;
- equivalence between persistence in memory space and physical component lower bounds.

This transfer was not found as a general theorem.

## 6. Direct fractional persistence is model-specific

Abbas et al. (2016), DOI 10.1007/s12591-014-0219-5, proves existence, uniqueness, permanence, persistence and stability for one fractional phytoplankton model. The method is advertised as potentially reusable but is not an abstract boundary-repeller framework.

Lu et al. (2023), DOI 10.1016/j.isatra.2022.12.006, proves model-specific uniform persistence for a fractional SEIHRDP migration model under R0>1.

These sources show that the words persistence/permanence already occur in applied fractional ecology/epidemiology. They do not supply an abstract Caputo persistence architecture.

Because a general Caputo system need not generate a finite-dimensional semiflow, any application of classical semiflow persistence results on the physical state must explicitly justify its state-space/semigroup assumptions.

## 7. Robust persistence and invasion criteria

Classical ordinary theory is mature:
- Garay & Hofbauer (2003), DOI 10.1137/S0036141001392815;
- Hofbauer & Schreiber (2010), DOI 10.1016/j.jde.2009.11.010;
- Patel & Schreiber (2018), DOI 10.1007/s00285-017-1187-5;
- Hofbauer & Schreiber (2022), DOI 10.1007/s00285-022-01815-2.

These develop robust permanence using average Lyapunov functions, invariant measures, Lyapunov/invasion exponents, Morse decompositions and invasion graphs.

No general Caputo theorem was found that:
- defines invasion rates over invariant measures of the memory-state boundary;
- relates their signs to robust permanence;
- treats perturbations of fractional order/kernel/vector field;
- gives an invasion-graph or acyclicity criterion.

This is one of the strongest surviving D11 subproblems.

## 8. Double/Multiple Allee changes the persistence notion

A strong Allee system intentionally contains an extinction basin containing strictly positive states. Therefore global uniform persistence of all positive initial conditions cannot hold.

Roth & Schreiber (2014), DOI 10.1080/17513758.2014.962631, explicitly studies conditional persistence in stochastic models with Allee effects. Thus conditional persistence is itself established terminology.

The natural fractional question is instead:

> identify a threshold-/basin-defined positively invariant subset of a Caputo memory state and prove persistence there, with a valid lower-bound interpretation for the physical population.

Classical persistence theory already permits persistence relative to a chosen persistence function or interior/boundary pair. The fractional novelty, if any, lies in constructing that pair in memory space and proving physical equivalence.

## 9. Verdicts

### Abstract fractional persistence theory
**NO RESOLVING ABSTRACT RESULT FOUND; PARTIAL/MODEL-SPECIFIC PRIOR ART EXISTS.**

### History-space subsumption
**PARTIAL — STRONG SUBSUMPTION THREAT, NOT A DIRECT KILL.**

### Boundary invariance
**UNRESOLVED IN GENERAL CAPUTO ECOLOGICAL FORM.**

### Compactness/dissipativity
**SUBSTANTIALLY COVERED UNDER MODERN CAPUTO SEMIFLOW HYPOTHESES.**

### Robust fractional persistence
**NO GENERAL RESULT FOUND.**

### General fractional invasion criteria
**NO RESOLVING RESULT FOUND.**

### Double-Allee relevance
**REQUIRES REFORMULATION.** Global uniform persistence is structurally mismatched; basin-/threshold-relative persistence is the appropriate bridge.

### Q1 research-opportunity potential
**CREDIBLE HIGH-INFORMATION CANDIDATE — NOT CERTIFIED / NOT SELECTED.**

The best narrowed formulation is:

> Persistence theory for positive Caputo systems on the Volterra memory state, with explicit transfer to physical populations and basin-relative variants for strong-Allee dynamics.

## Main killer risk

A careful construction of the positive invariant history space may show that the main persistence theorem follows almost verbatim from Hale–Waltman/Smith–Thieme.

## Main reason the candidate survives

No source found carries out that general transfer, and the physical constant-initial-data manifold versus full memory-state semiflow, invariant extinction boundary, robust perturbations and invasion quantities are substantive issues rather than terminology.
