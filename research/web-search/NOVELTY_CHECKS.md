# Novelty Checks

**As of:** 2026-09-28  
**Rule:** These classifications describe the searched corpus. They are not final scientific decisions.

## ROUND-0001 — Fractional stability

### NC-001 — Positive diagonal scaling relative to a fractional/sector stability region

**Formalized claim.** For a matrix (A), characterize whether (sigma(DA)) remains in a conic fractional stability region for every positive diagonal (D).

**Classification:** **DIRECT PRIOR RESULT FOUND**

**Evidence.**
Kushel–Pavani (2022, DOI 10.1007/s10884-020-09891-y) explicitly defines multiplicative ((mathfrak D,D))-stability for LMI regions and treats conic sectors (“relative D-stability”), with exact boundary-avoidance/equivalent criteria. Their earlier 2021 LAA paper (DOI 10.1016/j.laa.2021.08.004) supplies generalized diagonal-dominance sufficient conditions and explicitly connects conic-region results to fractional-order systems.

**Consequence for novelty.**
The broad statement “fractional sector D-stability under arbitrary positive diagonal scaling is unstudied” is false in the searched corpus.

**Remaining uncertainty.**
A narrower question may remain around finite/tractable, quantifier-free exact characterizations, special graph/sign classes, or structural criteria. A dedicated matrix-analysis follow-up is required before elevating any such gap.

---

### NC-002 — Exact finite-dimensional commensurate LTI fractional stability

**Classification:** **LIKELY ALREADY COVERED**

Matignon's sector criterion and numerous exact/equivalent LMI reformulations make the unstructured fixed-matrix problem a mature core. Novelty must come from additional structure, uncertainty, topology, converse, complexity, or nonlinear phenomena.

---

### NC-003 — Exact non-commensurate/incommensurate linear stability

**Classification:** **PARTIAL PRIOR ART / DIRECT EXACT TEST FOUND**

Sabatier–Farges–Trigeassou (2013, DOI 10.1016/j.sysconle.2013.04.008) supplies a necessary-and-sufficient BIBO test for non-commensurate systems. Low-dimensional exact multi-order state-space regions also exist. The existence of a simpler arbitrary-dimensional structural characterization is a separate question and was not resolved by this seed.

---

### NC-004 — Fractional positive-system diagonal stability

**Classification:** **DIRECT PRIOR RESULT FOUND**

Zhang–Huang (2017, DOI 10.1016/j.laa.2017.06.018) gives necessary-and-sufficient conditions for an extension of diagonal stability/stabilization in continuous-time fractional positive linear systems. The exact notion must not be conflated with general multiplicative D-stability.

---

### NC-005 — “Fractional D-stability” exact phrase

**Classification:** **AMBIGUOUS — TERMINOLOGY COLLISION**

Control literature uses “D-stability” for eigenvalues constrained to a specified region (mathcal D), while matrix analysis uses D-stability for (DA) Hurwitz/stable for every positive diagonal (D). Every future novelty claim must define the transformation explicitly.

---

### NC-006 — Robust interval fractional stability from a common LMI

**Classification:** **CLOSE PRIOR ART WITH CORRECTION RISK**

Ahn–Chen (2008) was later clarified (Ahn et al. 2014, arXiv:1407.3523): the exact common-matrix condition should be interpreted as quadratic stability rather than silently as conventional robust stability. Robust claims require assumption-level auditing.

---

## ROUND-0002 — Double/Multiple Allee

### NC-101 — “Double Allee effect” means two demographic thresholds

**Classification:** **AMBIGUOUS — MORE SEARCH/DEFINITION REQUIRED**

Foundational ecology and mathematical-model papers do not support one universal meaning. “Multiple Allee effects” often means multiple component mechanisms, while common mathematical “double Allee” prey-growth laws combine a strong threshold factor with a low-density saturating factor. Future work must define the threshold/equilibrium geometry directly.

---

### NC-102 — Double Allee + Caputo fractional memory

**Classification:** **DIRECT PRIOR RESULT FOUND**

Rahmi et al. (2021, DOI 10.3390/fractalfract5030084) already combine a Double Allee effect with Caputo memory and prove well-posedness/boundedness plus local and sufficient global stability results. Several 2025–2026 extensions exist.

**Consequence.**
Merely fractionalizing a known Double-Allee predator–prey ODE is not a defensible novelty claim.

---

### NC-103 — Double Allee + incommensurate fractional orders

**Classification:** **DIRECT PRIOR RESULT FOUND**

R. Mondal et al. (2025, DOI 10.1016/j.cjph.2025.09.020) explicitly studies a fractional Double-Allee predator–prey system including incommensurate-order dynamics, multistability and basin stability.

---

### NC-104 — Double Allee + spatial diffusion

**Classification:** **DIRECT PRIOR RESULT FOUND**

Li–Li (2024, DOI 10.3934/math.20241309) studies a diffusive predator–prey system with Double Allee effect and analytical/pattern-formation results.

---

### NC-105 — Double Allee + network topology gives a general exact threshold theorem

**Classification:** **PARTIAL PRIOR ART / NO DIRECT GENERAL RESULT FOUND IN SEARCHED SEED**

No general graph-theoretic Double-Allee theorem was identified in this seed. However, Lanchier (2013, DOI 10.1239/aap/1386857863) already proves topology/geometry-sensitive persistence/extinction results for interacting patches with a strong Allee effect. This is a serious adjacent-theory novelty threat.

**Required follow-up.**
Search deterministic graph Laplacian, stochastic patch process, metapopulation rescue, bistable network, pinning, and monotone-system formulations without “Double Allee” vocabulary.

---

### NC-106 — Data-constrained joint identification of two-threshold Allee geometry and fractional memory

**Classification:** **NO PRIOR RESULT FOUND IN SEARCHED CORPUS**

No source in this seed jointly established structural/practical identifiability of a genuinely multi-threshold Allee mechanism and fractional order from a real ecological dataset.

**Limitation.**
This result is search-dependent, not proof of absence. A dedicated inverse-problem/data search is mandatory before treating it as a candidate frontier.

---

### NC-107 — Multiple component Allee mechanisms occur in real systems

**Classification:** **DIRECT PRIOR EVIDENCE FOUND**

Berec–Angulo–Courchamp (2007) synthesizes multiple empirical examples. In addition, Angulo et al. (2007, DOI 10.1111/j.1523-1739.2007.00721.x) directly analyzed island-fox demographic data from 1988–2000 and reported a double component Allee effect affecting survival and the proportion of breeding females, with a resulting demographic effect and suboptimal growth below about 7 foxes/km^2. This is direct empirical support for compound component mechanisms, but it does not establish two demographic thresholds or a fractional-memory law.