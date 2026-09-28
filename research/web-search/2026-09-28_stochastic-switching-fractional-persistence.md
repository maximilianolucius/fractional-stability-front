# 2026-09-28 — Stochastic / Switching Fractional Persistence Audit

**Round:** ROUND-0015  
**Request:** research/coordination/chief-to-web/ROUND-0015_stochastic-switching-fractional-persistence_REQUEST.md  
**Role:** WEB SEARCHER

## 1. Scope

This audit separates four often-confused literatures:

- S1: genuine time-fractional stochastic equations;
- S2: ordinary equations driven by fractional Brownian noise;
- S3: spatial-fractional stochastic PDEs;
- S4: fractional deterministic dynamics under random/switching events.

Only S1 and S4 are direct evidence for this branch.

The target was global qualitative dynamics, not merely existence:
- positivity;
- stability;
- invariant measures;
- persistence/extinction;
- basin exit;
- switching memory conventions;
- Double-Allee relevance.

---

## 2. Canonical S1 formulation

A Brownian-driven Caputo equation is typically interpreted as

\[
X_t=X_0+
\frac1{\Gamma(\alpha)}
\int_0^t(t-s)^{\alpha-1}f(s,X_s)\,ds
+
\frac1{\Gamma(\alpha)}
\int_0^t(t-s)^{\alpha-1}g(s,X_s)\,dW_s.
\]

This is a stochastic Volterra integral equation.

With the same kernel in the Itô diffusion convolution, local square integrability requires the common regime

\[
\alpha>\frac12.
\]

This is not a cosmetic technicality.

It means direct white-noise fractionalization is not automatically compatible with all \(0<\alpha<1\) orders used in deterministic population models.

---

## 3. Well-posedness / stability prior

### Caputo stochastic existence

Carathéodory/Picard-type literature already establishes existence and uniqueness under Lipschitz/linear-growth assumptions.

### Xiao & Wang 2021

DOI 10.15388/namc.2021.26.22421.

Stability results include:
- stochastic stability;
- stochastic asymptotic stability;
- almost-sure exponential stability;
- \(p\)-moment exponential stability.

### Zhang & Zou 2025

DOI 10.1063/5.0285642.

Existence and finite-time stability for Brownian-driven Caputo-type stochastic equations.

### 2026 order dependence

DOI 10.1016/j.jmaa.2025.130177 studies Lipschitz continuity / optimal weak convergence rates with respect to fractional order.

Conclusion:

> generic stochastic Caputo well-posedness or equilibrium stability is not a frontier.

---

## 4. Stochastic Volterra state architecture

### Hamaguchi 2024

DOI 10.1016/j.spa.2024.104482.

Completely monotone kernels admit a separable-Hilbert-space Markovian lift.

For fractional power-law kernels in the admissible regime, this gives:
- memory state;
- lifted stochastic evolution equation;
- Markov and Feller structure;
- asymptotic coupling tools.

Invariant probability measures are characterized in important cases, though the paper itself identifies the general invariant-measure problem as open.

### Bianchi et al. 2026

DOI 10.1007/s40072-026-00428-w.

Abstract Markovian lifts of stochastic Volterra equations with operator-valued kernels.

Main results:
- limit distributions;
- stationary processes;
- invariant measures;
- LLN;
- CLT;
- convergence rates.

Fractional kernels with additive/multiplicative Gaussian noise are explicit examples.

### 2025/2026 Kolmogorov theory

Recent singular-SVE work derives Markovian transport-type SPDE lifts and backward/forward Kolmogorov equations.

Thus:

> non-Markov physical state does not mean absence of a Markovian memory-state framework.

---

## 5. Positivity and stochastic invariance

### Alfonsi 2025

DOI 10.1016/j.spa.2024.104535.

Defines nonnegativity-preserving convolution kernels and proves completely monotone kernels preserve nonnegativity.

Applies the property to:
- stochastic invariance of closed convex sets;
- one-dimensional comparison;
- positivity-preserving approximation.

### Abi Jaber–Alfonsi–Szulda 2026

DOI 10.1016/j.spa.2026.105078.

General kernels, including singular nonconvolution fractional-type kernels:
- weak existence;
- stochastic invariance of convex sets;
- nonnegative orthant preservation for square-root diffusion structures.

Implication for ecology:

> positivity should be treated as a structural constraint on drift/noise/kernel, not assumed from deterministic invariance.

---

## 6. Invariant measures versus random attractors

Search terminology is dangerous.

Many “fractional stochastic random attractor” papers are actually:
- fractional Laplacian SPDEs;
- ordinary equations driven by fBm.

They are S2/S3, not direct S1.

For S1:
- Markovian-lift invariant-measure theory is substantial;
- stationary processes and limit distributions now have modern general results.

But no broad direct random-attractor theorem was identified for finite-dimensional Brownian-driven Caputo systems in the same sense as classical RDS theory.

This leaves a distinction:

\[
\text{stationary/invariant measure}
\neq
\text{random attractor}.
\]

---

## 7. Ordinary stochastic Allee killer baseline

This literature is strong.

### Regime switching single-species Allee — 2018

DOI 10.1016/j.cnsns.2017.11.028.

Results:
- global positive solution;
- extinction;
- non-persistence in mean;
- persistence in mean;
- stochastic permanence;
- positive recurrence;
- ergodicity.

### He–Liu–Xu 2024

DOI 10.1002/mma.9880.

Stochastic eco-epidemic predator–prey with prey Allee and Lévy jumps:
- global positive solution;
- ultimate boundedness;
- long-time population behavior;
- ergodic stationary distribution in no-jump case.

### Granados–Valencia 2026

DOI 10.5614/cbms.2026.9.1.3.

Emergent Allee stochastic predator–prey:
- positivity;
- extinction/stability criteria;
- prey persistence.

### Pal et al. 2026

DOI 10.1016/j.chaos.2025.117567.

Allee + habitat complexity:
- deterministic multistability;
- stochastic persistence/extinction;
- noise-induced tipping;
- tipping probabilities and times;
- early-warning/sensitivity analysis.

Therefore any stochastic-fractional Allee work must exceed mature ordinary stochastic ecology.

---

## 8. Direct S1 persistence/extinction

Targeted searches did not identify a general positive-system theory for Brownian-driven time-fractional equations analogous to stochastic permanence/invasion theory.

No broad result was found for:
- almost-sure persistence;
- persistence in probability;
- stochastic permanence;
- invasion rates;
- boundary occupation measures;
- extinction probability;
- conditional persistence

on the stochastic Caputo/Volterra memory state.

There are model-specific stochastic fractional papers and epidemic applications, but the searched corpus did not provide a general theorem architecture.

This is a real residual.

---

## 9. Large deviations

### General SVE theory

Jacquier & Pannier 2022, DOI 10.1016/j.spa.2022.03.017:
pathwise large and moderate deviations for broad multidimensional stochastic Volterra systems with singular kernels.

### Weakly singular power-law direct result

Gao–Lu–Yan–Tang–Huang 2026, DOI 10.1016/j.cnsns.2026.109827:
\[
(t-s)^{\alpha-1},\qquad 1/2<\alpha<1
\]
with Lipschitz/Hölder coefficients.

Results:
- Euler–Maruyama convergence;
- almost-sure uniform convergence;
- Freidlin–Wentzell LDP.

Thus LDP itself is prior art.

### Gap after LDP

The ecological theorem burden is downstream:
- identify survival/extinction attractors on the lifted state;
- define a relevant basin/exiting set;
- derive quasipotential/action minimizers;
- prove asymptotic exit-time or transition-probability results;
- understand dependence on \(\alpha\).

No complete Allee version was found.

---

## 10. Switching taxonomy

A Caputo switch requires a lower-terminal convention.

### Reset / short memory

For switch times \(t_k\), use
\[
{}^C D_{t_k+}^{\alpha}
\]
on the \(k\)-th regime.

Past memory before \(t_k\) is discarded from the new Caputo derivative.

### Persistent memory

Keep
\[
{}^C D_{t_0+}^{\alpha}
\]
through all switches.

The new regime inherits the entire pre-switch history.

These are different models.

---

## 11. Reset-memory switched prior

### Wang et al. 2023

DOI 10.1080/00051144.2023.2262016.

Deterministic + stochastic switching signals; almost-sure stability through multi-Lyapunov/probability analysis.

The paper notes controversy over lower-bound updates.

### Agarwal–Hristova–O’Regan 2025

DOI 10.3390/math13223704.

Explicit short-memory generalized-Caputo switched gene-regulatory network:
- lower terminal updated at switch;
- Mittag-Leffler equilibrium stability.

### O’Regan & Hristova 2026

DOI 10.3390/fractalfract10090616.

Random Erlang switch times and lower-terminal reset at every switch.

The paper explicitly states that fixed initial lower limit is a different future problem.

Reset-memory stability is therefore not an open branch.

---

## 12. Persistent-memory switching

The literature is conceptually unsettled.

A 2022 reply, DOI 10.1016/j.nahs.2021.101123, argues for updating the lower terminal.

A 2025 short-memory paper states that some older fixed-lower-limit formulations used incorrect integral representations.

But a fixed lower terminal is the mathematically natural model if physical memory must survive switches.

The correct persistent-memory system cannot simply solve each interval independently.

At a switch the continuation contains inherited memory from previous vector fields/regimes.

No general rigorous framework was identified for:
- nonlinear random switching;
- fixed lower terminal;
- history-state Markov/cocycle formulation;
- positive invariance;
- persistence/extinction;
- Allee multibasin dynamics.

---

## 13. Direct stochastic-fractional Allee intersection

Search families:
- stochastic fractional Allee;
- Caputo stochastic Allee;
- time-fractional stochastic predator-prey Allee;
- Double Allee stochastic fractional;
- Brownian/Lévy Caputo Allee;
- random-switching fractional Allee.

Results mostly separated into:
- deterministic fractional Allee;
- ordinary stochastic Allee.

No theorem-level direct intersection resolving persistence/extinction was located.

This is a search-qualified gap, not proof of absence.

---

## 14. Noise-induced tipping

For ordinary SDE Allee models:
- tipping between coexistence/extinction basins is already studied;
- first-passage/tipping times and probabilities are standard numerical/theoretical objects.

For time-fractional memory:
- a deterministic physical-state basin is already subtler because of memory;
- noise creates an additional path-space exit problem.

A rigorous theory likely belongs on the Markovian lifted memory state, not solely in the current population vector.

This links ROUND-0015 naturally to ROUND-0012 without making them identical.

---

## 15. Strongest theorem residuals

### R15-A — stochastic fractional persistence

A general theorem for positive stochastic Caputo/Volterra systems that distinguishes:
- extinction;
- persistence in probability/mean;
- almost-sure persistence;
- stochastic permanence.

### R15-B — strong-Allee conditional persistence

Because low positive states may legitimately go extinct, formulate persistence relative to a survival region/basin.

### R15-C — memory-dependent rare exit

Use existing SVE LDP machinery to derive:
- quasipotential;
- most likely extinction path;
- mean exit-time asymptotics;
- \(\alpha\)-dependence.

### R15-D — persistent-memory switching

Random regime switching under fixed lower terminal, with a history-state process and global stability/persistence theory.

### R15-E — Double-Allee application theorem

A positive multistable model in which memory changes a rigorous stochastic survival/extinction or exit-time result.

---

## 16. Novelty killers

### Killer: generic stochastic Caputo existence/stability

**FIRES.**

### Killer: Markovian state lift absent

**FIRES.**

### Killer: invariant measures absent

**PARTLY FIRES.**

Modern SVE lifts supply substantial invariant-measure theory.

### Killer: stochastic-Volterra LDP absent

**FIRES.**

### Killer: ordinary stochastic Allee persistence/tipping absent

**FIRES.**

### Killer: reset-memory switched fractional stability absent

**FIRES.**

### Killer: general time-fractional stochastic persistence/extinction already mature

**DOES NOT FIRE.**

### Killer: persistent-memory random switching solved

**DOES NOT FIRE.**

### Killer: direct stochastic-fractional Double-Allee persistence/rare exit solved

**DOES NOT FIRE.**

---

## 17. Overall assessment

D8 is one of the most naturally Allee-connected branches mapped so far.

Its high-value content is not in “adding stochasticity” but in the interaction of:
- memory state;
- positive multistability;
- stochastic exit;
- extinction/persistence;
- switching memory convention.

The most promising mathematical bridge is between mature stochastic-Volterra machinery and mature stochastic ecology, where a general positive fractional-memory persistence/exit theory appears absent in the searched corpus.

This should be compared against D6 and D10/D11 rather than immediately selected.
