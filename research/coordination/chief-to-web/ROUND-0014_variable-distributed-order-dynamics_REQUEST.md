# ROUND-0014 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — INDEPENDENT DOMAIN BRANCH / VARIABLE & DISTRIBUTED ORDER  
**Status:** OPEN

## Topic

> **Dynamical-systems and stability theory for variable-order and distributed-order fractional differential equations**

This round deliberately expands a weakly mapped domain branch.

Do not search for examples only. Reconstruct theorem architecture.

## Central question

For systems where the memory operator itself changes through time/state/order distribution, what rigorous dynamical-system and stability theory exists beyond existence/uniqueness and model-specific numerics?

Distinguish:

1. variable-order (alpha=alpha(t));
2. state-dependent order (alpha=alpha(x,t));
3. distributed-order operators with fixed weight (c(alpha));
4. time-varying or state-dependent order distributions (c(alpha,t,x));
5. multi-term finite mixtures;
6. uncertain-order boxes from ROUND-0013.

These are not interchangeable.

## Mandatory baseline

At minimum inspect and citation-expand:

- distributed-order nonlinear asymptotic stability, DOI `10.1016/j.cnsns.2017.01.020`;
- distributed-order nonlinear Prabhakar stability, DOI `10.1155/2020/1896563`;
- review `Applications of Distributed-Order Fractional Operators`;
- variable-order Caputo existence/stability literature;
- 2026 non-autonomous variable-order FDE paper, DOI `10.1016/j.cam.2025.117235`.

## Search block A — state-space / semigroup architecture

For each operator class determine:

- is there a well-defined semiflow/process/cocycle?
- what is the state space?
- is memory encoded by a history state?
- is the process autonomous or nonautonomous?
- does time-varying order destroy semigroup structure?
- is there an equivalent Volterra kernel formulation?
- is there a Markovian/diffusive lift?

This is central.

## Search block B — linear stability

Map strongest results for:
- BIBO stability;
- asymptotic stability;
- exact/N&S criteria;
- characteristic equations;
- distributed-order transfer functions;
- variable-order linear systems.

Distinguish exact results from sufficient tests.

## Search block C — nonlinear stability

Search:
- Lyapunov stability;
- asymptotic stability;
- Mittag-Leffler-type stability;
- global stability;
- converse results;
- comparison principles;
- invariant regions.

Determine whether results are:
- fixed-distribution only;
- time-varying order;
- state-dependent order;
- operator-specific.

## Search block D — attractors / dissipativity / global dynamics

Search for:
- global attractors;
- pullback attractors;
- random attractors;
- absorbing sets;
- asymptotic compactness;
- omega-limit sets;
- gradient-like structure.

Key question:

> does variable/distributed order have a mature global dynamical-systems theory comparable to fixed-order Caputo?

## Search block E — bifurcation / nonhyperbolic dynamics

Search rigorously for:
- saddle-node;
- pitchfork;
- transcritical;
- cusp;
- Hopf semantics;
- center manifolds;
- normal forms;
- Lyapunov–Schmidt;
- attractor bifurcation.

Do not treat numerical parameter sweeps as theorem-level bifurcation theory.

## Search block F — persistence/extinction

Search:
- permanence;
- persistence;
- extinction;
- positivity;
- invariant cones;
- threshold dynamics;
- ecological variable-order/distributed-order models.

Determine whether general threshold/persistence theory exists or only model-specific results.

## Search block G — operator variation as a dynamical variable

For (alpha(t)) or (alpha(x,t)), ask:

- is the order prescribed externally?
- can it be treated as another state variable?
- does that create a skew-product or nonautonomous system?
- when is order adaptation itself stable?
- does the operator variation introduce new bifurcation mechanisms, or only time-varying coefficients in disguise?

## Search block H — distributed-order spectral structure

For

[
int_0^1 c(alpha) D^alpha x(t),dalpha = Ax(t),
]

map:
- exact stability conditions;
- dependence on support/shape of (c);
- positivity of (c);
- finite-mixture approximations;
- whether different weight distributions with same moments can have different stability.

## Search block I — Double/Multiple Allee relevance

Search carefully, but do not force a bridge.

Questions:

### I1
Are variable-/distributed-order Allee models already common?

### I2
Does changing the memory distribution alter equilibrium locations if the RHS is fixed?

### I3
Can memory-order variation alter stability, transient threshold crossing, basin geometry, or persistence?

### I4
Is there a mathematically natural Double-Allee problem where multiple mechanisms correspond to different memory scales/distributions?

### I5
Would a distributed-order model be biologically more defensible than assigning arbitrary separate (alpha_i)?

## Search block J — identifiability / model distinguishability

Search whether:
- variable order;
- distributed order;
- multi-term order;
- fixed fractional order

can be structurally or practically distinguished from observed trajectories.

For applied research, a theoretically rich model that cannot be distinguished from simpler memory models may be a weak target.

## Search block K — strongest killer tests

Downgrade the branch if:

1. general process/semiflow theory already covers variable/distributed order;
2. nonlinear stability is already mature beyond Lyapunov sufficient criteria;
3. center-manifold/bifurcation theory is already broad;
4. persistence/threshold theory already exists at generality;
5. Double-Allee connection is merely decorative.

## Required verdicts

Return separate verdicts for:

1. state-space/process architecture;
2. linear exact stability;
3. nonlinear stability;
4. attractor/global dynamics;
5. bifurcation/nonhyperbolic theory;
6. persistence/extinction theory;
7. variable-order versus distributed-order distinction;
8. identifiability/model distinguishability;
9. Double-Allee proximity;
10. strongest unresolved theorem-level frontiers.

Use:
- DIRECT PRIOR;
- SUBSTANTIAL PARTIAL THEORY;
- CLOSE PRIOR ART;
- NO RESOLVING RESULT FOUND;
- AMBIGUOUS / MORE SEARCH REQUIRED.

## Required deliverables

Create:

`research/coordination/web-to-chief/ROUND-0014_variable-distributed-order-dynamics_RETURN.md`

and:

`research/web-search/2026-09-28_variable-distributed-order-dynamics.md`

Update corpus, bibliography and provenance registries as warranted.

## Completion criterion

The Chief should be able to decide whether variable/distributed-order dynamics contains:

- a mature theory;
- only operator-level/existence results;
- a real global dynamical-systems frontier;
- a meaningful Double-Allee-adjacent opportunity;
- or mainly modeling complexity without sufficient theorem depth.

Do not select a final project winner.
