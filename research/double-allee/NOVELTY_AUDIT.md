# Double Allee — Novelty Audit

**Updated by Chief:** 2026-09-28 after ROUND-0003/0004/0005 and independent verification.

## Closed or strongly blocked routes

### N-DA-001 — Simple Caputo fractionalization
**Status:** CLOSED AS PRIMARY NOVELTY ROUTE.

### N-DA-002 — Incommensurate fractionalization
**Status:** CLOSED AS PRIMARY NOVELTY ROUTE.

### N-DA-003 — Discrete fractionalization
**Status:** CLOSED AS PRIMARY NOVELTY ROUTE.

### N-DA-004 — Continuum diffusion
**Status:** CLOSED AS PRIMARY NOVELTY ROUTE.

### N-DA-005 — Generic planar Double-Allee bifurcation
**Status:** HIGH PRIOR-ART DENSITY.

### N-DA-006 — Generic network transformation of an Allee/bistable threshold
**Status:** BROAD VERSION EFFECTIVELY COVERED.

Stehlík–Švígler–Volek 2023 already provides arbitrary connected-graph persistence/extinction conditions for heterogeneous local reactions including bistable dynamics. Additional graph-Allee and metapopulation results reinforce this.

### N-DA-007 — Generic structured fractional D-stability
**Status:** BROAD VERSION CLOSED.

General conic/LMI-region multiplicative D-stability exists; classical exact structural D-stability theory is rich.

---

## Leading surviving claim family

### N-DA-101 — Mechanism-resolved threshold composition theorem

**Current status:** PARTIAL/CLOSE PRIOR ART — SURVIVES ONLY IN EXACT FUNCTION-CLASS FORM.

Strongest threats:
- Berec–Angulo–Courchamp 2007;
- Lan 2025;
- two-Allee trade-off models;
- emergent-Allee stage-structured models;
- generic saddle-node/root geometry.

The residual claim is:

> For a controlled class of separately interpretable density-dependent component-fitness functions, derive reusable necessary-and-sufficient conditions for individually non-strong components to jointly create a strong demographic threshold, including root-count control, fold boundary and comparative statics.

The precise class is frozen in:

research/double-allee/MECHANISM_RESOLVED_FRAMEWORK.md

**Required final audit:** ROUND-0006.

---

### N-DA-102 — Gauge-type non-identifiability of hidden component mechanisms

**Current status:** SEARCH HYPOTHESIS.

Proposed mathematical invariance:

If aggregate dynamics depend on

P(x)=product_i A_i(x),

then admissible transformations satisfying

product_i h_i(x)=1

and

A_i -> A_i h_i

leave the demographic vector field invariant.

Potential consequence:

> abundance-only state trajectories identify the composite demographic effect but not the separate component mechanisms in a nonparametric class.

Threats to search:
- structural identifiability of factorized nonlinear systems;
- demographic decomposition from abundance-only data;
- life-cycle survival/fecundity identifiability;
- gauge/symmetry identifiability methods;
- nonparametric factorization;
- hidden-mechanism ecological inverse problems.

**Required final audit:** ROUND-0006.

---

### N-DA-103 — Minimal observation theorem

**Current status:** SEARCH HYPOTHESIS.

Candidate result:

> component-specific outputs can remove the factorization ambiguity, and the number/type of outputs required can be characterized.

Threats:
- observability of factorized nonlinear systems;
- multitype demographic inverse problems;
- survival/reproduction estimation theory;
- input-output identifiability.

**Required final audit:** ROUND-0006.

---

### N-DA-104 — Network/fractional invariance of mechanism non-identifiability

**Current status:** SECONDARY EXTENSION HYPOTHESIS.

If network coupling is known and independent of the hidden factorization, nodewise transformations preserving each composite local mechanism leave the full vector field unchanged.

Likewise, replacing the ordinary derivative by a fixed fractional operator does not break a right-hand-side invariance.

This would be useful only as a theorem extension to N-DA-102; it is not the primary novelty claim.

---

## Data novelty position

### Island fox
High-value multiple-component empirical system, but exact historical raw data are not verified openly reusable.

### Crested Ibis
High-value multiple-component alternative; raw data access unresolved.

### Open benchmarks
- herring: low-density model discrimination;
- cod: threshold uncertainty;
- freshwater mussel: component-effect observation design.

The primary theorem program must not depend on obtaining a closed dataset.

---

## Final novelty gate

PRIMARY_DIRECTION.md may be populated only if ROUND-0006 fails to find prior theory that subsumes both:

1. the mechanism-resolved composition theorem at comparable generality; and
2. the component-factor identifiability / minimal-observation theorem in the same ecological setting.

Until then use:

> No result resolving the frozen mechanism-resolved composition-and-identifiability program was identified in the searched corpus as of 2026-09-28.
