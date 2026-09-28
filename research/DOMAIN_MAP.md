# Domain Map — Dynamical Systems and Stability Theory: Fractional Differential Equations

**Status:** ACTIVE MAP  
**Date:** 2026-09-28  
**Purpose:** organize theorem-level coverage and expose under-mapped branches.

This file describes the **map architecture and repository coverage**, not a claim that each branch is already exhaustively reviewed.

## Coverage labels

- **SEED:** only foundational/partial evidence exists.
- **MODERATE:** several theorem families and frontier threats are mapped.
- **DEEP:** strong theorem-level state-of-art coverage with recent and adjacent literature.
- **AUDIT NEEDED:** evidence exists but has not been reconciled into a reliable frontier statement.

| Branch | Scope | Current repo coverage | Immediate mapping need | Double Allee relevance |
|---|---|---|---|---|
| D1 Linear commensurate spectral stability | Matignon sectors, exact spectral criteria | MODERATE | strengthen theorem lineage and modern generalizations | medium |
| D2 Incommensurate / multi-order stability | characteristic roots, fractional spectrum, multi-order dynamics | MODERATE | generic local/linear gap narrowed by Diethelm et al. 2024; focus global nonlinear/persistence/bifurcation | medium-high |
| D3 Nonlinear local stability | linearization, indirect methods, local asymptotic stability | SEED | theorem conditions, converse/regularity limits | **high** |
| D4 Lyapunov / Mittag-Leffler / global stability | direct methods, ML stability, comparison | SEED | strongest converse/exactness results, conservatism | **high** |
| D5 Structured matrix stability | D-stability, diagonal stability, positive/Metzler, M-matrix, sign structure | MODERATE | map exact vs sufficient regional results | medium-high |
| D6 Robustness / uncertainty | coefficient, matrix, order and structural uncertainty | SEED | robust exactness, interval/order uncertainty | **high** |
| D7 Delay / neutral systems | fractional delay characteristic roots and Lyapunov criteria | SEED | canonical theorem map and sharpness | high |
| D8 Switching / impulsive / stochastic / hybrid | nonautonomous and random fractional dynamics | SEED | subfield architecture and strongest stability results | medium-high |
| D9 Networks / multi-agent systems | synchronization, consensus, graph stability, dispersal | SEED-MODERATE | distinguish topology-aware theorems from stacked models | **high** |
| D10 Bifurcation / multistability / tipping | folds, invariant/center manifolds, periodicity semantics, attractor changes, threshold geometry | MODERATE | ROUND-0010 active; 2018 center-stable and 2026 center-manifold results are major prior-art threats | **very high** |
| D11 Persistence / extinction / population dynamics | memory-state persistence, permanence, extinction, basin-/threshold-relative survival | MODERATE | broad semiflow gap closed; residual is ecological boundary/physical-state transfer, invasion/robust persistence, strong-Allee-relative formulations | **very high** |
| D12 Double / Multiple Allee | component/demographic effects, double dormancy, multiple mechanisms | DEEP relative to repo | integrate with FDE branches rather than isolate | **central lens** |
| D13 Identifiability / inverse problems | structural/practical ID for fractional dynamics | SEED-MODERATE | determine relevance to stability/threshold questions | high |
| D14 Variable/distributed/uncertain order dynamics | changing memory architecture | SEED | strongest stability theory and exactness gaps | medium-high |
| D15 PDE/spatial fractional dynamics | reaction-diffusion and spatially extended systems | SEED | separate time-fractional from space-fractional and network cases | high |

## Known anchor findings already established

### Linear/spectral
- commensurate Matignon-type sector stability is classical;
- noncommensurate exact BIBO formulations exist;
- broad claims of “fractional sector D-stability” are preempted by regional/generalized D-stability theory.

### Structured matrices
- exact classical D-stability results exist for several low-dimensional and structural classes;
- Metzler/positive systems have strong diagonal-stability machinery;
- generic conic-sector multiplicative D-stability is not an empty field.

### Double Allee
- multiple component Allee effects and double dormancy are established;
- direct fractional Double-Allee models exist;
- generic network/diffusion extensions are already crowded;
- mechanism-space/persistence-filter composition remains a candidate opportunity, not a selected direction.

## Immediate map deficiency

The repository is currently **too Double-Allee-heavy relative to the full domain**.

The weakest coverage is in:

- general nonlinear fractional stability;
- converse Lyapunov theory;
- fractional bifurcation theory;
- delay/neutral stability;
- uncertainty and order robustness;
- switching/stochastic/hybrid dynamics;
- variable/distributed-order stability.

These branches must be mapped before the Chief can compare research opportunities responsibly.

## Mapping principle

For every branch, identify:

1. foundational theorem;
2. strongest current theorem;
3. strongest exact/N&S result;
4. dominant sufficient-method family;
5. key restrictions;
6. recent frontier papers;
7. explicit open problems;
8. adjacent mathematics;
9. Double Allee relevance.

## End condition

The domain map is mature only when the Chief can compare candidate gaps across branches without one branch dominating merely because it was searched earlier.


## ROUND-0008 Chief correction

The breadth audit confirmed that the generic incommensurate/local-stability branch is more mature than previously mapped. It also elevated two under-mapped areas:

- **D10 rigorous fractional bifurcation/nonhyperbolic dynamics**
- **D11 abstract persistence/permanence**

A terminology warning applies to D11: Cresson–Szafrańska (2017) use “fractional persistence problem” for preservation of properties such as positivity/order/stability under fractional embedding; this is not the same as ecological uniform persistence/permanence.

ROUND-0009 is now testing whether D11 is genuinely new or already subsumed by hereditary/history-space theory.


## ROUND-0009 Chief correction

Doan–Kloeden's history-space construction means the broad statement “Caputo systems lack a semiflow” is false under their hypotheses, and Hale–Waltman-type persistence theory is already infinite-dimensional.

The D11 candidate therefore narrows to:

> **memory-state persistence for positive Caputo systems with a rigorously defined ecological extinction boundary, physical-state transfer, robust/invasion criteria, and basin-/threshold-relative variants compatible with strong Allee bistability.**

This is retained as a high-information candidate with substantial subsumption risk.

ROUND-0010 now audits D10. Independent Chief verification added an important 2026 prior-art threat: Liao–Wu–Li, DOI 10.1016/j.physd.2026.135122, proves existence conditions for center manifolds in fractional differential equations and cites earlier center-manifold/Lyapunov–Schmidt work.
