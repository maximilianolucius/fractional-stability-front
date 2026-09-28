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

---

## ROUND-0003 — Structured conic D-stability

### NC-201 — Finite exact conic-sector D-stability for structured ecological matrices

**Classification:** **OPEN ONLY FOR A SHARPLY SPECIFIED SUBCLASS**

Classical exact D-stability results already cover low dimensions, tridiagonal matrices and acyclic matrices; Metzler matrices have strong Hurwitz/diagonal-stability equivalences; general conic regional D-stability already exists.

No finite exact conic-sector criterion was identified for a biologically natural **cyclic, non-Metzler** class in the searched corpus.

**Main novelty threat:** Berman–Hershkowitz 1984 + Kushel–Pavani 2022.

---

## ROUND-0004 — Double dormancy/network

### NC-301 — General double-dormancy composition theorem

**Classification:** **PARTIAL / CLOSE PRIOR ART**

Lan 2025 directly develops rigorous threshold dynamics for a single-species model with two component Allee effects. Berec 2007 already supplies the defining two-component model and partial analytical root/stability structure. General emergent-Allee theorems also exist under stage/spatial mechanisms.

No searched source gives the proposed broad necessary-and-sufficient composition theorem over separately parameterized component fitness functions with uniqueness/multiplicity and comparative statics.

### NC-302 — Generic network transformation of an Allee/bistable threshold

**Classification:** **CLOSE PRIOR ART; BROAD VERSION EFFECTIVELY COVERED**

Stehlík–Švígler–Volek 2023 provides arbitrary-connected-graph persistence/extinction threshold theory for heterogeneous local growth including logistic/bistable reactions. Additional direct graph/metapopulation Allee prior art exists.

A surviving C-DA-2 theorem must retain the **component decomposition** as an essential variable rather than collapse every node to a generic bistable reaction.

---

## ROUND-0005 — Data/identifiability

### NC-401 — Joint component + threshold + fractional-memory identifiability from real ecological data

**Classification:** **WEAKENED / NO DIRECT JOINT RESULT FOUND**

No direct joint resolving result was found. But:
- Allee model discrimination and low-density data requirements have strong empirical/statistical prior art;
- structural identifiability for fractional systems and fractional networks already exists;
- fractional order and delay/noise can be jointly estimated in controlled system-identification settings.

The remaining opportunity is therefore not generic fractional identifiability. It is a carefully formulated **observation-design/minimal-data theorem** for component mechanisms and threshold emergence, with memory added only if separately identifiable.

### NC-402 — Island fox as immediately reusable open dataset

**Classification:** **NOT SUPPORTED**

No open machine-readable copy of the exact 1988–2000 Angulo dataset was located after explicit repository/agency searches. NPS monitoring infrastructure exists, so data may be obtainable, but open access cannot be claimed.

### NC-403 — Real-data branch overall

**Classification:** **VIABLE FOR COMPONENT/THRESHOLD INFERENCE; NOT YET FOR FRACTIONAL MEMORY**

Open herring, cod and freshwater-mussel datasets provide immediate benchmarks. Island fox and Crested Ibis are closer to multiple-component biology but require raw-data access follow-up.

---

## ROUND-0006 — Final mechanism-resolved novelty gate

### NC-501 — Strict-unimodal threshold classification and fold

**Classification:** **COVERED AFTER REFORMULATION**

Once strict unimodality of (V) is assumed, the zero/two level-crossing classification from endpoint and maximum values is standard scalar analysis. The boundary (V=1, V'=0) with nonzero second derivative is standard saddle-node/fold geometry.

Do not claim Candidate Theorem A as standalone novelty.

### NC-502 — General mechanism-resolved double-dormancy composition

**Classification:** **NO RESOLVING RESULT FOUND IN SEARCHED CORPUS**

Direct threats include Berec 2007, Lan 2025, Pavlová–Berec–Boukal 2010, Rodriguez 1988, Feldman–Morris 2011 and Buddh–Krishna–Agashe 2024.

No searched source gives a reusable necessary-and-sufficient theorem over separately interpretable positive component functions with:
- explicit deletion counterfactuals;
- singleton non-strongness;
- joint strong-threshold creation;
- nontrivial root-count control;
- mechanism-specific threshold comparative statics.

**Caution:** the frozen low-density wedge plus assumed joint unimodality is nearly definitional/elementary. Novelty survives only if the theorem derives substantive shape/interaction consequences from component-level hypotheses.

### NC-503 — Factorization gauge as new identifiability principle

**Classification:** **COVERED AFTER REFORMULATION**

Yates–Evans–Chappell 2009 establishes observation-preserving model symmetries as structural-identifiability transformations. Massonis–Villaverde 2020 develops symmetry detection/breaking, and identifiable-combination theory treats composite functions of individually unidentifiable quantities.

The frozen (A_i	o A_i h_i), (prod h_i=1) transformation is an immediate output/vector-field-preserving symmetry.

The ecological nonparametric ((m-1))-function interpretation was not found verbatim, but is not sufficiently distinct to support a general novelty claim.

### NC-504 — Minimal component-output theorem as general novelty

**Classification:** **COVERED AFTER REFORMULATION**

Joubert–Stigter–Molenaar 2018 explicitly formulates and computes minimal output sets guaranteeing structural identifiability.

Integrated population model literature already combines abundance and demographic data streams to identify survival/reproduction processes.

A new result would require realistic ecology-specific observation operators or a nontrivial functional-identifiability theorem, not direct observation (y_i=A_i(x)).

### NC-505 — Implicit threshold comparative statics identity

**Classification:** **COVERED AFTER REFORMULATION**

The frozen derivative
[
da/d	heta=-partial_	hetalog V/partial_xlog V
]
is the implicit-function theorem. Only component-level sign/order consequences beyond the formula could contribute novelty.

### NC-506 — Network/fractional invariance of product ambiguity

**Classification:** **COVERED AFTER REFORMULATION**

If the factor transformation leaves each local RHS exactly unchanged and known network coupling is factor-independent, the full vector field remains unchanged. A fixed Caputo left-hand-side operator likewise cannot distinguish two parameterizations with identical RHS.

These are immediate corollaries once NC-503 is recognized.

### NC-507 — Integrated forward + inverse program

**Classification:** **CLOSE PRIOR ART — NARROW FURTHER**

No single prior work was identified that couples a general component-deletion double-dormancy composition theorem to mechanism-attribution identifiability in the same ecological framework.

However the inverse mathematics is standard at the abstract level. The defensible novelty core, if any, is the strengthened forward component-composition theorem; the inverse part is best positioned as a rigorous scientific consequence and observation-design layer.

---

## ROUND-0007 — Mechanism-space geometry

### NC-601 — Convexity/half-space representation of extinction region

**Classification:** **MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT**

For (M(lambda)=sup_x[b(x)-lambdacdot g(x)]), convexity is the standard supremum-of-affine-functions result. The representation
[
mathcal E=igcap_x{lambda:lambdacdot g(x)ge b(x)}
]
is a linear semi-infinite feasible set; López–Still 2007 supplies the generic optimization framework.

Novelty cannot rest on convexity or the intersection-of-halfspaces fact.

The ecological distinction not found in the searched corpus is the exact decomposition of mechanism space into low-density failure (mathcal L), global extinction (mathcal E), and the strong-Allee phase (mathcal Lsetminusmathcal E).

### NC-602 — Exact radial strong-Allee window

**Classification:** **MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT**

The critical values (t_0) and (t_E) arise by intersecting the two phase boundaries with a ray. Delmas–Dronnier–Zitt provide close population-level vector-intervention/ray analogues, but no searched result gives the same low-density-failure → strong-Allee → extinction sequence for mechanism-resolved Allee effects.

Retain as a corollary of the phase geometry, not a standalone deep theorem.

### NC-603 — Weighted minimal threshold-generating coalitions

**Classification:** **CLOSE PRIOR ART — NARROW**

The low-density condition
[
sum_{iin S}w_i>b(0)
]
with loss of the condition after deleting any member is exactly a minimal winning coalition of a weighted threshold game. Antichain/Sperner and pivotality consequences are standard.

The residual ecological object is the **persistence-filtered** family satisfying simultaneously
[
F_S(0)<0<M_S.
]

No searched weighted-game, reliability, or multiple-Allee source classifies these coalitions using the full density profiles (g_i(x)).

### NC-604 — Inclusion-chain contiguity / antichain claims

**Classification:** **COVERED AFTER REFORMULATION**

Low-density failure is an upset; persistence is a downset; their intersection is order-convex. Contiguous blocks on chains and antichain minimal elements are generic poset consequences.

Do not claim these as new combinatorics.

### NC-605 — Boundary normal (
abla M=-g(x^*))

**Classification:** **COVERED AFTER REFORMULATION**

This is the unique-maximizer form of Danskin's theorem applied to the value function (M). The biological interpretation is useful, but the derivative/normal formula is standard.

### NC-606 — P2–P4 combined ecological theorem

**Classification:** **NO RESOLVING RESULT FOUND IN SEARCHED CORPUS**

No single source identified in ROUND-0007 gives both:
1. continuous mechanism-strength phase geometry separating low-density failure, strong-Allee persistence, and extinction; and
2. minimal mechanism subsets that cross the local failure boundary while remaining globally persistent.

This integrated statement remains defensible, provided the manuscript explicitly credits the standard convex-analysis and weighted-game ingredients and derives new consequences from the persistence filter.

### NC-607 — Main remaining novelty burden

**Classification:** **OPEN THEOREM-SPECIFIC TARGET**

The strongest next mathematical target is not another convexity/antichain lemma. It is a structural theorem for the persistence-filtered coalition family, potentially involving:
- profile-level necessary/sufficient conditions;
- realizability restrictions;
- bounds sharper than generic Sperner;
- transitions between discrete coalitions and continuous extinction-boundary faces;
- algorithmic consequences of the entire (g_i(x)) profiles.

---

## ROUND-0009 — Fractional uniform persistence / permanence

### NC-901 — Abstract general Caputo persistence theorem

**Classification:** **NO RESOLVING ABSTRACT RESULT FOUND; MODEL-SPECIFIC PRIOR ART EXISTS**

Fractional ecological/epidemic papers prove persistence/permanence model by model, but no general Caputo theorem comparable to Hale–Waltman/Thieme was identified.

### NC-902 — Caputo lacks a semiflow and therefore needs wholly new persistence theory

**Classification:** **FALSE**

Doan–Kloeden 2021 constructs a legitimate infinite-dimensional semigroup for the singular Volterra representation on C(R_+,R^d). Modern 2024–2026 work adds skew-products, dissipativity, compact absorbing sets and attractors.

### NC-903 — Existing history-space persistence theory automatically solves Caputo persistence

**Classification:** **PARTIAL / UNRESOLVED**

Hale–Waltman and hereditary persistence theory provide the abstract machinery, but no general source was found constructing the ecological positive history state, invariant extinction boundary and physical-state transfer for Caputo systems.

The constant-function manifold encoding physical initial data is generally not invariant in the full Volterra semiflow.

### NC-904 — Asymptotic compactness / attractor theory is missing for Caputo

**Classification:** **LIKELY COVERED UNDER MODERN DISSIPATIVITY HYPOTHESES**

Cui–Kloeden 2024 and Cui–Kloeden–Xin 2026 provide substantial attractor/compactness machinery.

### NC-905 — Robust persistence/invasion criteria for general fractional ecology

**Classification:** **NO RESOLVING RESULT FOUND IN SEARCHED CORPUS**

Ordinary robust permanence and invasion-rate theory is mature; no general Caputo memory-state analogue was found for perturbations of vector field/order/kernel or invariant-measure invasion criteria.

### NC-906 — Global uniform persistence is the natural Double-Allee bridge

**Classification:** **STRUCTURALLY MISMATCHED**

Strong Allee dynamics intentionally has positive initial states in the extinction basin. Global persistence of every positive initial condition contradicts that structure.

The appropriate bridge is basin-/threshold-relative persistence.

### NC-907 — Basin-relative/conditional persistence itself is novel

**Classification:** **DIRECT PRIOR CONCEPT FOUND**

Roth–Schreiber 2014 studies conditional persistence in stochastic Allee models, and abstract persistence theory already permits persistence relative to chosen subsets/persistence functions.

The potential novelty is specifically the Caputo memory-state construction and physical-transfer theorem.

### NC-908 — D11 narrowed opportunity

**Classification:** **CREDIBLE SEARCH-QUALIFIED CANDIDATE**

Best current formulation:

Persistence theory for positive Caputo systems on the Volterra memory state, including explicit transfer to physical populations, robust/invasion criteria, and basin-relative variants for strong/Double-Allee dynamics.

Main killer risk: once the correct invariant positive memory space is chosen, classical infinite-dimensional persistence theorems may apply with only routine verification.

