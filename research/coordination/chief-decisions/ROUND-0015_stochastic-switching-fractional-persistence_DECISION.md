# ROUND-0015 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** `research/coordination/web-to-chief/ROUND-0015_stochastic-switching-fractional-persistence_RETURN.md`  
**Disposition:** ACCEPT — D8 RETAINED AS A HIGH-VALUE ALLEE-ADJACENT FRONTIER; MOVE TO CROSS-CANDIDATE COMPARISON

## 1. Executive decision

ROUND-0015 establishes that stochastic/time-fractional dynamics is neither empty nor immature in broad form.

Direct or substantial prior art already covers:

- stochastic Caputo/Volterra well-posedness;
- moment/pathwise stability;
- positivity/invariance machinery;
- Hilbert-space Markovian lifts for fractional stochastic Volterra kernels;
- invariant/stationary measures in important classes;
- stochastic Volterra large deviations;
- ordinary stochastic Allee persistence/extinction/tipping;
- switched fractional equilibrium stability with memory reset.

Therefore broad claims such as:
- “stochastic fractional systems lack state-space theory”;
- “large deviations are missing”;
- “stochastic Allee persistence is unexplored”;
- “randomly switched fractional stability is new”

are false.

## 2. Strongest surviving D8 residuals

### D8-A — stochastic fractional persistence/extinction

Search-qualified residual:

> no general theorem architecture was identified for persistence, permanence, extinction, invasion/boundary criteria, or conditional persistence in positive time-fractional stochastic systems on the appropriate lifted memory state.

This is stronger than moment stability of one equilibrium.

### D8-B — rare extinction / basin exit in multistable positive systems

General stochastic Volterra LDP machinery exists.

The unresolved ecological layer is:

- identify extinction/survival basins on the lifted memory state;
- derive quasipotential/action minimizers;
- prove exit-time/transition-probability asymptotics;
- understand dependence on fractional order;
- specialize to strong/Double-Allee multistability.

Thus the gap is downstream of LDP, not LDP itself.

### D8-C — persistent-memory random switching

Reset-memory switched fractional systems are direct prior.

O'Regan & Hristova 2026, DOI `10.3390/fractalfract10090616`, explicitly reset the Caputo lower terminal at each random switch and identify the fixed-lower-terminal case as a distinct future problem.

The residual is:

> nonlinear random switching with a fixed original lower terminal, inherited memory across regimes, a correct history-state process, and global persistence/extinction or basin theory.

This is structurally sharper than generic switched fractional stability.

## 3. Important stochastic-Volterra prior

Hamaguchi 2024, DOI `10.1016/j.spa.2024.104482`, gives Hilbert-space Markovian lifts for stochastic Volterra equations with completely monotone kernels, including fractional power-law kernels in the relevant integrability regime.

Bianchi et al. 2026, DOI `10.1007/s40072-026-00428-w`, develops stationary/invariant measures and limit theorems for such lifted stochastic Volterra processes.

Therefore future novelty must not rest on the mere need for a memory-state lift.

## 4. Important order restriction

For the standard Brownian stochastic convolution using the same kernel

[
K(t)=rac{t^{alpha-1}}{Gamma(alpha)},
]

square integrability near zero imposes the standard regime

[
alpha>rac12.
]

This matters for ecological modeling because deterministic Caputo population papers often range over all (0<alpha<1).

A future stochastic-Allee project must specify the noise/operator convention carefully.

## 5. Double-Allee assessment

D8 is among the most naturally Double-Allee-adjacent branches mapped so far because:

- Allee dynamics is intrinsically multistable;
- extinction is an actual attractor/outcome;
- stochastic forcing naturally induces basin exits;
- persistence is conditional rather than global;
- environmental switching has direct ecological meaning.

But “add stochastic noise to Double Allee” is not enough.

Ordinary stochastic Allee persistence/extinction and noise-induced tipping are mature prior art.

The fractional contribution must concern the interaction between:
- nonlocal memory state;
- positive multistability;
- stochastic exit/persistence;
- or persistent-memory switching.

## 6. Candidate status

**RETAIN — HIGH DOUBLE-ALLEE PROXIMITY / HIGH FDE CENTRALITY / MODERATE NOVELTY CONFIDENCE / HIGH MATHEMATICAL DEPTH.**

D8 should now compete directly against the best surviving candidates rather than receive another immediate depth round.

## 7. Why the project now changes phase

After ROUND-0008 through ROUND-0015 the project has sufficiently broadened beyond its original Double-Allee-heavy bias.

The portfolio now contains multiple independently sourced candidate frontiers.

Further blind breadth expansion has diminishing value.

The next task is not to select a winner immediately.

It is to perform a hostile, like-for-like comparison of the strongest surviving candidates and remove those whose novelty, theorem depth, or Double-Allee relevance does not survive side-by-side scrutiny.

## 8. Candidates entering comparative audit

The comparative round must include at least:

1. **DA-MEMORY-FIBER**  
   reachable same-present fiber intersecting distinct asymptotic basins in positive Caputo multistability;

2. **ROBUST-THRESHOLD**  
   uncertainty-uniform survival/extinction regions and basin-relative persistence under simultaneous parameter/order uncertainty;

3. **STOCH-PERSISTENCE-EXIT**  
   stochastic fractional persistence/extinction and rare basin exit in positive multistable systems;

4. **PERSISTENT-SWITCHING**  
   random switching with fixed lower terminal / persistent memory and extinction-survival dynamics;

5. **NONHYPERBOLIC-MEMORY**  
   singular-memory-state or incommensurate nonhyperbolic bifurcation beyond existing center-manifold/LS theory;

6. **MECHANISM-PERSISTENCE-FILTER**  
   persistence-filtered mechanism composition in Multiple/Double Allee;

7. **VO-DO-GLOBAL**  
   variable/distributed-order global dynamics as a mathematically deep but weaker Double-Allee benchmark.

## 9. Next action

Open:

`ROUND-0016_cross-candidate-adversarial-comparison_REQUEST.md`

This round is explicitly comparative.

No theorem proving follows from this decision.
