# Double Allee — Candidate Directions

**Status:** post-ROUND-0003/0004/0005 Chief synthesis, 2026-09-28.

The candidate set has been reduced substantially.

## C-DA-1 — Mechanism-resolved threshold composition

**Status:** LEADING CANDIDATE — survives adversarial search, pending final formula-level novelty audit.

### Core question

For a controlled class of separately interpretable density-dependent component-fitness functions, derive necessary-and-sufficient conditions under which:

- no component alone produces a strong demographic Allee threshold;
- the joint composition does produce one;
- the threshold is unique or multiple;
- the threshold moves monotonically with mechanism strength;
- threshold creation occurs through a characterized fold/nondegeneracy condition.

### Required mathematical form

The candidate is frozen in:

research/double-allee/MECHANISM_RESOLVED_FRAMEWORK.md

The preferred viability representation is

V_S(x)=B(x) product_{i in S} A_i(x),

with demographic sign determined by V_S-1 and component deletion implemented by A_i -> 1.

### Strongest prior-art threats

- Berec–Angulo–Courchamp 2007: multiple effects, double dormancy, concrete two-component model.
- Guijie Lan 2025: rigorous threshold dynamics for a stochastic single-species model with two component Allee effects.
- earlier emergent-Allee results from stage/predation structure.
- generic scalar fold/unimodality theory.

### Why it still survives

No searched source yet provides the proposed **general mechanism-resolved composition theorem** with:
- deletion counterfactuals;
- individual dormancy;
- exact joint threshold creation;
- root-count control;
- comparative statics;
- fold boundary;
- a function class broad enough to be reusable.

### Kill criterion

Reject if ROUND-0006 finds an equivalent or more general theorem in demographic/life-cycle, bifurcation, factorized-growth, survival–fecundity, or nonlinear-composition literature.

---

## C-DA-1I — Structural identifiability of the component decomposition

**Status:** MERGED INTO C-DA-1 AS A CORE SUPPORTING THEOREM.

This replaces the earlier standalone C-DA-3.

### Core question

If aggregate demographic dynamics depend on hidden component mechanisms through a composite operator such as

P(x)=product_i A_i(x),

what can abundance-only observations identify?

### Leading theorem hypothesis

In a nonparametric multiplicative class,

(A_1,...,A_m) -> (A_1 h_1,...,A_m h_m), with product_i h_i = 1,

leaves P unchanged.

Therefore aggregate state trajectories cannot uniquely identify the individual component mechanisms.

A second theorem should characterize the component-specific outputs needed to break this equivalence.

### Why this strengthens C-DA-1

It couples:
- the **forward problem**: when mechanisms compose to create a threshold;
- the **inverse problem**: whether those mechanisms can be recovered from data.

This makes the program applied mathematics rather than a scalar root exercise.

### Fractional/network connection

If the right-hand side depends on the same composite mechanism, replacing the ordinary derivative by a fractional operator or embedding the local dynamics in a known network does not automatically break the component-factor invariance.

This can provide an operator/network-independent non-identifiability result without forcing fractional memory into the empirical model.

### Kill criterion

Reject or sharply narrow if ROUND-0006 finds this factorization non-identifiability and minimal-output result already standard for ecological demographic decomposition.

---

## C-DA-2 — Generic network transformation of Allee thresholds

**Status:** REJECTED AS STANDALONE PRIMARY DIRECTION.

### Reason

Stehlík–Švígler–Volek 2023 already gives persistence/extinction theory on arbitrary connected graphs with heterogeneous logistic and bistable local reactions. Lanchier, Nagatani–Ichinose, Zhou–Wang, and 2026 N-patch bifurcation work further raise prior-art density.

A theorem that merely says dispersal/topology changes an Allee threshold is not enough.

### Retained use

Network structure may re-enter only through a mechanism-resolved statement that generic bistable-node theory cannot express, especially:

- whether network state observations can identify hidden component mechanisms;
- whether component-specific parameter changes propagate into persistence bounds in a way lost after collapsing nodes to generic bistable reactions.

---

## C-DA-4 — Structured conic D-stability of ecological Jacobians

**Status:** DEPRIORITIZED / CONDITIONAL.

### Reason

Generalized conic D-stability exists, and classical exact D-stability results already cover:
- low dimensions;
- tridiagonal matrices;
- acyclic matrices;
- Metzler/positive classes;
- qualitative/sign stability.

The only plausible residual novelty is a finite exact criterion for a concrete cyclic, non-Metzler class.

### Retained use

After the mechanism-resolved ecological model is fixed, inspect its Jacobian.

Reopen this branch only if the model naturally produces a structurally distinctive matrix family.

---

# Current convergence

The candidate program is now:

component mechanisms
-> exact threshold composition
-> structural identifiability
-> minimal observation design

with:
- network/fractional invariance as a possible theorem extension;
- real data as validation/observation-design evidence;
- matrix stability only if forced by the resulting Jacobian class.

PRIMARY_DIRECTION.md remains unselected until ROUND-0006 tests the exact frozen mathematical formulation.
