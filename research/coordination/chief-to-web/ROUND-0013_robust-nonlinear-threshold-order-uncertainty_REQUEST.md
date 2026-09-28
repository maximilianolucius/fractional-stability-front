# ROUND-0013 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — INDEPENDENT FRONTIER / ROBUST NONLINEAR THRESHOLDS  
**Status:** OPEN

## Topic

> **Robust nonlinear persistence/extinction and threshold geometry under parameter and fractional-order uncertainty**

This round deliberately moves away from the heavily searched basin-memory branch.

The goal is to test an independent candidate frontier inside:

> **Dynamical Systems and Stability Theory — Fractional Differential Equations**

with very high relevance to strong/Double Allee dynamics.

Do not assume a gap exists.

## Central question

For a nonlinear positive fractional system

[
{}^C D^{alpha}x=f(x;	heta),
]

or a genuinely incommensurate system

[
{}^C D^{alpha_i}x_i=f_i(x;	heta),
]

with

[
alphainmathcal A,
qquad
	hetainTheta,
]

what rigorous theory exists for conclusions that hold **uniformly over the uncertainty family**, especially:

- extinction;
- survival;
- permanence/persistence;
- multistability;
- basin inclusion;
- threshold existence;
- threshold robustness;
- tipping/bifurcation under uncertainty?

## Why this is not a generic robust-control search

A large literature already treats:
- robust linear stability;
- LMIs;
- (H_infty) control;
- synchronization;
- uncertain chaotic systems;
- interval matrices;
- uncertain controllers.

Those results are relevant prior art but do not automatically answer ecological qualitative questions.

The target is **uncontrolled nonlinear global dynamics and threshold structure**.

## Search block A — linear/order-uncertainty baseline

Map strongest exact/N&S or near-exact results for:

- uncertain coefficients;
- interval matrices;
- uncertain fractional order;
- simultaneous parameter + order uncertainty;
- incommensurate uncertain orders.

At minimum include/citation-expand around:
- Senol et al. 2014, DOI `10.1016/j.isatra.2013.09.004`;
- robust interval/order results already present in the repository;
- incommensurate interval/time-varying uncertainty literature;
- Zhang–Lu-type mixed-uncertainty results from prior rounds.

Purpose:

> establish what is already mature before examining nonlinear threshold dynamics.

## Search block B — nonlinear robust stability without control

Search:
- robust stability nonlinear fractional system uncertainty;
- uncertain nonlinear Caputo systems;
- parameter-dependent Lyapunov stability;
- uniform Mittag-Leffler stability;
- robust attractivity;
- differential inclusions / set-valued fractional systems;
- uncertain-order nonlinear systems.

Separate:
- uncontrolled system;
- controlled/stabilized system;
- synchronization problem;
- observer design.

Do not treat controller-dependent robustness as a theorem about the open-loop dynamics.

## Search block C — uniformity in fractional order

Search for theorems of the form:

[
orall alphain[alpha_-,alpha_+]:
quad 	ext{property }P(alpha)
]

where (P) is:
- asymptotic stability;
- global stability;
- invariance;
- boundedness;
- persistence;
- extinction;
- basin inclusion.

Determine whether order-robust nonlinear conclusions exist beyond local spectral-sector tests.

## Search block D — robust permanence / persistence

Use mature classical ecology as a killer baseline.

At minimum inspect/citation-expand:
- Schreiber 2000, DOI `10.1006/jdeq.1999.3719`;
- Garay & Hofbauer 2003, DOI `10.1137/S0036141001392815`;
- Hofbauer–Schreiber robust permanence/invasion literature from ROUND-0009.

Questions:

### D1
Are there fractional analogues of (C^r)-robust permanence?

### D2
Are perturbations allowed in:
- vector field;
- fractional order;
- memory kernel;
- initial-memory state?

### D3
Do invariant-measure / invasion-rate criteria exist for fractional memory-state dynamics?

### D4
Can classical robust-persistence theorems be transferred directly after a Volterra/history-state lift?

This is a strong subsumption test.

## Search block E — robust extinction/survival in Allee systems

Search specifically:
- Allee effect parameter uncertainty;
- robust Allee threshold;
- uncertain Allee threshold;
- interval ecological models with Allee;
- fractional Allee uncertainty;
- uncertain fractional predator-prey Allee;
- persistence/extinction under fractional-order uncertainty.

Distinguish:
- uncertainty in ecological parameters (	heta), which can change equilibrium locations;
- uncertainty only in (alpha), which does not change (f(x,	heta)=0) when RHS fixed;
- combined uncertainty.

## Search block F — robust threshold geometry

For strong/Double Allee, investigate set-valued questions such as:

### F1
Does every admissible model in ((alpha,	heta)inmathcal A	imesTheta) possess the same number/type of extinction/survival equilibria?

### F2
Is there a common robust survival region (S) such that all admissible systems starting in (S) survive?

### F3
Is there a common robust extinction region (E)?

### F4
Can one bound the basin separator uniformly over uncertainty?

### F5
Can a parameter/order uncertainty family change from bistable to monostable?

### F6
Are there exact, sharp or only sufficient robust-threshold conditions?

Search analogous mathematics in:
- robust invariant sets;
- viability kernels;
- uncertain dynamical systems;
- differential inclusions;
- set-oriented dynamics;
- reachability;
- interval ODE/FDE theory.

## Search block G — uncertain bifurcation / catastrophe

Search:
- robust bifurcation under uncertainty;
- interval bifurcation;
- uncertain saddle-node/cusp;
- bifurcation with uncertain parameters;
- fractional-order uncertain bifurcation.

Determine whether robust catastrophe/threshold-set theory already handles families of Allee-like systems.

## Search block H — order uncertainty as biological memory uncertainty

Do not assume (alpha) is known exactly.

Search:
- confidence intervals for fractional order;
- parameter/order identifiability;
- uncertainty propagation from estimated (alpha) to stability;
- robust conclusions when (alpha) lies in an interval.

For Double Allee, ask:

> can one make a survival/extinction conclusion that is valid despite uncertainty in the inferred memory order?

This is scientifically stronger than merely plotting several chosen (alpha) values.

## Search block I — incommensurate uncertainty

For

[
oldsymbolalpha=(alpha_1,dots,alpha_n)
]

search:
- box uncertainty in orders;
- robust multi-order stability;
- uniform nonlinear results;
- order-by-order monotonicity;
- uncertain-order basin/persistence results.

This may be especially natural for multi-species Double Allee systems.

## Search block J — adjacent robust-dynamics literature

Search non-fractional mathematics that might already subsume the problem:

- differential inclusions;
- control-invariant/robust invariant sets;
- viability theory;
- robust permanence;
- random/parametric dynamical systems;
- set-valued semiflows;
- monotone uncertain systems;
- Conley/Morse robust persistence;
- structural stability.

If a general theorem applies essentially verbatim after the Caputo lift, report that as a killer.

## Strong killer criteria

The candidate should be downgraded if any of the following is found:

1. a general nonlinear Caputo theorem gives robust persistence/extinction uniformly over parameter and order uncertainty;
2. a standard differential-inclusion/viability theorem applies directly and leaves only routine verification;
3. robust permanence theory transfers essentially verbatim to the Caputo history state;
4. existing fractional Allee papers already give rigorous uncertainty-uniform basin/threshold results.

## Required verdicts

Return separate verdicts for:

1. linear/order-uncertainty baseline;
2. nonlinear open-loop robust stability;
3. uniform-in-order nonlinear theory;
4. robust fractional permanence/persistence;
5. robust extinction/survival thresholds;
6. robust basin/invariant-region theory;
7. uncertain bifurcation/catastrophe;
8. incommensurate order uncertainty;
9. Double-Allee-specific prior art;
10. classical-theory subsumption.

Use:
- DIRECT PRIOR;
- SUBSTANTIAL PARTIAL THEORY;
- CLOSE PRIOR ART;
- NO RESOLVING RESULT FOUND;
- AMBIGUOUS / MORE SEARCH REQUIRED.

## Candidate formulation discipline

If a residual survives, formulate it at theorem level.

Preferred form:

> “No result resolving X uniformly over uncertainty class Y was identified under assumptions Z.”

Avoid:

> “robust fractional ecology is unexplored.”

## Required deliverables

Create:

`research/coordination/web-to-chief/ROUND-0013_robust-nonlinear-threshold-order-uncertainty_RETURN.md`

and:

`research/web-search/2026-09-28_robust-nonlinear-threshold-order-uncertainty.md`

Update corpus, theorem map inputs, bibliography and search registries as warranted.

## Completion criterion

The Chief should be able to decide whether robust nonlinear threshold/persistence theory under parameter/order uncertainty is:

- already mature;
- largely a standard viability/differential-inclusion translation;
- only model-specific;
- or a genuinely fertile fractional frontier naturally close to Double/Multiple Allee.

Do not select a final project winner.
