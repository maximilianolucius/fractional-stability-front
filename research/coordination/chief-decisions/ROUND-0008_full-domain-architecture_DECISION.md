# ROUND-0008 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** `research/coordination/web-to-chief/ROUND-0008_full-domain-architecture_RETURN.md`  
**Disposition:** ACCEPT WITH MAP CORRECTIONS — BREADTH AUDIT SUCCESSFUL; OPEN DEPTH-FIRST PHASE

## 1. Executive decision

ROUND-0008 materially improves the project because it corrects the earlier Double-Allee-heavy sampling bias.

The broad domain now shows a clear asymmetry:

- the **linear/spectral core** of fractional stability is substantially more mature than the seed map implied;
- the less unified frontier lies in genuinely dynamical nonlocal questions: bifurcation, invariant sets, persistence/extinction, changing memory, hybrid dynamics, and global spatial behavior.

No research winner is selected.

## 2. Accepted map corrections

### 2.1 Incommensurate local/linear stability is much more mature

Diethelm, Hashemishahraki, Thai & Tuan (2024), DOI `10.1016/j.jmaa.2024.128642`, gives a constructive modern framework including a necessary-and-sufficient rational-order criterion and a general-order fractional-spectrum approximation/equivalence, with nonlinear linearized stability in arbitrary finite dimension.

**Decision:** the prior broad candidate “incommensurate state-stability characterization” is no longer defensible as stated.

Residual interest must be global nonlinear, persistence, nonhyperbolic/bifurcation, robustness, or structured multi-order dynamics.

### 2.2 Broad converse-Lyapunov absence is false

Gallegos & Duarte-Mermoud (2019), DOI `10.3906/mat-1808-75`, gives converse Lyapunov/Mittag-Leffler results.

The 2025 FOISS converse work further strengthens this branch.

**Decision:** “fractional converse Lyapunov theory is missing” is closed as a broad gap.

### 2.3 Generic linear robust uncertainty is not a clean gap

Exact/N&S linear robust results exist for important interval/mixed uncertainty classes.

**Decision:** retain robustness only when it becomes nonlinear, threshold/persistence, changing-order, or otherwise structurally distinct.

### 2.4 Generic delay stability is too broad

The 2025 Zhang–Jin–Lu–Zhu result gives N&S delay-independent stability with an exact generalized-KYP/LMI representation.

**Decision:** any future delay candidate must be delay-dependent, neutral, nonlinear, incommensurate, or nonhyperbolic/threshold-specific.

### 2.5 Fractional bifurcation requires semantic/theorem reconstruction

Tavazoei–Haeri (2009), DOI `10.1016/j.automatica.2009.04.001`, establishes nonexistence of nonconstant exactly periodic solutions for the autonomous finite-lower-terminal Caputo setting considered there, including commensurate and incommensurate cases.

Yazdani–Salarieh (2011), DOI `10.1016/j.automatica.2011.04.013`, shows the statement must not be overgeneralized to all notions of steady-state/infinite-memory periodic behavior.

Doan–Kloeden (2022), DOI `10.1007/s13540-022-00030-6`, gives rigorous attractor and saddle-node/pitchfork results for a structured Caputo class.

**Decision:** D10 is a high-value depth-search branch. The gap is not “fractional bifurcation does not exist”; it is the exact architecture connecting nonhyperbolic equilibria, attractor changes, spectral crossings, finite-memory nonperiodicity, and admissible oscillatory notions.

## 3. Chief correction to D11 terminology

A source not emphasized in the return is:

Cresson & Szafrańska, *Discrete and continuous fractional persistence problems – the positivity property and applications*, DOI `10.1016/j.cnsns.2016.07.016`.

Its phrase **fractional persistence problem** does **not** mean ecological uniform persistence/permanence. It concerns persistence under fractional embedding of properties such as:
- positivity;
- order preservation;
- equilibrium points;
- stability.

Therefore it does not directly kill GAP-08-B, but it creates a serious terminology trap.

There are also model-specific Caputo ecological papers proving permanence/persistence, e.g. Abbas et al. (2016), DOI `10.1007/s12591-014-0219-5`.

The candidate must therefore be stated narrowly:

> **No abstract boundary-repeller / invasion-type uniform-persistence or permanence framework for general positive Caputo/nonlocal systems, comparable in role to mature local-semiflow/hereditary persistence theory, has yet been identified in the searched corpus.**

This remains a **search hypothesis**, not a novelty claim.

## 4. Adjacent killer literature for the persistence candidate

The next audit must search beyond the word “fractional” and beyond ecological model papers.

Relevant mature adjacent theories include:
- uniform persistence for continuous processes/skew-product semiflows;
- local dynamical systems;
- hereditary/functional differential equations;
- Volterra integral equations;
- infinite-delay systems;
- monotone dynamical systems;
- history-space/cocycle formulations.

If Caputo systems can be embedded into a history-state dynamical system to which an existing general persistence theorem applies essentially verbatim, the candidate may collapse from a new theorem gap to an application/translation gap.

That is the principal falsification target.

## 5. Candidate frontier disposition after ROUND-0008

### Retain for depth search
- **D10:** rigorous fractional bifurcation / nonhyperbolic threshold dynamics.
- **D11:** abstract uniform persistence/permanence for fractional/nonlocal systems.
- **D6 nonlinear:** robust threshold/persistence under order/parameter uncertainty.
- **D12:** variable/distributed-order nonlinear dynamics.
- **D7 residual:** exact delay-dependent / neutral nonlinear stability.
- **D2 residual:** global nonlinear incommensurate stability/persistence.

### Deprioritize as broad gaps
- fixed commensurate spectral criteria;
- generic incommensurate local stability;
- generic converse Lyapunov theory;
- generic linear robust uncertainty;
- generic delay-independent linear stability;
- generic fractional consensus;
- cosmetic Double-Allee fractionalization.

## 6. Why D11 gets the next round

D11 is selected for the **next evidence round**, not as a final research direction, because:

1. it is directly connected to extinction/persistence, hence to strong and Double Allee dynamics;
2. ROUND-0008 found a striking asymmetry between mature local persistence theory and model-specific fractional results;
3. the candidate has a clear killer test: hereditary/history-space theory may already subsume it;
4. resolving that killer test has high information value for both the opportunity portfolio and a future survey.

D10 remains the next-highest priority after D11.

## 7. Consequences for repository maps

- `OPPORTUNITY-FS-02` must be narrowed away from generic incommensurate local stability.
- Add D10 and D11 as **unverified high-priority candidate frontier areas**.
- Add the Cresson–Szafrańska terminology warning.
- Survey readiness remains **NO**.

## 8. Next round

Open:

`ROUND-0009_fractional-uniform-persistence-falsification_REQUEST.md`

This is a depth-first adversarial audit of abstract persistence/permanence, with explicit hereditary/Volterra/history-state search.

