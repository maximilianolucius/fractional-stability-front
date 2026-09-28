# 2026-09-28 — Fractional Stability Seed

**Round:** ROUND-0001  
**Request:** `research/coordination/chief-to-web/ROUND-0001_fractional-stability-seed_REQUEST.md`

## 1. Question investigated

What is the exact theorem-level core for finite-dimensional linear autonomous fractional systems, and does a general theory already exist for positive diagonal scaling while preserving a fractional-sector spectral region?

## 2. Canonical commensurate core

### Matignon (1998)

Primary source: Denis Matignon, *Stability properties for generalized fractional differential systems*, ESAIM Proceedings 5 (1998), 145–158. DOI: 10.1051/proc:1998004.

For the commensurate transfer-function/state-space setting with fractional order (gamma), (0<gamma<2), the canonical condition is spectral-sector exclusion:

[
|arg lambda| > rac{gammapi}{2}
]

for asymptotic stability (with the corresponding polynomial-root formulation in the transfer-function representation).

**Important reading caution.** The 1998 paper uses the generalized fractional-system/relaxed-state framework of its time. It should not be retrospectively described as a modern Caputo theorem without checking the derivative/initial-condition formulation.

### Caputo clarification

Brandibur–Garrappa–Kaslik (2021), DOI 10.3390/math9080914, gives a careful modern treatment of Caputo systems and explicitly distinguishes:
- asymptotic stability, requiring strict sector placement;
- non-asymptotic stability at the sector boundary, where the eigenvalue index/Jordan structure matters.

The review notes/corrects a common imprecision involving geometric multiplicity versus eigenvalue index.

**Extraction consequence.** The theorem corpus must record not just eigenvalue angle but strict versus boundary conditions and the exact stability notion.

## 3. Incommensurate/non-commensurate core

Sabatier–Farges–Trigeassou (2013), DOI 10.1016/j.sysconle.2013.04.008, gives a necessary-and-sufficient BIBO stability test for non-commensurate fractional-order systems. The method is not simply “apply Matignon to (A)”: it uses a recursively constructed closed-loop realization and a Cauchy-theorem/root-location test.

This is the strongest general exact non-commensurate result identified in the seed search. It means a blanket statement that “incommensurate systems lack exact stability tests” is false.

A separate question remains whether broad classes admit a simple arbitrary-dimensional algebraic/spectral characterization comparable in simplicity to the commensurate Matignon criterion.

## 4. Stability-notion separation

Li–Chen–Podlubny (2009), DOI 10.1016/j.automatica.2009.04.003, develops Mittag-Leffler stability for nonlinear fractional systems using fractional Lyapunov/comparison arguments.

The seed therefore supports keeping at least the following separate:
- asymptotic state stability;
- boundary/non-asymptotic stability;
- Mittag-Leffler stability;
- BIBO stability;
- quadratic/robust stability.

These should not be treated as interchangeable corpus labels.

## 5. LMI formulations: exactness versus certificates

Sabatier–Moze–Farges (2010), DOI 10.1016/j.camwa.2009.08.003, is an important LMI source.

Recent work shows that LMI formulations are not automatically “merely sufficient”:
- X. Zhang & Y. Di (2026), DOI 10.1016/j.isatra.2026.03.026, develops alternative equivalent LMI formulations for LTI fractional stability.
- J.-X. Zhang et al. (2026), DOI 10.1016/j.amc.2026.130036, gives a general LMI formulation; the inspected theorem includes an iff condition for the (alphain(0,1)) case and a unified treatment across the relevant order ranges.

**Protocol consequence.** “LMI” is a proof/representation method, not a theorem-strength category. Each LMI criterion must independently be tagged exact/sufficient/etc.

## 6. Falsification of the fractional D-stability bridge

### Terminology split

There are at least two incompatible uses of “D-stability” relevant to searches:

1. **Classical multiplicative D-stability:** (DA) remains stable for every positive diagonal (D).
2. **(mathcal D)-stability / regional stability:** eigenvalues lie in a prescribed region (mathcal D).

A paper title containing “D-stability” is therefore not enough to establish relevance.

### Direct prior art: Kushel–Pavani

Kushel–Pavani, *The Problem of Generalized D-Stability in Unbounded LMI Regions and Its Computational Aspects*, Journal of Dynamics and Differential Equations 34 (2022), 651–669, DOI 10.1007/s10884-020-09891-y, directly defines multiplicative ((mathfrak D,D))-stability:
- the stability region (mathfrak D) is an LMI region;
- the transformation is positive diagonal left scaling (DA);
- conic sectors are treated as a principal case (“relative D-stability”).

The inspected paper supplies:
- a forbidden-boundary exact characterization for multiplicative regional D-stability;
- equivalent determinant/boundary conditions for conic sectors;
- an exact lifted-matrix/additive-compound characterization for relative D-stability.

The exact conditions are mathematically substantive, but some remain universally quantified over all positive diagonal scalings. Therefore they do not automatically solve every computational/structural characterization problem.

Kushel–Pavani (2021), DOI 10.1016/j.laa.2021.08.004, develops generalized diagonal dominance for LMI regions and applies conic-sector dominance to matrix D-stability; the author manuscript explicitly notes fractional-order applications.

### Result of falsification search

**Classification:** DIRECT PRIOR RESULT FOUND.

The hypothesis

> “positive diagonal scaling with respect to a fractional Matignon sector appears unstudied”

does **not** survive.

A narrower structural question may remain—e.g. exact finite tests for sign/graph classes, tractability, dimension-independent criteria, or sharp subclass characterizations—but those require a new request and cannot be inferred from phrase scarcity.

## 7. Positive/Metzler bridge

Zhang–Huang (2017), DOI 10.1016/j.laa.2017.06.018, studies an extension of diagonal stability and stabilization for continuous-time fractional positive linear systems and reports necessary-and-sufficient conditions within that framework.

This is direct prior art for the “fractional positive + diagonal stability” bridge but should not be conflated with unrestricted multiplicative D-stability.

## 8. Robust interval caution

Ahn–Chen (2008), DOI 10.1016/j.automatica.2008.07.003, is frequently described as providing a necessary-and-sufficient robust interval condition using a common Hermitian/Lyapunov matrix.

A later clarification by Ahn et al. (2014), arXiv:1407.3523, explains that the exact interpretation concerns **quadratic stability**. This is a concrete example of why the project must audit the quantified stability notion rather than reproduce abstracts.

Zheng (2017), DOI 10.1016/j.sysconle.2016.11.001, provides necessary-and-sufficient graphical criteria for fractional systems with general interval uncertainties in coefficients and orders, showing that robust exact results exist beyond simple LMIs.

## 9. Current strongest novelty threats

1. Kushel–Pavani 2022 destroys a broad “fractional-sector multiplicative D-stability is unstudied” claim.
2. Kushel–Pavani 2021 supplies tractable sufficient structured criteria linked to fractional conic sectors.
3. Zhang–Huang 2017 already covers an important positive-system diagonal-stability bridge.
4. 2026 exact LMI work shows that merely producing another equivalent fixed-matrix LTI criterion is unlikely to be structurally novel.
5. Non-commensurate exact BIBO testing exists.

## 10. Unresolved questions deserving a later round

- Does multiplicative conic-sector D-stability admit a finite, quantifier-free exact characterization on important matrix/sign/graph classes?
- Which complexity/impossibility results are known for generalized/relative D-stability?
- Can qualitative/sign patterns certify multiplicative conic-sector D-stability?
- What are the exact logical relations between diagonal Lyapunov stability, multiplicative regional D-stability, and generalized diagonal dominance on Metzler/positive classes?
- What is the strongest arbitrary-dimensional exact state-stability theorem for genuinely incommensurate Caputo systems, beyond BIBO/root algorithms and low-dimensional explicit regions?

## 11. Search limitation statement

This is a high-value seed, not an exhaustive systematic review. Absence from this note must not be interpreted as absence from the literature.

## RETURN TO CHIEF

### Strongest evidence
The commensurate exact core is mature; an exact non-commensurate BIBO test exists; and generalized multiplicative D-stability in conic/LMI regions is direct prior art.

### Evidence against novelty
The broad fractional-sector D-stability bridge is already covered at theorem level by matrix-analysis literature.

### Remaining opportunity
Potentially narrower structural/exactness/computational subclasses, not the broad existence question.

### Recommended next search
A dedicated matrix-analysis round on **relative/conic-sector D-stability**, finite characterizations, qualitative/sign classes, complexity, and exact subclass results.