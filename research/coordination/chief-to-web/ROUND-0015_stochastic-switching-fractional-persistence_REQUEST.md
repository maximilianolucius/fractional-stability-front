# ROUND-0015 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0 — INDEPENDENT DOMAIN BRANCH / STOCHASTIC & SWITCHING DYNAMICS  
**Status:** OPEN

## Topic

> **Stochastic, randomly switched, and hybrid dynamics for time-fractional differential systems, with emphasis on persistence/extinction and Allee thresholds**

This round maps D8.

The project domain remains:

> **Dynamical Systems and Stability Theory — Fractional Differential Equations**

Do not select a project winner.

## 1. Mandatory terminology firewall

Before searching, separate at least four literatures.

### S1 — time-fractional stochastic differential equations

Examples:
[
{}^C D^alpha X(t)=f(X(t))+	ext{stochastic forcing}.
]

The time derivative/order is fractional.

### S2 — ordinary differential/evolution equations driven by fractional Brownian motion

The adjective “fractional” belongs to the noise, not the derivative.

These are adjacent stochastic/RDS theory but must not be counted as direct time-fractional FDE prior art.

### S3 — stochastic systems with spatial fractional operators

For example fractional Laplacians in SPDEs.

Again adjacent, not direct time-fractional ODE/FDE evidence.

### S4 — randomly switched / impulsive fractional systems

Fractional deterministic dynamics operate between random or switching events.

Record whether the fractional lower terminal:
- persists globally;
- resets at each switch;
- changes operator;
- changes order.

This modeling choice is mathematically decisive.

Do not merge these classes in theorem counts.

## 2. Central questions

For genuine time-fractional stochastic/switching systems, what rigorous theory exists for:

- well-posedness;
- positivity;
- moment stability;
- almost-sure stability;
- invariant probability measures;
- random dynamical systems;
- random/pullback attractors;
- stochastic permanence/persistence;
- extinction;
- noise-induced tipping;
- switching-induced threshold changes;
- basin probabilities;
- large deviations / rare extinction?

Which results are general and which are model-specific?

## 3. Baseline ordinary stochastic Allee theory

Map mature non-fractional stochastic Allee mathematics as a killer baseline.

At minimum inspect/citation-expand:
- stochastic logistic / strong-Allee diffusion models;
- stochastic persistence/extinction criteria;
- quasi-stationary distributions where relevant;
- noise-induced tipping;
- recent Allee persistence/extinction work such as Granados & Valencia 2026, DOI `10.5614/cbms.2026.9.1.3`;
- recent noise-induced tipping work around Allee multistability.

Purpose:

> identify what is already standard stochastic ecology before adding fractional memory.

## 4. Time-fractional stochastic equation architecture

Search rigorously for formulations of Caputo-type stochastic FDEs.

For each major formulation record:

- exact equation/integral form;
- interpretation of the stochastic integral;
- order range;
- adaptedness;
- existence/uniqueness;
- Markov/non-Markov status;
- restart/history state;
- whether a random dynamical system/cocycle is constructed.

Search:
- Caputo stochastic differential equation;
- fractional stochastic differential equation with Brownian motion;
- stochastic Volterra equation with power-law kernel;
- stochastic Volterra memory equation;
- Caputo stochastic semiflow/cocycle;
- random dynamical system time-fractional.

## 5. Random dynamical systems and invariant measures

For genuine time-fractional systems, determine whether there are:

- Markovian/history-state lifts;
- random dynamical systems;
- cocycles;
- invariant measures;
- random attractors;
- pullback attractors;
- ergodicity;
- stationary distributions.

Do not import results from fBm-driven ordinary equations or spatial-fractional SPDEs without labeling them adjacent.

## 6. Stability taxonomy

Separate:
- finite-time stability;
- p-th moment stability;
- mean-square stability;
- almost-sure stability;
- stochastic Mittag-Leffler stability;
- asymptotic stability in probability;
- pathwise stability.

Determine theorem strength and whether the result concerns:
- zero equilibrium;
- a single equilibrium;
- global multistable dynamics.

## 7. Positivity and ecological admissibility

For population models, search whether stochastic time-fractional formulations preserve:

- nonnegativity;
- strict positivity;
- boundedness/nonexplosion;
- biological state constraints.

This is critical.

A stochastic forcing convention that allows negative populations without a proper boundary treatment is weak ecological prior art.

## 8. Persistence and extinction

Search for general time-fractional stochastic theorems on:

- stochastic permanence;
- persistence in mean/probability;
- almost-sure persistence;
- extinction a.s.;
- extinction probability;
- conditional persistence;
- occupation measures;
- invasion rates;
- boundary behavior.

Distinguish general theory from one specific epidemic/ecological model.

## 9. Allee effect

Search:
- stochastic fractional Allee;
- time-fractional stochastic Allee;
- Caputo stochastic predator-prey Allee;
- Double Allee + stochastic + fractional;
- noise + memory + Allee;
- random switching + Allee + fractional.

At minimum inspect:
- direct fractional Allee papers already in the corpus;
- Granados & Valencia 2026 as ordinary stochastic Allee baseline;
- any 2025–2026 direct stochastic+fractional Allee papers.

Determine whether there is a theorem-level interaction between:
- nonlocal memory;
- environmental noise;
- extinction threshold;
- persistence probability.

## 10. Noise-induced tipping versus deterministic basin geometry

Search whether noise can induce transitions between extinction/survival basins in time-fractional systems.

Separate:

1. deterministic basin boundary;
2. stochastic exit from a basin;
3. quasi-potential / large-deviation barrier;
4. finite-time crossing probability;
5. noise-induced shift of an empirical threshold.

Do not call a stochastic transition a movement of the deterministic Allee equilibrium threshold.

## 11. Large deviations / rare extinction

This may be a high-value frontier.

Search for:
- Freidlin–Wentzell large deviations for stochastic Volterra equations;
- large deviations for stochastic fractional differential equations;
- exit-time asymptotics;
- quasipotential;
- metastability;
- rare-event extinction.

Determine whether power-law memory fundamentally changes:
- action functionals;
- Markov augmentation;
- extinction-time scaling.

If the theory already exists for general stochastic Volterra equations, identify whether Caputo ecological systems are routine instances.

## 12. Random switching

Inspect at minimum:

O'Regan & Hristova 2026, DOI `10.3390/fractalfract10090616`.

This source uses:
- random Erlang switching times;
- nonlinear fractional dynamics between switches;
- a changing lower limit at switching times;
- p-moment Lyapunov stability.

Critical questions:

### R1
What changes if the fractional memory is **not reset** at a switch?

### R2
Does random switching of vector fields/orders with persistent memory generate a well-defined history-state process?

### R3
Are stability results mostly sufficient equilibrium criteria, or is there global basin/persistence theory?

### R4
Can regime switching cause extinction/survival transitions in Allee systems?

## 13. Memory reset as a modeling/theorem issue

This is potentially important.

In a switched fractional system, compare:

### Reset-memory model
At switching time (t_k), the new Caputo derivative uses lower terminal (t_k).

### Persistent-memory model
All regimes retain memory from the original lower terminal (t_0), with switching only in the RHS/operator parameters.

These are different dynamical systems.

Search whether:
- both are treated rigorously;
- one has semigroup/cocycle structure;
- stability/persistence conclusions differ;
- ecological interpretation favors one.

Do not assume resetting memory is innocuous.

## 14. Hybrid/impulsive systems

Map:
- impulsive Caputo systems;
- switching;
- Markovian regime switching;
- random impulses;
- event-triggered changes.

Record whether the memory is reset or carried across impulses.

Search for global persistence/extinction results rather than only Hyers–Ulam stability.

## 15. Double-Allee proximity

The strongest possible bridge would not be “add noise to a Double-Allee model.”

It would be a theorem answering something like:

> how does nonlocal memory alter stochastic extinction risk, switching-induced survival, or basin-exit structure in a genuinely bistable Allee system?

Assess whether such a theorem is already known.

## 16. Killer tests

Downgrade the branch if:

1. general stochastic Volterra/RDS theory already gives the needed results directly for Caputo kernels;
2. persistence/extinction theory for stochastic time-fractional positive systems is already mature;
3. direct stochastic-fractional Double-Allee prior already resolves threshold/extinction questions rigorously;
4. the only gap is caused by ambiguous/nonphysical noise formulations;
5. random switching adds no mathematics beyond known hybrid Volterra systems.

## 17. Required verdicts

Return separate verdicts for:

1. stochastic time-fractional state architecture;
2. positivity/well-posedness;
3. moment/pathwise stability;
4. RDS/invariant measure/random attractor theory;
5. stochastic persistence/extinction;
6. large deviations / basin exit;
7. switching with memory reset;
8. switching with persistent memory;
9. direct stochastic-fractional Allee prior;
10. Double-Allee proximity;
11. strongest theorem-level residuals.

Use:
- DIRECT PRIOR;
- SUBSTANTIAL PARTIAL THEORY;
- CLOSE PRIOR ART;
- NO RESOLVING RESULT FOUND;
- AMBIGUOUS / MORE SEARCH REQUIRED.

## 18. Required deliverables

Create:

`research/coordination/web-to-chief/ROUND-0015_stochastic-switching-fractional-persistence_RETURN.md`

and:

`research/web-search/2026-09-28_stochastic-switching-fractional-persistence.md`

Update corpus, theorem records, bibliography and provenance registries as warranted.

## 19. Completion criterion

The Chief should be able to decide whether stochastic/switching time-fractional dynamics contains:

- a mature general theory;
- mostly equilibrium-stability results;
- a genuine persistence/extinction or rare-event frontier;
- a memory-reset/persistent-memory structural gap;
- and a natural research opportunity close to Double/Multiple Allee.

Do not select a final project winner.
