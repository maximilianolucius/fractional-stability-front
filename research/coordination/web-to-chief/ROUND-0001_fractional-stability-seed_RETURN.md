# ROUND-0001 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** `research/coordination/chief-to-web/ROUND-0001_fractional-stability-seed_REQUEST.md`  
**Status:** COMPLETE FOR SEED SCOPE

## Executive finding

The foundational exact stability core is recoverable and internally distinguishable, but the main bridge hypothesis requires substantial revision.

The classical commensurate finite-dimensional problem has the expected exact Matignon spectral-sector characterization. Modern Caputo literature clarifies boundary stability and eigenvalue-index/Jordan conditions. A necessary-and-sufficient BIBO test exists for non-commensurate systems.

Most importantly, the aggressive falsification search found **direct matrix-analysis prior art for multiplicative positive-diagonal D-stability in conic/LMI regions**. Kushel–Pavani (2022) treats exactly the abstract structure needed to model preservation of a Matignon-like conic sector under (DA), (D>0) diagonal. Therefore a broad claim that “fractional-sector D-stability under diagonal scaling is missing” is not defensible.

## Search coverage

### Sources/databases

Primary publisher/journal pages, DOI-indexed web search, PubMed where relevant, arXiv/author manuscripts, citation/author follow-up searches, and conference metadata.

### Query families

The complete representative registry is in:
`research/web-search/QUERY_REGISTRY.md`

Families included:
- Matignon / exact commensurate stability;
- Caputo clarification;
- incommensurate/non-commensurate exact stability;
- Mittag-Leffler versus asymptotic/BIBO notions;
- LMI exactness;
- fractional D-stability;
- conic-sector/relative/generalized D-stability;
- diagonal scaling in LMI regions;
- positive/Metzler diagonal stability;
- interval/robust exactness and corrections;
- current 2026 exact LTI criteria.

### Citation expansion

Performed around Matignon, Sabatier/Farges/Trigeassou, Kushel/Pavani, Zhang/Huang, and interval-uncertainty papers. Same-author follow-ups were specifically searched where a result looked capable of closing the working gap.

### Recent-literature check

2026 LTI fractional stability papers were found in ISA Transactions and Applied Mathematics and Computation. They reinforce that equivalent exact fixed-matrix LTI criteria remain an active but mature subfield.

## Strongest evidence found

### 1. Exact commensurate spectral criterion

Matignon (1998), DOI 10.1051/proc:1998004, gives the canonical spectral-sector criterion for commensurate finite-dimensional generalized fractional systems.

Brandibur–Garrappa–Kaslik (2021), DOI 10.3390/math9080914, provides a careful Caputo formulation and distinguishes strict asymptotic stability from boundary stability, with the correct eigenvalue-index condition.

### 2. Exact non-commensurate test

Sabatier–Farges–Trigeassou (2013), DOI 10.1016/j.sysconle.2013.04.008, gives a necessary-and-sufficient BIBO stability test for non-commensurate fractional systems using a recursively defined realization/root test.

### 3. Direct generalized multiplicative D-stability prior art

Kushel–Pavani (2022), DOI 10.1007/s10884-020-09891-y:
- defines multiplicative ((mathfrak D,D))-stability for LMI regions;
- includes conic-sector “relative D-stability”;
- gives exact forbidden-boundary and equivalent conic-sector criteria;
- gives an exact lifted/additive-compound characterization.

Kushel–Pavani (2021), DOI 10.1016/j.laa.2021.08.004, supplies generalized diagonal-dominance sufficient conditions for LMI-region D-stability and explicitly links conic-region results to fractional-order stability.

### 4. Positive-system diagonal stability prior art

Zhang–Huang (2017), DOI 10.1016/j.laa.2017.06.018, gives necessary-and-sufficient results for an extension of diagonal stability/stabilization in continuous-time fractional positive linear systems.

### 5. Robust-result correction example

Ahn–Chen (2008), DOI 10.1016/j.automatica.2008.07.003, is followed by Ahn et al. (2014), arXiv:1407.3523, clarifying the exact common-matrix result as quadratic stability. This directly validates the repository rule that theorem strength and stability notion must be audited beyond abstracts.

## Closest prior art

The closest prior art to the hypothesized “fractional D-stability” bridge is not an application paper but the generalized matrix theory of Kushel–Pavani.

Mathematically, the relevant object is:

[
A mapsto DA,qquad D>0	ext{ diagonal},
]

with (sigma(DA)) required to remain in a conic LMI region.

That is already studied as **multiplicative generalized/relative D-stability**.

## Evidence against novelty

### Working hypothesis H2

> The interaction between positive diagonal scaling and Matignon-sector stability may be substantially undeveloped.

**Seed finding:** weakened strongly.

A direct general framework exists. A new project could still target a sharper subclass/exact finite characterization, complexity barrier, sign/topology theorem, or nonlinear application whose Jacobian family has special structure, but the broad bridge itself cannot be presented as new.

### Terminology hazard

The 2017 conference title *Necessary and sufficient D-stability condition of fractional-order linear systems* (DOI 10.23919/ChiCC.2017.8027318) appears to use “D-stability” in the regional-control sense. It is retained as **AMBIGUOUS** until full transformation definitions are verified. This source must not be used to conflate regional (mathcal D)-stability with multiplicative matrix D-stability.

## Negative searches and limitations

No general finite, quantifier-free, arbitrary-dimensional characterization of multiplicative conic-sector D-stability was identified in this seed. This is **not** proof that none exists.

The seed does not exhaust:
- classical matrix-analysis monographs on D-stability;
- all qualitative/sign-stability literature;
- complexity/impossibility results;
- all incommensurate state-stability formulations;
- every structured robust-control variant.

## Dataset findings

Not applicable to this round.

## Source registry

See:
- `research/web-search/SOURCE_REGISTRY.md`
- `research/web-search/2026-09-28_fractional-stability-seed.md`

High-value identifiers include:
- 10.1051/proc:1998004
- 10.3390/math9080914
- 10.1016/j.sysconle.2013.04.008
- 10.1007/s10884-020-09891-y
- 10.1016/j.laa.2021.08.004
- 10.1016/j.laa.2017.06.018
- 10.1016/j.automatica.2008.07.003
- arXiv:1407.3523
- 10.1016/j.sysconle.2016.11.001
- 10.1016/j.isatra.2026.03.026
- 10.1016/j.amc.2026.130036

## Files updated

- `research/web-search/SEARCH_LOG.md`
- `research/web-search/QUERY_REGISTRY.md`
- `research/web-search/SOURCE_REGISTRY.md`
- `research/web-search/NOVELTY_CHECKS.md`
- `research/web-search/2026-09-28_fractional-stability-seed.md`
- `corpus/papers.csv`
- `corpus/theorems.csv`
- `bibliography/references.bib`
- this RETURN

## Recommended next search

Issue a narrow follow-up on:

> **relative/conic-sector multiplicative D-stability: finite exact characterizations, complexity, qualitative/sign classes, graph/sparsity classes, and precise relation to diagonal Lyapunov stability.**

That round should search matrix-analysis vocabulary first and fractional terminology second.

## RETURN TO CHIEF

**What the evidence supports:** The Matignon commensurate core is exact and mature; exact non-commensurate BIBO testing exists; generalized conic-region multiplicative D-stability exists.

**What the evidence does not support:** It does not support a broad claim that fractional-sector positive-diagonal D-stability is an unstudied bridge.

**Main novelty threat:** Kushel–Pavani 2022 (+ 2021 predecessor).

**Most important unresolved question:** Whether important structured subclasses admit sharper, finite, exact and potentially topology/sign-sensitive characterizations beyond the general universally quantified framework.