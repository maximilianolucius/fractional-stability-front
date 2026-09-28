# Project Status

## Current phase

**Phase 2R — Domain-map expansion and research-opportunity discovery**

The project mission was clarified on 2026-09-28.

The target domain is:

> **Dynamical Systems and Stability Theory — Fractional Differential Equations**

The project objective is to map the state of the art and identify fertile research gaps, preferably directly involving Double/Multiple Allee dynamics or otherwise very close to them.

The project does **not** proceed from gap selection into full theorem proving. Solving the chosen gap belongs to a separate future project.

## Authoritative charter

`docs/PROJECT_CHARTER.md`

## Completed evidence rounds

- ROUND-0001 — fractional stability seed.
- ROUND-0002 — Double Allee terminology and prior-art seed.
- ROUND-0003 — structured conic D-stability.
- ROUND-0004 — double dormancy/network falsification.
- ROUND-0005 — Double Allee data/identifiability.
- ROUND-0006 — mechanism-resolved novelty gate.
- ROUND-0007 — mechanism-space geometry falsification.
- ROUND-0008 — full-domain architecture audit.
- ROUND-0009 — fractional uniform-persistence/permanence falsification.

## Assimilated lesson from ROUND-0007

The mechanism-space candidate was not killed, but most of its individual mathematical ingredients were shown to be standard:

- convex/semi-infinite geometry;
- weighted threshold games;
- antichain/order-convex structure;
- Danskin/envelope sensitivity.

The residual candidate gap is the coupling between:

[
	ext{low-density failure}
quad	ext{and}quad
	ext{global positive persistence}
]

for component-resolved multiple Allee mechanisms.

This is retained as a **candidate opportunity**, not an active proof program.

See:

`research/double-allee/CANDIDATE_MECHANISM_SPACE_GEOMETRY.md`

## Correction of prior project state

The prior status “primary direction selected; theorem proving” is withdrawn.

`research/double-allee/PRIMARY_DIRECTION.md` is de-selected.

Historical exploratory files:

- `MECHANISM_RESOLVED_FRAMEWORK.md`
- `THEOREM_PROGRAM.md`
- `PROOF_LEDGER.md`

are preserved as candidate-analysis provenance and are not current proof tasks.

## Current mapping priorities

The full domain map must now be expanded across:

1. fractional operator/order architectures relevant to dynamical stability;
2. linear autonomous spectral stability;
3. incommensurate/multi-term stability;
4. nonlinear local/global stability;
5. Lyapunov/Mittag-Leffler and converse theory;
6. structured/positive/D-stability/diagonal-stability bridges;
7. robustness and uncertainty;
8. delays, switching, stochastic and hybrid systems;
9. graph/network dynamics;
10. bifurcation, multistability, persistence/extinction and tipping;
11. ecological/population applications;
12. Double/Multiple Allee as a preferred frontier lens.

## Active round

### ROUND-0010 — Fractional bifurcation semantics and architecture

**Status:** OPEN

Purpose:

- reconstruct rigorous invariant/center-manifold and reduction theory for continuous-time fractional systems;
- separate equilibrium bifurcation from stability crossing, attractor bifurcation and periodic-orbit claims;
- audit the meaning of “Hopf” under finite-lower-terminal Caputo memory;
- determine what remains genuinely unresolved for nonhyperbolic, multidimensional and incommensurate systems;
- test whether Double Allee exposes a real fractional bifurcation gap rather than an ODE-equilibrium calculation.

## Current candidate opportunity portfolio

Current high-information candidates include:

- persistence-filtered mechanism composition in Multiple/Double Allee systems;
- rigorous fractional bifurcation/nonhyperbolic threshold dynamics;
- memory-state and basin-/threshold-relative persistence for positive Caputo/nonlocal systems;
- robust nonlinear threshold/persistence under order/parameter uncertainty;
- variable/distributed-order nonlinear threshold dynamics.

No candidate is selected.

## Survey objective

Once coverage is sufficiently mature, evaluate preparation of a survey/state-of-the-art paper.

The survey is a legitimate output of this project.

## Immediate Chief agenda

1. expand `research/DOMAIN_MAP.md`;
2. reconcile `theorem-map.md`, `frontier-map.md`, and `open-problems.md`;
3. build a nontrivial `opportunity-matrix.csv`;
4. assimilate ROUND-0010 when returned;
5. compare D10 versus narrowed D11 before launching the next depth wave;
6. maintain Double Allee proximity as a selection criterion;
7. only after broad coverage, recommend the most fertile gaps.
