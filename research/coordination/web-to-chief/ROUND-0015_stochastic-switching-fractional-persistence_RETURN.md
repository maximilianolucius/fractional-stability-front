# ROUND-0015 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** research/coordination/chief-to-web/ROUND-0015_stochastic-switching-fractional-persistence_REQUEST.md  
**Status:** COMPLETE

## RETURN TO CHIEF

### Question investigated

Map the theorem architecture for **genuine time-fractional stochastic, randomly switched and hybrid systems**, with emphasis on:

- state architecture;
- positivity and ecological admissibility;
- moment/pathwise stability;
- invariant measures / random dynamical systems;
- persistence/extinction;
- rare-event and basin-exit theory;
- switching with reset memory versus persistent memory;
- direct stochastic-fractional Allee prior.

The search enforced the terminology firewall:

- **S1:** time-fractional derivative + stochastic forcing;
- **S2:** ordinary equations driven by fractional Brownian motion;
- **S3:** stochastic equations with spatial fractional operators;
- **S4:** deterministic fractional dynamics with random/switching events.

S2 and S3 are adjacent theory, not direct time-fractional FDE evidence.

---

# Executive finding

ROUND-0015 identifies a sharp maturity split.

## Already substantial / direct prior

1. **Well-posed stochastic time-fractional equations.**  
   Caputo stochastic equations driven by Brownian motion have an established stochastic-Volterra integral formulation, existence/uniqueness theory, finite-time stability and several stochastic/asymptotic stability notions.

2. **Stochastic Volterra state architecture.**  
   For completely monotone kernels, including the power-law fractional kernel in the standard Itô-integrable regime, there are Hilbert-space Markovian lifts with existence, uniqueness, Feller/Markov structure, asymptotic coupling and invariant-measure theory.

3. **Positivity/invariance machinery.**  
   Stochastic Volterra equations now have nonnegativity-preserving-kernel and convex-domain invariance results. Thus positivity is not an untouched mathematical problem.

4. **Large deviations.**  
   General multidimensional stochastic Volterra equations with singular kernels already have pathwise Freidlin–Wentzell large/moderate deviation principles, and a 2026 paper gives an LDP directly for weakly singular power-law kernels of Caputo type.

5. **Ordinary stochastic Allee theory.**  
   Nonfractional stochastic Allee systems already possess rigorous positivity, persistence/extinction, regime-switching ergodicity, stationary distributions, and noise-induced tipping / first-passage analyses.

6. **Randomly switched fractional equilibrium stability.**  
   Almost-sure and p-moment/Lyapunov stability results exist for switched fractional systems, including stochastic switching.

## What remains unresolved in the searched corpus

No general theorem was identified combining all of:

\[
\text{time-fractional memory}
+
\text{positive multistable ecology}
+
\text{stochastic forcing}
+
\text{persistence/extinction or basin exit}.
\]

More specifically, no searched source supplied a rigorous general framework for:

- stochastic persistence/permanence of positive **time-fractional** systems;
- extinction criteria relative to fractional-memory basins;
- invariant/occupation measures adapted to extinction boundaries of positive Caputo systems;
- quasipotential / exit-time asymptotics for strong/Double-Allee stochastic Caputo systems;
- switching-induced survival/extinction with **persistent fractional memory** across regime changes.

The strongest residuals are therefore **not** generic existence, stability, invariant measures or large deviations.

They are:

\[
\boxed{
\text{fractional-memory persistence/extinction}
}
\]

and

\[
\boxed{
\text{rare exit / tipping in multistable positive systems}
}
\]

plus a distinct hybrid problem:

\[
\boxed{
\text{random switching with a fixed lower terminal / persistent memory}.
}
\]

---

# 1. Terminology firewall

## S1 — genuine time-fractional stochastic equations

Canonical Brownian-driven formulation:

\[
{}^C D_{0+}^{\alpha}X(t)
=
f(t,X(t))
+
g(t,X(t))\,\dot W_t
\]

is interpreted through the stochastic Volterra equation

\[
X_t
=
X_0
+
\frac1{\Gamma(\alpha)}
\int_0^t (t-s)^{\alpha-1}f(s,X_s)\,ds
+
\frac1{\Gamma(\alpha)}
\int_0^t (t-s)^{\alpha-1}g(s,X_s)\,dW_s.
\]

For the standard Itô integral with the same power-law kernel in the diffusion term, the common theory requires

\[
\alpha>\frac12,
\]

because square integrability of the kernel near \(s=t\) is needed.

This restriction is mathematically important for ecology: many deterministic Caputo papers freely use all \(0<\alpha<1\), but adding classical white noise through the same fractional convolution changes the admissible order regime.

## S2 — fBm-driven ordinary equations

These may have long-memory noise but no time-fractional derivative.

Do not count them as S1.

## S3 — spatial fractional SPDEs

Papers on random attractors for fractional Laplacians belong here unless the time derivative is also fractional.

Do not count them as direct evidence for S1.

## S4 — switched/hybrid fractional deterministic dynamics

Fractional deterministic equations operate between switches. The lower terminal convention is part of the model definition.

---

# 2. Stochastic time-fractional state architecture

## Caputo stochastic well-posedness

Direct prior includes:

- Carathéodory approximation and existence/uniqueness for Brownian-driven Caputo stochastic equations;
- Caputo stochastic neutral equations;
- 2025 finite-time stability and existence results;
- order-continuity results in 2026.

The architecture is therefore not foundationally empty.

## Stochastic Volterra Markovian lift

Yushi Hamaguchi,  
*Markovian lifting and asymptotic log-Harnack inequality for stochastic Volterra integral equations*, SPA 178 (2024), 104482, DOI 10.1016/j.spa.2024.104482.

For completely monotone kernels, the stochastic Volterra process is represented by a stochastic evolution equation on a separable Hilbert space containing the memory state.

The framework includes singular fractional kernels of the form

\[
K(t)=\frac{t^{\alpha-1}}{\Gamma(\alpha)}
\]

in the relevant integrability regime and establishes:
- lifted existence/uniqueness;
- Markov property;
- Feller-type properties;
- asymptotic log-Harnack inequalities;
- invariant-measure results in important cases.

Bianchi–Bonaccorsi–Cañadas–Friesen 2026 further develops:
- limit distributions;
- invariant measures;
- stationary processes;
- laws of large numbers;
- central limit theorems

for stochastic Volterra processes and explicitly treats fractional kernels.

### Verdict 1 — stochastic time-fractional state architecture

**SUBSTANTIAL PARTIAL THEORY.**

A Markovian history-state lift is direct prior. A general ecological RDS/persistence theory on that lift is not.

---

# 3. Positivity / well-posedness

## Direct Caputo stochastic well-posedness

Zhang & Zou 2025, DOI 10.1063/5.0285642, studies Brownian-driven Caputo-type stochastic equations and gives existence and finite-time stability.

Xiao & Wang 2021, DOI 10.15388/namc.2021.26.22421, proves stochastic stability, stochastic asymptotic stability, almost-sure exponential stability and \(p\)-moment exponential stability.

Thus basic stochastic stability notions are populated.

## Stochastic Volterra positivity

Aurélien Alfonsi 2025, DOI 10.1016/j.spa.2024.104535, develops nonnegativity-preserving convolution kernels and applies them to stochastic invariance of closed convex domains. Completely monotone kernels preserve nonnegativity.

Abi Jaber–Alfonsi–Szulda 2026, DOI 10.1016/j.spa.2026.105078, extends stochastic invariance to broad possibly singular nonconvolution kernels and obtains nonnegative-orthant results for square-root-type models.

### Ecological caution

An additive Gaussian forcing can violate population nonnegativity.

A biologically admissible stochastic fractional ecology theorem should specify a diffusion/boundary structure that preserves the positive cone rather than simply append additive white noise.

### Verdict 2 — positivity/well-posedness

**SUBSTANTIAL PARTIAL THEORY.**

The mathematical ingredients exist, but ecological positivity must be built into the noise model.

---

# 4. Moment / pathwise stability

Direct prior is substantial.

## Xiao & Wang 2021

For Caputo stochastic differential equations:
- stochastic stability;
- stochastic asymptotic stability;
- almost-sure exponential stability;
- \(p\)-moment exponential stability.

## Zhang & Zou 2025

Existence plus finite-time stability.

## Tempered/generalized Caputo stochastic equations

Recent Lévy-noise and generalized-Caputo papers extend existence/uniqueness and Mittag-Leffler/mean-square style stability.

### Limitation

These results overwhelmingly concern:
- zero/single equilibria;
- equilibrium stability;
- finite-time or moment bounds.

They do not amount to a theory of stochastic multibasin persistence/extinction.

### Verdict 3 — moment/pathwise stability

**DIRECT PRIOR / SUBSTANTIAL THEORY.**

This is not a high-value novelty route by itself.

---

# 5. RDS / invariant measures / random attractors

The terminology firewall is decisive.

Searches for “fractional stochastic random attractor” frequently return:
- spatial-fractional reaction–diffusion SPDEs;
- fBm-driven ordinary/SPDE systems.

Those are not S1.

## Genuine stochastic-Volterra long-time theory

The strongest direct architecture is the Markovian lift.

Hamaguchi 2024 gives Markov/Feller structure and invariant-measure theory in important classes.

Bianchi et al. 2026 gives limit distributions, stationary processes and invariant measures for fractional stochastic Volterra examples.

Recent work on Kolmogorov equations for singular stochastic Volterra processes also establishes Hilbert-space Markovian lifts and Fokker–Planck/Kolmogorov equations.

### What was not found

No broad random-attractor / pullback-attractor theory was identified specifically for finite-dimensional Brownian-driven Caputo stochastic equations with the genuine time-fractional derivative.

### Verdict 4 — RDS / invariant measures / random attractors

**SUBSTANTIAL PARTIAL THEORY.**

Invariant/stationary-measure theory is increasingly strong through stochastic-Volterra lifts. Direct random-attractor theory for S1 remains much thinner than misleading search terminology suggests.

---

# 6. Stochastic persistence / extinction

This is one of the strongest residuals.

## Ordinary stochastic ecology is mature

### He–Liu–Xu 2024

DOI 10.1002/mma.9880.

Stochastic eco-epidemic predator–prey with Allee effect and Lévy jumps:
- unique global positive solution;
- long-term population behavior;
- stochastic ultimate boundedness;
- ergodic stationary distribution in the no-jump case.

### Granados & Valencia 2026

DOI 10.5614/cbms.2026.9.1.3.

Stochastic predator–prey with emergent Allee effect:
- positivity;
- extinction/stability conditions;
- prey persistence conditions.

### Regime switching

2018 single-species Allee regime-switching work, DOI 10.1016/j.cnsns.2017.11.028, proves:
- positive global solution;
- extinction;
- non-persistence in mean;
- persistence in mean;
- stochastic permanence;
- positive recurrence / ergodicity.

Thus stochastic Allee persistence is mature **without fractional time memory**.

## Time-fractional stochastic search

No general time-fractional analogue of the above framework was located.

No searched source gave:
- stochastic permanence for a broad positive Caputo class;
- invasion-rate criteria on a stochastic memory-state lift;
- basin-relative stochastic persistence for strong Allee;
- a general extinction theorem combining Caputo power-law memory and Brownian/Lévy noise.

### Verdict 5 — stochastic persistence/extinction

**NO RESOLVING GENERAL RESULT FOUND.**

This is a credible theorem-level frontier.

---

# 7. Large deviations / basin exit

The broad claim that large deviations for stochastic fractional-memory systems are unexplored is false.

## Jacquier & Pannier 2022

*Large and moderate deviations for stochastic Volterra systems*, SPA 149:142–187, DOI 10.1016/j.spa.2022.03.017.

Gives pathwise large and moderate deviation principles for broad multidimensional SVEs with singular kernels, including nonconvolution kernels.

## Gao–Lu–Yan–Tang–Huang 2026

DOI 10.1016/j.cnsns.2026.109827.

For

\[
X(t)
=
x+
\int_0^t (t-s)^{\alpha-1}f(s,X_s)\,ds
+
\int_0^t (t-s)^{\alpha-1}g(s,X_s)\,dW_s,
\qquad \frac12<\alpha<1,
\]

proves:
- strong Euler–Maruyama convergence;
- almost-sure uniform convergence;
- a Freidlin–Wentzell LDP.

Thus **path LDP itself is direct prior**.

### What remains

A path LDP is not yet an Allee rare-extinction theorem.

The search did not identify a general Caputo/weakly-singular stochastic-Volterra result deriving:
- quasipotential geometry between survival/extinction attractors;
- sharp first-exit asymptotics;
- Eyring/Kramers-type extinction-time scaling;
- most-probable extinction path in a positive strong/Double-Allee system;
- dependence of those quantities on \(\alpha\).

### Verdict 6 — large deviations / basin exit

**DIRECT PRIOR for path LDP; NO RESOLVING RESULT FOUND for ecological basin-exit/quasipotential theory.**

This is a narrower but potentially high-value residual.

---

# 8. Switching with reset memory

This branch is directly populated.

## Wang–Long–Mo–Yang 2023

DOI 10.1080/00051144.2023.2262016.

Caputo switched linear systems with deterministic and stochastic switching signals:
- Markov switching component;
- sufficient global asymptotic stability almost surely;
- exponential stability almost surely;
- multi-Lyapunov method.

The paper acknowledges controversy over the fractional lower-limit convention.

## Agarwal–Hristova–O’Regan 2025

DOI 10.3390/math13223704.

Switched generalized-Caputo gene regulatory network with **short memory**:
- lower terminal changes at switching times;
- generalized Mittag-Leffler stability;
- Lyapunov sufficient conditions.

## O’Regan & Hristova 2026

DOI 10.3390/fractalfract10090616.

Random Erlang switching times; nonlinear fractional dynamics between switches; **lower terminal is reset at every switching time**; p-moment/Lyapunov stability.

### Verdict 7 — switching with memory reset

**DIRECT PRIOR / SUBSTANTIAL THEORY.**

Equilibrium stability under short-memory/reset switching is not an open general novelty route.

---

# 9. Switching with persistent memory

This is structurally different.

## Explicit 2026 open direction

O’Regan & Hristova 2026 states directly that they reset the Caputo lower terminal at each switching time and that keeping a fixed lower limit at the initial time would change both the problem and the Lyapunov analysis; they identify it as a future direction.

## Existing controversy

The switching literature contains conflicting formulations.

A 2022 reply paper argues that updating the lower limit is significant and defends the reset convention.

A 2025 short-memory paper states that several earlier fixed-lower-limit switched formulations used problematic integral representations.

Conversely, fixed lower-terminal memory is physically meaningful if the modeled system is meant to retain pre-switch history.

Therefore:

> “persistent memory” cannot simply reuse reset-memory proofs.

The state after a switch must include inherited memory generated under earlier regimes.

### No searched result found for

- nonlinear positive persistent-memory switched Caputo systems;
- stochastic switching with a rigorous history-state process and fixed lower terminal;
- persistence/extinction or multibasin dynamics under persistent memory;
- Allee survival/extinction under random regime switching with inherited Caputo memory.

### Verdict 8 — switching with persistent memory

**NO RESOLVING GENERAL RESULT FOUND.**

This is a sharply defined structural frontier, strengthened by an explicit 2026 source statement.

---

# 10. Direct stochastic-fractional Allee prior

The intersection of the two mature literatures is unexpectedly sparse.

## Mature deterministic fractional Allee side

Already catalogued:
- Caputo strong/Double-Allee predator–prey;
- fractional basins;
- commensurate/incommensurate cases;
- delay and recent 2026 Allee models.

## Mature stochastic Allee side

Direct prior includes:
- stochastic Allee persistence/extinction;
- Lévy jumps;
- regime switching;
- ergodicity;
- noise-induced tipping;
- first-passage/tipping probabilities.

## Direct intersection searched

Queries for:
- stochastic fractional Allee;
- time-fractional stochastic Allee;
- Caputo stochastic predator–prey Allee;
- stochastic + fractional + Double Allee;
- Brownian/Lévy + Caputo + Allee

did not identify a theorem-level paper combining genuine **S1 time-fractional stochastic dynamics** with Allee persistence/extinction.

This is a negative search result, not proof of absence.

### Verdict 9 — direct stochastic-fractional Allee prior

**NO RESOLVING RESULT FOUND.**

---

# 11. Noise-induced tipping versus deterministic threshold

Ordinary stochastic Allee theory already makes this distinction useful.

Pal–Mondal–Biswas–Saha 2026, DOI 10.1016/j.chaos.2025.117567, studies:
- deterministic bistability/tristability and basin structure;
- stochastic persistence/extinction;
- noise-induced transitions;
- tipping probabilities and tipping times.

The stochastic forcing does not algebraically move the deterministic equilibrium equation; instead it changes transition probabilities and exit behavior.

For time-fractional systems, the correct analogue should distinguish:

1. deterministic fractional-memory basin;
2. stochastic escape from that basin;
3. small-noise action/quasipotential;
4. finite-time extinction/tipping probability;
5. possible stationary/occupation measures on the memory-state lift.

No general theorem package combining these was located.

---

# 12. Double-Allee proximity

This branch is naturally close to Double Allee.

Why:

- strong/Double Allee creates extinction/survival multistability;
- environmental noise makes basin exit biologically meaningful;
- memory can modify transient approach and history-state basin geometry;
- regime changes can alter the vector field while inherited memory retains information from previous ecological regimes;
- rare extinction is a scientifically meaningful observable.

The strongest formulation is **not**:

> add white noise to a fractional Double-Allee ODE.

A theoremically meaningful target would be one of:

### A. Fractional-memory stochastic persistence

A general condition for extinction versus conditional persistence in a positive stochastic Caputo/Volterra class.

### B. Fractional-memory basin exit

Small-noise exit/quasipotential theory specialized to multistable positive Caputo systems, with dependence on \(\alpha\).

### C. Persistent-memory regime switching

A history-state process for random switching without resetting the lower terminal, plus conditions for survival/extinction.

### D. Double-Allee realization

Demonstrate that one of A–C produces a genuinely new theorem in a strong/Double-Allee system.

### Verdict 10 — Double-Allee proximity

**CLOSE / HIGH NATURAL PROXIMITY, BUT MODELING DISCIPLINE REQUIRED.**

Stronger than D14 proximity because extinction/tipping is intrinsic to Allee dynamics rather than operator decoration.

---

# 13. Required verdict summary

| Item | ROUND-0015 verdict | Core reason |
|---|---|---|
| 1. stochastic time-fractional state architecture | **SUBSTANTIAL PARTIAL THEORY** | stochastic-Volterra Markovian lifts and invariant measures exist |
| 2. positivity/well-posedness | **SUBSTANTIAL PARTIAL THEORY** | direct Caputo FSDE well-posedness + stochastic convex-domain invariance |
| 3. moment/pathwise stability | **DIRECT PRIOR / SUBSTANTIAL THEORY** | stochastic, a.s., p-moment and finite-time stability results exist |
| 4. RDS/invariant measure/random attractor | **SUBSTANTIAL PARTIAL THEORY** | invariant measures via Markov lifts; genuine S1 random-attractor theory much thinner |
| 5. stochastic persistence/extinction | **NO RESOLVING GENERAL RESULT FOUND** | ordinary stochastic ecology mature; time-fractional general theory not located |
| 6. large deviations / basin exit | **DIRECT PRIOR for LDP; NO RESOLVING RESULT for exit/quasipotential** | general singular-SVE LDP exists; ecological metastable exit theory not found |
| 7. switching with memory reset | **DIRECT PRIOR** | extensive short-memory/reset equilibrium-stability literature |
| 8. switching with persistent memory | **NO RESOLVING GENERAL RESULT FOUND** | explicitly left open by 2026 source; literature/formulation controversy |
| 9. direct stochastic-fractional Allee prior | **NO RESOLVING RESULT FOUND** | no theorem-level S1 + Allee persistence/extinction paper located |
| 10. Double-Allee proximity | **CLOSE / HIGH NATURAL PROXIMITY** | multistability, extinction risk and switching are intrinsic Allee questions |
| 11. strongest theorem residuals | **RETAIN AS DOMAIN FRONTIER** | persistence/extinction, rare exit, persistent-memory switching |

---

# 14. Strongest prior-art threats

1. **General stochastic Volterra theory**  
   Markovian lifts, invariant measures and LDP machinery already cover major structural pieces.

2. **Ordinary stochastic Allee ecology**  
   Persistence/extinction, switching and noise-induced tipping are mature enough that fractional work must show a genuine memory effect.

3. **Fractional switched stability literature**  
   Reset-memory stability is already populated.

4. **Positivity/invariance theory for stochastic Volterra equations**  
   A future ecological paper cannot treat positivity as a trivial afterthought.

---

# 15. Evidence against broad novelty

The following are not defensible as new:

- stochastic Caputo well-posedness;
- finite-time stochastic Caputo stability;
- almost-sure or \(p\)-moment Caputo equilibrium stability;
- Markovian lifting of stochastic Volterra equations with fractional kernels;
- invariant measures for broad stochastic Volterra lifts;
- pathwise large deviations for singular stochastic Volterra systems;
- positivity/invariance for completely monotone stochastic Volterra kernels;
- stochastic Allee persistence/extinction in ordinary SDEs;
- random switching of reset-memory Caputo systems;
- noise-induced tipping in ordinary Allee systems.

---

# 16. Strongest unresolved theorem-level residuals

## F-S15-A — stochastic persistence on fractional memory-state space

Develop an extinction/persistence theory for positive stochastic Volterra/Caputo systems analogous to stochastic persistence/invasion theory, but on a non-Markov physical projection with a Markovian memory lift.

## F-S15-B — basin-relative stochastic persistence

For strong Allee systems, formulate conditional persistence relative to a stochastic memory-state survival region rather than global permanence.

## F-S15-C — rare extinction / quasipotential

Starting from the existing SVE LDP, derive basin-exit and extinction-time asymptotics for multistable positive fractional-memory systems.

## F-S15-D — persistent-memory stochastic switching

Construct a mathematically correct history-state process for random switching with fixed Caputo lower terminal and analyze stability/persistence without memory reset.

## F-S15-E — Double-Allee realization

Show that memory changes a rigorous extinction/persistence or rare-exit theorem in a Double-Allee model, not merely numerical tipping trajectories.

---

# 17. Remaining uncertainty

1. General stochastic Volterra theory is moving quickly; invariant-measure and Kolmogorov theory strengthened substantially in 2024–2026.
2. There may be specialized stochastic-population papers using alternative fractional operators/terminology not located in this round.
3. Path LDP does not automatically imply a clean quasipotential or Kramers law for non-Markov physical coordinates; the Markovian lift may be essential.
4. Ecological positivity strongly constrains admissible diffusion coefficients.
5. Standard Brownian convolution with the Caputo kernel commonly requires \(\alpha>1/2\), so a stochastic theory covering all deterministic ecological orders \(0<\alpha<1\) may require a different noise/integration framework.
6. Persistent-memory switching requires careful formulation before any theorem claim because published switched-FDE conventions are contested.

---

# Files updated

- research/coordination/web-to-chief/ROUND-0015_stochastic-switching-fractional-persistence_RETURN.md
- research/web-search/2026-09-28_stochastic-switching-fractional-persistence.md
- research/web-search/SEARCH_LOG.md
- research/web-search/QUERY_REGISTRY.md
- research/web-search/SOURCE_REGISTRY.md
- research/web-search/NOVELTY_CHECKS.md
- corpus/papers.csv
- corpus/theorems.csv
- bibliography/references.bib

---

## Searcher's bottom line

D8 contains a **real and naturally Allee-adjacent frontier**, but only beyond already-mature stochastic-stability machinery.

The strongest statement supported by this round is:

\[
\boxed{
\begin{array}{c}
\text{No general theorem was identified for stochastic persistence/extinction}\\
\text{or rare basin exit in positive time-fractional multistable systems,}\\
\text{and persistent-memory random switching remains structurally unresolved.}
\end{array}
}
\]

This is substantially more specific than “stochastic fractional ecology is unexplored.”

Do not select a final project winner from this round alone.
